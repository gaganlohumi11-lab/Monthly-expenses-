# Monthly expenses — Android project

ऐप का नाम: Monthly expenses
रंग: Green
Package: com.monthlyexpenses.app

## APK बनाने का तरीका
1. Android Studio खोलें।
2. File > Open चुनें और इस ZIP से निकाला हुआ `MonthlyExpensesAndroid` फ़ोल्डर खोलें।
3. Android SDK Platform 35 और JDK 17 उपलब्ध होने दें।
4. Gradle sync पूरा होने दें।
5. Build > Build Bundle(s) / APK(s) > Build APK(s) चुनें।
6. APK `app/build/outputs/apk/debug/app-debug.apk` में मिलेगी।

## ऐप में शामिल
- मासिक आमदनी, कुल खर्च और बची रकम
- किराया, राशन, सब्जी, दूध, बिजली, पानी और अन्य खर्च
- तारीख व विवरण के साथ खर्च एंट्री
- महीने के अनुसार रिकॉर्ड
- CSV export और JSON backup

डेटा Android WebView के local browser storage में रहता है। ऐप का डेटा हटाने या ऐप uninstall करने से पहले JSON बैकअप डाउनलोड कर लें।
