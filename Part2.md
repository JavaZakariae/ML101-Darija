<h1 dir="rtl" lang="ar">#الجزء_الثاني :</h1>
<p dir="rtl" lang="ar">
السلام عليكم، بعدما شرحت ليكم بعض الاساسيات في الذكاء الإصطناعي، اليوم غانزيد حوايج اخرين اللي داخلين حتاهوما فالأساسيات. غاندوي على شنو هوما انواع استعمالات(types of usage) الذكاء الاصطناعي ؟ و شنو خاص يكون متوفر باش تبدى فالمجال؟
كاين عندنا زوج أنواع استعمالات :

</p>
<ul dir="rtl" lang="ar">
<li >
لوكال اي (Local AI) هو فاش الخوارزميات كايكونو عندك فالحاسوب تاعك أي كتخدم لوكال بدون الاتصال الى اي REST API. و هنا غايخصك تعلم شوي تاع الخوارزميات باش تعرف تخدم ف الماشين ليرنينغ، object reognition، face recognition،… اي حاجة عندها علاقة بمعالجة الصور داخليا على الجهاز. غايخصك تكون competent فلغات البرمجة اللي كتخدم بها و اللي عندهم مكتبات في ai بحال البايثون ولا سويفت ...الخ و غايخصك شي حاسوب مزيان ذو اداء عالي حيت كاينة واحد الحاجة سميتها تدريب تاع lmodules كتدخل data و تدير classification, و هاد العملية كتسمى تدريب البيانات و كاتطلب ما يقارب 30 تال 45 دقيقة فشي حاسوب اللي high performance و بالنسبة لشي حاسوب متوسط اليبرفورمانس تقدر توصل فيه هاد العملية الى ساعات. كايبان اللي هاكا غانكون فسرت ليك هاد البلان و شنو خاصك بالنسبة ليه.
</li>
<li>إن كلاود أي (In-Cloud AI) بكل بساطة هو فاش هاد الخوارزميات كايكونو فالكلاود واللي كيخليك انك تستخدم دوك الخورازميات في اي حاسوب بغيتي عن طريق تقديم REST API (هو اللي كايخلي تبادل البيانات يكون بين زوج أنظمة مختلفين و غالبا كايستعن ببروتوكل الاتصال http، و عندو 4 ديال lmethodes و اللي هي get , post ,put,delete،..الخ و غير هاذا خاصو منشور خاص بيه على حسب مكايبان لي.) أوك قولينا أخاي إسماعيل شنو خصنا باش نبداو نخدمو بـ In-Cloud AI ، هنا ماشي بزاف غاخصك تكون عندك مهارات برمجية حيت غايخصك تتبادل البيانات مع الكلاود اللي غادي يدرا ليها تدريب. و غايخصك تكون كتعرف تخدم ب les fichiers json او xml حيت فاش كتصيفط البيانات للسيرفر او كتستقبلها كيجو ليك sous forme json ou xml ، و غايخص يكون عندك شوي مع الشبكات هههه و ما أدراك الشبكات المهم الأساسيات وصافي بحال تعرف كيفاش تربط بين الخوادم Les serveurs ، حيت غاتكون مثلا عندك واحد الداتا و بغيتي تشاركها مع أكثر من سيرفر، المهم ضروري شي بركة ف networks. كنظن دابا عرفتي شنو خاصك يكون عندك و ايلا لاحظتي هنا ماقلتش ليك pc مزيان حيت التدريب تاع البيانات ماغايكونش ف الحاسوب ديالك .
</li>
</ul>
<p dir="rtl" lang="ar">
أوك دابا باش يتم اتخاذ القرار خاص يكونو بعدا عندنا معلومات ( DATA ) ، و انطلاقا من هاد المعلومات كيتم اتخاذ القرار. و لكن باش نوضح ليك أكثر تخيل نتا أستاذ كتصحح الأوراق د الامتحانات ديال التلاميذ ديالك. كتقرى الجواب كتشوف واش صحيح ولا لا و كتعطيه النقطة و هكذا تماما كيخدم الذكاء الاصطناعي كايحاول يتخذ واحد القرار فبلاصتك بنفس التفكير ديالك أ السي المصحح بناءا على المعلومات اللي ديجا علمناها الحاسوب من قبل حيت نتا قبل ماتصحح اعتمدتي على معلومات عندك فبالك حول المادة اللي كتقري.
أوك كيفاش كنعلمو الحاسوب هاد المعلومات ؟

</p>
<p dir="rtl" lang="ar">
أوك دابا غاتكون دختي و ماعرفتي باش غاتخدم ؟ 
ايلا كان ممكن تقراو هادشي اللي كنكتب دابا و فنفس الوقت شوفو فالصورة اللي حطيت مع المنشور.

</p>
<p dir="rtl" lang="ar">
بالنسبة local ai ديما غايخصك تكون عندك مهارات أكثر مقارنة مع in-cloud ai، ايضا بالنسبة usability فتخيل انك خدمتي ب local ai و خدمتي بخوارزميات اللي كاتديطيكتي واحد object راه فاش غاتجي تخدم بشي لغة برمجة اخرى ماغاديش يخدمو ليك دوك الخوارزميات على عكس in-cloud ai غاتصيفط غير request و ترجع ليك response و ديتيكتا ل object و هانتا بيخير. أخوتي دابا كتكتب و ماعرفتكم واش غاتفهموني ولا لا ههه المهم للي مافهمش شي حاجة بيناتنا التعليقات و لا دوزو privé. حاجة اخرى اللي هي اللغات البرمجية غايخص تكون نيت شاد مزياااان اللغة البرمجية اللي كتخدم بها و اللي عندها مكتبات ف ai هادشي فحالة خدمتي ب local ai ماشي بحال ايلا خدمتي بـ in-cloud ai و راه ديجا شرحت علاش فلفوق. و اخيرا بالنسبة ل perfermance ماخاتحاجش حاسوب ذو اداء عالي حيت اغلبية الحواسيب اللي كايتباعو راه ماداروش على قبل تدرييب البيانات و كيفما قلت من قبل هاد العملية كاتخاذ وقت و كتبغي اداء الجهاز يكون مجهد ، يعني دابا غير من هاد ل graph اللي شرحت ليك غايبان ليك باش تخدم.
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/44703725/55366066-ad601300-54d6-11e9-92f4-ecb3fc737f63.jpg" width="700" >
</p>
<p dir="rtl" lang="ar">
كنظن غاتكون دابا وليتي قادر تفرق بين AI و ML ، و دابا بغيت ندوز بيك les catégories تاع ai و فين تقدر تخصص ايلا بغيتي تكمل ف المجال و اللي هوما : البحث العلمي، سونطر دابيل و المساعد الوهمي، الطب، الالعاب،.برمجة التطبيقات...الخ
كنتمنى تكونو استفدتو شوي و عرفتو كيفاش الالة كتعلم و كيفاش كاتخاذ القرار و كتستافد من الاخطاء.

</p>
<p dir="rtl" lang="ar">
اوك باينة فكرتي فانك تخدم ب in-cloud ai، مزيان خليني نشرح ليكم كيفاش كايخدم فمثلا واحد المستعمل تاع الموقع ديالك دخل واحد الصورة و بغى يعرفها شنوهي، الصورة غاتوصل الخادم تاعك من بعد الخادم تاعك غايصفطها للخادم للي فيه خورزميات الذكاء الاصطناعي و فاش تجيه response غايصفط response للمستعمل للي مزال كايتسنى. و هكا كاتكون تدارت image recognition غير ف الكلاود و بسرعة قوية.
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/44703725/55366097-c963b480-54d6-11e9-9dbd-2f8cb2a0ab25.jpg" width="700" >
</p>
<p dir="rtl" lang="ar">
كنتمنى تكونو فهمتو شوي، بصراحة راه صعيب تكتب محتوى تشرح للناس ههه،كندير للي فجهدي باش توصل ليكم الفكرة.
</p>
<p dir="rtl" lang="ar">
إسماعيل فداوي ❤️
</p>
