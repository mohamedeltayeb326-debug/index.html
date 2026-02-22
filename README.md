<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MONEEB GLOBAL</title>
    <style>
        :root { --gold: #D4AF37; --navy: #001329; }
        body { background: var(--navy); color: white; font-family: sans-serif; direction: rtl; margin: 0; padding-bottom: 30px; }
        header { text-align: center; padding: 25px; border-bottom: 3px solid var(--gold); }
        .card { border: 1px solid var(--gold); border-radius: 12px; margin: 15px; padding: 15px; background: #002244; box-shadow: 0 4px 10px rgba(0,0,0,0.3); }
        .grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
        .btn { display: block; background: var(--gold); color: var(--navy); text-align: center; padding: 12px; border-radius: 8px; font-weight: bold; text-decoration: none; margin-top: 10px; border: none; width: 100%; cursor: pointer; transition: 0.3s; }
        .btn:hover { opacity: 0.8; transform: scale(0.98); }
        input, select, textarea { width: 100%; padding: 12px; margin: 8px 0; border-radius: 8px; border: 1px solid var(--gold); background: #001329; color: white; box-sizing: border-box; font-size: 14px; }
        img, video { width: 100%; height: 130px; object-fit: cover; border-radius: 8px; border: 1px solid var(--gold); }
        summary { color: var(--gold); font-weight: bold; cursor: pointer; text-align: center; list-style: none; padding: 5px; }
        .trading-section { background: linear-gradient(45deg, #001329, #002244); padding: 10px; border-radius: 8px; margin-top: 10px; }
    </style>
</head>
<body>

<header>
    <h1 style="color:var(--gold); margin:0; font-size: 28px;">MONEEB GLOBAL</h1>
    <p style="font-size: 14px; opacity: 0.9;">التجارة العالمية • العقارات • حلول Pi الآمنة</p>
</header>

<div class="card">
    <h3 style="color:var(--gold); margin-top: 0;">🏡 معرض العقارات والخدمات</h3>
    <div class="grid">
        <img src="https://via.placeholder.com/400x300.png?text=Property+Image" alt="Real Estate">
        <video controls>
            <source src="your-video-link.mp4" type="video/mp4">
            متصفحك لا يدعم تشغيل الفيديو.
        </video>
    </div>
    <a href="https://wa.me/249123456789" class="btn">💬 استفسر الآن عبر واتساب</a>
</div>

<div class="card">
    <h3 style="color:var(--gold); margin-top: 0;">📦 التجارة والخدمات اللوجستية</h3>
    <div class="trading-section">
        <p style="font-size: 13px; line-height: 1.5;">نقدم حلول الاستيراد والتصدير، الوساطة التجارية، وإدارة المشاريع العالمية بمرونة وسرعة.</p>
        <div class="grid">
            <button class="btn" style="font-size: 12px; padding: 8px;">تصفح الخدمات</button>
            <button class="btn" style="font-size: 12px; padding: 8px; background: #fff; color: #000;">طلب عرض سعر</button>
        </div>
    </div>
</div>

<div class="card">
    <h3 style="color:var(--gold); margin-top: 0;">📝 انضم كشريك (تاجر / صاحب عقار)</h3>
    <form>
        <input type="text" placeholder="الاسم الكامل أو اسم الشركة" required>
        <select>
            <option value="" disabled selected>اختر نوع النشاط</option>
            <option value="real-estate">تسويق عقاري</option>
            <option value="trade">تجارة عامة (استيراد وتصدير)</option>
            <option value="services">خدمات مهنية وتقنية</option>
        </select>
        <textarea rows="3" placeholder="اكتب تفاصيل العرض أو المنتج الذي تقدمه..."></textarea>
        <button type="submit" class="btn" style="background: var(--gold);">إرسال البيانات للمراجعة</button>
    </form>
</div>

<div class="card" style="text-align:center; border: 2px dashed var(--gold);">
    <h3 style="color:var(--gold); margin: 0;">⚡ الدفع عبر محفظة Pi</h3>
    <p style="font-size: 12px; margin: 10px 0;">ندعم المعاملات الآمنة باستخدام عملة Pi لجميع خدماتنا.</p>
    <button class="btn" style="background: white; color: black; border: 1px solid #ccc;">Pay with Pi Wallet</button>
</div>

<div class="card" style="font-size: 12px; opacity: 0.9; line-height: 1.6;">
  <details>
    <summary>⚖️ الشروط والأحكام | Terms & Conditions</summary>
    <div style="margin-top: 10px; border-top: 1px solid #444; padding-top: 10px; text-align: justify;">
      <p><strong>العربية:</strong> إن استخدامك لمنصة MONEEB GLOBAL يعني موافقتك على شروط الوساطة التجارية. المنصة توفر الربط التقني ولا تتحمل مسؤولية جودة السلع أو العقارات المعروضة.</p>
      <hr style="border: 0.5px solid #333;">
      <p><strong>English:</strong> By using MONEEB GLOBAL, you agree that we are a service provider. We are not responsible for the quality of third-party listings.</p>
    </div>
  </details>
</div>

<footer style="text-align: center; color: var(--gold); padding: 20px; font-size: 11px;">
  &copy; 2026 MONEEB GLOBAL | Powered by Pi Network Ecosystem
</footer>

</body>
</html>
