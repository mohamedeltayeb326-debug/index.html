<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MONEEB GLOBAL | منيب العالمية</title>
    <style>
        :root { --gold: #D4AF37; --navy: #001329; --light-navy: #002244; }
        body { background: var(--navy); color: white; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; direction: rtl; margin: 0; padding-bottom: 50px; }
        header { text-align: center; padding: 30px; border-bottom: 3px solid var(--gold); background: linear-gradient(to bottom, #001a33, var(--navy)); }
        .logo-text { color: var(--gold); margin: 0; font-size: 32px; font-weight: bold; letter-spacing: 2px; }
        .card { border: 1px solid var(--gold); border-radius: 15px; margin: 20px; padding: 20px; background: var(--light-navy); box-shadow: 0 8px 16px rgba(0,0,0,0.5); }
        .grid { display: grid; grid-template-columns: 1fr 1fr; gap: 15px; margin-bottom: 15px; }
        .btn { display: block; background: var(--gold); color: var(--navy); text-align: center; padding: 15px; border-radius: 10px; font-weight: bold; text-decoration: none; margin-top: 15px; border: none; width: 100%; cursor: pointer; transition: 0.3s; font-size: 16px; }
        .btn:hover { opacity: 0.9; transform: translateY(-2px); }
        .btn-pi { background: white; color: black; border: 2px solid var(--gold); }
        input, select, textarea { width: 100%; padding: 12px; margin: 10px 0; border-radius: 8px; border: 1px solid var(--gold); background: #001329; color: white; box-sizing: border-box; }
        img, video { width: 100%; height: 150px; object-fit: cover; border-radius: 10px; border: 1px solid var(--gold); }
        summary { color: var(--gold); font-weight: bold; cursor: pointer; text-align: center; list-style: none; padding: 10px; border: 1px dashed var(--gold); border-radius: 8px; }
        .status-badge { background: #28a745; color: white; padding: 5px 10px; border-radius: 20px; font-size: 12px; display: inline-block; margin-bottom: 10px; }
    </style>
</head>
<body>

<header>
    <div class="status-badge">متصل بشبكة Pi Network</div>
    <h1 class="logo-text">MONEEB GLOBAL</h1>
    <p style="font-size: 14px; opacity: 0.8; margin-top: 10px;">الريادة في التجارة العالمية • العقارات • حلول الدفع الرقمية</p>
</header>

<div class="card">
    <h3 style="color:var(--gold); border-right: 4px solid var(--gold); padding-right: 10px;">🏠 العقارات والخدمات اللوجستية</h3>
    <p style="font-size: 13px; opacity: 0.9;">استكشف فرص الاستثمار العقاري والخدمات التجارية العابرة للحدود.</p>
    <div class="grid">
        <img src="https://via.placeholder.com/400x300.png?text=Global+Trade" alt="Trade">
        <video controls>
            <source src="your-property-video.mp4" type="video/mp4">
        </video>
    </div>
    <a href="https://wa.me/905550654474" class="btn">📱 تواصل مع المستشار التجاري (WhatsApp)</a>
</div>

<div class="card" style="text-align: center; background: linear-gradient(135deg, #002244 0%, #003366 100%);">
    <h3 style="color:var(--gold);">⚡ بوابة الدفع الآمنة Pi Wallet</h3>
    <p style="font-size: 12px; line-height: 1.6;">بصفتنا شريكاً في نظام Pi Ecosystem، نقبل الدفع مقابل العقارات والخدمات التجارية عبر المحفظة الرسمية.</p>
    <button class="btn btn-pi" onclick="alert('سيتم توجيهك للمحفظة عند إتمام المراجعة')">Pay with Pi Wallet</button>
</div>

<div class="card">
    <h3 style="color:var(--gold);">🤝 طلب انضمام كشريك أو وكيل</h3>
    <form>
        <input type="text" placeholder="الاسم الكامل / اسم الشركة الموفرة" required>
        <select required>
            <option value="" disabled selected>نوع التعاون التجاري</option>
            <option value="real-estate">مطور عقاري / مالك</option>
            <option value="trade">تاجر جملة / استيراد وتصدير</option>
            <option value="logistics">خدمات شحن ولوجستيك</option>
        </select>
        <textarea rows="4" placeholder="يرجى كتابة تفاصيل العرض أو الطلب هنا..."></textarea>
        <button type="submit" class="btn">إرسال البيانات للمراجعة</button>
    </form>
</div>

<div class="card" style="font-size: 12px; opacity: 0.9;">
  <details>
    <summary>⚖️ الشروط والأحكام | Terms & Conditions</summary>
    <div style="margin-top: 15px; border-top: 1px solid #444; padding-top: 10px; text-align: justify;">
      <p><strong>العربية:</strong> باستخدامك لمنصة MONEEB GLOBAL، فإنك توافق على أننا منصة وسيطة لتسهيل التجارة والعقارات. جميع معاملات Pi تتم برضا الطرفين والمنصة غير مسؤولة عن أخطاء التحويل الشخصية.</p>
      <hr style="border: 0.5px solid #333;">
      <p><strong>English:</strong> By accessing MONEEB GLOBAL, you agree to our terms as a trade and real estate facilitator. Pi transactions are peer-to-peer and conducted at your own discretion.</p>
    </div>
  </details>
</div>

<footer style="text-align: center; color: var(--gold); padding: 30px; font-size: 11px; opacity: 0.7;">
  &copy; 2026 MONEEB GLOBAL | منصة موثقة في Pi Network Browser
</footer>

</body>
</html>
