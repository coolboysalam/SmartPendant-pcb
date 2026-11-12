# دانلود دو فریمور آخر SmartPendant F411CE

این دو بسته در [انتشار آزمایشی F411CE](https://github.com/coolboysalam/SmartPendant-pcb/releases/tag/f411ce-experimental-v1) به‌صورت عمومی منتشر شده‌اند. ZIPها همان فایل‌های تحویل‌داده‌شدهٔ قبلی هستند و تغییر داده نشده‌اند. هر بسته، فایل HEX و BIN و راهنمای فارسی دارد.

| نسخه | دانلود مستقیم | امکانات | شناسهٔ سورس |
| --- | --- | --- | --- |
| لوگوی راه‌اندازی | [SmartPendant_Omid_Startup_F411CE.zip](https://github.com/coolboysalam/SmartPendant-pcb/releases/download/f411ce-experimental-v1/SmartPendant_Omid_Startup_F411CE.zip) | تاچ GT911/FT6236 و لوگوی OMID TAHERI هنگام شروع | [4174d78](https://github.com/coolboysalam/SmartPendant-pcb/commit/4174d7809e9b17a94023f3ed203f080cdf63a866) |
| اتولول PCB v1 | [SmartPendant_F411CE_PCB_AutoLevel_v1.zip](https://github.com/coolboysalam/SmartPendant-pcb/releases/download/f411ce-experimental-v1/SmartPendant_F411CE_PCB_AutoLevel_v1.zip) | لوگو و تاچ به‌همراه شبکهٔ پروب تا ۲۱×۲۱، نقشهٔ ارتفاع و ساخت PCB_LEV.NC | [8befe48](https://github.com/coolboysalam/SmartPendant-pcb/commit/8befe48801c591a2339d4fde1464b458b18f3c09) |

نسخهٔ لوگوی راه‌اندازی قابلیت اتولول PCB ندارد. برای اسکن و جبران ارتفاع، بستهٔ اتولول را انتخاب کن. این فریمورها برای **STM32F411CE / Black Pill** و نمایشگر عمودی ۳۲۰×۴۸۰ ساخته شده‌اند؛ برای F401CC نیستند. آدرس شروع فایل BIN برابر `0x08000000` است. فایل HEX آدرس‌ها را داخل خودش دارد.

ساخت و آزمون‌های نرم‌افزاری پاس شده‌اند. **نسخهٔ دارای اتولول هنوز روی CNC واقعی آزمایش نشده است.** راهنمای کامل داخل ZIP را پیش از فلش و اجرای اسکن بخوان.

## راهنما و نتیجهٔ آزمون‌ها

- [راهنمای فارسی اتولول](Firmware/GT911/PCB_HEIGHT_MAP_FA.md)
- [گزارش توسعه و آزمون‌ها](Firmware/GT911/WORK_LOG_FA.md)
- [جزئیات فنی انگلیسی](Firmware/GT911/PCB_HEIGHT_MAP.md)
- [ساخت موفق همین مخزن در GitHub Actions](https://github.com/coolboysalam/SmartPendant-pcb/actions/runs/43319199984)
- [SHA256SUMS.txt](https://github.com/coolboysalam/SmartPendant-pcb/releases/download/f411ce-experimental-v1/SHA256SUMS.txt)
- [اعلان‌های حق نشر و مجوزها](https://github.com/coolboysalam/SmartPendant-pcb/releases/download/f411ce-experimental-v1/THIRD_PARTY_NOTICES.txt)

## SHA-256 بسته‌ها

```text
3a4bb95e58f25c9d517fb8eecd86f125dbe00deea54d6a5e96b16fb813838ea7  SmartPendant_Omid_Startup_F411CE.zip
ad83da2598dd7a270112eadc1b3d7d17beb7ea79e9a9d89cdf2fa8b0072d0dcc  SmartPendant_F411CE_PCB_AutoLevel_v1.zip
```

سورس کامل نسخهٔ اتولول و مستندات جاری در شاخهٔ `main` همین مخزن هستند. ارتباط Fork مخزن قبلی `coolboysalam/SmartPendant` حفظ شده و برای این نسخه پول‌ریکوئست ساخته نشده است. اعتبار سازندگان اصلی سخت‌افزار، فریمور و DevCore محفوظ است.
