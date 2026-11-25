OLD METER RECEIVED - GitHub offline app

APK banane ka tareeqa (recommended):
1. GitHub par naya repository banayein (private bhi chalega).
2. Is zip ki saari files repository mein upload karein (Add file > Upload files).
   Agar .github folder upload na ho to Add file > Create new file mein naam likhein
   .github/workflows/apk.yml aur workflows_copy/apk.yml ka text paste karein.
3. Repository > Actions tab > "Build APK" > Run workflow.
4. 5-8 minute baad run khol kar neeche Artifacts se "old-meters-apk" download karein.
   Zip ke andar app-debug.apk hoga. Phone mein install karein
   (Install unknown apps allow karna paray ga).

Install ke baad app bilkul offline chalti hai. List, ACL aur fitter list usi phone mein save rehti hain.
Excel/CSV save karne par share sheet khulti hai (Files, Drive ya WhatsApp chunein).

GitHub Pages (optional): repository PUBLIC ho, Settings > Pages > Source: GitHub Actions.
Phir "Deploy Pages" chalayein, link Chrome mein khol kar "Install app" / "Add to Home screen" karein.
Repository mein sirf app ka code hai, koi data nahi, is liye public rakhna mehfooz hai.
