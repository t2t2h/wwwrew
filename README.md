# libs/ — مكتبات خارجية اختيارية

ضع هنا مخرجات `build-ntgcalls-ios.yml` (Artifact باسم `ntgcalls-ios`):

- `libs/libntgcalls.a` — المكتبة (لـ iOS arm64 فقط)
- `libs/include/ntgcalls.h` — الهيدر

عند وجود `libntgcalls.a` يربطها الـ Makefile تلقائياً ويعرّف `DS_HAS_NTGCALLS=1`، فيتحول زر «NTgCalls» بالمنيو إلى «مرتبطة بالأداة».
إن لم تضعها، يُبنى المشروع بدونها بدون أي مشكلة.
