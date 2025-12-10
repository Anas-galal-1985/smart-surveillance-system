# 🛡️ نظام المراقبة الذكي

نظام مراقبة ذكي يستخدم الذكاء الاصطناعي للكشف عن الأشخاص المطلوبين عبر تحليل الفيديو المباشر والمسجل.

## 📋 المميزات

- **كشف وتتبع الأشخاص** باستخدام YOLOv8
- **التعرف على الوجوه** باستخدام InsightFace
- **إدارة قاعدة بيانات المطلوبين**
- **لوحة تحكم تفاعلية** باستخدام Streamlit
- **واجهة برمجة متكاملة** باستخدام Django
- **إشعارات فورية** عند اكتشاف مطلوبين

## 🏗️ هيكل المشروع
smart-surveillance-system/
├── 1_django_backend/ # واجهة برمجة APIs (Django)
├── 2_streamlit_dashboard/ # لوحة التحكم (Streamlit)
├── 3_ai_processing/ # معالجة الذكاء الاصطناعي
├── 4_shared/ # مصادر مشتركة
├── docker-compose.yml # تشغيل جميع الخدمات
└── Makefile # أوامر سريعة

text

## 🚀 البدء السريع

### المتطلبات
- Docker و Docker Compose
- Git

### خطوات التشغيل
1. نسخ المشروع:
```bash
git clone https://github.com/Anas-galal-1985/smart-surveillance-system.git
cd smart-surveillance-system
تشغيل جميع الخدمات:

bash
make up
فتح المتصفح:

لوحة التحكم: http://localhost:8501

واجهة APIs: http://localhost:8000

👥 فريق التطوير
الشخص ج: Django Backend

الشخص د: Streamlit Pages 1-5

الشخص هـ: Streamlit Pages 6-13

فريق الذكاء الاصطناعي: نماذج المعالجة

📄 الرخصة
هذا المشروع مرخص تحت رخصة MIT.
