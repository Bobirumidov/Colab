# 📊 O‘zbekistonning xalqaro savdo oqimlari tahlili (2010–2024)

## 📌 Loyiha haqida
Ushbu loyiha O‘zbekistonning xalqaro savdo oqimlarini (eksport, import va savdo balansi) o‘rganish va prognoz qilish uchun yaratilgan.  
Ma’lumotlar **World Bank API**, demo dataset va vizualizatsiyalar asosida ishlab chiqilgan.

---

## 🎯 Maqsad
- Eksport va import hajmlarining vaqt bo‘yicha o‘zgarishini tahlil qilish  
- Savdo balansini aniqlash  
- Asosiy savdo hamkorlarini ko‘rsatish  
- 2030-yilgacha eksport hajmi prognozini tuzish  
- Umumiy tavsiyalar ishlab chiqish  

---

## 📂 Ma’lumot manbalari
- 🌍 **World Bank WITS API** – eksport va import statistikasi  
- 📊 **UN Comtrade** – savdo oqimlari ma’lumotlari  
- 💹 **IMF DOTS** – tashqi savdo statistikasi  
- 📑 **O‘zbekiston Davlat statistika qo‘mitasi** – rasmiy ma’lumotlar  

---

## ⚙️ Foydalanilgan texnologiyalar
- **Python**  
- **Pandas** – ma’lumotlarni tahlil qilish  
- **Matplotlib & Plotly** – vizualizatsiya  
- **Scikit-learn (Linear Regression)** – prognozlash  

---

## 📈 Tahlil bosqichlari
1. **Ma’lumotlarni olish** – demo dataset va World Bank API orqali  
2. **Ma’lumotlarni tozalash** – yilni int turiga o‘tkazish, savdo balansini hisoblash  
3. **Deskriptiv statistikalar** – o‘rtacha qiymat, min, max, std  
4. **Vaqt bo‘yicha trendlar** – eksport, import va savdo balansi grafigi  
5. **Asosiy hamkorlar** – Xitoy, Rossiya, Turkiya, Qozog‘iston, Koreya  
6. **Korrelatsiya tahlili** – eksport va import o‘zaro bog‘liqligi  
7. **Geografik vizualizatsiya** – choropleth xarita  
8. **Linear Regression asosida prognoz** – 2030-yilgacha eksport prognozi  

---

## 📊 Asosiy natijalar
- 2010–2024 yillarda eksport hajmi **barqaror o‘smoqda**  
- Import hajmi esa **tezroq o‘sib**, savdo balansini salbiy holatda ushlab turmoqda  
- **Xitoy va Rossiya** eng yirik savdo hamkorlari  
- Linear Regression prognozlariga ko‘ra, eksport hajmi 2030-yilgacha o‘sishda davom etadi  

---

## 📝 Tavsiyalar
- Eksportni **diversifikatsiya qilish** (tayyor mahsulotlar va xizmatlar)  
- Yangi bozorlar: **Yevropa, Osiyo, Yaqin Sharq** bilan aloqalarni kengaytirish  
- Importni qisqartirish uchun **mahalliy ishlab chiqarishni qo‘llab-quvvatlash**  
- **Logistika va transport infratuzilmasini** rivojlantirish  

---

## 🚀 Ishga tushirish
Loyihani lokalda ishga tushirish uchun:

```bash
git clone https://github.com/username/uzbekistan-trade-analysis.git
cd uzbekistan-trade-analysis
pip install -r requirements.txt
jupyter notebook
