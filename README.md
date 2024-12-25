# Style-Hub-Client. 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Loyiha haqida

**Style Hub** - bu mijozlarni sartaroshlar qabuliga onlayn ro'yxatdan o'tkazish va joylarni bron qilish uchun mo'ljallangan mobil ilova. Ilova mijozlarga o'zlari istagan sartaroshni tez va qulay topish, xizmatlar va narxlar bilan tanishish, qulay vaqtga onlayn yozilish va xizmatlar uchun onlayn to'lovni amalga oshirish imkonini beradi. 

## Asosiy xususiyatlari

### Mijozlar uchun:

*   Sartaroshlarni joylashuv, xizmat turi, reyting bo'yicha qidirish va filtrlash.
*   Sartaroshlarning profillarini ko'rish (xizmatlar ro'yxati, narxlar, ish vaqti, rasmlar, sharhlar).
*   Sartarosh qabuliga onlayn yozilish (kun va vaqtni tanlash).
*   Joylarni bron qilish.
*   Xizmatlar uchun onlayn to'lovni amalga oshirish (Payme, Click, Mbank orqali).
*   Shaxsiy kabinet (bronlar tarixi, to'lovlar tarixi, sevimli sartaroshlar).
*   Xarita orqali yaqin atrofdagi sartaroshlarni ko'rish.
*   Xizmatlar haqida bildirishnomalar (eslatmalar, aksiyalar, chegirmalar).
*   Sartaroshlarga sharh qoldirish va baholash.
*   Sartaroshlarning ish namunalarini galereya ko'rinishida ko'rish.
*   Ko'p tilli interfeys (o'zbek, rus, ingliz).
*   Ilova ichida sartarosh bilan bog'lanish uchun chat funksiyasi.
*   Shaxsiy hisob raqamini boshqarish.

## Texnologiyalar

*   **Dasturlash tili:** Dart
*   **Freymvork:** Flutter
*   **Ma'lumotlar bazasi:** PostgreSQL
*   **Server qismi:** Mavjud, PostgreSQL ma'lumotlar bazasi bilan ishlaydi.
*   **To'lov tizimlari:** Payme, Click, Mbank

## Loyiha strukturasi

Loyiha "Clean Architecture" tamoyillariga asoslangan va quyidagi asosiy papkalardan iborat:

*   `lib/`: Ilovaning asosiy kodini o'z ichiga oladi. 
*   `test/`: Test fayllari.
*   `android/`: Android platformasiga xos kod.
*   `ios/`: iOS platformasiga xos kod.

## Ishga tushirish

1.  Ushbu repozitoriyni klon qiling:

    ```bash
    git clone <repository_url>
    ```
2.  Kerakli bog'liqliklarni o'rnating:

    ```bash
    flutter pub get
    ```
3.  Ilovani ishga tushiring:

    ```bash
    flutter run
    ```

## Litsenziya

Ushbu loyiha MIT litsenziyasi ostida tarqatilgan. Batafsil ma'lumot uchun [LICENSE](LICENSE) fayliga qarang.

## Mualliflar

*   **Eldor** 

## Aloqa

Agar sizda loyiha bo'yicha savol yoki takliflar bo'lsa, iltimos, eldor.turgunov.94@yandex.com orqali bog'laning.

---