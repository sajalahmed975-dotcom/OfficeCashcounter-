Office Cash Counter Pro - Android Studio Project

এই ZIP-এ আপনার দেওয়া HTML অ্যাপটি Android WebView অ্যাপ হিসেবে রাখা হয়েছে।

APK তৈরি করতে:
1. Android Studio ইনস্টল করুন।
2. ZIP Extract করে OfficeCashCounterAndroid ফোল্ডারটি Android Studio থেকে Open করুন।
3. Gradle Sync শেষ হতে দিন (প্রথমবার ইন্টারনেট লাগতে পারে)।
4. Build > Build Bundle(s) / APK(s) > Build APK(s) নির্বাচন করুন।
5. APK পাওয়া যাবে: app/build/outputs/apk/debug/app-debug.apk

নোট:
- অ্যাপের HTML ফাইল app/src/main/assets/index.html-এ আছে।
- PDF তৈরির জন্য HTML-এ html2pdf.js CDN ব্যবহার করা হয়েছে, তাই PDF ফিচারের জন্য ইন্টারনেট সংযোগ প্রয়োজন।
- এটি Android Studio-তে build করার জন্য প্রস্তুত প্রজেক্ট; এই পরিবেশে Android SDK/Gradle build system না থাকায় সরাসরি APK কম্পাইল করা সম্ভব হয়নি।
