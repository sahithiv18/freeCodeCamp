---
id: 587d774c367417b2b2512a9c
title: إضافة بديل نصي للصور لضعاف البصر
challengeType: 0
videoUrl: 'https://scrimba.com/c/cPp7VfD'
forumTopicId: 16628
dashedName: add-a-text-alternative-to-images-for-visually-impaired-accessibility
---

# --description--

من المرجح أنك رأيت خاصية `alt` لوسم `img` في تحديات أخري. نص `alt` يصف محتوي الصورة ويوفر بديل نصي لها. هذا يساعد في حالة فشل الصورة في التحميل أو عدم قدرة المستخدم علي رؤيتها. تستخدم أيضا من قبل محركات البحث لفهم ما تحتوي عليه الصورة لتضمينها في نتائج البحث. إليك مثال:

```html
<img src="importantLogo.jpeg" alt="Company logo">
```

يعتمد الأشخاص الذين يعانون من إعاقات بصرية على برامج قراءة الشاشة لتحويل محتوى الويب إلى واجهة صوتية. لن يمكنهم الحصول على المعلومات المقدمة فقط بشكل بصري. في حالة الصور، يعتمد قارئ الشاشة على الوصول لخاصية `alt` وقراءة محتوياتها لإيصال المعلومات الرئيسية.

من خواص نص `alt` الجيد أنه يقدم شرحا مختصرا لمحتوى الصورة. يجب عليك دائما إضافة خاصية `alt` للصور التي تستخدمها. فبحسب مواصفات HTML5، تعد إضافة نص بديل للصور أمرا إلزاميا.

# --instructions--

كامبر القط هو نينجا في البرمجة وهو أيضا نينجا حقيقي، يقوم ببناء صفحة ويب لمشاركة معرفتة. الصورة الشخصية التي يريد استخدامها تظهر مهاراته ويجب أن تحظي بتقدير جميع زوار الموقع. أضف خاصية (attribute) `alt` في الوسم (tag) `img` لتظهر أن كامبر القط يجيد لعبة الكاراتية. (خاصية الصورة `src` لا ترتبط بملف فعلي، لذا يجب أن ترى نص `alt` في العرض.)

# --hints--

يجب أن يحتوي وسم `img` الخاص بك علي خاصية `alt` ويجب ألا يكون فارغا.

```js
assert($('img').attr('alt'));
```

# --seed--

## --seed-contents--

```html
<img src="doingKarateWow.jpeg">
```

# --solutions--

```html
<img src="doingKarateWow.jpeg" alt="Someone doing karate">
```