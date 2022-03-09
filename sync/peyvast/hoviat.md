# هویت

نحوه‌ی انتقال هویت به‌صورت دوطرفه از پیام‌گستر به پیوست و از پیوست به پیام‌گستر می‌باشد.

**نقطه اشتراک همگام‌سازی:**

مقدار داشتن فیلد شماره مشتری در پیام‌گستر و کد اشتراک (کد تفضیلی سطح یک) در پیوست به‌عنوان مبنا برای سینک بین دو نرم‌افزار، الزامی می‌باشد.

## فیلدهای قابل انتقال:

**حقیقی:** نام، نام خانوادگی، تاریخ مشتری شدن، کد تفصیلی سطح یک یا کد اشتراک (شماره مشتری)، ایمیل، نشانی، موبایل، تلفن، نمابر، کد ملی، تاریخ تولد، کشور، استان، شهر و توضیحات از هویت حقیقی پیوست به پیام‌گستر انتقال پیدا می‌کند.

**حقوقی:** نام شرکت، کد تفصیلی سطح یک یا کد اشتراک (شماره مشتری)، ایمیل، نشانی، موبایل، تلفن، نمابر، تاریخ ثبت، شماره ثبت، کد اقتصادی، کشور، استان، شهر، منطقه، کد پستی و توضیحات از هویت حقوقی پیوست به پیام‌گستر انتقال پیدا می‌کند.
لازم به ذکر است در نرم‌افزار پیوست کد اشتراک و کد تفصیلی سطح یک، ممکن است دارای مقادیر یکسان باشند.

## نکات مرتبط باهویت:

•    در نظر داشته باشید در انتقال نشانی از پیوست به پیام‌گستر، می‌بایست نام کشور، استان، شهر از قبل در پیام‌گستر تعریف شده باشد، در غیر این صورت فقط آدرس منتقل می‌شود.

•    درصورتی‌که حقیقی یا حقوقی بودن هویت در پیام‌گستر ویرایش شود، تغییرات به‌صورت خودکار در پیوست اعمال می‌شوند؛ ولی اگر حقیقی یا حقوقی بودن هویت در پیوست ویرایش شود، تغییرات در پیام‌گستر اعمال نمی‌شوند.

•    در سیستم مالی پیوست، یک فیلد برای ذخیره شماره تماس وجود دارد. درصورتی‌که بخواهید چندین شماره تماس را در فیلد موردنظر وارد کنید، باید بین شماره‌ها  space یا ویرگول قرار دهید. به‌عنوان‌مثال شماره 88445566 22334455 به‌صورت دو شماره مجزا در نظر گرفته می‌شود و به پیام‌گستر اضافه می‌شود.

### مانده‌حساب مشتری از طریق وب‌سرویس به دو روش خوانده می‌شود:

**1.**    به شرطی که کد حساب صفر نباشد، ازروی فیلد مانده‌حساب خوانده می‌شود. (مسیر فیلد مانده‌حساب: امکانات > مدیریت اشخاص > انتخاب طرف حساب > انتخاب مانده‌حساب از پایین صفحه )

**2.**    ازروی کد حساب پیش‌فرض که در تنظیمات همگام ساز تعیین شده است.

•    حذف هویت فقط از سمت پیوست به پیام‌گستر تأثیر دارد.

•    ویرایش هویت طبق مرجع مشخص شده در تنظیمات همگام ساز اعمال می‌شود. اگر مرجع پیوست باشد ویرایش از سمت پیوست به پیام‌گستر انجام می‌شود و اگر مرجع پیام‌گستر باشد ویرایش از سمت پیام‌گستر به پیوست اعمال می‌شود.

•    در تنظیمات همگام ساز 2 چک باکس به نام‌های "سیستم مالی به نرم‌افزار CRM" و "نرم‌افزار CRM به سیستم مالی" وجود دارد که بر اساس آن‌ها می‌توان جهت سینک هویت را مشخص کرد.


