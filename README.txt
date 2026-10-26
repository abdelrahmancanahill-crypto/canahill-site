موقع مؤسسة الكناهل الزراعية — canahill-agri.com.sa

رفع الموقع على GitHub Pages:
1) اعمل حساب على github.com ثم New repository باسم canahill-site (Public).
2) Add file > Upload files  وارفع كل محتويات الفولدر ده (index.html و CNAME وفولدر assets).
3) Settings > Pages > Source: Deploy from a branch > main / (root) > Save.
4) Custom domain: canahill-agri.com.sa (ملف CNAME موجود بالفعل).
5) في dnet > إدارة DNS ضيف:
   A    @    185.199.108.153
   A    @    185.199.109.153
   A    @    185.199.110.153
   A    @    185.199.111.153
   CNAME www  <اسم-حسابك>.github.io
6) بعد ما الدومين يتفعل، علّم على Enforce HTTPS.
