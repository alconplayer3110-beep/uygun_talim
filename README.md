# Uygun Ta'lim

Bu Flutter ilovasi `Uygun Ta'lim` loyihasi uchun yozilgan.

## Ishga tushirish

```bash
git clone https://github.com/Sharof19/uygun_talim.git
cd uygun_talim
flutter pub get
flutter run
```

## Ishlatilgan texnologiyalar

- Flutter
- Dart
- Provider
- HTTP API

## Asosiy papkalar

- `lib/domain/services/` - API bilan ishlash
- `lib/domain/provider/` - state management
- `lib/ui/pages/` - sahifalar
- `lib/ui/routes/` - routing
- `lib/main.dart` - kirish nuqtasi

## Eslatma

Ilova backend API bilan ishlaydi. Asosiy manzillar kod ichida yozilgan:

- `https://api.uyguntalim.tsue.uz/api`
- `https://api.uyguntalim.tsue.uz/api-v1`

## Repository

`https://github.com/Sharof19/uygun_talim`

## Fork Qilish

O'quvchilar loyiha ustida xavfsiz ishlashi uchun `fork` qilishi kerak. Shunda asosiy repo siz tasdiqlamaguningizcha o'zgarmaydi.

1. GitHub'da repo sahifasini oching:
   `https://github.com/Sharof19/uygun_talim`
2. O'ng yuqoridagi `Fork` tugmasini bosing
3. O'z akkauntingizga fork yarating
4. Fork qilingan repo'ni kompyuterga yuklab oling:

```bash
git clone https://github.com/SIZNING_LOGIN/uygun_talim.git
cd uygun_talim
flutter pub get
```

5. Kodga o'zgartirish kiriting
6. O'zgarishni saqlang va commit qiling:

```bash
git add .
git commit -m "O'zgartirish tavsifi"
```

7. O'z fork'ingizga push qiling:

```bash
git push origin main
```

8. GitHub'da `Compare & pull request` tugmasini bosing
9. Pull request yuboring

Asosiy repo faqat maintainer tasdiqlab `merge` qilgandan keyin o'zgaradi.
