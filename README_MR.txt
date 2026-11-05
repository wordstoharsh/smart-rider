SMART RIDER – मोबाईलवरून वापरण्यासाठी PWA फाइल्स

या ZIP मध्ये index.html, manifest.json, sw.js आणि icon.svg आहेत.
हे APK नाही. Home Screen वर install करता येणारे वेब ॲप बनवण्यासाठी या फाइल्स HTTPS वेबसाइटवर प्रकाशित कराव्या लागतील.

महत्त्वाचे:
- GitHub Pages सारखी HTTPS hosting आवश्यक आहे.
- फक्त फोनमध्ये ZIP extract करून index.html उघडल्यास PWA install आणि GPS व्यवस्थित चालेलच असे नाही.
- Google Maps मधील live traffic/road ETA Maps मध्ये तपासा.
- Porter/WeFast account मध्ये login, private order import किंवा auto-accept होत नाही.
- Order pickup/drop पत्ते स्वतः भरावे लागतात.
- Route ordering हा प्राथमिक nearest-next-stop अंदाज आहे; deadline आणि live traffic चा पूर्ण solver नाही.

मोबाईलवर GitHub Pages वापरण्याची रूपरेषा:
1. Chrome मध्ये github.com उघडा आणि sign in करा / account तयार करा.
2. New repository तयार करा; नाव smart-rider ठेवा; Public निवडा.
3. Add file > Upload files वापरून या ZIP मधील चार फाइल्स upload करा (ZIP नव्हे, extract केल्यानंतरच्या फाइल्स).
4. Commit changes करा.
5. Repository Settings > Pages > Deploy from a branch > main > /(root) > Save.
6. GitHub Pages ने दिलेला https://...github.io/smart-rider/ पत्ता उघडा.
7. Chrome menu ⋮ > Add to Home screen / Install app निवडा.

पहिल्यांदा internet लागेल. GPS permission Allow करा. Driving करताना फोन हाताळू नका.
