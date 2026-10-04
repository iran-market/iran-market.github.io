<div align="center">
  <img src="assets/favicon.png" width="76" height="76" alt="Iran Market Data - API رایگان قیمت بازار ایران">
  <h1 dir="rtl">API رایگان قیمت دلار، طلا، سکه و بازار ایران</h1>
  <p dir="rtl"><strong>دادهٔ آمادهٔ JSON برای قیمت فعلی و تاریخچهٔ روزانه بازار ایران؛ بدون ثبت‌نام و بدون API Key</strong></p>
  <p>
    <a href="https://iran-market.github.io/"><img alt="وب‌سایت Iran Market Data" src="https://img.shields.io/badge/Website-Live-0f766e"></a>
    <a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/latest-toman.json"><img alt="قیمت‌ها هر ۳۰ دقیقه به‌روزرسانی می‌شوند" src="https://img.shields.io/badge/Prices-Every_30_Min-2563eb"></a>
    <a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/history/index.json"><img alt="۱۲۸ فایل تاریخچه روزانه" src="https://img.shields.io/badge/History-128_Symbols-f59e0b"></a>
    <a href="LICENSE"><img alt="MIT License" src="https://img.shields.io/badge/License-MIT-111827"></a>
  </p>
</div>

<p dir="rtl" align="right">
<strong>Iran Market Data</strong> مجموعه‌ای عمومی از فایل‌های JSON برای دریافت قیمت دلار آزاد، یورو، طلا، سکه، تتر، رمزارزها، نفت، انرژی، قهوه، غلات و فلزات است. این مخزن برای وب‌سایت، اپلیکیشن، ربات، داشبورد، پروژهٔ دانشگاهی و تحلیل داده طراحی شده و برای استفاده از آن به ثبت‌نام، توکن، SDK یا اجرای scraper نیاز ندارید.
</p>

<p dir="rtl" align="right">
در خروجی فعلی، <strong>۱٬۳۵۰ شناسهٔ canonical</strong>، <strong>۹۵۵ نماد دارای قیمت فعلی</strong> و <strong>۱۲۸ فایل تاریخچهٔ OHLC روزانه</strong> منتشر می‌شود. اعداد زنده و قابل اتکا همیشه در <a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/symbols.json"><code>data/symbols.json</code></a> و <a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/history/index.json"><code>data/history/index.json</code></a> قرار دارند.
</p>

<p align="center">
  <a href="https://iran-market.github.io/"><strong>داشبورد و مستندات زنده</strong></a>
  ·
  <a href="SYMBOLS.md"><strong>راهنمای کامل نمادها</strong></a>
  ·
  <a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/history/index.json"><strong>فهرست تاریخچه‌ها</strong></a>
</p>

<h2 dir="rtl" align="right">شروع سریع</h2>

<p dir="rtl" align="right">برای دریافت قیمت‌های پرکاربرد بازار به تومان:</p>

```bash
curl --fail --silent \
  https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/popular.json
```

<p dir="rtl" align="right">این URL عمومی است، CORS دارد و مستقیماً در مرورگر یا کد قابل استفاده است:</p>

```text
https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/popular.json
```

<h2 dir="rtl" align="right">فایل‌های عمومی و کاربرد هرکدام</h2>

<table dir="rtl" align="right">
  <thead>
    <tr>
      <th align="right">فایل</th>
      <th align="right">محتوا</th>
      <th align="right">زمان به‌روزرسانی</th>
      <th align="right">لینک مستقیم</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>popular.json</code></td>
      <td>دلار آزاد، یورو، پوند، طلای ۱۸ عیار، سکه امامی و تتر؛ مناسب شروع سریع</td>
      <td>هر ۳۰ دقیقه</td>
      <td><a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/popular.json">Raw GitHub</a></td>
    </tr>
    <tr>
      <td><code>latest-toman.json</code></td>
      <td>همهٔ قیمت‌های فعلی؛ دارایی‌های ریالی به تومان و دارایی‌های جهانی در ارز اصلی خودشان</td>
      <td>هر ۳۰ دقیقه</td>
      <td><a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/latest-toman.json">Raw GitHub</a></td>
    </tr>
    <tr>
      <td><code>latest.json</code></td>
      <td>همهٔ قیمت‌های فعلی؛ دارایی‌های ریالی به ریال و دارایی‌های جهانی در ارز اصلی خودشان</td>
      <td>هر ۳۰ دقیقه</td>
      <td><a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/latest.json">Raw GitHub</a></td>
    </tr>
    <tr>
      <td><code>symbols.json</code></td>
      <td>مرجع شناسه‌ها، نام معتبر، دسته، واحد، وضعیت قیمت فعلی و مسیر تاریخچه</td>
      <td>هر ۳۰ دقیقه</td>
      <td><a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/symbols.json">Raw GitHub</a></td>
    </tr>
    <tr>
      <td><code>history/index.json</code></td>
      <td>فهرست ماشین‌خوان تاریخچه‌ها، تعداد رکورد، ارز و بازهٔ زمانی هر نماد</td>
      <td>فهرست هر ۳۰ دقیقه؛ فایل‌های تاریخچه روزانه</td>
      <td><a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/history/index.json">Raw GitHub</a></td>
    </tr>
    <tr>
      <td><code>history/{SYMBOL}.json</code></td>
      <td>کندل‌های OHLC روزانهٔ یک نماد، مرتب‌شده از قدیمی به جدید</td>
      <td>روزانه</td>
      <td><a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/history/USD_IRR_FREE.json">نمونهٔ دلار آزاد</a></td>
    </tr>
    <tr>
      <td><code>manifest.json</code></td>
      <td>فهرست فایل‌های منتشرشده، تعداد رکوردها و metadata انتشار</td>
      <td>هر ۳۰ دقیقه</td>
      <td><a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/manifest.json">Raw GitHub</a></td>
    </tr>
  </tbody>
</table>

<br clear="all">

<blockquote dir="rtl">
<strong>مسیر پیشنهادی برای مصرف JSON، Raw GitHub است</strong> تا ترافیک فایل‌ها از سهمیهٔ پهنای باند GitHub Pages عبور نکند. Raw GitHub معمولاً حدود ۵ دقیقه cache می‌شود و برای قیمت‌های نیم‌ساعتی انتخاب مناسب‌تری است:<br>
<code>https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/{FILE}</code><br><br>
jsDelivr نیز به‌عنوان CDN جایگزین در دسترس است، اما ممکن است فایل شاخهٔ <code>main</code> را حدود ۱۲ ساعت cache کند؛ بنابراین برای داده‌ای استفاده کنید که تأخیر بیشتر در تازه‌شدن آن قابل قبول است:<br>
<code>https://cdn.jsdelivr.net/gh/iran-market/iran-market.github.io@main/data/{FILE}</code>
</blockquote>

<h2 dir="rtl" align="right">API رایگان قیمت دلار، ارز، طلا و سکه</h2>

<p dir="rtl" align="right">
شناسه‌های عمومی پروژه مستقل از slug داخلی منبع هستند. برای نمونه، <code>USD_IRR_FREE</code> دلار بازار آزاد، <code>GOLD_18K_IRR</code> طلای ۱۸ عیار و <code>COIN_EMAMI_IRR</code> سکه امامی است. برای جلوگیری از خطای تطبیق، در کد خود همیشه از فیلد <code>symbol</code> استفاده کنید، نه نام نمایشی.
</p>

<table dir="rtl" align="right">
  <thead>
    <tr><th align="right">بازار</th><th align="right">نماد نمونه</th><th align="right">تاریخچه مستقیم</th></tr>
  </thead>
  <tbody>
    <tr><td>دلار آزاد</td><td><code>USD_IRR_FREE</code></td><td><a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/history/USD_IRR_FREE.json">JSON</a></td></tr>
    <tr><td>یورو آزاد</td><td><code>EUR_IRR_FREE</code></td><td><a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/history/EUR_IRR_FREE.json">JSON</a></td></tr>
    <tr><td>طلای ۱۸ عیار</td><td><code>GOLD_18K_IRR</code></td><td><a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/history/GOLD_18K_IRR.json">JSON</a></td></tr>
    <tr><td>سکه امامی</td><td><code>COIN_EMAMI_IRR</code></td><td><a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/history/COIN_EMAMI_IRR.json">JSON</a></td></tr>
    <tr><td>تتر ریالی</td><td><code>USDT_IRR</code></td><td><a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/history/USDT_IRR.json">JSON</a></td></tr>
    <tr><td>بیت‌کوین دلاری</td><td><code>BTC_USD</code></td><td><a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/history/BTC_USD.json">JSON</a></td></tr>
    <tr><td>قهوه لندن</td><td><code>COMMODITY_LONDON_COFFEE</code></td><td><a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/history/COMMODITY_LONDON_COFFEE.json">JSON</a></td></tr>
  </tbody>
</table>

<br clear="all">

<p dir="rtl" align="right">
فهرست کامل و قابل جست‌وجوی شناسه‌ها در <a href="SYMBOLS.md">راهنمای نمادها</a> و نسخهٔ ماشین‌خوان آن در <a href="https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/symbols.json"><code>symbols.json</code></a> قرار دارد. نام فارسی یا انگلیسی حدس زده نمی‌شود؛ اگر نام معتبر موجود نباشد مقدار آن <code>null</code> است و رابط وب خود symbol را نمایش می‌دهد.
</p>

<h2 dir="rtl" align="right">نمونهٔ JavaScript</h2>

```js
const url = 'https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/popular.json';
const response = await fetch(url);

if (!response.ok) {
  throw new Error(`Iran Market request failed: ${response.status}`);
}

const payload = await response.json();
const dollar = payload.data.find(
  (item) => item.symbol === 'USD_IRR_FREE',
);

console.log({
  price: dollar.price,
  currency: dollar.currency, // IRT یعنی تومان
  marketTime: dollar.timestamp_tehran,
  publishedAt: payload.meta.published_at,
  stale: dollar.stale,
});
```

<h2 dir="rtl" align="right">نمونهٔ Python برای تاریخچهٔ قیمت دلار</h2>

```python
import requests

url = "https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/history/USD_IRR_FREE.json"
response = requests.get(url, timeout=20)
response.raise_for_status()

payload = response.json()

for candle in payload["data"][-7:]:
    print(
        candle["date_jalali"],
        candle["open"],
        candle["high"],
        candle["low"],
        candle["close"],
    )
```

<h2 dir="rtl" align="right">کشف خودکار همهٔ تاریخچه‌ها</h2>

<p dir="rtl" align="right">
مسیر فایل‌ها را در کد hard-code نکنید. ابتدا <code>history/index.json</code> را بخوانید و سپس URL نماد موردنظر را از همان فهرست دریافت کنید:
</p>

```js
const directory = await fetch(
  'https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/history/index.json',
).then((response) => response.json());

const coffee = directory.data.find(
  (item) => item.symbol === 'COMMODITY_LONDON_COFFEE',
);

const history = await fetch(coffee.url).then((response) => response.json());
console.log(history.meta.currency, history.data.at(-1));
```

<h2 dir="rtl" align="right">ساختار دادهٔ قیمت فعلی</h2>

```json
{
  "symbol": "USD_IRR_FREE",
  "name_fa": "دلار آمریکا (بازار آزاد)",
  "name_en": "US Dollar (open market)",
  "category": "currency",
  "currency": "IRT",
  "price": 258465,
  "high": 258520,
  "low": 254660,
  "change": 0,
  "change_pct": 0,
  "timestamp": "2026-09-30T20:30:00.000Z",
  "timestamp_tehran": "2026-10-01T00:00:00+03:30",
  "timestamp_jalali": "1405/07/09 00:00:00",
  "checked_at": "2026-10-02T11:08:26.797Z",
  "source": "tgju",
  "stale": false,
  "quality": []
}
```

<h3 dir="rtl" align="right">معنای زمان‌ها</h3>

<ul dir="rtl" align="right">
  <li><code>timestamp</code>: زمان خود قیمت یا کندل در UTC.</li>
  <li><code>timestamp_tehran</code>: همان زمان با منطقهٔ زمانی تهران.</li>
  <li><code>timestamp_jalali</code> و <code>date_jalali</code>: نمایش جلالی برای رابط فارسی.</li>
  <li><code>checked_at</code>: آخرین زمانی که سامانه وضعیت این قیمت را بررسی کرده است.</li>
  <li><code>meta.published_at</code>: زمان ساخته‌شدن فایل عمومی؛ الزاماً زمان تغییر قیمت بازار نیست.</li>
</ul>

<h2 dir="rtl" align="right">ساختار تاریخچهٔ OHLC</h2>

```json
{
  "t": "2011-11-25T20:30:00.000Z",
  "t_tehran": "2011-11-26T00:00:00+03:30",
  "date_jalali": "1390/09/05",
  "open": 1370,
  "high": 1370,
  "low": 1370,
  "close": 1370,
  "volume": null,
  "origin": "source",
  "quality": []
}
```

<p dir="rtl" align="right">
رکوردهای تاریخچه صعودی هستند؛ یعنی قدیمی‌ترین کندل ابتدای آرایه و جدیدترین کندل انتهای آرایه است. بازهٔ پوشش برای هر نماد متفاوت است و باید از فیلدهای <code>from</code> و <code>to</code> در <code>history/index.json</code> خوانده شود. بعضی بازارها در مجموعهٔ فعلی تا سال ۲۰۱۰ میلادی سابقه دارند.
</p>

<h2 dir="rtl" align="right">دسته‌های تاریخچه</h2>

<table dir="rtl" align="right">
  <thead><tr><th align="right">دسته</th><th align="right">تعداد فایل</th><th align="right">نمونه‌ها</th></tr></thead>
  <tbody>
    <tr><td>ارز آزاد</td><td>۲۵</td><td>دلار، یورو، پوند، درهم، لیر، ارزهای منطقه‌ای و…</td></tr>
    <tr><td>طلا و فلزات گران‌بها</td><td>۱۶</td><td>طلای ۱۸ و ۲۴ عیار، آب‌شده، انس طلا، نقره و…</td></tr>
    <tr><td>سکه</td><td>۱۵</td><td>بازار، تک‌فروشی و حباب انواع سکه</td></tr>
    <tr><td>رمزارز</td><td>۳۲</td><td>جفت‌های دلاری و ریالی بیت‌کوین، تتر، سولانا و…</td></tr>
    <tr><td>انرژی</td><td>۶</td><td>نفت برنت، گاز طبیعی، بنزین، سبد اوپک و…</td></tr>
    <tr><td>کالا و فلز صنعتی</td><td>۲۸</td><td>قهوه، کاکائو، گندم، دام، مس، فولاد و…</td></tr>
    <tr><td>جفت‌ارز جهانی</td><td>۶</td><td>EUR/USD، GBP/USD، USD/JPY و…</td></tr>
  </tbody>
</table>

<br clear="all">

<h2 dir="rtl" align="right">نکات مهم دربارهٔ واحد و تازگی داده</h2>

<ul dir="rtl" align="right">
  <li><code>IRR</code> یعنی ریال ایران و <code>IRT</code> یعنی تومان ایران.</li>
  <li>در <code>latest-toman.json</code> فقط قیمت‌هایی که مبنای ریالی دارند به تومان تبدیل می‌شوند؛ قیمت جهانی قهوه، طلا، نفت یا فلزات با <code>currency: USD</code> دلاری باقی می‌ماند.</li>
  <li>فیلد <code>currency</code> هر رکورد را بخوانید و واحد را از نام فایل حدس نزنید.</li>
  <li><code>stale: true</code> یعنی قیمت از آستانهٔ تازگی مورد انتظار قدیمی‌تر است؛ این وضعیت ممکن است هنگام تعطیلی بازار طبیعی باشد.</li>
  <li>مقادیر <code>null</code> به معنی «داده موجود نیست» هستند؛ آن‌ها را با صفر جایگزین نکنید.</li>
  <li>قیمت فعلی هر ۳۰ دقیقه منتشر می‌شود و تاریخچه‌های کامل روزی یک‌بار بازسازی می‌شوند.</li>
  <li>نسخهٔ عمومی دادهٔ tick-by-tick یا real-time نیست؛ فاصلهٔ انتشار قیمت‌های فعلی ۳۰ دقیقه است.</li>
</ul>

<h2 dir="rtl" align="right">پایداری، محدودیت‌ها و منبع داده</h2>

<ul dir="rtl" align="right">
  <li>فرمت همهٔ خروجی‌ها UTF-8 JSON و دسترسی آن‌ها عمومی است.</li>
  <li>منبع فعلی داده <strong>TGJU</strong> است؛ منبع دیگری در این نسخه ادغام نشده است.</li>
  <li>این مخزن static data API است؛ پارامتر جست‌وجو، API key، حساب کاربری و rate-limit اختصاصی ندارد.</li>
  <li>برای JSON از Raw GitHub (پیشنهادی، cache حدود ۵ دقیقه) یا jsDelivr (جایگزین، cache حدود ۱۲ ساعت) استفاده کنید؛ GitHub Pages فقط میزبان رابط و مستندات وب است.</li>
  <li>دسترسی به Raw GitHub یا jsDelivr تابع پایداری و سیاست cache همان سرویس‌ها است و SLA تجاری ارائه نمی‌شود.</li>
  <li>قیمت‌ها صرفاً جهت اطلاع‌رسانی‌اند و توصیهٔ خرید یا فروش نیستند؛ برای استفادهٔ مالی یا حساس، داده را مستقلاً راستی‌آزمایی کنید.</li>
</ul>

<h2 dir="rtl" align="right">گزارش خطا و مشارکت</h2>

<p dir="rtl" align="right">
اگر نماد اشتباه، واحد نادرست، دادهٔ قدیمی یا مشکل نمایشی پیدا کردید، یک <a href="https://github.com/iran-market/iran-market.github.io/issues/new">Issue</a> بسازید و symbol، URL فایل و نمونهٔ رکورد را بنویسید. فایل‌های داخل <code>data/</code> خودکار تولید می‌شوند؛ برای اصلاح داده مستقیماً آن‌ها را ویرایش نکنید.
</p>

<h2>Free Iran Market API</h2>

Iran Market Data provides public, no-auth JSON files for current and historical Iranian market data: free-market USD/IRR exchange rates, EUR and GBP, Iranian gold and coins, USDT, cryptocurrencies, energy, coffee, grains, and industrial metals. Current-price snapshots are published every 30 minutes, while selected daily OHLC histories are refreshed once per day. Start with [`popular.json`](https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/popular.json), discover canonical identifiers in [`symbols.json`](https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/symbols.json), and enumerate available histories through [`history/index.json`](https://raw.githubusercontent.com/iran-market/iran-market.github.io/main/data/history/index.json).

<h2 dir="rtl" align="right">مجوز</h2>

<p dir="rtl" align="right">
کد رابط، مستندات و مثال‌های این مخزن تحت <a href="LICENSE">مجوز MIT</a> منتشر می‌شوند. دادهٔ بازار متعلق به تولیدکنندگان و ارائه‌دهندگان اصلی آن است.
</p>
