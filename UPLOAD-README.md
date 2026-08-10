# حزمة الرفع النهائية — أكاديمية تودوما (محدّثة)

ارفع الملفات مع الحفاظ على البنية:

- `academy/` → مجلد جديد في جذر الموقع (الصفحة الرئيسية + 10 مقالات).
- صفحات الجذر (استبدال) — وكلها تحمل رابط «الأكاديمية» في Header + Mobile + Footer:
  `index.html` · `about.html` · `services.html` · `industries.html` · `blog.html` · `contact.html` · `third-party-logistics.html` · `fleet-management.html`
  (services/industries بهما أيضًا إصلاحا QA-031/QA-032.)

## خطوتان يدويتان بعد الرفع
1. **sitemap.xml:** ادمج محتوى `academy-sitemap-snippet.xml` داخل `<urlset>` في sitemap.xml الحي.
2. **مقالات B2B المتبقية غير المرفقة** (المقالات الأخرى ما عدا fleet و3PL): أضِف في Nav وMobile وFooter بعد «المقالات»:
   `<a href="academy/index.html">الأكاديمية</a>`

> Content Lock (v3) — لم يتغيّر أي محتوى أو تصميم. الصفحات about/blog/contact أضيف لها الرابط فقط (لا شيء آخر).
