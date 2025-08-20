
# Login + Reset HWID Site (KeyAuth Ready)

هذا المشروع عبارة عن موقع بسيط:
- `index.html`: تسجيل دخول عبر KeyAuthApp.login.
- `reset.html`: إعادة تعيين HWID عبر KeyAuthApp.resetUserHWID.

⚠️ مهم: يجب أن تضع ملف **KeyAuth.js** الرسمي (من KeyAuth SDK) في نفس المجلد حتى يعمل.
حاليًا الكود يستدعي `<script src="KeyAuth.js"></script>` لذلك بدون الملف الأصلي سيعطي خطأ.
