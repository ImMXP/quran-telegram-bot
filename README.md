# 🌿 Quran Telegram Bot · بوت القرآن الكريم

<p align="center">
  <b><a href="#english">English</a></b> · <b><a href="#arabic">العربية</a></b>
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3572A5?style=for-the-badge&logo=python&logoColor=white">
  <img alt="python-telegram-bot 20.3" src="https://img.shields.io/badge/python--telegram--bot-20.3-26A5E4?style=for-the-badge&logo=telegram&logoColor=white">
</p>

---

## <a id="english"></a>English

An Arabic Telegram bot that greets users with a keyboard menu and replies with a selected Quran verse for each category — morning, evening, tranquility and repentance. Built with [python-telegram-bot](https://python-telegram-bot.org/) v20 and its async API.

### Features
- `/start` greets the user by name and shows a six-button reply keyboard.
- Each button returns its verse; the *recitations* and *favourite reciters* buttons are placeholders for upcoming content.
- Any other text gets a friendly hint to use the menu.
- Logs every interaction and stops with a clear error when the bot token is missing.

### Run locally
1. Create a bot with [@BotFather](https://t.me/BotFather) and copy its token.
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Provide the token as an environment variable and start the bot:
   ```bash
   export TELEGRAM_BOT_TOKEN="<your-token>"   # PowerShell: $env:TELEGRAM_BOT_TOKEN="<your-token>"
   python bot.py
   ```

> Keep the token in environment variables (or your host's secret settings, such as Render) and never commit it.

---

## <a id="arabic"></a>العربية

بوت تيليجرام عربي يرحّب بالمستخدم بقائمة أزرار، ويرسل آية مختارة لكل قسم: آيات الصباح، آيات المساء، آيات السكينة، وآيات التوبة. مبني بمكتبة [python-telegram-bot](https://python-telegram-bot.org/) (الإصدار 20) وواجهتها غير المتزامنة.

### المميزات
- الأمر `/start` يرحّب بالمستخدم باسمه ويعرض لوحة من ستة أزرار.
- كل زر يرسل الآية الخاصة به، وزرّا *التلاوات المختارة* و*المشايخ المفضلين* مخصصان لمحتوى قادم.
- أي رسالة أخرى يرد عليها البوت بتوجيه المستخدم لاستخدام القائمة.
- تسجيل كل تفاعل، وإيقاف التشغيل برسالة واضحة إذا لم يُعثر على التوكن.

### طريقة التشغيل
1. أنشئ بوتاً عبر [@BotFather](https://t.me/BotFather) وانسخ التوكن.
2. ثبّت المكتبات: `pip install -r requirements.txt`
3. ضع التوكن في متغير البيئة `TELEGRAM_BOT_TOKEN` ثم شغّل `python bot.py`.

> احفظ التوكن في متغيرات البيئة أو إعدادات الاستضافة، ولا ترفعه إلى المستودع.

---

<p align="center">Developed by <a href="https://github.com/ImMXP">Moha0x</a></p>
