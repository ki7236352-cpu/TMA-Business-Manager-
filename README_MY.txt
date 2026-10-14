TMA BUSINESS MANAGER — Android project

ဒီ ZIP ထဲမှာ Android Studio နဲ့ APK တည်ဆောက်နိုင်မယ့် project source ပါဝင်ပါတယ်။
APK ဖိုင်ကို ဒီနေရာမှာ compile လုပ်ထားတာ မဟုတ်သေးပါ။

APK တည်ဆောက်ရန်
1. Computer မှာ Android Studio ကို install လုပ်ပါ။
2. Android Studio > Open ကိုနှိပ်ပြီး ဒီ ZIP ကို extract လုပ်ထားတဲ့
   TMA_Business_Manager_Android_Project folder ကိုရွေးပါ။
3. Gradle sync ပြီးအောင်စောင့်ပါ။ SDK 35 မရှိလျှင် Android Studio က install လုပ်ရန်ပြပါလိမ့်မယ်။
4. Build > Build Bundle(s) / APK(s) > Build APK(s) ကိုနှိပ်ပါ။
5. APK ကို app/build/outputs/apk/debug/app-debug.apk မှာရနိုင်ပါတယ်။

မှတ်ချက်:
- App သည် internet permission မလိုဘဲ offline WebView အဖြစ် အလုပ်လုပ်ရန် ရည်ရွယ်ထားသည်။
- ဒေတာများကို app WebView local storage ထဲတွင်သိမ်းသည်။ App data ဖျက်ခြင်း/ပြန်တင်ခြင်းတွင် ဒေတာပျောက်နိုင်သောကြောင့် Backup ကိုသုံးပါ။
- Password သည် အခြေခံကာကွယ်မှုသာဖြစ်ပြီး sensitive data အတွက် မလုံလောက်ပါ။
