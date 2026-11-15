# پنل آریو

[![وب‌سایت](https://img.shields.io/badge/getario.com-0F766E?style=flat-square)](https://getario.com)
[![گزارش ایراد](https://img.shields.io/badge/Issues-گزارش_ایراد-blue?style=flat-square)](../../issues/new/choose)
[![امنیت](https://img.shields.io/badge/Security-گزارش_خصوصی-crimson?style=flat-square)](SECURITY.md)

**فروش اشتراک با فروشگاه اختصاصی، حسابداری شفاف، و پرداخت کارت‌به‌کارت.**

سایت: [getario.com](https://getario.com)

این مخزن عمومی برای معرفی پنل آریو، گزارش ایرادها و پیشنهاد قابلیت‌هاست. کد اصلی پنل خصوصی می‌ماند. اسکریپت نصب سرور در مرحلهٔ بعد به همین مخزن افزوده می‌شود.

کمتر پنلی فروشگاه مستقل برای هر فروشنده، مخزن ترافیک روی سرورهای مالک، پرداخت کارت‌به‌کارت با تأیید رسید در تلگرام، و نمایش تومان را در یک جا جمع کرده است.

## چرا آریو؟

| قابلیت | پنل آریو | پنل معمولی |
| --- | --- | --- |
| فروشگاه و دامنهٔ اختصاصی برای هر فروشنده | دارد | معمولاً یک پنل مشترک |
| مخزن ترافیک روی سرورهای مالک | دارد | محدود یا نیست |
| سرور خود فروشنده، با سطوح مجوز | دارد | کمتر دیده می‌شود |
| کارت‌به‌کارت با تأیید رسید در تلگرام و شمارهٔ پیگیری یکتا | دارد | کمتر پنلی چنین امکانی دارد |
| تومان در کنار ارزهای دیگر | دارد | معمولاً فقط دلار |
| چند اشتراک برای هر مشتری، با وضعیت آنلاین | دارد | اغلب یک اشتراک |
| راهنمای فارسی و صفحهٔ دانش | دارد | ترجمهٔ ناقص یا بدون راهنما |

## امکانات

### فروشنده و فروشگاه

- هر فروشنده فروشگاه و دامنهٔ خودش را دارد و برند فروشگاه روی لینک اشتراک دیده می‌شود.
- فروشنده از مخزن ترافیک روی سرورهای مالک سهم می‌گیرد و می‌تواند سرور خودش را هم، متناسب با سطح مجوز، اضافه کند.
- حسابداری فروشنده، کیف پول، و سابقهٔ تراکنش‌ها در میز کار مشخص است.
- کارت هدیه و بستهٔ حجم اضافه نیز پشتیبانی می‌شود.

### پرداخت و حسابداری

- پرداخت کارت‌به‌کارت با ارسال رسید در تلگرام، شمارهٔ پیگیری یکتا، و به‌روزرسانی زندهٔ وضعیت.
- درگاه‌های Plisio، Stripe، PayPal، زرین‌پال و زیبال.
- چند ارز، از جمله تومان، با نرخ قابل به‌روزرسانی.

### سرور و هسته

- پشتیبانی از چند هسته، از جمله sing-box، و پروتکل وایرگارد.
- نصب و مدیریت روی سرور با ario-node.
- گزارش مصرف جداگانهٔ هر کاربر وایرگارد، و محدودیت سرعت.

### مشتری و اشتراک

- چند اشتراک برای هر مشتری، با یادداشت قابل ویرایش برای هر اشتراک.
- نمایش مصرف‌شده، کل و باقی‌مانده، وضعیت آنلاین یا آفلاین، و آخرین اتصال.
- کد QR قابل اسکن برای لینک اشتراک.

### رابط فارسی و راهنما

- رابط کاربری فارسی‌اول برای فروشنده، مشتری و منوی مدیریت.
- راهنما و صفحه‌های دانش، بدون نیاز به مستندات پراکنده.

## برای فروشنده‌ها

میز کار فروشنده برای ساخت طرح، مدیریت مشتریان، پیگیری پرداخت‌ها و مشاهدهٔ حساب‌ها طراحی شده است. فروشگاه با برند و دامنهٔ فروشنده به مشتری نمایش داده می‌شود و فروشنده می‌تواند از مخزن ترافیک مالک یا سرور خودش استفاده کند.

## برای مالکان پنل

منوی مدیریت برای دعوت یا تأیید فروشنده‌ها، تخصیص مجوز و ترافیک، مدیریت سرورها و هسته‌ها، و نظارت بر درگاه‌ها و حساب‌ها در نظر گرفته شده است. هر فروشنده فضای کار جداگانه دارد و به پنل دیگران دسترسی ندارد.

## برای مشتریان

مشتری از فروشگاه فروشنده طرح می‌خرد، چند اشتراک را در یک حساب می‌بیند، وضعیت اتصال و مصرف را دنبال می‌کند، و با کد QR یا لینک اشتراک به برنامهٔ خود وصل می‌شود. آموزش‌های پایه در صفحهٔ دانش در دسترس است.

## در راه

موارد زیر هنوز عرضه نشده‌اند و در برنامه هستند:

- ربات تلگرام مشتریان
- ترانزیت
- دستیار پشتیبانی هوشمند

## گزارش ایراد یا پیشنهاد

از بخش [Issues](../../issues) یک گزارش تازه باز کنید و یکی از فرم‌های آماده را پر کنید.

- برای ایراد امنیتی از [گزارش آسیب‌پذیری خصوصی](SECURITY.md) استفاده کنید و آن را در Issue عمومی ننویسید.
- در گزارش‌ها لینک اشتراک، ایمیل، آدرس IP، اطلاعات پرداخت، شماره کارت یا شماره پیگیری نفرستید.

## تصاویر

تصاویر رابط پس از بازبینی و حذف اطلاعات حساس در [`docs/screenshots/`](docs/screenshots/) اضافه می‌شوند.

---

# Ario Panel

[![Website](https://img.shields.io/badge/getario.com-0F766E?style=flat-square)](https://getario.com)
[![Issues](https://img.shields.io/badge/Issues-bug_reports-blue?style=flat-square)](../../issues/new/choose)
[![Security](https://img.shields.io/badge/Security-private_report-crimson?style=flat-square)](SECURITY.md)

**A subscription panel with per-seller shops, clear accounting, and card-to-card payments.**

Website: [getario.com](https://getario.com)

This public repository introduces Ario Panel and collects bug reports and feature requests. The main panel code remains private. The server installer will be added in a later stage.

Few panels combine a separate shop and domain for each seller, a traffic pool on the owner’s servers, card-to-card payment with Telegram receipt review, and Toman alongside other currencies.

## Highlights

- **For sellers:** a dedicated shop and domain, a traffic pool on owner servers, optional seller-owned servers under licence tiers, a wallet and ledger, gift cards, and extra traffic packages.
- **For owners:** seller onboarding and licences, server and core management (including sing-box and WireGuard via ario-node), and oversight of payments and accounts.
- **For customers:** multiple subscriptions with remarks, usage and remaining traffic, online/offline status and last connection, scannable QR codes, and Persian knowledge pages.

## Payments

Card-to-card transfers with Telegram receipt approval, unique tracking numbers, and live status updates — plus Plisio, Stripe, PayPal, Zarinpal, and Zibal. Prices can be shown in Toman and other currencies.

## Coming later

These items are planned and not available yet:

- a Telegram assistant for customers
- transit
- a smart support assistant

## Issues

Open a report from [Issues](../../issues) and use one of the forms. Report security vulnerabilities privately ([SECURITY.md](SECURITY.md)). Do not include subscription links, emails, IP addresses, payment details, card numbers, or tracking numbers.

Screenshots will be added under [`docs/screenshots/`](docs/screenshots/) after they have been reviewed and sensitive details removed.
