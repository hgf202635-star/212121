# استيراد بيانات الجهات بعد التحقق

الحقول المقترحة: `name`, `slug`, `description`, `category`, `region`, `official_website`, `official_donation_url`, `verification_status`, `verified_at`, `last_reviewed_at`, `source_url`, `source_type`, `review_notes`, `reviewer_id`.

قبل النشر: تحقق من المدخلات وحدود النص، افحص روابط HTTP(S) وتحويلاتها على الخادم، اكتشف التكرارات وراجعها يدوياً، افصل staging عن المنشور، سجّل المراجعات والتغييرات، ولا تمنح حالة `verified` تلقائياً. لا تستورد سجلات غير مراجعة إلى بيانات منشورة.
