DUKAAN UDHAR HISAB — ANDROID APP PROJECT

Yeh native Android WebView app project hai. Install hone ke baad yeh apne app icon se khulega, Chrome browser tab mein nahi.

Features:
- Sirf Date aur Amount
- Total amount aur current-month total
- History, entry edit/delete
- CSV backup download
- Entries app ke local browser storage mein save hoti hain

APK banane ka aasaan tareeka (online GitHub Actions):
1. ZIP ko extract karein.
2. GitHub par ek naya repository banayein.
3. Is folder ke saare files repository mein upload karein, including hidden .github folder.
4. Repository mein Actions tab kholein. "Build Dukaan Udhar APK" workflow run karein (ya main branch par push karein).
5. Workflow complete hone par "Dukaan-Udhar-APK" artifact download karein.
6. ZIP artifact extract karein; app-debug.apk ko Android phone mein bhej kar install karein.
7. Android agar pooche, to browser/files app ko "Install unknown apps" permission dein.

Important:
- Is ChatGPT runtime mein Android SDK/Gradle available nahi hai, isliye APK ko yahin compile karna possible nahi tha.
- ZIP source project hai, APK nahi. Workflow APK online build karne mein madad karta hai.
