from pathlib import Path

html = r'''<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#081326">
<meta name="description" content="دعوة زفاف Mohamed & Esraa يوم 10 نوفمبر 2026 في نادي الجلاء.">
<meta name="robots" content="index, follow">
<meta name="author" content="Mohamed & Esraa">
<meta property="og:title" content="Mohamed & Esraa - Wedding Invitation">
<meta property="og:description" content="يسعدنا دعوتكم لحضور حفل زفاف Mohamed & Esraa يوم 10 نوفمبر 2026 في نادي الجلاء.">
<meta property="og:type" content="website">

<title>دعوة زفاف | Mohamed &amp; Esraa</title>

<style>
:root{--navy:#071326;--navy2:#0c1d35;--gold:#d6b36a;--gold2:#f0d99b;--cream:#fff4d7}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:#050d1a;color:var(--cream);font-family:Tahoma,Arial,sans-serif}
button,input,select{font:inherit}
.page{max-width:480px;margin:auto;min-height:100vh;overflow:hidden;background:
 radial-gradient(ellipse at 50% 15%,#1b2b43 0,#0b1930 42%,#050d1b 100%);position:relative}
.page:before{content:"";position:absolute;inset:0;pointer-events:none;opacity:.32;background-image:
 radial-gradient(2px 2px at 20% 12%,#f5d995 50%,transparent 60%),
 radial-gradient(1px 1px at 78% 8%,#fff 50%,transparent 60%),
 radial-gradient(1px 1px at 65% 27%,#f5d995 50%,transparent 60%),
 radial-gradient(2px 2px at 13% 39%,#fff 50%,transparent 60%),
 radial-gradient(1px 1px at 88% 48%,#f5d995 50%,transparent 60%),
 radial-gradient(1px 1px at 33% 61%,#fff 50%,transparent 60%),
 radial-gradient(2px 2px at 72% 74%,#f5d995 50%,transparent 60%)}
.section{position:relative;padding:40px 28px;text-align:center}
.frame{border:1px solid #b89652;outline:1px solid #6e572f;outline-offset:5px;margin:14px;position:relative}
.moon{position:absolute;top:28px;left:28px;color:var(--gold2);font-size:35px;filter:drop-shadow(0 0 12px #e9c87a)}
.orn{color:var(--gold);font-size:22px;letter-spacing:7px;margin:8px 0 20px}
.kicker{font-size:10px;letter-spacing:3px;color:#d7c18e;direction:ltr}
.arabic-title{font-family:Georgia,"Times New Roman",serif;font-size:26px;color:var(--gold2);line-height:1.8;margin:22px 0}
.sub{font-size:14px;line-height:2;color:#e7dcc2}
.goldline{width:90px;height:1px;background:linear-gradient(90deg,transparent,var(--gold),transparent);margin:22px auto}
.names{direction:ltr;font-family:Georgia,"Times New Roman",serif;font-weight:normal;font-size:clamp(29px,8vw,42px);color:var(--gold2);margin:20px 0;line-height:1.5}
.names .name{display:inline-block;white-space:nowrap;overflow:hidden;vertical-align:bottom;width:0;animation:type 1.5s steps(16,end) forwards}
.names .one{animation-delay:.5s}.names .two{animation-delay:2s}
.amp{display:inline-block;opacity:0;animation:fade 1s 1.7s forwards;margin:0 8px;color:#fff0c5}
@keyframes type{to{width:var(--w);}}
@keyframes fade{to{opacity:1}}
@keyframes rise{from{opacity:0;transform:translateY(16px)}to{opacity:1;transform:none}}
.intro{min-height:100svh;display:flex;align-items:center;justify-content:center;padding:35px 24px}
.envelope{width:min(100%,340px);min-height:480px;display:flex;align-items:center;justify-content:center;flex-direction:column;position:relative;border:1px solid #a9894d;background:linear-gradient(145deg,#0d203a,#061126);box-shadow:0 20px 60px #0008;cursor:pointer;transition:transform .7s,opacity .7s}
.envelope:before{content:"";position:absolute;inset:10px;border:1px solid #66532f}
.seal{width:78px;height:78px;border-radius:50%;display:grid;place-items:center;border:2px solid var(--gold);background:radial-gradient(circle,#755a2c,#241d15);color:#f4dba0;font-size:28px;box-shadow:0 0 25px #d6b36a44;margin:24px}
.open-label{color:var(--gold2);font-size:14px;margin-top:24px}
.invite-content{display:none;animation:rise .8s ease both}
body.opened .intro{min-height:auto;padding:20px 24px 0}
body.opened .envelope{display:none}
body.opened .invite-content{display:block}
.date{direction:ltr;color:var(--gold2);font-size:22px;letter-spacing:2px;margin:12px 0}
.info-label{color:#c7b17d;font-size:12px;margin-top:20px}
.venue{font-size:22px;color:#fff0c5;margin:6px 0 12px}
.countdown{display:flex;direction:ltr;justify-content:center;gap:10px;margin:18px auto 0}
.countdown div{border:1px solid #8c7040;padding:10px 6px;min-width:62px;background:#071226b8}
.countdown strong{display:block;font-size:20px;color:var(--gold2);font-weight:normal}
.countdown small{font-size:10px;color:#c9b98e}
.arch{height:135px;margin:28px auto 5px;max-width:290px;border:1px solid #8f7040;border-bottom:0;border-radius:150px 150px 0 0;position:relative;background:linear-gradient(180deg,#152943,#091429)}
.arch:before,.arch:after{content:"";position:absolute;bottom:0;width:34px;height:72px;border:1px solid #9b7a42;border-bottom:0}
.arch:before{right:16px}.arch:after{left:16px}
.arch span{position:absolute;bottom:0;left:50%;transform:translateX(-50%);font-size:38px;color:#d5b36d;white-space:nowrap}
.card{border:1px solid #82683c;background:#071327b8;padding:22px 18px;margin-top:22px}
.card h2{font-family:Georgia,"Times New Roman",serif;font-weight:normal;color:var(--gold2);font-size:23px;margin:0 0 14px}
.form{display:grid;gap:12px;text-align:right}
.form label{font-size:12px;color:#d7c18e}
.form input,.form select{width:100%;border:1px solid #5c4b30;background:#09172b;color:#fff4d7;border-radius:2px;padding:12px;outline:none}
.form button,.mapbtn{border:1px solid var(--gold);background:linear-gradient(100deg,#6c5128,#b28b46);color:#fff7e2;padding:12px 18px;cursor:pointer;text-decoration:none;display:inline-block;margin-top:6px}
.note{font-size:11px;color:#bcae8d;line-height:1.8;margin-top:12px}
footer{padding:20px;text-align:center;font-family:Georgia,serif;letter-spacing:3px;color:#c4a568;font-size:11px}
@media(prefers-reduced-motion:reduce){*,*:before,*:after{animation:none!important;transition:none!important}.names .name{width:var(--w)}}
</style>
</head>
<body>
<main class="page">
  <section class="intro">
    <button class="envelope" id="openBtn" aria-label="افتح الدعوة">
      <div class="moon">☾</div>
      <div class="orn">✦ ❦ ✦</div>
      <div class="kicker">YOU ARE INVITED</div>
      <div class="seal">م &amp; إ</div>
      <div class="sub">بكل الحب، ندعوكم لمشاركتنا فرحتنا</div>
      <div class="open-label">اضغط لفتح الدعوة ✧</div>
    </button>
  </section>
  <div class="invite-content">
    <section class="section frame">
      <div class="moon">☾</div>
      <div class="orn">✧ ❦ ✧</div>
      <div class="kicker">WEDDING INVITATION</div>
      <div class="arabic-title">بسم الله الرحمن الرحيم<br>دعوة زفاف</div>
      <div class="sub">بكل الحب والسعادة،<br>يسعدنا دعوتكم لتشاركونا أجمل لحظات العمر</div>
      <div class="names"><span class="name one" style="--w:190px">Mohamed</span><span class="amp">&amp;</span><span class="name two" style="--w:135px">Esraa</span></div>
      <div class="goldline"></div>
      <div class="sub">حضوركم يزيد فرحتنا ويكمل سعادتنا</div>
      <div class="date">10 · 11 · 2026</div>
      <div class="sub">الثلاثاء · 10 نوفمبر 2026</div>
      <div class="info-label">مكان الاحتفال</div>
      <div class="venue">نادي الجلاء</div>
      <div class="arch"><span>✧</span></div>
      <div class="info-label">يتبقى على فرحتنا</div>
      <div class="countdown" id="countdown">
        <div><strong id="days">--</strong><small>يوم</small></div>
        <div><strong id="hours">--</strong><small>ساعة</small></div>
        <div><strong id="minutes">--</strong><small>دقيقة</small></div>
        <div><strong id="seconds">--</strong><small>ثانية</small></div>
      </div>
    </section>
    <section class="section">
      <div class="orn">✧ ❦ ✧</div>
      <div class="card">
        <h2>ننتظركم لنفرح معًا</h2>
        <p class="sub">يشرفنا حضوركم ومشاركتكم هذه المناسبة الغالية.<br>نتمنى أن تكون ليلة مليئة بالحب والذكريات الجميلة.</p>
        <div class="goldline"></div>
        <div class="sub">التاريخ</div><div class="date">10 / 11 / 2026</div>
        <div class="sub">المكان</div><div class="venue">نادي الجلاء</div>
      </div>
      <div class="card">
        <h2>تأكيد الحضور</h2>
        <p class="sub">يسعدنا معرفة ما إذا كنتم ستشاركوننا فرحتنا.</p>
        <form class="form" id="rsvp">
          <div><label for="guest">الاسم</label><input id="guest" name="guest" placeholder="اكتب اسمك" required></div>
          <div><label for="attendance">تأكيد الحضور</label><select id="attendance" name="attendance"><option>بإذن الله سأحضر</option><option>أعتذر عن الحضور</option></select></div>
          <div><label for="guests">عدد الحضور</label><select id="guests" name="guests"><option>شخص واحد</option><option>شخصان</option><option>3 أشخاص</option><option>4 أشخاص أو أكثر</option></select></div>
          <button type="submit">تجهيز رسالة التأكيد</button>
        </form>
        <p class="note" id="formNote">نموذج التأكيد يجهّز رسالة يمكنك إرسالها بنفسك؛ لا يتم إرسال بياناتك تلقائيًا.</p>
      </div>
    </section>
    <footer>MOHAMED &amp; ESRAA · WITH LOVE</footer>
  </div>
</main>
<script>
document.getElementById('openBtn').addEventListener('click',()=>{document.body.classList.add('opened');window.scrollTo({top:0,behavior:'smooth'});});
function tick(){
 const target=new Date('2026-11-10T19:00:00+02:00').getTime(), now=Date.now(), diff=target-now;
 if(diff<=0){document.getElementById('countdown').innerHTML='<div style="padding:12px;color:#f0d99b">فرحتنا بدأت! أهلاً بكم</div>';return;}
 const vals={days:Math.floor(diff/86400000),hours:Math.floor(diff%86400000/3600000),minutes:Math.floor(diff%3600000/60000),seconds:Math.floor(diff%60000/1000)};
 Object.keys(vals).forEach(k=>document.getElementById(k).textContent=String(vals[k]).padStart(2,'0'));
}
tick();setInterval(tick,1000);
document.getElementById('rsvp').addEventListener('submit',e=>{
 e.preventDefault();
 const name=document.getElementById('guest').value.trim();
 const attendance=document.getElementById('attendance').value;
 const guests=document.getElementById('guests').value;
 const msg=`تأكيد حضور فرح Mohamed & Esraa%0Aالاسم: ${encodeURIComponent(name)}%0A${encodeURIComponent(attendance)}%0Aعدد الحضور: ${encodeURIComponent(guests)}%0Aالتاريخ: 10/11/2026%0Aالمكان: نادي الجلاء`;
 const note=document.getElementById('formNote');
 note.innerHTML='تم تجهيز رسالة التأكيد. <a style="color:#f0d99b" href="https://wa.me/?text='+msg+'" target="_blank" rel="noopener">اضغط هنا لفتح واتساب وإرسالها</a>.';
});
</script>
</body>
</html>'''

path = Path("/mnt/data/mohamed_esraa_invitation_detailed.html")
path.write_text(html, encoding="utf-8")
print(f"تم إنشاء النسخة المدمجة بنجاح: {path}")
