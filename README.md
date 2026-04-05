```
███████╗███╗   ███╗ █████╗ ██╗  ██╗
╚══███╔╝████╗ ████║██╔══██╗╚██╗██╔╝
  ███╔╝ ██╔████╔██║███████║ ╚███╔╝ 
 ███╔╝  ██║╚██╔╝██║██╔══██║ ██╔██╗ 
███████╗██║ ╚═╝ ██║██║  ██║██╔╝ ██╗
╚══════╝╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝
```

> **Advanced Penetration Simulation Framework v4.2.1**  
> `CLASSIFIED // FOR DEMONSTRATION PURPOSES ONLY`

---

## ما هو ZMAX؟

**ZMAX** هو موقع محاكاة اختراق أنظمة (Hacking Simulation) مصمم ليبدو واقعياً بشكل كامل.  
يعرض عملية اختراق مكونة من **6 مراحل** مع terminal حي، إحصائيات live، وخريطة شبكة متحركة.

---

## المميزات

| الميزة | التفاصيل |
|--------|----------|
| **Terminal تفاعلي** | اكتب أي أمر واضغط Enter لبدء الاختراق |
| **6 مراحل اختراق** | Init → Recon → Exploit → Credentials → Exfil → Cleanup |
| **Network Topology** | خريطة شبكة متحركة تظهر مسار الاختراق |
| **Live Stats** | IP، packets، data extracted، ping — كلها تتحدث لحظياً |
| **Resource Monitor** | CPU / Memory / Network / Disk bars متحركة |
| **Active Modules** | قائمة بكل module شغّال في الوقت الحقيقي |
| **3 Progress Bars** | Penetration / Data Exfil / Trace Erase |
| **Matrix Rain** | خلفية matrix متحركة |
| **Scanlines + Vignette** | تأثير شاشة CRT كلاسيكية |
| **Custom Cursor** | cursor مخصص بتصميم هكر |
| **Gallery** | الصور تظهر بعد نجاح الاختراق مع lightbox للتكبير |

---

## كيفية الاستخدام

```
1. افتح ملف zmax.html في أي متصفح
2. اكتب أي أمر في الـ terminal (مثلاً: hack، start، run، أي كلمة)
3. اضغط Enter
4. شاهد عملية الاختراق كاملة (~27 ثانية)
5. بعد الانتهاء تظهر الصور — اضغط على أي صورة للتكبير
```

---

## مراحل الاختراق

```
[PHASE 1/6]  INITIALIZATION     ← تحميل modules + TOR routing
[PHASE 2/6]  RECONNAISSANCE     ← scan المنافذ + OS fingerprinting
[PHASE 3/6]  EXPLOITATION       ← CVE-2024-4577 + privilege escalation
[PHASE 4/6]  CREDENTIAL HARVEST ← dump password hashes + brute force
[PHASE 5/6]  DATA EXFILTRATION  ← نقل الملفات مشفرة AES-256
[PHASE 6/6]  CLEANUP & ESCAPE   ← مسح الـ logs + إغلاق الـ tunnel
```

---

## التقنيات المستخدمة

```
HTML5          ← هيكل الصفحة
CSS3           ← تصميم + animations
JavaScript     ← منطق المحاكاة + Canvas animations
Canvas API     ← Matrix rain + Network topology
Google Fonts   ← Share Tech Mono / Orbitron
```

---

## ملفات المشروع

```
📁 ZMAX/
├── 📄 zmax.html      ← الملف الرئيسي (كل شيء مضمّن فيه)
└── 📄 README.md      ← هذا الملف
```

> **ملاحظة:** الصور مضمّنة داخل `zmax.html` كـ Base64 — لا تحتاج أي ملفات خارجية.

---

## متطلبات التشغيل

```
✅ أي متصفح حديث (Chrome / Firefox / Edge / Safari)
✅ لا يحتاج إنترنت (يعمل offline بالكامل)
✅ لا يحتاج server أو installation
✅ افتح الملف مباشرة وشغّله
```

---

## تحذير

```
⚠️  هذا المشروع للأغراض الترفيهية والتعليمية فقط
⚠️  لا يقوم بأي اختراق حقيقي
⚠️  جميع البيانات المعروضة وهمية ومولّدة عشوائياً
```

---

```
[ZMAX] ✓ README LOADED — MISSION BRIEFING COMPLETE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```
