# راهکار سطح بالا
به‌عنوان راه‌کار سطح بالا برای رفع این آسیب‌پذیری، می‌توان موارد زیر را در نظر گرفت:
* در صورت امکان از HTTP2 استفاده شود و فرآیند Downgrade نیز به صورت امن پیاده‌سازی شده باشد
* اطمینان حاصل شود که درخواست کاربر فاقد سرآیندهای مربوط به ین حمله، نظیر Chunk می‌باشد
* مقدار Content-Lenght ارسال شده از سمت کاربر با مقدار حجم واقعی درخواس مقایسه شود
* بررسی عدم وجود سرآیند Transfer-Encoding با مقدار مخرب
# راهکار جزئی
این بخش به‌زودی تکمیل خواهد شد