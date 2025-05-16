# California Housing Price Prediction

Ushbu loyiha Kaliforniya uy-joy bozorining ma'lumotlar to'plami asosida uy narxlarini bashorat qilish uchun mashinani o'rganish modellari yaratishni maqsad qilgan.

---

## Loyihaning mazmuni

- **Ma'lumotlar**: `housing.csv` faylida joylashgan Kaliforniya hududidagi turli xususiyatlar va uy narxlari.
- **Oldindan ishlov berish**:
  - Yo'qolgan qiymatlar o'rtacha bilan to'ldirildi.
  - Kategorik ustun `ocean_proximity` one-hot encoding yordamida kodlandi.
  - Yangi xususiyatlar yaratildi: `rooms_per_household`, `bedrooms_per_room`, `population_per_household`.
- **Model**:  
  - Linear Regression modeli  
  - Random Forest Regressor modeli
- **Baholash**:  
  - Mean Squared Error (MSE)  
  - R-squared (R2) ko'rsatkichlari orqali

---

## Foydalanish

### Talablar

- Python 3.x
- Quyidagi kutubxonalar:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
