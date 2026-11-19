# حزمة مراجعة TypeScript 7.0.2 من upstream

هذه حزمة مراجعة محلية لنسخة npm الرسمية `typescript@7.0.2`. ملف التوزيعة `typescript-7.0.2.tgz` هو الأرشيف الرسمي كما نُشر؛ لم يُعاد ضغطه أو تعديله. أُرفقت منه نسخ مطابقة للملفات upstream المتعلقة بالترخيص والإشعارات فقط.

## المصدر والتحقق

المصدر هو [صفحة الإصدار على npm](https://www.npmjs.com/package/typescript/v/7.0.2)، و[metadata الرسمية للإصدار](https://registry.npmjs.org/typescript/7.0.2)، ومنها رابط [أرشيف التوزيعة](https://registry.npmjs.org/typescript/-/typescript-7.0.2.tgz). metadata تسجل `dist.integrity` بقيمة `sha512-8FYau96o3NKOhbjKi/qNvG/W5jhzxkbdm5sj9AbZ/5T5sWqn3hJgLfGx27sRKZWTvyzCP8dLRBTf5tBTSRVUNA==` وSHA-1 `9ec773d7954a8c182c17cc5bbd575aa28bc51582`. طابق الملف المحلي القيمتين، وفُحصت سلامة gzip و416 ملفًا داخل الأرشيف. راجع [provenance.json](provenance.json) و[CHECKSUMS.txt](CHECKSUMS.txt) للتفاصيل والـhashes المحسوبة.

تُظهر بيانات npm و`package/package.json` داخل الأرشيف الإصدار `7.0.2` والترخيص المعلن `Apache-2.0`. أسماء ملفات الترخيص والإشعارات الفعلية في هذه التوزيعة هي `LICENSE` و`NOTICE.txt` و`vendor/vscode-jsonrpc/License.txt`؛ لا يحتوي الأرشيف على `LICENSE.txt` أو `ThirdPartyNoticeText.txt` بالاسمين المتوقعين أولًا. الملفات المنسوخة هنا مستخرجة حرفيًا من الأرشيف الذي اجتاز التحقق.

## حدّ الترخيص

ملفات TypeScript المنقولة هي مواد upstream؛ لا يشملها MIT الخاص بأي مواد أصلية في مستودع مضيف. يظل ترخيص Apache-2.0 upstream وشروط الإشعارات التابعة والملف المرخّص للمكوّن vendor هي المرجع لهذه المواد. لا يغيّر MIT لمحتوى أصلي منفصل هذه الشروط ولا يحل محلها. لا تُزل `NOTICE.txt` أو `vendor/vscode-jsonrpc/License.txt` عند إعادة التوزيع. هذا بيان نطاق للمراجعة، وليس استشارة قانونية.

## ملاحظة مطابقة المصدر

لم تُنسخ ملفات ترخيص منفصلة من GitHub: صفحة raw للعلامة `v7.0.2` أظهرت `package.json` بإصدار `6.0.0`، كما أعاد استعراض محتويات GitHub روابط إلى `main`. لتجنّب خلط ملفات غير مطابقة، اعتُمدت التوزيعة المنشورة في npm وملفات الرخصة/الإشعارات المستخرجة من الأرشيف نفسه. لم تُثبّت الحزمة أو تُشغّل؛ هذا فحص مصدر وسلامة فقط.
