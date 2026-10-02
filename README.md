# VIVID IELTS — V24 Clean Runtime

Bu paket faqat ishlaydigan sayt uchun kerakli fayllarni saqlaydi.

## Ishga tushirish
1. Papkani VS Code’da oching.
2. `dist/index.html` ni **Live Server** bilan oching.
3. Yoki terminalda: `python -m http.server 5500 --directory dist`

## Qoldirilgan asosiy qismlar
- VIVID IELTS asosiy ilovasi (`dist/`)
- Reading Upgrade / Listening Upgrade / Writing Upgrade / Speaking Upgrade
- Reading Mock va Listening Mock uchun amalda ishlatiladigan test sahifalari
- Speed Listening transcript → 15 Gap Filling + 15 Dictation auto-check
- Supabase login/cloud progress frontend konfiguratsiyasi
- PWA/service worker va 100 kunlik jurnal

## Tozalangan narsalar
Eski Academy dashboard, article sahifalari, eski writing/speaking/vocabulary sahifalari, keraksiz PDF/DOCX manbalar, extractor skriptlar, Supabase deploy source nusxalari, eski promo videolar, build/report fayllari va `dist/server/index.js` kabi takroriy bundle olib tashlandi.

Git tarixida yoki oldingi V23 ZIP’da ularning asl nusxasi saqlanadi.
