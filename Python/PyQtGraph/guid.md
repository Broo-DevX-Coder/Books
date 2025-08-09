# 📘 **الدليل الشامل لـ PyQtGraph: من الصفر إلى الاحتراف**

> ✅ **الهيكل: 20 درسًا موسعًا حسب خطتك**  
> ✅ **اللغة: عربي، مع كود بالإنجليزية (كما هو متعارف عليه)**  
> ✅ **الجمهور: مبرمجون يعرفون Python ويرغبون في بناء واجهات رسومية تفاعلية عالية الأداء**

## ✅ 1. **فهرس كامل لدليل PyQtGraph**

1. [الدرس 1: مقدمة عن PyQtGraph](#)
2. [الدرس 2: التثبيت والإعداد](#)
3. [الدرس 3: مفهوم GraphicsWindow و PlotWidget](#)
4. [الدرس 4: PlotItem و ViewBox](#)
5. [الدرس 5: الرسم الخطي (Line Plot)](#)
6. [الدرس 6: الرسم التشتتي (Scatter Plot)](#)
7. [الدرس 7: رسم الأعمدة (Bar Graphs)](#)
8. [الدرس 8: عرض الصور (ImageView)](#)
9. [الدرس 9: التكبير والتحريك (Zoom & Pan)](#)
10. [الدرس 10: إضافة التعليقات (Annotations)](#)
11. [الدرس 11: التعامل مع الإشارات (Signals)](#)
12. [الدرس 12: الرسم اللحظي (Real-time plotting)](#)
13. [الدرس 13: الرسوم ثلاثية الأبعاد](#)
14. [الدرس 14: الخرائط اللونية (Color Maps)](#)
15. [الدرس 15: عرض عدة رسوم (Multiple Plots)](#)
16. [الدرس 16: دمج PyQtGraph في واجهات PyQt/PySide](#)
17. [الدرس 17: التصدير والحفظ](#)
18. [الدرس 18: مشروع عملي](#)


## 🗂 خطة تعلم PyQtGraph — من الصفر إلى الاحتراف

### **المرحلة 1: الأساسيات والفهم العام**

1. **مقدمة عن PyQtGraph**

   * ما هي المكتبة ولماذا تم تصميمها؟
   * الفرق بينها وبين Matplotlib وPlotly.
   * حالات الاستخدام في التحليل العلمي، عرض البيانات اللحظي (real-time plotting)، وتطبيقات GUI.
2. **التثبيت والإعداد**

   * تثبيت PyQtGraph وPyQt5 أو PySide6.
   * إنشاء نافذة عرض بسيطة.

---

### **المرحلة 2: فهم عناصر المكتبة الأساسية**

3. **مفهوم GraphicsWindow وPlotWidget**

   * الفرق بين PlotWidget وGraphicsLayoutWidget.
   * إنشاء نافذة بسيطة وعرض رسم خطي.

4. **PlotItem و ViewBox**

   * ما هو الـ PlotItem ودوره في التحكم في المحاور والعناوين.
   * فهم ViewBox للتكبير والتحريك.

---

### **المرحلة 3: أنواع الرسوم الأساسية**

5. **الرسم الخطي Line Plot**

   * رسم بيانات بسيطة باستخدام `plot()`.
   * تخصيص الألوان، الأنماط، والنقاط.

6. **الرسم التشتتي Scatter Plot**

   * استخدام `ScatterPlotItem`.
   * تغيير حجم وألوان النقاط.

7. **رسم الأعمدة Bar Graphs**

   * إنشاء أعمدة بسيطة.
   * تلوين الأعمدة وإضافة بيانات نصية.

8. **الصور ImageView**

   * عرض الصور والمصفوفات.
   * تطبيق colormaps والتحكم في السطوع/التباين.

---

### **المرحلة 4: الميزات التفاعلية والتحكم**

9. **التكبير والتحريك Zoom & Pan**

   * التحكم في عرض البيانات.
   * تعطيل/تفعيل التفاعلية.

10. **إضافة التعليقات Annotations**

    * رسم نصوص وأسهم على الرسم.
    * تخصيص الخطوط والألوان.

11. **التعامل مع الإشارات Signals**

    * ربط الأحداث مثل النقر على النقاط أو التحريك.
    * تنفيذ ردود أفعال لحظية.

---

### **المرحلة 5: الرسوم المتقدمة**

12. **الرسم اللحظي (Real-time plotting)**

    * تحديث البيانات في الوقت الحقيقي.
    * التعامل مع البيانات الكبيرة بسرعة.

13. **الرسوم ثلاثية الأبعاد**

    * استخدام `GLViewWidget`.
    * رسم الأسطح (Surface) والنقاط ثلاثية الأبعاد.

14. **الخرائط اللونية (Color Maps)**

    * التحكم في الألوان لتمثيل القيم.
    * استخدام Gradients مخصصة.

15. **Multiple Plots**

    * عرض عدة رسوم في نافذة واحدة.
    * مزامنة المحاور بين الرسوم.

---

### **المرحلة 6: الدمج مع مشاريع أكبر**

16. **دمج PyQtGraph في واجهات PyQt/PySide**

    * وضع الرسوم داخل QMainWindow أو QDialog.
    * إضافة أزرار وأدوات تحكم GUI.

17. **التصدير والحفظ**

    * حفظ الرسوم كصور.
    * أخذ لقطات من النوافذ.

18. **مشروع عملي**

    * مثل: برنامج لمراقبة أسعار العملات أو المستشعرات في الزمن الحقيقي.

### **المرحلة 7: المستوى الاحترافي**

19. **تحسين الأداء مع بيانات ضخمة**
    * استخدام `setData()` بكفاءة.
    * التعامل مع ملايين النقاط بدون بطء.

20. **التخصيص العميق**
    * إنشاء Widgets ورسوم مخصصة.
    * تعديل سلوك ViewBox وPlotItem.

# 📘 **الدرس 1: مقدمة عن PyQtGraph**

## 🔹 **ما هي PyQtGraph؟**

**PyQtGraph** هي مكتبة بايثون مبنية على **PyQt5/PySide6** تُستخدم لرسم البيانات بسرعة وكفاءة، خصوصًا في التطبيقات التي تتطلب:
- عرض بيانات في **الزمن الحقيقي (real-time)**
- تفاعلات سريعة (تكبير، تحريك، نقر)
- أداء عالٍ مع كميات كبيرة من البيانات

> 💡 تُستخدم في:  
> - أنظمة مراقبة المستشعرات  
> - أدوات التحليل الطيفي  
> - واجهات تداول العملات  
> - التجارب العلمية

---

## 🔹 **الفرق بين PyQtGraph و Matplotlib و Plotly**

| الميزة | PyQtGraph | Matplotlib | Plotly |
|-------|----------|------------|--------|
| الأداء | ⚡ عالي جدًا | متوسط | متوسط إلى منخفض |
| الزمن الحقيقي | ✅ ممتاز | ❌ ضعيف | ⚠️ محدود |
| التفاعلية | ✅ مدمجة | ❌ تحتاج إعداد | ✅ جيدة |
| التكامل مع GUI | ✅ ممتاز (مع PyQt) | ⚠️ ممكن لكن معقد | ✅ مع Dash |
| السهولة | متوسطة | عالية | عالية |

> ✅ **استخدم PyQtGraph عندما:**  
> - تحتاج تحديثات سريعة (مئات الإطارات في الثانية)  
> - تعمل على تطبيق ديسك توب (Desktop App)  
> - تعرض بيانات مستشعرات أو إشارات كهربائية

---

## 🔹 **حالات استخدام واقعية**

- 📈 عرض سعر السهم لحظيًا
- 🧪 تحليل إشارة كهربائية من جهاز قياس
- 🛰️ مراقبة بيانات مستشعرات IoT
- 🎮 واجهة تحكم في روبوت

---

## 🔹 **تمارين مراجعة**

1. ما الفرق بين PyQtGraph و Matplotlib من حيث الأداء؟
2. في أي مشروع تُفضل استخدام PyQtGraph؟
3. لماذا لا يُنصح باستخدام Matplotlib للرسم اللحظي؟

---

# 📘 **الدرس 2: التثبيت والإعداد**

## 🔹 **تثبيت PyQtGraph و PySide6 (موصى به)**

```bash
pip install pyqtgraph PySide6
```

> ✅ نوصي بـ **PySide6** لأنه مفتوح المصدر بالكامل ولا يتطلب ترخيصًا.

---

## 🔹 **إنشاء أول نافذة عرض**

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication
import sys

# إنشاء تطبيق Qt
app = QApplication(sys.argv)

# إنشاء نافذة عرض
win = pg.GraphicsLayoutWidget(show=True, title="أول نافذة في PyQtGraph")
win.resize(800, 600)

# عرض النافذة
if __name__ == '__main__':
    pg.exec()
```

> ✅ `show=True`: تُظهر النافذة فور الإنشاء  
> ✅ `title`: عنوان النافذة  
> ✅ `pg.exec()`: تبدأ حلقة الأحداث (Event Loop)

---

## 🔹 **النتيجة**
- نافذة بيضاء بعنوان "أول نافذة في PyQtGraph"
- يمكنك التكبير والتحريك بالفأرة

---

## 🔹 **الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| `ModuleNotFoundError` | لم تُثبّت المكتبة | `pip install pyqtgraph` |
| النافذة تفتح وتغلق فورًا | لم تُضف `pg.exec()` | أضف `pg.exec()` في النهاية |
| لا تظهر أي وظائف | استخدمت `import pyqtgraph` بدل `import pyqtgraph as pg` | استخدم `as pg` |

---

## 🔹 **تمارين**

1. غير حجم النافذة إلى 1000x700.
2. غيّر عنوان النافذة إلى "مشروع المراقبة".
3. أضف تعليقًا يشرح كل سطر في الكود.

---

## 🔹 **نصائح احترافية**

- استخدم `PySide6` بدل `PyQt5` لتجنب مشاكل الترخيص.
- احفظ هذا الكود كقالب أساسي لمشاريعك.
- استخدم `if __name__ == '__main__':` لمنع التنفيذ عند الاستيراد.


# 📘 **الدرس 3 (موسع): مفهوم GraphicsWindow و PlotWidget**

## 🔹 **مقدمة: ما هي وحدات العرض في PyQtGraph؟**

بعد أن أنشأت أول نافذة في PyQtGraph، حان الوقت لفهم **البنية الداخلية** للرسم.

في PyQtGraph، لا ترسم البيانات مباشرة على النافذة.  
بالتالي، ما هي العناصر التي تُستخدم لعرض الرسومات؟

الإجابة تكمن في فهم الفرق بين:
- **`PlotWidget`**
- **`GraphicsLayoutWidget`**

كلاهما يُستخدم لعرض الرسوم، لكن لكل منهما استخداماته وخصائصه.

---

## 🔹 **1. `PlotWidget` — أبسط طريقة لعرض رسم**

`PlotWidget` هو عنصر (Widget) جاهز يمكنك إضافته إلى واجهة PyQt، ويحتوي على:
- **رسم بياني واحد**
- **محور X وY**
- **أداة تكبير وتحريك مدمجة**
- **إمكانيات تخصيص عالية**

### 📌 المثال 1: إنشاء رسم خطي بسيط

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication
import numpy as np
import sys

app = QApplication(sys.argv)

# إنشاء نافذة تحتوي على PlotWidget
win = pg.plot(title="رسم خطي بسيط")
win.setLabel('left', 'القيمة')
win.setLabel('bottom', 'الزمن')
win.setXRange(0, 10)
win.setYRange(0, 100)

# بيانات بسيطة
x = np.arange(10)
y = np.array([10, 20, 25, 30, 50, 60, 75, 80, 90, 100])

# رسم البيانات
curve = win.plot(x, y, pen='b', symbol='o', symbolBrush='r', name='البيانات')

# عرض النافذة
if __name__ == '__main__':
    pg.exec()
```

#### 🔍 شرح الكود:
- `pg.plot()`: دالة سريعة لإنشاء `PlotWidget` وعرض رسم فورًا.
- `setLabel()`: لوضع عناوين للمحاور.
- `setXRange()`, `setYRange()`: لتحديد مدى العرض.
- `pen='b'`: خط أزرق.
- `symbol='o'`: نقاط دائرية.
- `symbolBrush='r'`: نقاط حمراء.

> ✅ هذا هو الشكل المثالي للرسومات البسيطة.

---

## 🔹 **2. `GraphicsLayoutWidget` — للرسومات المعقدة متعددة الأجزاء**

إذا أردت عرض **عدة رسومات في نافذة واحدة** (مثل: رسمين جنبًا إلى جنب، أو عموديًا)، فاستخدم `GraphicsLayoutWidget`.

### 📌 المثال 2: عرض رسمين في نافذة واحدة

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication
import numpy as np
import sys

app = QApplication(sys.argv)

# إنشاء نافذة متعددة الأجزاء
win = pg.GraphicsLayoutWidget(show=True, title="رسمان في نافذة واحدة")
win.resize(1000, 600)

# إنشاء أول رسم (صف 0، عمود 0)
p1 = win.addPlot(row=0, col=0, title="الرسم 1: جيب التمام")
x = np.linspace(0, 4*np.pi, 100)
y1 = np.cos(x)
p1.plot(x, y1, pen='g')

# إنشاء ثاني رسم (صف 0، عمود 1)
p2 = win.addPlot(row=0, col=1, title="الرسم 2: الجيب")
y2 = np.sin(x)
p2.plot(x, y2, pen='m')

# إضافة شبكة للرسم الثاني
p2.showGrid(x=True, y=True, alpha=0.5)

if __name__ == '__main__':
    pg.exec()
```

#### 🔍 شرح الكود:
- `addPlot(row, col)`: لإضافة رسم في موقع معين.
- `showGrid()`: لعرض شبكة خلفية.
- يمكنك إضافة أكثر من صف وعمود.

> ✅ مثالي لواجهات تتطلب عرض بيانات متعددة (مثل: مراقبة مستشعرات متعددة).

---

## 🔹 **3. الفرق بين `PlotWidget` و `GraphicsLayoutWidget`**

| الميزة | `PlotWidget` | `GraphicsLayoutWidget` |
|-------|--------------|-------------------------|
| الغرض | رسم واحد بسيط | عدة رسومات في نافذة واحدة |
| السهولة | عالية (`pg.plot()`) | متوسطة (يتطلب `addPlot`) |
| التحكم في التخطيط | محدود | كامل (صفوف وأعمدة) |
| الأداء | عالي | عالي |
| الاستخدام الشائع | تطبيقات بسيطة | واجهات متقدمة |

---

## 🔹 **4. متى تستخدم أيًا منهما؟**

| الحالة | الأداة الموصى بها |
|-------|-------------------|
| عرض رسم واحد بسيط | ✅ `PlotWidget` |
| رسم بيانات زمنية لحظية | ✅ `PlotWidget` |
| عرض 4 رسومات (2×2) | ✅ `GraphicsLayoutWidget` |
| بناء واجهة معقدة مع أدوات | ✅ `GraphicsLayoutWidget` |
| بدء تعلم PyQtGraph | ✅ `PlotWidget` |

---

## 🔹 **5. الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| `NameError: name 'pg' is not defined` | لم تستورد `pyqtgraph as pg` | تأكد من `import pyqtgraph as pg` |
| لا تظهر النافذة | نسيت `pg.exec()` | أضف `pg.exec()` في النهاية |
| الرسم فارغ | البيانات ليست من نوع `numpy array` أو `list` | تأكد من صحة البيانات |
| `addPlot()` لا يعمل | استخدمت `pg.plot()` بدل `GraphicsLayoutWidget` | استخدم `win = pg.GraphicsLayoutWidget()` |

---

## 🔹 **6. تمارين تطبيقية**

1. أنشئ `PlotWidget` يعرض منحنى تربيعي: `y = x²`.
2. غيّر لون الخط إلى أخضر، والنقاط إلى مثلثات (`t`).
3. أنشئ `GraphicsLayoutWidget` به 3 رسومات: في صف واحد.
4. في الرسم الأوسط، أضف شبكة عرض.

---

## 🔹 **7. الربط بالواقع: واجهة مراقبة مستشعرات**

### 🎯 الهدف: عرض بيانات 3 مستشعرات في وقت واحد

```python
# فرض بيانات مستشعرات (درجة حرارة، رطوبة، ضغط)
temp = np.random.rand(50) * 30 + 20  # 20-50°C
humi = np.random.rand(50) * 30 + 40  # 40-70%
pres = np.random.rand(50) * 10 + 980 # 980-990 hPa

# إنشاء النافذة
win = pg.GraphicsLayoutWidget(show=True, title="مراقبة المستشعرات")
win.resize(1200, 400)

# درجة الحرارة
p1 = win.addPlot(row=0, col=0, title="درجة الحرارة")
p1.plot(temp, pen='r', symbol='o', symbolBrush='r')

# الرطوبة
p2 = win.addPlot(row=0, col=1, title="الرطوبة")
p2.plot(humi, pen='b', symbol='t', symbolBrush='b')

# الضغط
p3 = win.addPlot(row=0, col=2, title="الضغط")
p3.plot(pres, pen='g', symbol='s', symbolBrush='g')

print("✅ واجهة المراقبة جاهزة للتشغيل اللحظي!")
```

> ✅ هذا النوع من الواجهات يُستخدم في الأنظمة الصناعية.

---

## 🔹 **8. نصائح احترافية**

1. ✅ ابدأ بـ `PlotWidget` إذا كنت مبتدئًا.
2. ✅ استخدم `GraphicsLayoutWidget` للتطبيقات المعقدة.
3. ✅ استخدم `pg.plot()` للتجريب السريع.
4. ✅ احفظ `win` و `p1`, `p2` كمتغيرات للوصول إليها لاحقًا.
5. ✅ استخدم `win.resize()` لضبط حجم النافذة.

---

## 🔹 **9. أسئلة مراجعة**

1. ما الفرق بين `pg.plot()` و `GraphicsLayoutWidget`؟
2. كيف تُضيف رسمًا في الصف 1 والعمود 0؟
3. ما وظيفة `showGrid()`؟
4. كيف تُغير شكل النقاط في الرسم؟
5. لماذا نستخدم `pg.exec()` في النهاية؟

---

## 🔹 **10. مراجعة سريعة (ملخص الدرس)**

| الأداة | الوظيفة |
|-------|--------|
| `pg.plot()` | إنشاء `PlotWidget` سريع |
| `PlotWidget` | عرض رسم واحد |
| `GraphicsLayoutWidget` | عرض عدة رسومات |
| `addPlot(row, col)` | إضافة رسم في موقع معين |
| `setLabels()` | تسمية المحاور |
| `showGrid()` | عرض شبكة |


# 📘 **الدرس 4 (موسع): PlotItem و ViewBox**

## 🔹 **مقدمة: ما هي وحدات التحكم في الرسم؟**

بعد أن تعلمت كيفية إنشاء نافذة عرض (`PlotWidget` أو `GraphicsLayoutWidget`)، حان الوقت لفهم **العناصر الداخلية** التي تُكوّن الرسم البياني نفسه.

في PyQtGraph، لا يتم رسم البيانات مباشرة على النافذة، بل عبر طبقة من العناصر تتحكم في كل شيء:
- المحاور (X و Y)
- العنوان
- الشبكة
- التكبير والتحريك
- حدود العرض

هذان العنصران الرئيسيان هما:
- **`PlotItem`**
- **`ViewBox`**

فهمهما يمنحك **تحكمًا دقيقًا** في شكل وسلوك الرسم.

---

## 🔹 **1. `PlotItem` — وحدة التحكم في الرسم**

### ✅ ما هو الـ `PlotItem`؟

`PlotItem` هو الكائن الذي يحتوي على:
- المحاور (Axis)
- العنوان (Title)
- الشبكة (Grid)
- جميع الخطوط والنقاط (الـ Items)
- الإعدادات العامة للرسم

> 💡 اعتبر أن `PlotItem` هو "الرسم البياني" نفسه، بينما `PlotWidget` هو "الإطار" الذي يحتويه.

---

### 📌 المثال 1: الوصول إلى `PlotItem` وتخصيصه

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication
import numpy as np
import sys

app = QApplication(sys.argv)

# إنشاء نافذة باستخدام PlotWidget
win = pg.plot(title="تخصيص PlotItem")
win.resize(800, 600)

# 1. الوصول إلى PlotItem
plot_item = win.getPlotItem()

# 2. تخصيص المحاور
plot_item.setLabel('left', 'الدرجة (°C)')
plot_item.setLabel('bottom', 'الزمن (ثانية)')

# 3. تعيين عنوان
plot_item.setTitle('بيانات مستشعر درجة الحرارة')

# 4. إضافة شبكة
plot_item.showGrid(x=True, y=True, alpha=0.3)

# 5. تحديد مدى العرض
plot_item.setXRange(0, 10)
plot_item.setYRange(15, 35)

# 6. إضافة بيانات
x = np.linspace(0, 10, 100)
y = 25 + 5 * np.sin(x) + np.random.normal(0, 0.5, 100)
plot_item.plot(x, y, pen='b', name='الدرجة')

if __name__ == '__main__':
    pg.exec()
```

#### 🔍 شرح الكود:
- `getPlotItem()`: يُرجع كائن `PlotItem` الموجود داخل `PlotWidget`.
- `setLabel()`: لوضع تسميات للمحاور.
- `showGrid()`: لعرض شبكة خلفية.
- `setXRange()`, `setYRange()`: لضبط حدود العرض.
- `plot()`: لإضافة بيانات إلى `PlotItem`.

> ✅ هذا هو الشكل المثالي للتحكم الكامل في الرسم.

---

## 🔹 **2. `ViewBox` — قلب التفاعلية**

### ✅ ما هو الـ `ViewBox`؟

`ViewBox` هو العنصر المسؤول عن:
- **التكبير (Zoom)**
- **التحريك (Pan)**
- **تحديد منطقة العرض**
- **التحكم في سلوك الفأرة**

> 💡 بدون `ViewBox`، لا يمكن التفاعل مع الرسم.

---

### 📌 المثال 2: التحكم في `ViewBox`

```python
# بعد الحصول على plot_item
view_box = plot_item.getViewBox()

# تعطيل التفاعلية (لإيقاف التكبير والتحريك)
# view_box.setMouseEnabled(False, False)

# تمكين التكبير فقط على المحور X
# view_box.setMouseEnabled(x=True, y=False)

# تغيير لون خلفية ViewBox
view_box.setBackgroundColor('w')  # أبيض
```

> ✅ مفيد في التطبيقات التي تحتاج تحكمًا دقيقًا في التفاعل.

---

### 📌 المثال 3: ربط حدث التحريك

```python
def on_pan():
    print("تم التحريك!")
    # يمكنك هنا تحديث عناصر أخرى في الواجهة

# ربط الحدث
view_box.sigXRangeChanged.connect(on_pan)
```

> ✅ `sigXRangeChanged`: يُطلق عند التكبير أو التحريك.

---

## 🔹 **3. الفرق بين `PlotWidget` و `PlotItem` و `ViewBox`**

| العنصر | الوظيفة | من يتحكم فيه؟ |
|-------|--------|--------------|
| `PlotWidget` | الحاوية (Widget) التي تُضاف إلى واجهة PyQt | أنت (كـ `QWidget`) |
| `PlotItem` | وحدة التحكم في الرسم (المحاور، العنوان، الشبكة) | `PlotWidget` |
| `ViewBox` | وحدة التفاعلية (التكبير، التحريك) | `PlotItem` |

> 🎯 التسلسل الهرمي:
> ```
> PlotWidget
>     └── PlotItem
>             └── ViewBox
>                     └── البيانات (الخطوط، النقاط...)
> ```

---

## 🔹 **4. الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| `AttributeError: 'PlotWidget' object has no attribute 'setLabel'` | حاولت استخدام `setLabel` على `PlotWidget` مباشرة | استخدم `getPlotItem().setLabel()` |
| لا يعمل التكبير | `setMouseEnabled(False)` | أعد تمكين الفأرة |
| لا تظهر الشبكة | نسيت `showGrid()` | أضف `showGrid(x=True, y=True)` |
| `sigXRangeChanged` لا يعمل | لم تُنشئ `ViewBox` بشكل صحيح | تأكد من `getViewBox()` |

---

## 🔹 **5. تمارين تطبيقية**

1. أنشئ `PlotWidget`، ثم استخدم `getPlotItem()` لتغيير لون خلفية `ViewBox` إلى رمادي فاتح.
2. عطّل التكبير على المحور Y فقط.
3. أضف دالة تُطبع "تم التكبير" عند تغيير مدى المحور X.
4. غيّر لون الشبكة إلى أخضر شفاف.

---

## 🔹 **6. الربط بالواقع: واجهة تحليل إشارة كهربائية**

### 🎯 الهدف: عرض إشارة كهربائية مع تحكم دقيق

```python
# فرض إشارة كهربائية (مثل ECG)
t = np.linspace(0, 5, 1000)
signal = 0.5 * np.sin(2*np.pi*5*t) + 0.1 * np.random.randn(1000)

# إنشاء النافذة
win = pg.plot()
plot_item = win.getPlotItem()
view_box = plot_item.getViewBox()

# التخصيص
plot_item.setLabel('left', 'الجهد (V)')
plot_item.setLabel('bottom', 'الزمن (ثانية)')
plot_item.setTitle('تحليل إشارة كهربائية')
plot_item.showGrid(x=True, y=True, alpha=0.5)
view_box.setBackgroundColor('k')  # خلفية سوداء للمحترفين

# رسم الإشارة
plot_item.plot(t, signal, pen='y')

# ربط حدث
def on_zoom():
    print(f"مدى X الحالي: {view_box.viewRange()[0]}")

view_box.sigXRangeChanged.connect(on_zoom)

print("📊 الواجهة جاهزة لتحليل الإشارات!")
```

> ✅ هذا النوع من الواجهات يُستخدم في الأجهزة الطبية والصناعية.

---

## 🔹 **7. نصائح احترافية**

1. ✅ استخدم `getPlotItem()` دائمًا عند الحاجة لتخصيص متقدم.
2. ✅ استخدم `getViewBox()` للتحكم في التفاعلية.
3. ✅ احفظ `plot_item` و `view_box` كمتغيرات للوصول السريع.
4. ✅ استخدم `setMouseEnabled()` لتعطيل الحركة عند الحاجة (مثلاً: أثناء التسجيل).
5. ✅ استخدم `sigXRangeChanged` لتحديث عناصر أخرى في الواجهة (مثل: عرض الوقت الحالي).

---

## 🔹 **8. أسئلة مراجعة**

1. ما الفرق بين `PlotWidget` و `PlotItem`؟
2. كيف تُغير لون خلفية `ViewBox`؟
3. ما وظيفة `showGrid()`؟
4. كيف تُعطل التكبير على محور معين؟
5. ما الفائدة من `sigXRangeChanged`؟

---

## 🔹 **9. مراجعة سريعة (ملخص الدرس)**

| العنصر | الوظيفة |
|-------|--------|
| `PlotWidget` | الحاوية الأساسية |
| `getPlotItem()` | للوصول إلى إعدادات الرسم |
| `setLabel()` | تسمية المحاور |
| `showGrid()` | عرض شبكة |
| `setXRange()` | ضبط مدى العرض |
| `getViewBox()` | للتحكم في التفاعلية |
| `setMouseEnabled()` | تمكين/تعطيل التكبير |
| `sigXRangeChanged` | ربط حدث التكبير |


# 📘 **الدرس 5 (موسع): الرسم الخطي (Line Plot)**


## 🔹 **مقدمة: لماذا الرسم الخطي هو الأساس؟**

الرسم الخطي (Line Plot) هو **أكثر أنواع الرسوم شيوعًا** في التحليل العلمي والهندسي.

يُستخدم لتمثيل:
- كيف تتغير قيمة ما مع الزمن (مثل: سعر السهم، درجة الحرارة)
- العلاقة بين متغيرين (مثل: السعر والطلب)
- الاتجاهات والأنماط في البيانات

في هذا الدرس، ستتعلم كيفية إنشاء رسم خطي باستخدام PyQtGraph، وتخصيصه بالكامل: الألوان، الأنماط، النقاط، والأساطير.

---

## 🔹 **1. إنشاء رسم خطي بسيط**

### 📌 المثال 1: رسم دالة جيب التمام

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication
import numpy as np
import sys

app = QApplication(sys.argv)

# إنشاء نافذة رسم
win = pg.plot(title="رسم دالة cos(x)")

# إنشاء البيانات
x = np.linspace(0, 4*np.pi, 100)  # 100 نقطة من 0 إلى 4π
y = np.cos(x)

# رسم البيانات
curve = win.plot(x, y)

if __name__ == '__main__':
    pg.exec()
```

#### 🔍 شرح الكود:
- `np.linspace()`: لتوليد نقاط متساوية.
- `win.plot(x, y)`: لرسم الخط.
- الناتج: منحنى جيب التمام.

> ✅ هذا هو الشكل الأساسي للرسم الخطي.

---

## 🔹 **2. تخصيص الخط (Pen)**

يمكنك تغيير لون، سمك، ونمط الخط باستخدام معامل `pen`.

### 📌 المثال 2: خط أخضر متقطع سميك

```python
curve = win.plot(x, y, pen=pg.mkPen(color='g', width=3, style=pg.QtCore.Qt.DashLine))
```

### ✅ خيارات `pen` الشائعة
| الخيار | القيمة | الوصف |
|--------|-------|------|
| `color` | `'r'`, `'g'`, `'b'`, `'#FF0000'` | لون الخط |
| `width` | `2`, `5` | سمك الخط (بكسل) |
| `style` | `Qt.SolidLine`, `Qt.DashLine`, `Qt.DotLine` | نمط الخط |

---

## 🔹 **3. إضافة النقاط (Symbols)**

لجعل الرسم أكثر وضوحًا، أضف نقاطًا على كل قيمة.

### 📌 المثال 3: خط مع نقاط دائرية حمراء

```python
curve = win.plot(x, y, 
                 pen='b', 
                 symbol='o',        # شكل النقطة: 'o', 's', 't', 'd'
                 symbolSize=8,      # حجم النقطة
                 symbolBrush='r',   # لون ملء النقطة
                 symbolPen='w')     # لون الحدودة
```

### ✅ أشكال النقاط (Symbols)
| الرمز | الشكل |
|------|------|
| `'o'` | دائرة |
| `'s'` | مربع |
| `'t'` | مثلث |
| `'d'` | الماس |
| `'+'` | علامة زائد |

---

## 🔹 **4. إضافة عنوان وأسماء المحاور**

لجعل الرسم مفهومًا، أضف تسميات.

```python
win.setLabel('left', 'القيمة (V)')
win.setLabel('bottom', 'الزمن (ثانية)')
win.setTitle('تحليل إشارة جيب التمام')
```

---

## 🔹 **5. إضافة الشبكة (Grid)**

لتسهيل القراءة.

```python
win.showGrid(x=True, y=True, alpha=0.5)
```

- `alpha`: درجة الشفافية (من 0 إلى 1)

---

## 🔹 **6. إضافة أسطورة (Legend)**

مفيد عند رسم أكثر من منحنى.

### 📌 المثال 4: رسم جيب التمام والجيب مع أسطورة

```python
win = pg.GraphicsLayoutWidget(show=True, title="دالتا الجيب والجيب تمامًا")
p1 = win.addPlot()

# بيانات
x = np.linspace(0, 4*np.pi, 100)
y1 = np.cos(x)
y2 = np.sin(x)

# رسم cos(x)
p1.plot(x, y1, pen='b', name='cos(x)', symbol='o', symbolSize=5)

# رسم sin(x)
p1.plot(x, y2, pen='r', name='sin(x)', symbol='t', symbolSize=5)

p1.showGrid(True, True, 0.3)
p1.setLabel('left', 'القيمة')
p1.setLabel('bottom', 'الزمن')
```

> ✅ `name=` هو ما يظهر في الأسطورة.

---

## 🔹 **7. الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| لا يظهر الخط | `pen=None` أو لون شفاف | تأكد من `pen='color'` |
| النقاط لا تظهر | نسيت `symbol` | أضف `symbol='o'` |
| الأسطورة لا تظهر | نسيت `name=` | أضف `name='الاسم'` |
| الشبكة لا تظهر | نسيت `showGrid()` | أضف `showGrid(True, True)` |

---

## 🔹 **8. تمارين تطبيقية**

1. ارسم منحنى تربيعي: `y = x²` من -10 إلى 10.
2. غيّر لون الخط إلى أرجواني، والنقاط إلى مربعات زرقاء.
3. أضف شبكة وشبّك الأسطورة باسم "المنحنى التربيعي".
4. أضف تسميات للمحور الرأسي "الناتج" والأفقي "المدخل".

---

## 🔹 **9. الربط بالواقع: عرض سعر السهم لحظيًا**

### 🎯 الهدف: محاكاة عرض سعر سهم

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication
import numpy as np
import sys

app = QApplication(sys.argv)

# نافذة عرض السعر
win = pg.plot(title="سعر السهم - التحديث اللحظي")
win.setLabel('left', 'السعر (ريال)')
win.setLabel('bottom', 'الزمن')
win.showGrid(y=True, alpha=0.3)

# بيانات وهمية لسعر السهم
time = np.arange(100)
price = 100 + np.cumsum(np.random.randn(100) * 0.5)  # مشي عشوائي

# رسم السعر
curve = win.plot(time, price, pen='c', symbol='o', symbolSize=6, symbolBrush='m', name='السعر')

print("📈 واجهة عرض السعر جاهزة!")

if __name__ == '__main__':
    pg.exec()
```

> ✅ هذا الشكل يُستخدم في لوحات التداول.

---

## 🔹 **10. نصائح احترافية**

1. ✅ استخدم `pg.mkPen()` لصنع ألوان متقدمة.
2. ✅ استخدم `alpha` في `symbolBrush` لجعل النقاط شفافة.
3. ✅ احفظ كائن `curve` إذا كنت ستحديثه لاحقًا.
4. ✅ استخدم `GraphicsLayoutWidget` إذا كنت سترسم أكثر من رسم.
5. ✅ استخدم `name=` فقط عند الحاجة إلى أسطورة.

---

## 🔹 **11. أسئلة مراجعة**

1. كيف تُغير لون الخط إلى أصفر؟
2. ما الفرق بين `symbolBrush` و `symbolPen`؟
3. كيف تُظهر الشبكة على المحور X فقط؟
4. ما وظيفة `name=` في `plot()`؟
5. كيف تُغير نمط الخط إلى منقط؟

---

## 🔹 **12. مراجعة سريعة (ملخص الدرس)**

| العنصر | الكود |
|-------|------|
| رسم خط | `plot(x, y)` |
| تغيير لون الخط | `pen='r'` أو `pen=pg.mkPen(...)` |
| إضافة نقاط | `symbol='o'` |
| تغيير حجم النقاط | `symbolSize=8` |
| ألوان النقاط | `symbolBrush='b'` |
| تسمية المحاور | `setLabel('left', '...')` |
| الشبكة | `showGrid(x=True, y=True)` |
| الأسطورة | `name='الاسم'` |


# 📘 **الدرس 6 (موسع): الرسم التشتتي (Scatter Plot)**

## 🔹 **مقدمة: ما هو الرسم التشتتي ولماذا هو مهم؟**

الرسم التشتتي (Scatter Plot) هو أداة قوية لتمثيل العلاقة بين **متغيرين عددين**.

يُستخدم لفهم:
- هل هناك **ارتباط** بين السعر والطلب؟
- كيف تتوزع النقاط في الفضاء (مثل: بيانات العملاء حسب العمر والدخل)؟
- اكتشاف **القيم الشاذة (Outliers)**

في هذا الدرس، ستتعلم كيفية إنشاء رسم تشتتي باستخدام `ScatterPlotItem`، وتخصيصه بالكامل: الألوان، الأحجام، والتفاعل.

---

## 🔹 **1. استخدام `ScatterPlotItem` — الطريقة الأساسية**

### 📌 المثال 1: رسم تشتتي بسيط

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication
import numpy as np
import sys

app = QApplication(sys.argv)

# إنشاء نافذة
win = pg.plot(title="رسم تشتتي: العلاقة بين X وY")
win.setLabel('bottom', 'X')
win.setLabel('left', 'Y')
win.showGrid(True, True, 0.3)

# بيانات وهمية
x = np.random.normal(size=100)
y = x * 0.5 + np.random.normal(size=100) * 0.3  # علاقة خطية

# إنشاء عنصر النقاط
scatter = pg.ScatterPlotItem(x=x, y=y, pen=None, brush='b', size=10)

# إضافة العنصر إلى النافذة
win.addItem(scatter)

if __name__ == '__main__':
    pg.exec()
```

#### 🔍 شرح الكود:
- `pg.ScatterPlotItem()`: يُنشئ مجموعة من النقاط.
- `pen=None`: لا حدود للنقاط.
- `brush='b'`: لون ملء النقطة (أزرق).
- `size=10`: حجم النقطة.
- `win.addItem(scatter)`: لإضافة العنصر إلى الرسم.

> ✅ مثالي للبيانات ذات الألوان والمقاييس المتغيرة.

---

## 🔹 **2. تخصيص شكل النقاط**

يمكنك تغيير شكل، حجم، ولون كل نقطة.

### 📌 المثال 2: نقاط متعددة الأشكال والألوان

```python
# بيانات
x = [1, 2, 3, 4, 5]
y = [2, 5, 3, 8, 7]
colors = ['r', 'g', 'b', 'c', 'm']  # أحمر، أخضر، أزرق، سماوي، أرجواني
sizes = [20, 30, 40, 50, 60]

# إنشاء النقاط
spots = []
for i in range(len(x)):
    spots.append({
        'pos': (x[i], y[i]),
        'size': sizes[i],
        'brush': colors[i]
    })

scatter = pg.ScatterPlotItem(spots=spots)
win.addItem(scatter)
```

> ✅ يمكنك استخدام قاموس لكل نقطة لتحكم دقيق.

---

## 🔹 **3. استخدام `plot()` لرسم تشتتي (طريقة مختصرة)**

إذا كنت لا تحتاج تحكمًا دقيقًا، يمكنك استخدام `plot()`.

```python
# طريقة أسرع
win.plot(x, y, pen=None, symbol='o', symbolBrush='r', symbolSize=10)
```

> ✅ نفس النتيجة، لكن أقل مرونة.

---

## 🔹 **4. ربط النقط بالخطوط (Scatter + Line)**

لعرض الاتجاه مع التوزيع.

```python
# رسم خط + نقاط
curve = win.plot(x, y, pen='g')  # خط أخضر
scatter = pg.ScatterPlotItem(x=x, y=y, brush='r', size=8)
win.addItem(scatter)
```

> ✅ مفيد في تتبع المسارات أو الإشارات.

---

## 🔹 **5. التحكم في الشفافية (Alpha)**

لحل مشكلة التداخل (Overplotting).

```python
# شفافية 50%
brush = pg.mkBrush(color=(255, 0, 0, 128))  # RGBA (الأخير هو alpha)
scatter = pg.ScatterPlotItem(x=x, y=y, brush=brush, size=10)
```

> ✅ `128` = 50% شفافية (من 0 إلى 255)

---

## 🔹 **6. الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| لا تظهر النقاط | `pen=None` و`brush=None` | تأكد من تعيين `brush` |
| الحجم صغير جدًا | `size=1` | زد قيمة `size` |
| الألوان لا تعمل | تمرير قائمة مباشرة | استخدم `spots` أو `mkBrush` |
| `addItem()` لا يعمل | استخدمت `plot()` بدل `addItem` | تأكد من استخدام `addItem` مع `ScatterPlotItem` |

---

## 🔹 **7. تمارين تطبيقية**

1. ارسم 50 نقطة عشوائية مع ألوان عشوائية.
2. غير حجم النقاط ليكون متناسبًا مع القيمة (مثل: `size = y * 5`).
3. أضف شفافية للنقاط.
4. ارسم خطًا يربط النقاط مع الحفاظ على النقاط.

---

## 🔹 **8. الربط بالواقع: تحليل بيانات العملاء**

### 🎯 الهدف: تحليل العلاقة بين العمر والدخل

```python
# بيانات وهمية للعملاء
np.random.seed(42)
age = np.random.randint(18, 70, 100)
income = 20000 + age * 1000 + np.random.randn(100) * 5000

# إنشاء النافذة
win = pg.GraphicsLayoutWidget(show=True, title="تحليل العملاء", size=(800, 600))
p1 = win.addPlot(title="العمر مقابل الدخل")
p1.setLabel('bottom', 'العمر (سنة)')
p1.setLabel('left', 'الدخل (ريال)')
p1.showGrid(True, True, 0.3)

# تحديد نقاط العملاء المميزين (دخل عالي)
colors = ['r' if inc > 80000 else 'b' for inc in income]
sizes = [15 if inc > 80000 else 8 for inc in income]

spots = [{'pos': (age[i], income[i]), 'size': sizes[i], 'brush': colors[i]} for i in range(len(age))]
scatter = pg.ScatterPlotItem(spots=spots)
p1.addItem(scatter)

# إضافة نص توضيحي
text = pg.TextItem(text="العملاء المميزون (أحمر)", color='r', anchor=(0, 1))
text.setPos(30, 120000)
p1.addItem(text)

print("📊 تحليل العملاء جاهز للعرض!")
```

> ✅ هذا النوع من التحليل يُستخدم في التسويق والتجزئة.

---

## 🔹 **9. نصائح احترافية**

1. ✅ استخدم `ScatterPlotItem` عندما تحتاج تحكمًا دقيقًا في كل نقطة.
2. ✅ استخدم `spots` لجعل كل نقطة فريدة.
3. ✅ استخدم الشفافية لتجنب التداخل.
4. ✅ اجمع بين `plot()` و `ScatterPlotItem` للحصول على خطوط ونقاط.
5. ✅ استخدم `addItem()` وليس `plot()` عند استخدام `ScatterPlotItem`.

---

## 🔹 **10. أسئلة مراجعة**

1. ما الفرق بين `plot()` و `ScatterPlotItem`؟
2. كيف تُغير لون كل نقطة على حدة؟
3. ما وظيفة `alpha` في `mkBrush`؟
4. كيف تُظهر الشبكة في الرسم التشتتي؟
5. كيف تُربط النقاط بخط؟

---

## 🔹 **11. مراجعة سريعة (ملخص الدرس)**

| العنصر | الكود |
|-------|------|
| `ScatterPlotItem()` | إنشاء نقاط |
| `spots` | قائمة بالخصائص لكل نقطة |
| `pos` | موقع النقطة (x, y) |
| `size` | حجم النقطة |
| `brush` | لون ملء النقطة |
| `pen` | لون الحدودة |
| `alpha` | الشفافية (في RGBA) |
| `addItem()` | إضافة العنصر للرسم |

# 📘 **الدرس 7 (موسع): رسم الأعمدة (Bar Graphs)**

## 🔹 **مقدمة: لماذا نستخدم رسم الأعمدة؟**

رسم الأعمدة (Bar Graph) هو الطريقة المثالية لتمثيل **البيانات الفئوية (Categorical Data)** ومقارنتها.

يُستخدم لعرض:
- مبيعات كل منتج
- عدد الموظفين في كل قسم
- توزيع الدرجات بين الطلاب
- نتائج الاستبيانات

في هذا الدرس، ستتعلم كيفية إنشاء رسم أعمدة باستخدام PyQtGraph، وتخصيصه بالكامل: الألوان، التسميات، والتباين.

---

## 🔹 **1. استخدام `BarGraphItem` — الطريقة الأساسية**

### 📌 المثال 1: رسم أعمدة بسيط

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication
import numpy as np
import sys

app = QApplication(sys.argv)

# إنشاء نافذة
win = pg.plot(title="مبيعات المنتجات")
win.setLabel('bottom', 'المنتج')
win.setLabel('left', 'الكمية')
win.showGrid(y=True, alpha=0.3)

# بيانات المبيعات
products = ['تفاح', 'موز', 'حليب', 'لابتوب']
sales = [50, 30, 40, 5]

# تحويل الأسماء إلى مواقع عددية
x = np.arange(len(products))

# إنشاء أعمدة
bars = pg.BarGraphItem(x=x, height=sales, width=0.6, brush='g')

# إضافة الأعمدة إلى النافذة
win.addItem(bars)

# تعديل تسميات محور X
ax = win.getAxis('bottom')
ax.setTicks([[(i, products[i]) for i in range(len(products))]])

if __name__ == '__main__':
    pg.exec()
```

#### 🔍 شرح الكود:
- `BarGraphItem(x, height, width, brush)`: يُنشئ أعمدة.
- `x`: المواقع الأفقية (أرقام).
- `height`: ارتفاع العمود (القيمة).
- `width`: عرض العمود.
- `brush`: لون العمود.
- `setTicks()`: لتغيير تسميات المحور X إلى أسماء.

> ✅ هذا هو الشكل الأساسي لرسم الأعمدة.

---

## 🔹 **2. تخصيص ألوان الأعمدة**

يمكنك جعل كل عمود بلون مختلف.

### 📌 المثال 2: أعمدة متعددة الألوان

```python
# ألوان لكل عمود
colors = ['r', 'y', 'b', 'm']  # أحمر، أصفر، أزرق، أرجواني

# إنشاء الأعمدة
bars = pg.BarGraphItem(x=x, height=sales, width=0.6)

# تعيين الألوان فورًا
bars.setOpts(brushes=colors)

win.addItem(bars)
```

> ✅ استخدم `brushes` (جمع) لتحديد لون لكل عمود.

---

## 🔹 **3. إضافة التسميات فوق الأعمدة**

لجعل الرسم أكثر وضوحًا.

### 📌 المثال 3: إضافة نص فوق كل عمود

```python
from pyqtgraph import TextItem

# بعد إنشاء الأعمدة
for i in range(len(products)):
    text = TextItem(text=str(sales[i]), color='k', anchor=(0.5, 1.2))
    text.setPos(x[i], sales[i])
    win.addItem(text)
```

> ✅ `anchor=(0.5, 1.2)`: لمركز النص فوق العمود.

---

## 🔹 **4. رسم أعمدة متعددة (Grouped Bar Chart)**

لعرض بيانات متعددة (مثل: مبيعات 2023 و2024).

### 📌 المثال 4: مقارنة بين عامين

```python
# بيانات
sales_2023 = [50, 30, 40, 5]
sales_2024 = [55, 35, 42, 8]

# تحديد عرض المجموعة
width = 0.3

# إنشاء الأعمدة
bars_2023 = pg.BarGraphItem(x=x - width/2, height=sales_2023, width=width, brush='b', name='2023')
bars_2024 = pg.BarGraphItem(x=x + width/2, height=sales_2024, width=width, brush='r', name='2024')

win.addItem(bars_2023)
win.addItem(bars_2024)

# إضافة أسطورة
legend = win.addLegend()
legend.addItem(bars_2023, '2023')
legend.addItem(bars_2024, '2024')
```

> ✅ `x ± width/2`: لوضع الأعمدة جنبًا إلى جنب.

---

## 🔹 **5. رسم أعمدة مكدسة (Stacked Bar Chart)**

لعرض المجموع الكلي.

### 📌 المثال 5: أعمدة مجمعة

```python
# القيم المكدسة
y1 = sales_2023
y2 = [a + b for a, b in zip(sales_2023, sales_2024)]

bars_2023 = pg.BarGraphItem(x=x, height=y1, width=0.6, brush='b', name='2023')
bars_2024 = pg.BarGraphItem(x=x, y=y1, height=sales_2024, width=0.6, brush='r', name='2024')

win.addItem(bars_2023)
win.addItem(bars_2024)
```

> ✅ `y=y1`: لبدء العمود الجديد من قمة العمود الأول.

---

## 🔹 **6. الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| لا تظهر الأعمدة | `width=0` أو `height=0` | تأكد من القيم |
| التسميات لا تظهر | نسيت `setTicks()` | أضف `setTicks()` للمحور |
| الألوان لا تعمل | استخدمت `brush` بدل `brushes` | استخدم `setOpts(brushes=...)` |
| `addItem()` لا يعمل | لم تُنشئ `BarGraphItem` أولًا | تأكد من `pg.BarGraphItem()` |

---

## 🔹 **7. تمارين تطبيقية**

1. ارسم أعمدة لدرجات 5 طلاب.
2. غير لون كل عمود ليكون متناسبًا مع الدرجة (أحمر للمنخفضة، أخضر للعالية).
3. أضف تسمية رقمية فوق كل عمود.
4. أنشئ رسمًا مزدوجًا يقارن بين فصلي "أول ثانوي" و"ثاني ثانوي".

---

## 🔹 **8. الربط بالواقع: تقرير مبيعات متجر**

### 🎯 الهدف: عرض مبيعات شهرين

```python
# بيانات وهمية
products = ['موز', 'تفاح', 'حليب', 'خبز', 'لبن']
jan_sales = [120, 150, 80, 100, 90]
feb_sales = [130, 140, 85, 110, 95]

x = np.arange(len(products))
width = 0.4

win = pg.GraphicsLayoutWidget(show=True, title="مبيعات يناير وفبراير", size=(900, 600))
p1 = win.addPlot()

# الأعمدة
bars_jan = pg.BarGraphItem(x=x - width/2, height=jan_sales, width=width, brush='g', name='يناير')
bars_feb = pg.BarGraphItem(x=x + width/2, height=feb_sales, width=width, brush='b', name='فبراير')

p1.addItem(bars_jan)
p1.addItem(bars_feb)

# التسميات
ax = p1.getAxis('bottom')
ax.setTicks([[(i, products[i]) for i in range(len(products))]])

p1.setLabel('left', 'الكمية')
p1.setLabel('bottom', 'المنتج')
p1.setTitle('مقارنة مبيعات شهرين')
p1.showGrid(y=True, alpha=0.3)

# أسطورة
p1.addLegend()
print("📊 تقرير المبيعات جاهز للعرض!")
```

> ✅ هذا النوع من التقارير يُستخدم في الإدارة.

---

## 🔹 **9. نصائح احترافية**

1. ✅ استخدم `BarGraphItem` فقط للرسمات الثابتة.
2. ✅ استخدم `plot()` مع `stepMode=True` للتحديث السريع.
3. ✅ استخدم `TextItem` لإضافة تسميات.
4. ✅ استخدم `addLegend()` للرسومات المتعددة.
5. ✅ استخدم `setTicks()` لتخصيص تسميات المحور.

---

## 🔹 **10. أسئلة مراجعة**

1. كيف تُغير عرض العمود؟
2. كيف تُظهر تسميات نصية على محور X؟
3. ما الفرق بين `brush` و `brushes`؟
4. كيف تُنشئ أعمدة مزدوجة؟
5. كيف تُضيف أسطورة؟

---

## 🔹 **11. مراجعة سريعة (ملخص الدرس)**

| العنصر | الكود |
|-------|------|
| `BarGraphItem()` | إنشاء أعمدة |
| `x`, `height` | الموقع والارتفاع |
| `width` | عرض العمود |
| `brush` | لون العمود |
| `brushes` | ألوان متعددة |
| `setTicks()` | تسميات المحور |
| `TextItem()` | نص فوق العمود |
| `addLegend()` | أسطورة |


# 📘 **الدرس 8 (موسع): عرض الصور (ImageView)**

## 🔹 **مقدمة: لماذا نعرض الصور في تطبيقات PyQtGraph؟**

رغم أن PyQtGraph تُعرف بالرسوم البيانية، إلا أنها توفر أداة قوية جدًا لعرض **الصور والمصفوفات الثنائية والثلاثية الأبعاد**.

تُستخدم في:
- تطبيقات التصوير الطبي (مثل: عرض صور الأشعة)
- تحليل الصور الحرارية
- معالجة الإشارات (Spectrograms)
- عرض بيانات المصفوفات (مثل: نتائج التجارب)

العنصر الرئيسي لذلك هو **`ImageView`** — وهو أكثر من مجرد عارض صور، بل يوفر:
- التكبير والتحريك
- التحكم في السطوع والتباين
- اختيار الخرائط اللونية (Colormaps)
- قراءة قيمة البكسل عند النقر

---

## 🔹 **1. استخدام `ImageView` — العارض المتكامل**

### 📌 المثال 1: عرض صورة بسيطة (مصفوفة)

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication
import numpy as np
import sys

app = QApplication(sys.argv)

# إنشاء ImageView
view = pg.ImageView()

# إنشاء صورة وهمية (مصفوفة 2D)
# مثل: صورة حرارية أو بيانات تجربة
image_data = np.random.normal(size=(100, 100)) * 50 + 100  # قيم من 50 إلى 150

# عرض الصورة
view.setImage(image_data)

# تعيين عنوان
view.setWindowTitle("عرض صورة باستخدام ImageView")

# عرض النافذة
view.show()

if __name__ == '__main__':
    pg.exec()
```

#### 🔍 شرح الكود:
- `pg.ImageView()`: يُنشئ نافذة عرض صور متكاملة.
- `setImage(data)`: يعرض المصفوفة كصورة.
- لا حاجة لإضافة العنصر يدويًا — `ImageView` يحتوي كل شيء.

> ✅ الناتج: نافذة بها صورة، شريط تمرير للسطوع، وشريط جانبي للتحكم.

---

## 🔹 **2. التحكم في السطوع والتباين (Levels)**

`ImageView` يُظهر شريطين جانبيين للتحكم في:
- **الحد الأدنى (Black Level)**
- **الحد الأعلى (White Level)**

### 📌 المثال 2: ضبط مستويات العرض يدويًا

```python
# بعد إنشاء view
view.setImage(image_data, levels=(50, 150))
```

> ✅ `levels=(min, max)`: يُعيّن أي قيمة أقل من `min` تكون سوداء، وأي قيمة أكبر من `max` تكون بيضاء.

---

## 🔹 **3. استخدام الخرائط اللونية (Colormaps)**

يمكنك تغيير طريقة عرض القيم باستخدام خريطة لونية.

### 📌 المثال 3: تطبيق خريطة لونية

```python
import pyqtgraph.colormap as cm

# قائمة بالخرائط الشهيرة: 'viridis', 'plasma', 'hot', 'cool', 'gray', 'jet'
view = pg.ImageView()
view.setImage(image_data, levels=(50, 150), colorMap=cm.get('hot'))
view.setWindowTitle("خريطة لونية: hot")
view.show()
```

> ✅ `cm.get('hot')`: يُنشئ خريطة لونية حمراء-صفراء.

---

## 🔹 **4. عرض صور متعددة (أطر فيديو أو طبقات)**

يمكن لـ `ImageView` عرض سلسلة من الصور (مثل: فيديو أو طبقات متعددة).

### 📌 المثال 4: عرض 3 صور (مصفوفة 3D)

```python
# إنشاء بيانات ثلاثية الأبعاد (3 صور حجم 50x50)
video_data = np.random.rand(3, 50, 50)

# عرض الفيديو
view = pg.ImageView()
view.setImage(video_data)
view.setWindowTitle("عرض 3 أطر (فيديو قصير)")
view.show()
```

> ✅ تظهر أداة تمرير للتنقل بين الإطارات.

---

## 🔹 **5. التفاعل مع النقر على الصورة**

للحصول على قيمة البكسل عند النقر.

### 📌 المثال 5: ربط حدث النقر

```python
def on_click():
    pos = view.imageItem.pos()  # موقع الصورة
    view_box = view.getView()
    mouse_point = view_box.mapSceneToView(view_box.mapToView(pg.QtCore.QPoint(pg.QtGui.QCursor.pos())))
    print(f"تم النقر عند: X={mouse_point.x():.1f}, Y={mouse_point.y():.1f}")

# ربط الحدث بالنقر الأيمن
view.viewBox.menu.actions()[0].triggered.connect(on_click)
```

> ✅ مفيد في التطبيقات التي تحتاج تفاعلًا دقيقًا.

---

## 🔹 **6. الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| `AttributeError: 'ImageView' has no attribute 'plot'` | حاولت استخدام `plot()` | استخدم `setImage()` |
| لا تظهر الصورة | البيانات ليست مصفوفة 2D أو 3D | تأكد من `shape` |
| الخريطة اللونية لا تعمل | لم تُستخدم `cm.get()` | استخدم `colorMap=cm.get('viridis')` |
| `levels` لا تؤثر | القيم خارج النطاق | تأكد من نطاق البيانات |

---

## 🔹 **7. تمارين تطبيقية**

1. أنشئ مصفوفة 100x100 تمثل توزيع حرارة، واعرضها بخريطة `hot`.
2. غير مستويات العرض لتركيز الاهتمام على القيم العالية.
3. أنشئ 5 صور (5x100x100) واعرضها كفيديو.
4. أضف دالة تُطبع قيمة البكسل عند النقر.

---

## 🔹 **8. الربط بالواقع: تحليل صورة طبية**

### 🎯 الهدف: محاكاة عرض صورة أشعة

```python
# فرض صورة أشعة (مصفوفة 2D)
np.random.seed(42)
xray = np.random.normal(128, 20, (200, 200))

# إضافة "عيب" صغير (مثل كتلة)
xray[80:100, 90:110] += 50

# عرض الصورة
view = pg.ImageView()
view.setImage(xray, levels=(50, 200), colorMap=cm.get('gray'))
view.setWindowTitle("تحليل صورة أشعة")
view.show()

print("🩻 واجهة تحليل الأشعة جاهزة!")
```

> ✅ هذا النوع من التطبيقات يُستخدم في الأنظمة الطبية.

---

## 🔹 **9. نصائح احترافية**

1. ✅ استخدم `ImageView` فقط للصور أو المصفوفات.
2. ✅ استخدم `colorMap=cm.get('gray')` للصور الطبية.
3. ✅ استخدم `levels` لتحسين التباين.
4. ✅ تحكم في حجم النافذة باستخدام `resize()`.
5. ✅ استخدم `setImage()` وليس `addItem()` مع `ImageView`.

---

## 🔹 **10. أسئلة مراجعة**

1. ما الفرق بين `ImageView` و `PlotWidget`؟
2. كيف تُعرض صورة ثلاثية الأبعاد؟
3. ما وظيفة `levels` في `setImage()`؟
4. كيف تُغير الخريطة اللونية؟
5. كيف تُعرف قيمة البكسل عند النقر؟

---

## 🔹 **11. مراجعة سريعة (ملخص الدرس)**

| العنصر | الكود |
|-------|------|
| `ImageView()` | إنشاء عارض صور |
| `setImage(data)` | عرض الصورة |
| `levels=(min, max)` | التحكم في السطوع |
| `colorMap=cm.get('...')` | تطبيق خريطة لونية |
| `setImage(3D_data)` | عرض فيديو أو طبقات |
| `viewBox` | للتفاعل مع النقر |


# 📘 **الدرس 9 (موسع): التكبير والتحريك (Zoom & Pan)**

## 🔹 **مقدمة: لماذا التكبير والتحريك ضروريان؟**

في أي تطبيق لعرض البيانات، من الضروري أن يتمكن المستخدم من:
- **التكبير (Zoom)** على منطقة معينة لرؤية التفاصيل الدقيقة (مثل: تغيرات سعر السهم في دقائق).
- **التحريك (Pan)** عبر البيانات الكبيرة (مثل: عرض ساعة من البيانات على مدى 24 ساعة).

PyQtGraph يوفر هذه الوظائف **مدمجة افتراضيًا**، لكن فهم آلية عملها يمنحك القدرة على:
- تعطيلها عند الحاجة
- تخصيص سلوكها
- ربطها بأحداث أخرى

---

## 🔹 **1. كيف يعمل التكبير والتحريك افتراضيًا؟**

بمجرد إنشاء `PlotWidget` أو `ImageView`، تصبح وظائف التفاعلية مفعلة تلقائيًا:
- **التكبير**: استخدام عجلة الماوس (Scroll)
- **التحريك**: الضغط والتحريك بالماوس (Drag)
- **إعادة التعيين**: الضغط بالزر الأيمن → "Auto-range"

### 📌 المثال 1: تفعيل التفاعلية

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication
import numpy as np
import sys

app = QApplication(sys.argv)

# إنشاء نافذة
win = pg.plot(title="التكبير والتحريك")

# بيانات كبيرة (10,000 نقطة)
x = np.linspace(0, 100, 10000)
y = np.sin(x) + 0.1 * np.random.randn(10000)

# رسم البيانات
win.plot(x, y)

if __name__ == '__main__':
    pg.exec()
```

> ✅ يمكنك التكبير بالعجلة، والتحريك بالضغط والتحريك.

---

## 🔹 **2. التحكم في التفاعلية باستخدام `ViewBox`**

كما تعلمت في الدرس 4، `ViewBox` هو العنصر المسؤول عن التفاعل.

### 📌 المثال 2: تعطيل التكبير على محور Y

```python
plot_item = win.getPlotItem()
view_box = plot_item.getViewBox()

# تعطيل التكبير على المحور الرأسي (Y)، والسماح به على الأفقي (X)
view_box.setMouseEnabled(x=True, y=False)
```

> ✅ مفيد في الرسومات الزمنية حيث لا تريد تكبير المحور الرأسي.

---

### 📌 المثال 3: تعطيل التفاعلية بالكامل

```python
view_box.setMouseEnabled(False, False)
```

> ✅ مفيد عند بناء واجهة تحكم مخصصة.

---

## 🔹 **3. التكبير باستخدام البرمجة (Programmatic Zoom)**

يمكنك تكبير/تصغير العرض برمجيًا.

### 📌 المثال 4: التكبير على منطقة معينة

```python
# تحديد منطقة الاهتمام (من x=10 إلى x=20)
plot_item.setXRange(10, 20)
```

### 📌 المثال 5: إعادة التعيين التلقائي (Auto-range)

```python
plot_item.autoRange()
```

> ✅ يُعيد العرض إلى جميع البيانات.

---

## 🔹 **4. ربط أحداث التكبير والتحريك**

يمكنك تنفيذ إجراءات عند تغيير منطقة العرض.

### 📌 المثال 6: طباعة نطاق العرض عند التكبير

```python
def on_range_changed():
    range_x = view_box.viewRange()[0]  # [min_x, max_x]
    print(f"نطاق العرض الجديد: {range_x[0]:.2f} - {range_x[1]:.2f}")

# ربط الحدث
view_box.sigXRangeChanged.connect(on_range_changed)
```

> ✅ مفيد لتحديث عناصر واجهة أخرى (مثل: عرض الوقت الحالي).

---

## 🔹 **5. التحريك باستخدام الأسهم (مخصص)**

إذا أردت التحكم بالتحريك عبر لوحة المفاتيح.

### 📌 المثال 7: التحريك باستخدام أسهم لوحة المفاتيح

```python
from PySide6 import QtCore

def keyPressEvent(event):
    if event.key() == QtCore.Qt.Key_Left:
        view_box.translateBy(x=-1)
    elif event.key() == QtCore.Qt.Key_Right:
        view_box.translateBy(x=1)
    elif event.key() == QtCore.Qt.Key_Up:
        view_box.translateBy(y=0.1)
    elif event.key() == QtCore.Qt.Key_Down:
        view_box.translateBy(y=-0.1)

# ربط حدث لوحة المفاتيح
win.keyPressEvent = keyPressEvent
```

> ✅ `translateBy()` يُحرك العرض.

---

## 🔹 **6. الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| لا يعمل التكبير | `setMouseEnabled(False)` | أعد تمكين الفأرة |
| التحريك بطيء | بيانات كبيرة جدًا | استخدم `setDownsampling()` |
| `sigXRangeChanged` لا يعمل | لم يتم ربط الحدث بشكل صحيح | تأكد من `connect()` |
| التكبير لا يعيد التعيين | لم تُستخدم `autoRange()` | استخدم `plot_item.autoRange()` |

---

## 🔹 **7. تمارين تطبيقية**

1. أنشئ رسمًا به 50,000 نقطة، وتأكد من أن التكبير يعمل بسلاسة.
2. عطّل التكبير على المحور Y فقط.
3. أضف دالة تُطبع "تم التكبير" عند تغيير نطاق العرض.
4. أضف دعمًا للتحريك باستخدام أسهم لوحة المفاتيح.

---

## 🔹 **8. الربط بالواقع: واجهة تحليل بيانات حية**

### 🎯 الهدف: مراقبة إشارة حية مع تحكم دقيق

```python
# فرض إشارة حية (مثل: قياس ضغط دم)
t = np.linspace(0, 60, 6000)  # 60 ثانية
signal = 120 + 20 * np.sin(2*np.pi*0.5*t) + np.random.normal(0, 5, 6000)

win = pg.plot(title="مراقبة الإشارة الحية")
curve = win.plot(t, signal, pen='y')

plot_item = win.getPlotItem()
view_box = plot_item.getViewBox()

# تعطيل التكبير على Y (لأن المقياس معروف)
view_box.setMouseEnabled(x=True, y=False)

# ربط حدث
def update_stats():
    range_x = view_box.viewRange()[0]
    visible_data = signal[(t >= range_x[0]) & (t <= range_x[1])]
    print(f"المتوسط في المنطقة: {np.mean(visible_data):.1f}")

view_box.sigXRangeChanged.connect(update_stats)

print("🔍 واجهة التحليل جاهزة للتكبير والتحليل!")
```

> ✅ هذا النوع من الواجهات يُستخدم في التطبيقات الطبية.

---

## 🔹 **9. نصائح احترافية**

1. ✅ استخدم `setMouseEnabled()` للتحكم في التفاعل.
2. ✅ استخدم `autoRange()` لإعادة العرض.
3. ✅ استخدم `sigXRangeChanged` لتحديث العناصر الأخرى.
4. ✅ استخدم `translateBy()` للتحريك البرمجي.
5. ✅ استخدم `setDownsampling(True)` للبيانات الكبيرة.

---

## 🔹 **10. أسئلة مراجعة**

1. ما العنصر المسؤول عن التكبير والتحريك؟
2. كيف تُعطل التكبير على محور معين؟
3. ما وظيفة `autoRange()`؟
4. كيف تُعرف عند تغيير نطاق العرض؟
5. كيف تُحرك العرض باستخدام لوحة المفاتيح؟

---

## 🔹 **11. مراجعة سريعة (ملخص الدرس)**

| الوظيفة | الكود |
|--------|------|
| التكبير/التحريك | مدمج افتراضيًا |
| تعطيل التفاعل | `setMouseEnabled(False, False)` |
| التكبير على X فقط | `setMouseEnabled(x=True, y=False)` |
| التكبير البرمجي | `setXRange(min, max)` |
| إعادة العرض | `autoRange()` |
| ربط حدث التكبير | `sigXRangeChanged.connect(func)` |
| التحريك بالكود | `translateBy(x, y)` |


# 📘 **الدرس 10 (موسع): إضافة التعليقات (Annotations)**

## 🔹 **مقدمة: لماذا نحتاج إلى التعليقات؟**

الرسم البياني الجيد لا يُكتفى بعرض البيانات، بل يجب أن **يُوجه المستخدم** إلى النتائج المهمة.

التعليقات (Annotations) هي أدوات تسمح لك بإضافة:
- **نصوص** توضيحية ("أعلى سعر في الشهر")
- **أسهم** تشير إلى أحداث معينة ("انقطاع التيار الكهربائي")
- **مربعات نصية** أو **أشرطة** لتظليل مناطق معينة

في هذا الدرس، ستتعلم كيفية استخدام عناصر مثل `TextItem` و `ArrowItem` و `InfiniteLine` لجعل رسوماتك أكثر **وضوحًا واحترافية**.

---

## 🔹 **1. إضافة نص باستخدام `TextItem`**

العنصر `TextItem` يُستخدم لإضافة نص في موقع محدد على الرسم.

### 📌 المثال 1: إضافة نص بسيط

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication
import numpy as np
import sys

app = QApplication(sys.argv)

# إنشاء نافذة
win = pg.plot(title="إضافة نص توضيحي")
x = np.linspace(0, 4*np.pi, 100)
y = np.sin(x)
win.plot(x, y, pen='b')

# إنشاء نص
text = pg.TextItem(text="ذروة الموجة", color='r', anchor=(0.5, 1.2))
text.setPos(1.57, 1.0)  # x ≈ π/2, y = 1.0

# إضافة النص إلى النافذة
win.addItem(text)

if __name__ == '__main__':
    pg.exec()
```

#### 🔍 شرح الكود:
- `text="..."`: النص المراد عرضه.
- `color='r'`: لون النص (أحمر).
- `anchor=(0.5, 1.2)`: يحدد نقطة التثبيت. `(0.5, 1.2)` = منتصف النص من الأعلى، مع هامش أعلاه.
- `setPos(x, y)`: لتحديد الموقع على الرسم.

> ✅ مثالي للإشارة إلى القيم القصوى أو الحدث المهم.

---

## 🔹 **2. إضافة سهم باستخدام `ArrowItem`**

لإظهار اتجاه أو الإشارة إلى نقطة معينة.

### 📌 المثال 2: إضافة سهم يشير إلى نقطة

```python
# بعد إنشاء النافذة
arrow = pg.ArrowItem(angle=-45, tipAngle=60, baseAngle=20, headLen=20, tailLen=40, brush='y', pen=None)
arrow.setPos(3, 0.5)

win.addItem(arrow)
```

#### 🔍 خيارات `ArrowItem`
| الخيار | الوظيفة |
|--------|--------|
| `angle` | زاوية السهم (بالدرجات) |
| `tipAngle`, `baseAngle` | زوايا الرأس والقاعدة |
| `headLen`, `tailLen` | طول الرأس والذيل |
| `brush` | لون التعبئة |
| `pen` | لون الحدودة |

> ✅ `angle=-45`: يشير السهم إلى أسفل اليمين.

---

## 🔹 **3. إضافة خطوط لا نهائية باستخدام `InfiniteLine`**

مفيد لتمثيل:
- حدود قبول/رفض
- المتوسطات
- تواريخ أحداث

### 📌 المثال 3: خط رأسي يمثل حدثًا

```python
# خط رأسي عند x = 6.28 (نهاية الدورة)
v_line = pg.InfiniteLine(pos=6.28, angle=90, pen=pg.mkPen('r', width=2, style=pg.QtCore.Qt.DashLine))
win.addItem(v_line)

# خط أفقي عند y = 0 (المحور الصفر)
h_line = pg.InfiniteLine(pos=0, angle=0, pen=pg.mkPen('g', width=1))
win.addItem(h_line)
```

> ✅ `angle=90`: خط رأسي، `angle=0`: خط أفقي.

---

## 🔹 **4. تظليل منطقة باستخدام `LinearRegionItem`**

لإبراز فترة زمنية أو نطاق معين.

### 📌 المثال 4: تظليل فترة زمنية

```python
from pyqtgraph import LinearRegionItem

# إنشاء منطقة تظليل
region = LinearRegionItem(values=(2, 4), orientation='vertical', brush=pg.mkBrush('r', 50))  # شفاف
win.addItem(region)

# يمكنك ربط الحدث بتحريك المنطقة
def on_region_changed():
    print(f"المنطقة: {region.getRegion()}")

region.sigRegionChanged.connect(on_region_changed)
```

> ✅ `brush=pg.mkBrush('r', 50)`: لون أحمر بشفافية 50.

---

## 🔹 **5. الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| النص لا يظهر | خارج نطاق العرض | استخدم `autoRange()` أو عدّل `setPos()` |
| السهم لا يظهر | `pen=None` و`brush=None` | تأكد من تعيين `brush` |
| الخط لا يظهر | `pos` خارج النطاق | تأكد من قيمة `pos` |
| `addItem()` لا يعمل | لم تُنشئ العنصر أولًا | تأكد من `pg.TextItem()` إلخ |

---

## 🔹 **6. تمارين تطبيقية**

1. أضف نصًا يُشير إلى أدنى قيمة في منحنى جيب التمام.
2. أضف سهمًا أصفر يشير إلى منتصف الرسم.
3. أضف خطًا رأسيًا عند `x=5` بلون أخضر متقطع.
4. ظلل المنطقة بين `x=1` و`x=3` بلون أزرق شفاف.

---

## 🔹 **7. الربط بالواقع: تحليل بيانات حية**

### 🎯 الهدف: إظهار أحداث مهمة في إشارة حية

```python
# فرض إشارة حية
t = np.linspace(0, 10, 1000)
signal = np.sin(t) + 0.1 * np.random.randn(1000)

win = pg.plot(title="تحليل الإشارة مع تعليقات")
win.plot(t, signal, pen='y')

# حدث: انقطاع مؤقت عند t=5
v_line = pg.InfiniteLine(pos=5, angle=90, pen=pg.mkPen('r', width=3))
win.addItem(v_line)

text = pg.TextItem(text="انقطاع التيار", color='r', anchor=(0.5, 1.2))
text.setPos(5, 1.5)
win.addItem(text)

# متوسط الإشارة
avg = np.mean(signal)
h_line = pg.InfiniteLine(pos=avg, angle=0, pen=pg.mkPen('g', width=2, style=pg.QtCore.Qt.DashLine))
win.addItem(h_line)

avg_text = pg.TextItem(text=f"المتوسط: {avg:.2f}", color='g')
avg_text.setPos(0.5, avg + 0.2)
win.addItem(avg_text)

print("📌 تم إضافة التعليقات التوضيحية!")
```

> ✅ هذا النوع من التحليل يُستخدم في المراقبة الصناعية.

---

## 🔹 **8. نصائح احترافية**

1. ✅ استخدم `anchor` لضبط موضع النص بدقة.
2. ✅ استخدم `LinearRegionItem` للمناطق القابلة للتحريك.
3. ✅ استخدم `sigRegionChanged` لتحديث العناصر الأخرى.
4. ✅ استخدم الشفافية (`alpha`) لتجنب إخفاء البيانات.
5. ✅ احفظ كائنات التعليقات إذا كنت ستحديثها لاحقًا.

---

## 🔹 **9. أسئلة مراجعة**

1. كيف تُضيف نصًا إلى الرسم؟
2. ما وظيفة `anchor` في `TextItem`؟
3. كيف تُنشئ خطًا رأسيًا؟
4. ما الفرق بين `InfiniteLine` و `LinearRegionItem`؟
5. كيف تُحدث موقع التعليق عند تغيير الرسم؟

---

## 🔹 **10. مراجعة سريعة (ملخص الدرس)**

| العنصر | الوظيفة |
|-------|--------|
| `TextItem` | إضافة نص توضيحي |
| `ArrowItem` | إضافة سهم |
| `InfiniteLine` | خط رأسي أو أفقي لا نهائي |
| `LinearRegionItem` | تظليل منطقة قابلة للتحريك |
| `setPos()` | تحديد موقع العنصر |
| `sigRegionChanged` | ربط حدث تغيير المنطقة |

# 📘 **الدرس 11 (موسع): التعامل مع الإشارات (Signals)**

## 🔹 **مقدمة: ما هي الإشارات (Signals) في PyQtGraph؟**

في واجهات المستخدم الرسومية (GUI)، لا تعمل البرامج خطوة بخطوة، بل تنتظر **أحداثًا (Events)** مثل:
- النقر بالفأرة
- الضغط على زر
- التمرير
- التحرك على عنصر

في PyQtGraph، تُسمى هذه الأحداث بـ **الإشارات (Signals)**، وهي طريقة لربط **حدث ما** بـ **رد فعل (Function)**.

> 💡 مثل: "عند النقر على نقطة، اعرض قيمتها في نافذة منفصلة".

فهم الإشارات هو المفتاح لبناء تطبيقات **تفاعلية وذكية**.

---

## 🔹 **1. كيف تعمل الإشارات؟**

النمط العام هو:
```python
widget.signal.connect(function)
```

- `widget`: العنصر (مثل: `PlotItem` أو `ViewBox`)
- `signal`: الإشارة (مثل: `sigClicked` أو `sigRangeChanged`)
- `function`: الدالة التي تُنفذ عند حدوث الحدث

---

## 🔹 **2. ربط حدث النقر على النقاط (Scatter Plot)**

مثالي لعرض تفاصيل عند النقر على نقطة.

### 📌 المثال 1: عرض قيمة النقطة عند النقر

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication, QMessageBox
import numpy as np
import sys

app = QApplication(sys.argv)

# إنشاء نافذة
win = pg.plot(title="النقر على النقاط")
x = np.random.normal(size=10)
y = np.random.normal(size=10)

# إنشاء نقاط
scatter = pg.ScatterPlotItem(x=x, y=y, pen='w', brush='r', size=10, symbol='o')
win.addItem(scatter)

# دالة تُنفّذ عند النقر
def on_point_clicked(plot, points):
    index = points[0].index()  # فهرس النقطة
    msg = f"النقطة {index}: X={x[index]:.2f}, Y={y[index]:.2f}"
    print(msg)
    # يمكن عرضها في نافذة منبثقة
    # QMessageBox.information(None, "بيانات النقطة", msg)

# ربط الحدث
scatter.sigClicked.connect(on_point_clicked)

if __name__ == '__main__':
    pg.exec()
```

#### 🔍 شرح الكود:
- `scatter.sigClicked.connect(...)`: يربط حدث النقر.
- `points[0].index()`: يُرجع فهرس النقطة المُنقر عليها.
- يمكن استخدام `QMessageBox` لعرض نافذة منبثقة.

> ✅ مثالي لتحليل البيانات النقطية.

---

## 🔹 **3. ربط حدث التكبير والتحريك (ViewBox)**

لتحديث عناصر واجهة أخرى عند تغيير العرض.

### 📌 المثال 2: عرض نطاق العرض الحالي

```python
plot_item = win.getPlotItem()
view_box = plot_item.getViewBox()

def on_zoom():
    range_x = view_box.viewRange()[0]
    range_y = view_box.viewRange()[1]
    print(f"العرض الحالي: X({range_x[0]:.1f} → {range_x[1]:.1f}), Y({range_y[0]:.1f} → {range_y[1]:.1f})")

# ربط حدث تغيير مدى المحور X
view_box.sigXRangeChanged.connect(on_zoom)
```

> ✅ مفيد لتحديث تسميات أو عناصر تحكم أخرى.

---

## 🔹 **4. ربط حدث النقر على الرسم (PlotItem)**

لإضافة نقطة جديدة بالنقر.

### 📌 المثال 3: إضافة نقطة بالنقر الأيمن

```python
def on_plot_clicked(event):
    if event.button() == 2:  # الزر الأيمن
        # تحويل موقع الفأرة إلى إحداثيات الرسم
        pos = event.pos()
        view_box = win.getViewBox()
        point = view_box.mapSceneToView(pos)
        
        # إضافة نقطة جديدة
        new_point = {'pos': (point.x(), point.y()), 'brush': 'b', 'size': 15}
        current_spots = [dict(pos=(x[i], y[i]), brush='r', size=10) for i in range(len(x))]
        current_spots.append(new_point)
        
        scatter.clear()
        scatter.addPoints(current_spots)

# ربط حدث النقر على الرسم
plot_item = win.getPlotItem()
plot_item.scene().sigMouseClicked.connect(on_plot_clicked)
```

> ✅ `scene().sigMouseClicked`: للوصول إلى حدث الفأرة على النافذة.

---

## 🔹 **5. ربط حدث تحريك السهم (InfiniteLine)**

مثالي لتحديد حدود ديناميكية.

### 📌 المثال 4: خط قابل للتحريك يعرض قيمته

```python
line = pg.InfiniteLine(pos=0, angle=90, movable=True, pen='y')
win.addItem(line)

def on_line_moved():
    print(f"تم تحريك الخط إلى X = {line.getXPos()}")

line.sigDragged.connect(on_line_moved)
```

> ✅ `movable=True`: يجعل الخط قابلاً للتحريك.
> ✅ `sigDragged`: يُطلق أثناء التحريك.
> ✅ `sigPositionChanged`: يُطلق بعد الانتهاء من التحريك.

---

## 🔹 **6. الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| `AttributeError: 'PlotItem' object has no attribute 'sigClicked'` | حاولت ربط إشارة على `PlotItem` بدل `ScatterPlotItem` | تأكد من نوع العنصر |
| الدالة لا تُنفّذ | لم تُستخدم `connect()` | تأكد من `signal.connect(func)` |
| `pos()` غير معرف | نسيت `event.pos()` | استخدم `event.pos()` للحصول على موقع الفأرة |
| لا يعمل النقر الأيمن | لم تتحقق من `event.button()` | استخدم `event.button() == 2` |

---

## 🔹 **7. تمارين تطبيقية**

1. أنشئ رسمًا تشتتيًا، وعند النقر على نقطة، اطبع قيمتها.
2. أضف خطًا رأسيًا قابلاً للتحريك، وعند تحريكه، اطبع موضعه.
3. عند التكبير على منطقة، احسب متوسط القيم في تلك المنطقة وأظهره.
4. أضف نقطة جديدة عند النقر الأيسر على الرسم.

---

## 🔹 **8. الربط بالواقع: واجهة تحليل تداول**

### 🎯 الهدف: تفاعل مع بيانات السعر

```python
# فرض بيانات سعر سهم
t = np.linspace(0, 10, 100)
price = 100 + np.cumsum(np.random.randn(100) * 0.5)

win = pg.plot(title="تحليل التداول التفاعلي")
curve = win.plot(t, price, pen='c')

# عند النقر على الرسم، عرض السعر
def on_click(event):
    if event.button() == 1:  # الزر الأيسر
        pos = event.pos()
        view_box = win.getViewBox()
        point = view_box.mapSceneToView(pos)
        x, y = point.x(), point.y()
        # تقريب إلى أقرب نقطة بيانات
        idx = (np.abs(t - x)).argmin()
        print(f"سعر السهم عند t={t[idx]:.1f}: {price[idx]:.2f} ريال")

win.scene().sigMouseClicked.connect(on_click)

print("🖱️ انقر على أي نقطة في الرسم لعرض السعر!")
```

> ✅ هذا النوع من التفاعل يُستخدم في لوحات التداول.

---

## 🔹 **9. نصائح احترافية**

1. ✅ استخدم `sigClicked` مع `ScatterPlotItem` فقط.
2. ✅ استخدم `scene().sigMouseClicked` للنقر على أي مكان في الرسم.
3. ✅ استخدم `mapSceneToView()` لتحويل موقع الفأرة إلى إحداثيات البيانات.
4. ✅ استخدم `sigDragged` للتحديث أثناء التحريك، و`sigPositionChanged` للتحديث بعد الانتهاء.
5. ✅ احفظ مراجع العناصر (مثل `scatter`, `line`) لتعديلها لاحقًا.

---

## 🔹 **10. أسئلة مراجعة**

1. ما الفرق بين `sigClicked` و `scene().sigMouseClicked`؟
2. كيف تُعرف موقع الفأرة على الرسم؟
3. ما وظيفة `movable=True`؟
4. كيف تُربط حدث التكبير؟
5. كيف تُضيف نقطة جديدة بالنقر؟

---

## 🔹 **11. مراجعة سريعة (ملخص الدرس)**

| العنصر | الإشارة | الوظيفة |
|-------|--------|--------|
| `ScatterPlotItem` | `sigClicked` | عند النقر على نقطة |
| `ViewBox` | `sigXRangeChanged` | عند التكبير/التحريك |
| `InfiniteLine` | `sigDragged` | أثناء تحريك الخط |
| `PlotItem.scene()` | `sigMouseClicked` | عند النقر على أي مكان |


# 📘 **الدرس 12 (موسع): الرسم اللحظي (Real-time plotting)**

## 🔹 **مقدمة: ما هو الرسم اللحظي؟ ولماذا هو مهم؟**

الرسم اللحظي (Real-time plotting) هو القدرة على **تحديث الرسم البياني بشكل مستمر** مع وصول بيانات جديدة، دون تأخير ملحوظ.

يُستخدم في:
- مراقبة مستشعرات IoT (درجة حرارة، رطوبة)
- عرض أسعار الأسهم أو العملات الحية
- تحليل الإشارات الكهربائية (مثل ECG)
- تجارب علمية تتطلب مراقبة فورية

في هذا الدرس، ستتعلم كيفية بناء تطبيق PyQtGraph يُحدث الرسم **بمعدل 60 إطارًا في الثانية**، مع الحفاظ على الأداء.

---

## 🔹 **1. المبدأ الأساسي: الحلقة والتحديث**

لا يمكن استخدام `time.sleep()` لأنه يُجمّد واجهة المستخدم.

الحل: استخدام **مُؤقّت (Timer)** من PyQt.

### 📌 المثال 1: تحديث بيانات خطية بسيطة

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication
from PySide6.QtCore import QTimer
import numpy as np
import sys

app = QApplication(sys.argv)

# إنشاء نافذة
win = pg.plot(title="الرسم اللحظي - مثال بسيط")
win.setLabel('left', 'القيمة')
win.setLabel('bottom', 'الزمن')
curve = win.plot(pen='y')  # خط أصفر

# بيانات افتراضية
x = np.linspace(0, 50, 1000)  # 1000 نقطة
i = 0

def update():
    global i
    if i >= len(x):
        i = 0  # إعادة التدوير
    y = np.sin(x[:i+1] * 0.5) + 0.1 * np.random.randn(i+1)  # بيانات ديناميكية
    curve.setData(x[:i+1], y)  # تحديث البيانات
    i += 1

# إنشاء مؤقت يُنفّذ update كل 50 ميلي ثانية (20 إطار/ثانية)
timer = QTimer()
timer.timeout.connect(update)
timer.start(50)

if __name__ == '__main__':
    pg.exec()
```

#### 🔍 شرح الكود:
- `QTimer()`: يُنفّذ دالة بشكل دوري.
- `timer.start(50)`: كل 50 ميلي ثانية.
- `curve.setData()`: الطريقة **الوحيدة** لتحديث بيانات الرسم بسرعة.
- `setData()` أسرع بكثير من `plot()`.

> ✅ لا تُنشئ خطوطًا جديدة في كل دورة!

---

## 🔹 **2. التعامل مع البيانات الكبيرة**

عندما تصل البيانات بشكل مستمر، لا يمكن تخزينها إلى الأبد.

### 📌 المثال 2: استخدام مصفوفة دائرية (Circular Buffer)

```python
# حجم المخزن المؤقت
buffer_size = 1000
x = np.linspace(0, 100, buffer_size)
y = np.zeros(buffer_size)
ptr = 0  # مؤشر الكتابة

curve = win.plot(x, y, pen='m')

def update():
    global ptr
    new_value = np.sin(0.1 * ptr) + 0.2 * np.random.randn()  # قيمة جديدة
    y[ptr] = new_value
    ptr = (ptr + 1) % buffer_size  # تدوير المؤشر

    # تحديث العرض: عرض من ptr إلى النهاية، ثم من البداية إلى ptr
    x_view = np.concatenate([x[ptr:], x[:ptr]])
    y_view = np.concatenate([y[ptr:], y[:ptr]])
    curve.setData(x_view, y_view)

timer = QTimer()
timer.timeout.connect(update)
timer.start(30)  # ~33 إطار/ثانية
```

> ✅ مثالي للبيانات التي تتدفق باستمرار.

---

## 🔹 **3. تحسين الأداء مع آلاف النقاط**

لجعل الرسم أسرع:
- تفعيل التفريغ (Downsampling)
- تعطيل التحديثات غير الضرورية

### 📌 المثال 3: تحسين الأداء

```python
# تفعيل التفريغ
win.setDownsampling(mode='peak')  # يُظهر الحد الأقصى والأدنى
win.setClipToView(True)  # فقط اعرض ما يظهر على الشاشة

# زيادة حجم المخزن
buffer_size = 10000
```

> ✅ `setClipToView(True)` يُسرّع التحديث بشكل كبير.

---

## 🔹 **4. الرسم التشتتي اللحظي**

### 📌 المثال 4: إضافة نقاط تدريجيًا

```python
scatter = pg.ScatterPlotItem(pen=None, brush='r', size=8)
win.addItem(scatter)

spots = []

def update_scatter():
    global spots
    new_spot = {'pos': (np.random.normal(), np.random.normal()), 'brush': 'b'}
    spots.append(new_spot)
    if len(spots) > 100:  # احتفظ بأحدث 100 نقطة فقط
        spots = spots[-100:]
    scatter.clear()
    scatter.addPoints(spots)

timer.timeout.connect(update_scatter)
```

> ✅ `clear()` و `addPoints()` للتحديث.

---

## 🔹 **5. الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| توقف الواجهة | استخدام `time.sleep()` | استخدم `QTimer` |
| بطء شديد | إنشاء خطوط جديدة في كل دورة | استخدم `setData()` |
| البيانات لا تُحدّث | نسيت `timer.start()` | تأكد من بدء المؤقت |
| `setData()` لا يعمل | تمرير بيانات خاطئة | تأكد من أن `x` و `y` نفس الطول |

---

## 🔹 **6. تمارين تطبيقية**

1. أنشئ رسمًا يعرض 1000 نقطة تُحدّث كل 100 ميلي ثانية.
2. استخدم `setDownsampling()` و `setClipToView(True)` لتحسين الأداء.
3. أنشئ رسمًا تشتتيًا يُظهر أحدث 50 نقطة فقط.
4. أضف خطًا رأسيًا يتحرك مع الزمن.

---

## 🔹 **7. الربط بالواقع: مراقبة سعر السهم**

### 🎯 الهدف: محاكاة تحديث سعر سهم لحظيًا

```python
# فرض سعر سهم يتحرك عشوائيًا
price = 100.0
times = []
prices = []

curve = win.plot(pen='c')

def update_stock():
    global price, times, prices
    price += np.random.randn() * 0.1  # تغير صغير
    current_time = len(times)
    times.append(current_time)
    prices.append(price)
    
    # احتفظ بأحدث 200 قيمة فقط
    if len(times) > 200:
        times = times[-200:]
        prices = prices[-200:]
    
    # تحديث الرسم
    curve.setData(times, prices)
    win.setTitle(f"سعر السهم: {price:.2f} ريال")

timer = QTimer()
timer.timeout.connect(update_stock)
timer.start(100)  # كل 100 ميلي ثانية

print("📈 تحديث سعر السهم جارٍ الآن...")
```

> ✅ هذا هو الشكل الذي تُبنى عليه لوحات التداول.

---

## 🔹 **8. نصائح احترافية**

1. ✅ استخدم دائمًا `setData()` بدل `plot()` في الحلقات.
2. ✅ استخدم `QTimer` وليس `time.sleep()`.
3. ✅ استخدم `setDownsampling(mode='peak')` للبيانات الكبيرة.
4. ✅ استخدم `setClipToView(True)` لتحسين الأداء.
5. ✅ احذف البيانات القديمة للحفاظ على الذاكرة.

---

## 🔹 **9. أسئلة مراجعة**

1. لماذا لا نستخدم `time.sleep()` في الرسم اللحظي؟
2. ما وظيفة `setData()`؟
3. كيف تُحسن أداء الرسم مع 10,000 نقطة؟
4. ما الفرق بين `setDownsampling()` و `setClipToView()`؟
5. كيف تُحدث رسمًا تشتتيًا بشكل لحظي؟

---

## 🔹 **10. مراجعة سريعة (ملخص الدرس)**

| العنصر | الوظيفة |
|-------|--------|
| `QTimer` | تنفيذ دالة بشكل دوري |
| `setData()` | تحديث بيانات الرسم بسرعة |
| `setDownsampling()` | تفريغ البيانات لتحسين الأداء |
| `setClipToView(True)` | عرض ما يظهر فقط |
| `Circular Buffer` | تخزين بيانات دائرية |

# 📘 **الدرس 13 (موسع): الرسوم ثلاثية الأبعاد باستخدام `GLViewWidget`**
## 🔹 **مقدمة: لماذا نحتاج إلى الرسوم 3D؟**

بينما تُكفي الرسوم ثنائية الأبعاد (2D) لمعظم التحليلات، فإن بعض البيانات تتطلب بُعدًا ثالثًا لفهمها بشكل كامل.

تُستخدم الرسوم 3D في:
- عرض **السطوح ثلاثية الأبعاد** (مثل: التضاريس، نتائج المحاكاة)
- تحليل **البيانات المكانية** (X, Y, Z)
- عرض **الأنماط في البيانات ذات الأبعاد العالية**
- التطبيقات العلمية والهندسية (مثل: تدفق السوائل، مجالات الجاذبية)

في هذا الدرس، ستتعلم كيفية استخدام **`GLViewWidget`** من PyQtGraph لعرض:
- نقاط ثلاثية الأبعاد
- سطوح (Surfaces)
- شبكات (Meshes)

---

## 🔹 **1. التثبيت والمتطلبات**

الرسوم 3D في PyQtGraph تعتمد على **OpenGL**، لذلك تأكد من:
- تثبيت `PyQtGraph` (الإصدار الأحدث)
- تشغيل الكود على بيئة تدعم OpenGL

```bash
pip install pyqtgraph PySide6
```

> ✅ لا حاجة لتثبيت OpenGL يدويًا — PyQtGraph يتعامل معه داخليًا.

---

## 🔹 **2. `GLViewWidget` — نافذة العرض ثلاثية الأبعاد**

هو العنصر الرئيسي لعرض الرسوم 3D.

### 📌 المثال 1: إنشاء نافذة 3D فارغة

```python
import pyqtgraph.opengl as gl
from PySide6.QtWidgets import QApplication
import sys

app = QApplication(sys.argv)

# إنشاء نافذة عرض 3D
view = gl.GLViewWidget()
view.show()
view.setWindowTitle("نافذة 3D فارغة")
view.setCameraPosition(distance=50)  # تحديد موضع الكاميرا

if __name__ == '__main__':
    app.exec()
```

> ✅ `pyqtgraph.opengl as gl`: وحدة الرسوم 3D.
> ✅ يمكنك التفاعل بالفأرة: التدوير، التكبير، التحريك.

---

## 🔹 **3. رسم النقاط ثلاثية الأبعاد باستخدام `GLScatterPlotItem`**

### 📌 المثال 2: عرض مجموعة من النقاط العشوائية

```python
import pyqtgraph.opengl as gl
import numpy as np
from PySide6.QtWidgets import QApplication
import sys

app = QApplication(sys.argv)
view = gl.GLViewWidget()
view.show()
view.setWindowTitle("نقاط ثلاثية الأبعاد")
view.setCameraPosition(distance=40)

# بيانات ثلاثية الأبعاد
n = 1000
x = np.random.normal(size=n)
y = np.random.normal(size=n)
z = np.random.normal(size=n)
pos = np.vstack((x, y, z)).T  # مصفوفة بحجم (n, 3)

# إنشاء نقاط
scatter = gl.GLScatterPlotItem(pos=pos, color=(1, 0, 0, 1), size=0.5)

# إضافة النقاط إلى النافذة
view.addItem(scatter)

if __name__ == '__main__':
    app.exec()
```

#### 🔍 شرح الكود:
- `pos`: مصفوفة ثنائية الأبعاد بحجم `(عدد_النقاط, 3)`
- `color=(r, g, b, a)`: لون النقطة (أحمر، شفافية كاملة)
- `size`: حجم النقطة

> ✅ يمكنك تغيير لون كل نقطة باستخدام قائمة من الألوان.

---

## 🔹 **4. رسم السطوح باستخدام `GLSurfacePlotItem`**

مثالي لعرض الدوال الرياضية أو التضاريس.

### 📌 المثال 3: رسم سطح دالة جيب التمام

```python
import pyqtgraph.opengl as gl
import numpy as np
from PySide6.QtWidgets import QApplication
import sys

app = QApplication(sys.argv)
view = gl.GLViewWidget()
view.show()
view.setWindowTitle("رسم سطح ثلاثي الأبعاد")
view.setCameraPosition(distance=40)

# شبكة من النقاط (X, Y)
x = np.linspace(-10, 10, 50)
y = np.linspace(-10, 10, 50)
X, Y = np.meshgrid(x, y)

# دالة Z = cos(r) حيث r = الجذر التربيعي لـ (X² + Y²)
R = np.sqrt(X**2 + Y**2)
Z = np.cos(R)

# إنشاء السطح
surface = gl.GLSurfacePlotItem(x=x, y=y, z=Z, color=(0.5, 0.5, 1, 1), shader='shaded', drawEdges=False)

# إضافة السطح
view.addItem(surface)

if __name__ == '__main__':
    app.exec()
```

#### 🔍 خيارات مهمة:
- `shader='shaded'`: إضافة تظليل واقعي
- `drawEdges=True`: عرض خطوط الشبكة
- `color`: لون ثابت أو يمكن تغييره باستخدام `setColors()`

---

## 🔹 **5. الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| `ModuleNotFoundError: No module named 'OpenGL'` | لم يتم تثبيت التبعيات | تأكد من `pip install pyqtgraph` |
| لا تظهر النافذة 3D | بيئة غير مدعومة (مثل بعض الأجهزة الافتراضية) | جرب على جهاز به بطاقة رسومات |
| النقاط لا تظهر | `size` صغير جدًا | زد قيمة `size` |
| السطح مشوّش | بيانات `z` غير منظمة | تأكد من أن `X`, `Y`, `Z` نفس الشكل |

---

## 🔹 **6. تمارين تطبيقية**

1. ارسم 500 نقطة في شكل كرة (استخدم الإحداثيات الكروية).
2. غيّر لون النقاط بناءً على موقعها في الفضاء.
3. ارسم سطحًا لدالة `Z = X² + Y²`.
4. أضف عنوانًا واجعل الكاميرا تتحرك تلقائيًا.

---

## 🔹 **7. الربط بالواقع: تحليل تضاريس رقمية**

### 🎯 الهدف: محاكاة عرض تضاريس

```python
# فرض بيانات تضاريس (مثل: ارتفاعات جبل)
x = np.linspace(-5, 5, 100)
y = np.linspace(-5, 5, 100)
X, Y = np.meshgrid(x, y)
# نموذج جبل مع عدة قمم
Z = 5 * np.exp(-((X-1)**2 + (Y-1)**2)) + \
    3 * np.exp(-((X+2)**2 + (Y+2)**2)) + \
    2 * np.exp(-(X**2 + Y**2))

view = gl.GLViewWidget()
view.show()
view.setWindowTitle("نموذج تضاريس رقمية")
view.setCameraPosition(distance=20)

surface = gl.GLSurfacePlotItem(x=x, y=y, z=Z, shader='shaded', color=(0.2, 0.6, 0.2, 1))  # لون أخضر
view.addItem(surface)

print("🏔️ نموذج التضاريس جاهز للعرض ثلاثي الأبعاد!")
```

> ✅ هذا النوع من العرض يُستخدم في نظم المعلومات الجغرافية (GIS).

---

## 🔹 **8. نصائح احترافية**

1. ✅ استخدم `GLViewWidget` فقط عند الحاجة إلى 3D.
2. ✅ استخدم `GLScatterPlotItem` للنقاط، و`GLSurfacePlotItem` للسطوح.
3. ✅ تجنب استخدام أكثر من 10,000 نقطة على أجهزة ضعيفة.
4. ✅ استخدم `setCameraPosition()` لضبط العرض الابتدائي.
5. ✅ اختبر الكود على جهاز به دعم جيد لـ OpenGL.

---

## 🔹 **9. أسئلة مراجعة**

1. ما هو `GLViewWidget`؟
2. كيف تُنشئ نقاطًا ثلاثية الأبعاد؟
3. ما شكل مصفوفة `pos` في `GLScatterPlotItem`؟
4. كيف تُرسم دالة رياضية كسطح؟
5. ما وظيفة `shader='shaded'`؟

---

## 🔹 **10. مراجعة سريعة (ملخص الدرس)**

| العنصر | الوظيفة |
|-------|--------|
| `GLViewWidget` | نافذة العرض ثلاثية الأبعاد |
| `GLScatterPlotItem` | رسم نقاط 3D |
| `GLSurfacePlotItem` | رسم سطوح 3D |
| `pos` | مصفوفة (n, 3) للنقاط |
| `x, y, z` | شبكات للسطوح |
| `setCameraPosition()` | ضبط الكاميرا |
| `shader='shaded'` | تظليل واقعي |


# 📘 **الدرس 14 (موسع): الخرائط اللونية (Color Maps)**

## 🔹 **مقدمة: ما هي الخرائط اللونية؟ ولماذا تُستخدم؟**

الخريطة اللونية (Colormap) هي وسيلة لتمثيل **القيم العددية** باستخدام **التدرجات اللونية**.

بدلاً من عرض الأرقام فقط، يمكنك:
- تمثيل **الحرارة** بألوان من الأزرق (بارد) إلى الأحمر (ساخن)
- عرض **كثافة البيانات** من الشفاف إلى المعتم
- تمييز **القيم العالية والمنخفضة** في الصور أو المصفوفات

تُستخدم الخرائط اللونية في:
- **ImageView** (عرض الصور الحرارية، الأشعة)
- **GLSurfacePlotItem** (رسم السطوح 3D)
- **الرسوم البيانية المكانية** (مثل الخرائط الجغرافية)

---

## 🔹 **1. استخدام الخرائط الجاهزة**

يأتي PyQtGraph مع مجموعة من الخرائط اللونية الجاهزة.

### 📌 المثال 1: تطبيق خريطة لونية على صورة

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication
import numpy as np
import sys

app = QApplication(sys.argv)

# إنشاء بيانات صورة (مثل: توزيع حرارة)
image_data = np.random.normal(size=(100, 100)) * 50 + 100

# إنشاء ImageView
view = pg.ImageView()
view.setImage(image_data)

# تطبيق خريطة لونية جاهزة
cmap = pg.colormap.get('viridis')  # أو 'plasma', 'hot', 'cool', 'gray', 'jet'
view.setColorMap(cmap)

view.setWindowTitle("خريطة لونية: viridis")
view.show()

if __name__ == '__main__':
    pg.exec()
```

#### 🔍 خرائط شائعة:
| الخريطة | الاستخدام |
|--------|----------|
| `'viridis'` | افتراضية، واضحة، مناسبة للطباعة |
| `'plasma'` | تباين عالي، من الأرجواني إلى الأصفر |
| `'hot'` | من الأسود إلى الأحمر إلى الأصفر (مثل النار) |
| `'cool'` | من الأزرق إلى الوردي |
| `'gray'` | تدرج رمادي (مثالي للصور الطبية) |
| `'jet'` | تدرج كامل (مثير بصريًا، لكنه غير دقيق) |

> ✅ `pg.colormap.get('name')`: للحصول على خريطة لونية.

---

## 🔹 **2. إنشاء خريطة لونية مخصصة**

يمكنك تعريف تدرج لوني خاص بك.

### 📌 المثال 2: خريطة لونية من الأزرق إلى الأحمر

```python
# تحديد الألوان عند نقاط معينة (من 0.0 إلى 1.0)
colors = [
    (0, 0, 255),    # أزرق (قيمة منخفضة)
    (0, 255, 255),  # سماوي
    (0, 255, 0),    # أخضر
    (255, 255, 0),  # أصفر
    (255, 0, 0)     # أحمر (قيمة عالية)
]

# إنشاء الخريطة
custom_cmap = pg.ColorMap(pos=np.linspace(0.0, 1.0, len(colors)), color=colors)

# تطبيقها على ImageView
view.setColorMap(custom_cmap)
```

#### 🔍 شرح:
- `pos`: مواقع النسب (0.0 = القيمة الدنيا، 1.0 = القيمة العليا)
- `color`: قائمة بألوان RGB (من 0 إلى 255)

---

## 🔹 **3. استخدام الخرائط في الرسوم 3D**

### 📌 المثال 3: تطبيق خريطة لونية على سطح 3D

```python
import pyqtgraph.opengl as gl
import numpy as np
from PySide6.QtWidgets import QApplication
import sys

app = QApplication(sys.argv)
view = gl.GLViewWidget()
view.show()
view.setWindowTitle("سطح 3D مع خريطة لونية")
view.setCameraPosition(distance=40)

# إنشاء شبكة
x = np.linspace(-10, 10, 50)
y = np.linspace(-10, 10, 50)
X, Y = np.meshgrid(x, y)
Z = np.cos(np.sqrt(X**2 + Y**2))

# إنشاء خريطة لونية
cmap = pg.colormap.get('plasma')

# تحويل الخريطة إلى ألوان لكل نقطة
normalized_z = (Z - Z.min()) / (Z.max() - Z.min())  # من 0 إلى 1
colors = cmap.getLookupTable(nPts=256)
surface_colors = np.array([colors[int(i*255)] for i in normalized_z.flatten()])
surface_colors = surface_colors.reshape((*Z.shape, 4))  # (H, W, 4)

# إنشاء السطح
surface = gl.GLSurfacePlotItem(x=x, y=y, z=Z, colors=surface_colors, shader='shaded')
view.addItem(surface)

if __name__ == '__main__':
    app.exec()
```

> ✅ يتم تحويل القيم إلى نطاق [0,1] ثم تعيين لون لكل قيمة.

---

## 🔹 **4. عرض شريط الخريطة اللونية (Color Bar)**

لإضافة شريط توضيحي يُظهر العلاقة بين اللون والقيمة.

### 📌 المثال 4: إضافة شريط ألوان

```python
# بعد إنشاء ImageView
view = pg.ImageView()
view.setImage(image_data)
view.setColorMap(pg.colormap.get('hot'))

# إضافة شريط الألوان
color_bar = pg.ColorBarItem(values=(image_data.min(), image_data.max()), colorMap=pg.colormap.get('hot'))
view.layout.addItem(color_bar, 2, 1)  # إضافته في الصف 2، العمود 1

view.show()
```

> ✅ `ColorBarItem` يُظهر مقياس الألوان.

---

## 🔹 **5. الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| `AttributeError: 'ImageView' has no attribute 'setColorMap'` | استخدمت `setColorMap` بدل `setColorMap` | التهجئة الصحيحة: `setColorMap` |
| الألوان لا تظهر | لم تُستخدم `colors` بشكل صحيح في 3D | تأكد من شكل `colors` (يجب أن يكون `(H, W, 4)`) |
| الشريط لا يظهر | لم تُضف `ColorBarItem` إلى التخطيط | استخدم `layout.addItem()` |
| `getLookupTable()` لا يعمل | نسيت تحديد `nPts` | استخدم `cmap.getLookupTable(nPts=256)` |

---

## 🔹 **6. تمارين تطبيقية**

1. أنشئ خريطة لونية من الأخضر إلى الأحمر لتمثيل "حالة النظام" (جيدة → سيئة).
2. طبّق خريطة `cool` على صورة مصفوفة.
3. أضف شريط ألوان إلى `ImageView`.
4. في رسم 3D، اجعل اللون يعتمد على قيمة `Z`.

---

## 🔹 **7. الربط بالواقع: تحليل حرارة المبنى**

### 🎯 الهدف: عرض توزيع الحرارة عبر الطبقات

```python
# فرض بيانات حرارة (مثل: من مستشعرات في الجدران)
heat_map = np.random.rand(50, 50) * 30 + 20  # 20-50 درجة مئوية

view = pg.ImageView()
view.setImage(heat_map)
view.setColorMap(pg.colormap.get('hot'))

# شريط توضيحي
color_bar = pg.ColorBarItem(values=(20, 50), colorMap=pg.colormap.get('hot'), label='درجة الحرارة (°C)')
view.layout.addItem(color_bar, 2, 1)

view.setWindowTitle("تحليل توزيع الحرارة")
view.show()

print("🌡️ تحليل الحرارة جاهز للعرض!")
```

> ✅ هذا النوع من التحليل يُستخدم في أنظمة مراقبة المباني.

---

## 🔹 **8. نصائح احترافية**

1. ✅ استخدم `'viridis'` أو `'plasma'` للعروض العامة.
2. ✅ استخدم `'gray'` للصور الطبية.
3. ✅ تجنب `'jet'` في التقارير الرسمية (غير دقيق بصريًا).
4. ✅ استخدم `ColorBarItem` لجعل الرسم مفهومًا.
5. ✅ عدّل `levels` في `ImageView` لتحسين التباين.

---

## 🔹 **9. أسئلة مراجعة**

1. كيف تُطبق خريطة لونية على `ImageView`؟
2. ما وظيفة `pg.colormap.get()`؟
3. كيف تُنشئ خريطة لونية مخصصة؟
4. كيف تُضيف شريط ألوان؟
5. كيف تُستخدم الخرائط في الرسوم 3D؟

---

## 🔹 **10. مراجعة سريعة (ملخص الدرس)**

| العنصر | الوظيفة |
|-------|--------|
| `pg.colormap.get('name')` | الحصول على خريطة لونية |
| `setColorMap()` | تطبيق الخريطة على `ImageView` |
| `ColorMap(pos, color)` | إنشاء خريطة مخصصة |
| `ColorBarItem` | شريط توضيحي للون |
| `getLookupTable()` | تحويل الخريطة إلى ألوان |

# 📘 **الدرس 15 (موسع): عرض عدة رسوم (Multiple Plots)**

## 🔹 **مقدمة: لماذا نعرض عدة رسوم معًا؟**

في التطبيقات الواقعية، نادرًا ما يكفي رسم واحد لفهم الصورة الكاملة.

غالبًا ما نحتاج إلى عرض:
- **مخططات مقارنة** (مثل: المبيعات مقابل التكاليف)
- **بيانات متعددة الأبعاد** (مثل: درجة الحرارة، الرطوبة، الضغط في نفس الوقت)
- **تحليل متعدد الجوانب** (مثل: السعر، الحجم، مؤشرات فنية)

في هذا الدرس، ستتعلم كيفية استخدام `GraphicsLayoutWidget` لتنظيم **عدة رسومات في نافذة واحدة**، مع التحكم الكامل في التخطيط والتنسيق.

---

## 🔹 **1. `GraphicsLayoutWidget` — حاوية الرسومات المتعددة**

كما تعلمت سابقًا، `GraphicsLayoutWidget` هو العنصر المثالي لعرض أكثر من رسم.

### 📌 المثال 1: رسمان جنبًا إلى جنب

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication
import numpy as np
import sys

app = QApplication(sys.argv)

# إنشاء حاوية متعددة الرسومات
win = pg.GraphicsLayoutWidget(show=True, title="رسمان جنبًا إلى جنب")
win.resize(1000, 500)

# الرسم الأول: جيب التمام
p1 = win.addPlot(row=0, col=0, title="cos(x)")
x = np.linspace(0, 4*np.pi, 100)
y1 = np.cos(x)
p1.plot(x, y1, pen='b')

# الرسم الثاني: الجيب
p2 = win.addPlot(row=0, col=1, title="sin(x)")
y2 = np.sin(x)
p2.plot(x, y2, pen='r')

if __name__ == '__main__':
    pg.exec()
```

#### 🔍 شرح الكود:
- `addPlot(row, col)`: يُضيف رسمًا في موقع معين.
- `row=0, col=0`: الصف 0، العمود 0 (أعلى اليسار)
- `row=0, col=1`: الصف 0، العمود 1 (أعلى اليمين)

> ✅ مثالي للعرض المقارن.

---

## 🔹 **2. تخطيطات معقدة (2×2، 3×1، إلخ)**

### 📌 المثال 2: أربع رسومات (2 صفوف × 2 أعمدة)

```python
win = pg.GraphicsLayoutWidget(show=True, title="مخططات 2×2")
win.resize(1000, 800)

# إنشاء الرسومات
p1 = win.addPlot(row=0, col=0, title="cos(x)")
p1.plot(x, np.cos(x), pen='b')

p2 = win.addPlot(row=0, col=1, title="sin(x)")
p2.plot(x, np.sin(x), pen='r')

p3 = win.addPlot(row=1, col=0, title="cos²(x)")
p3.plot(x, np.cos(x)**2, pen='g')

p4 = win.addPlot(row=1, col=1, title="sin²(x)")
p4.plot(x, np.sin(x)**2, pen='m')
```

> ✅ يمكنك إنشاء أي تخطيط شبكي.

---

## 🔹 **3. مزامنة المحاور (Linking Axes)**

مفيد عندما تريد التكبير والتحريك على أكثر من رسم معًا.

### 📌 المثال 3: مزامنة المحور X

```python
# بعد إنشاء p1 و p2
p2.setXLink(p1)  # ربط محور X للرسم الثاني بالرسم الأول
```

> ✅ الآن، عند التكبير على `p1`، سيتكبّر `p2` بنفس النطاق.

---

### 📌 المثال 4: مزامنة المحور Y

```python
p2.setYLink(p1)
```

> ✅ مفيد في الرسومات التي تستخدم نفس المقياس.

---

## 🔹 **4. إخفاء المحاور المشتركة**

لتحسين المظهر البصري.

### 📌 المثال 5: إخفاء محور Y للرسم الثاني

```python
p2.hideAxis('left')  # إخفاء المحور الأيسر
p2.showAxis('right')  # (اختياري) إظهار محور على اليمين
```

> ✅ يجعل التخطيط أكثر انسيابية.

---

## 🔹 **5. إضافة نص أو عناصر فارغة**

لإضافة عناوين أو فواصل.

### 📌 المثال 6: إضافة نص بين الرسومات

```python
from pyqtgraph import LabelItem

label = LabelItem("تحليل دوال مثلثية", color='w', size=20)
win.addItem(label, row=0, col=0, colspan=2)  # تمتد على عمودين
```

> ✅ `colspan=2`: يُغطي عمودين.

---

## 🔹 **6. الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| لا تظهر الرسومات | نسيت `addPlot()` | تأكد من استخدام `addPlot(row, col)` |
| التكبير لا يعمل | لم يتم تفعيل `ViewBox` | تأكد من أن `mouseEnabled=True` |
| `setXLink()` لا يعمل | لم يتم ربط الرسومات بشكل صحيح | تأكد من ترتيب الإنشاء |
| التخطيط مشوّش | لم تُضبط الحجم | استخدم `win.resize()` |

---

## 🔹 **7. تمارين تطبيقية**

1. أنشئ تخطيطًا 3×1 يعرض `sin(x)`, `cos(x)`, و`tan(x)`.
2. مزامن محور X لجميع الرسومات.
3. أخفِ محور Y للرسمين الثاني والثالث.
4. أضف عنوانًا رئيسيًا أعلى التخطيط.

---

## 🔹 **8. الربط بالواقع: لوحة مراقبة بيانات حية**

### 🎯 الهدف: عرض 4 إشارات حية معًا

```python
# فرض 4 إشارات (مثل: مستشعرات في مصنع)
t = np.linspace(0, 10, 1000)
signals = {
    'درجة الحرارة': 25 + 5 * np.sin(t) + np.random.normal(0, 0.5, 1000),
    'الرطوبة': 60 + 10 * np.cos(t) + np.random.normal(0, 1, 1000),
    'الضغط': 1013 + np.random.normal(0, 5, 1000),
    'الاهتزاز': 0.1 * np.random.randn(1000)
}

win = pg.GraphicsLayoutWidget(show=True, title="لوحة مراقبة المصنع", size=(1200, 800))

plots = {}
for i, (name, data) in enumerate(signals.items()):
    row = i // 2
    col = i % 2
    plots[name] = win.addPlot(row=row, col=col, title=name)
    plots[name].plot(t, data, pen='y')
    plots[name].showGrid(y=True, alpha=0.3)
    if col > 0:
        plots[name].hideAxis('left')

# مزامنة محور الزمن
for name, p in plots.items():
    if name != 'درجة الحرارة':
        p.setXLink(plots['درجة الحرارة'])

print("📊 لوحة المراقبة جاهزة للتشغيل اللحظي!")
```

> ✅ هذا النوع من الواجهات يُستخدم في أنظمة SCADA.

---

## 🔹 **9. نصائح احترافية**

1. ✅ استخدم `GraphicsLayoutWidget` دائمًا للرسومات المتعددة.
2. ✅ استخدم `setXLink()` لربط الرسومات الزمنية.
3. ✅ استخدم `hideAxis()` لتحسين التصميم.
4. ✅ ضع الرسومات الأكثر أهمية في الزاوية العلوية اليسرى.
5. ✅ استخدم `LabelItem` لإضافة عناوين.

---

## 🔹 **10. أسئلة مراجعة**

1. كيف تُضيف رسمًا في الصف 1 والعمود 0؟
2. ما وظيفة `setXLink()`؟
3. كيف تُخفي محور Y؟
4. ما الفرق بين `GraphicsLayoutWidget` و `PlotWidget`؟
5. كيف تُجعل نصًا يغطي عمودين؟

---

## 🔹 **11. مراجعة سريعة (ملخص الدرس)**

| العنصر | الوظيفة |
|-------|--------|
| `GraphicsLayoutWidget` | حاوية للرسومات المتعددة |
| `addPlot(row, col)` | إضافة رسم في موقع معين |
| `setXLink(p)` | مزامنة محور X |
| `setYLink(p)` | مزامنة محور Y |
| `hideAxis('left')` | إخفاء محور |
| `LabelItem` | إضافة نص |
| `colspan` | تمديد العنصر على أعمدة |


# 📘 **الدرس 16 (موسع): دمج PyQtGraph في واجهات PyQt/PySide**


## 🔹 **مقدمة: لماذا ندمج PyQtGraph في واجهات أكبر؟**

حتى الآن، كنا نستخدم `PlotWidget` و `ImageView` بشكل منفصل.  
لكن في التطبيقات الحقيقية، نادرًا ما تكون الرسومات هي الشيء الوحيد في الواجهة.

غالبًا ما نحتاج إلى:
- إضافة **أزرار تحكم** (تشغيل، إيقاف، تحديث)
- إضافة **مربعات نصية** (إدخال معلمات)
- إضافة **قوائم منسدلة** (اختيار نوع البيانات)
- دمج الرسم مع **جداول** أو **نصوص توضيحية**

لهذا، يجب أن نتعلم كيفية دمج عناصر PyQtGraph داخل واجهات PyQt/PySide الأكبر، مثل `QMainWindow` أو `QDialog`.

---

## 🔹 **1. وضع `PlotWidget` داخل `QMainWindow`**

### 📌 المثال 1: نافذة رئيسية مع رسم وزر**

```python
import pyqtgraph as pg
from PySide6.QtWidgets import (
    QApplication, QMainWindow, QWidget, QVBoxLayout, QPushButton
)
from PySide6.QtCore import QTimer
import numpy as np
import sys

class MainWindow(QMainWindow):
    def __init__(self):
        super().__init__()
        self.setWindowTitle("تطبيق مراقبة مع أزرار")
        self.resize(800, 600)

        # إنشاء عنصر مركزي
        central_widget = QWidget()
        self.setCentralWidget(central_widget)

        # إنشاء تخطيط عمودي
        layout = QVBoxLayout(central_widget)

        # إنشاء الرسم
        self.plot_widget = pg.PlotWidget(title="بيانات حية")
        self.plot_widget.setLabel('left', 'القيمة')
        self.plot_widget.setLabel('bottom', 'الزمن')
        self.curve = self.plot_widget.plot(pen='y')

        # إضافة الرسم إلى التخطيط
        layout.addWidget(self.plot_widget)

        # إضافة زر
        self.btn_toggle = QPushButton("إيقاف/تشغيل التحديث")
        self.btn_toggle.setCheckable(True)
        self.btn_toggle.setChecked(True)
        self.btn_toggle.toggled.connect(self.toggle_timer)
        layout.addWidget(self.btn_toggle)

        # بيانات افتراضية
        self.x = np.linspace(0, 50, 1000)
        self.i = 0

        # مؤقت التحديث
        self.timer = QTimer()
        self.timer.timeout.connect(self.update_plot)
        self.timer.start(50)

    def update_plot(self):
        if not self.btn_toggle.isChecked():
            return
        y = np.sin(self.x[:self.i+1] * 0.5) + 0.1 * np.random.randn(self.i+1)
        self.curve.setData(self.x[:self.i+1], y)
        self.i = (self.i + 1) % len(self.x)

    def toggle_timer(self, checked):
        if checked:
            self.timer.start(50)
        else:
            self.timer.stop()

app = QApplication(sys.argv)
window = MainWindow()
window.show()
app.exec()
```

#### 🔍 شرح الكود:
- `QMainWindow`: النافذة الرئيسية.
- `QWidget` + `QVBoxLayout`: لتنظيم العناصر.
- `setCentralWidget()`: لتحديد العنصر المركزي.
- `QPushButton` مع `setCheckable(True)`: زر تبديل.
- يتم التحكم في المؤقت من الزر.

> ✅ هذا هو الشكل الأساسي لأي تطبيق تفاعلي.

---

## 🔹 **2. استخدام `GraphicsLayoutWidget` في التخطيطات المعقدة**

### 📌 المثال 2: تخطيط شبكة (Grid Layout)

```python
from PySide6.QtWidgets import QGridLayout

# داخل __init__ بعد إنشاء central_widget
layout = QGridLayout(central_widget)

# إنشاء رسمين
self.plot1 = pg.PlotWidget(title="الرسم 1")
self.plot2 = pg.PlotWidget(title="الرسم 2")

# إضافة الرسومات إلى التخطيط
layout.addWidget(self.plot1, 0, 0)  # الصف 0، العمود 0
layout.addWidget(self.plot2, 0, 1)  # الصف 0، العمود 1
```

> ✅ مثالي للواجهات التي تدمج نصوص، أزرار، ورسومات.

---

## 🔹 **3. دمج `ImageView` مع عناصر تحكم**

### 📌 المثال 3: عرض صورة مع زر تحميل

```python
from PySide6.QtWidgets import QFileDialog

# إضافة زر لتحميل صورة
self.btn_load = QPushButton("تحميل صورة")
self.btn_load.clicked.connect(self.load_image)
layout.addWidget(self.btn_load)

# إنشاء ImageView
self.image_view = pg.ImageView()
layout.addWidget(self.image_view)

def load_image(self):
    file_path, _ = QFileDialog.getOpenFileName(
        self, "اختر صورة", "", "Images (*.png *.xpm *.jpg *.bmp)"
    )
    if file_path:
        # في الواقع، يجب استخدام مكتبة مثل `imageio` أو `Pillow`
        # لكن لهذا المثال، نُنشئ بيانات وهمية
        import numpy as np
        fake_image = np.random.rand(200, 200) * 255
        self.image_view.setImage(fake_image)
```

> ✅ في التطبيقات الحقيقية، استخدم `imageio.imread()` أو `Pillow`.

---

## 🔹 **4. الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| لا تظهر الرسومات | لم تُضف إلى التخطيط | تأكد من `layout.addWidget(plot)` |
| الزر لا يعمل | لم تُربط الإشارة | تأكد من `clicked.connect()` |
| `PlotWidget` لا يأخذ المساحة | لم يتم تعيين التخطيط بشكل صحيح | تأكد من `setCentralWidget()` |
| `QFileDialog` لا يظهر | لم يتم استدعاء `exec()` | استخدم `getOpenFileName()` بشكل صحيح |

---

## 🔹 **5. تمارين تطبيقية**

1. أنشئ `QMainWindow` به `PlotWidget` وزر "إعادة تعيين".
2. أضف قائمة منسدلة لاختيار نوع الخريطة اللونية.
3. أنشئ تطبيقًا يعرض `ImageView` مع زر "تحديث البيانات".
4. ضع رسمين في تخطيط شبكة 2×2.

---

## 🔹 **6. الربط بالواقع: تطبيق مراقبة متكامل**

### 🎯 الهدف: بناء واجهة مراقبة مع تحكم كامل

```python
class MonitoringApp(QMainWindow):
    def __init__(self):
        super().__init__()
        self.setWindowTitle("لوحة مراقبة متكاملة")
        self.resize(1200, 800)

        central = QWidget()
        self.setCentralWidget(central)
        layout = QVBoxLayout(central)

        # تخطيط رئيسي (على شكل شبكة)
        main_layout = QGridLayout()
        layout.addLayout(main_layout)

        # رسومات
        self.temp_plot = pg.PlotWidget(title="درجة الحرارة")
        self.humi_plot = pg.PlotWidget(title="الرطوبة")
        self.pres_plot = pg.PlotWidget(title="الضغط")

        main_layout.addWidget(self.temp_plot, 0, 0)
        main_layout.addWidget(self.humi_plot, 0, 1)
        main_layout.addWidget(self.pres_plot, 1, 0, 1, 2)  # يمتد على عمودين

        # عناصر التحكم
        control_layout = QHBoxLayout()
        self.btn_start = QPushButton("بدء")
        self.btn_stop = QPushButton("إيقاف")
        self.btn_reset = QPushButton("إعادة تعيين")
        control_layout.addWidget(self.btn_start)
        control_layout.addWidget(self.btn_stop)
        control_layout.addWidget(self.btn_reset)
        layout.addLayout(control_layout)

        # المؤقت
        self.timer = QTimer()
        self.setup_plots()

        self.btn_start.clicked.connect(self.start_monitoring)
        self.btn_stop.clicked.connect(self.stop_monitoring)
        self.btn_reset.clicked.connect(self.reset_data)

    def setup_plots(self):
        # إعداد الرسومات
        pass

    def start_monitoring(self):
        self.timer.start(100)

    def stop_monitoring(self):
        self.timer.stop()

    def reset_data(self):
        # إعادة تعيين البيانات
        pass

# تشغيل التطبيق
app = QApplication(sys.argv)
window = MonitoringApp()
window.show()
app.exec()
```

> ✅ هذا هو الشكل الذي تُبنى عليه التطبيقات الصناعية.

---

## 🔹 **7. نصائح احترافية**

1. ✅ استخدم `QMainWindow` كنقطة بداية لأي تطبيق كبير.
2. ✅ استخدم `QVBoxLayout` أو `QGridLayout` لتنظيم العناصر.
3. ✅ احفظ مراجع لعناصر الرسم (مثل `self.plot_widget`) للوصول إليها لاحقًا.
4. ✅ استخدم `setCheckable(True)` للأزرار التي تُغيّر الحالة.
5. ✅ فصل منطق التحديث عن واجهة المستخدم (مبدأ الفصل).

---

## 🔹 **8. أسئلة مراجعة**

1. كيف تُضيف `PlotWidget` إلى `QMainWindow`؟
2. ما الفرق بين `QVBoxLayout` و `QGridLayout`؟
3. كيف تُربط زرًا بحدث؟
4. كيف تُوقف مؤقتًا عند النقر على زر؟
5. كيف تُنشئ زر تبديل (Toggle Button)؟

---

## 🔹 **9. مراجعة سريعة (ملخص الدرس)**

| العنصر | الوظيفة |
|-------|--------|
| `QMainWindow` | النافذة الرئيسية |
| `setCentralWidget()` | تعيين العنصر المركزي |
| `QVBoxLayout` | تخطيط عمودي |
| `QGridLayout` | تخطيط شبكي |
| `QPushButton` | زر تحكم |
| `clicked.connect()` | ربط حدث الزر |
| `setCheckable(True)` | جعل الزر قابلاً للتبديل |


# 📘 **الدرس 17 (موسع): التصدير والحفظ**


## 🔹 **مقدمة: لماذا نحتاج إلى تصدير النتائج؟**

بعد أن تحلّل البيانات، وتُنظّفها، وتُنتج رؤى قيّمة، يأتي الوقت لـ:
- **مشاركة النتائج** مع الفريق أو الإدارة
- **استخدام البيانات في تطبيقات أخرى** (مثل: Excel، تقارير Power BI)
- **حفظ النتائج الوسيطة** لاستخدامها لاحقًا
- **أرشفة التحليل** للرجوع إليه

لهذا، نحتاج إلى أدوات قوية وآمنة لـ **حفظ البيانات وتصدير الرسومات**.

في هذا الدرس، ستتعلم كيفية:
- حفظ DataFrame إلى ملفات
- أخذ لقطات (Screenshot) من رسومات PyQtGraph
- تصدير النتائج بشكل احترافي

---

## 🔹 **1. حفظ البيانات إلى ملفات (مراجعات وتوسع)**

### 📌 المثال 1: حفظ إلى CSV (مع دعم العربية)

```python
# أفضل إعدادات لملفات CSV
df.to_csv('results.csv', 
          index=False, 
          encoding='utf-8-sig',  # ضروري لعرض العربية في إكسل
          sep=',')
```

> ✅ `utf-8-sig`: يحل مشكلة عرض النصوص العربية في Excel.

---

### 📌 المثال 2: حفظ إلى Excel متعدد الأوراق

```python
with pd.ExcelWriter('report.xlsx', engine='openpyxl') as writer:
    df_sales.to_excel(writer, sheet_name='المبيعات', index=False)
    df_summary.to_excel(writer, sheet_name='الملخص', index=False)
    df_trends.to_excel(writer, sheet_name='الاتجاهات', index=False)
```

> ✅ مثالي للتقارير الإدارية.

---

### 📌 المثال 3: حفظ إلى JSON لواجهات برمجة التطبيقات

```python
df.to_json('api_data.json', 
           force_ascii=False,  # يسمح بالحروف غير الإنجليزية
           orient='records',   # كل صف ككائن
           indent=4)           # تنسيق جميل
```

> ✅ جاهز للإرسال عبر API.

---

## 🔹 **2. أخذ لقطات من رسومات PyQtGraph (Screenshots)**

### 📌 المثال 4: حفظ لقطة من `PlotWidget`

```python
import pyqtgraph as pg
from PySide6.QtWidgets import QApplication
import numpy as np
import sys

app = QApplication(sys.argv)

# إنشاء رسم
win = pg.plot(title="بيانات المبيعات")
x = np.linspace(0, 10, 100)
y = np.sin(x)
win.plot(x, y, pen='b')

# حفظ لقطة
win.grab().save("plot_screenshot.png")

print("✅ تم حفظ اللقطة كـ plot_screenshot.png")

if __name__ == '__main__':
    pg.exec()
```

#### 🔍 شرح:
- `win.grab()`: يلتقط صورة من النافذة.
- `.save("filename.png")`: يحفظ الصورة.

> ✅ التنسيقات المدعومة: PNG, JPG, BMP.

---

### 📌 المثال 5: حفظ لقطة من `ImageView`

```python
view = pg.ImageView()
view.setImage(np.random.rand(100, 100))
view.setWindowTitle("تحليل حرارة")

# بعد عرض النافذة
view.show()
view.grab().save("thermal_analysis.png")
```

> ✅ مثالي لعرض النتائج في التقارير.

---

## 🔹 **3. أزرار التحكم في الحفظ (دمج مع واجهة PyQt)**

### 📌 المثال 6: زر لحفظ لقطة

```python
from PySide6.QtWidgets import QPushButton, QFileDialog

# داخل واجهة المستخدم
self.btn_save_plot = QPushButton("حفظ الرسم كصورة")
self.btn_save_plot.clicked.connect(self.save_plot_screenshot)

def save_plot_screenshot(self):
    # فتح نافذة اختيار الملف
    file_path, _ = QFileDialog.getSaveFileName(
        self, "حفظ الصورة", "", "Images (*.png *.jpg *.bmp)"
    )
    if file_path:
        self.plot_widget.grab().save(file_path)
        print(f"تم حفظ الصورة في: {file_path}")
```

> ✅ يجعل التطبيق تفاعليًا.

---

## 🔹 **4. الأخطاء الشائعة**

| الخطأ | السبب | الحل |
|------|------|------|
| النص العربي مشوّش في CSV | ترميز خاطئ | استخدم `encoding='utf-8-sig'` |
| `grab()` لا يعمل | النافذة لم تُعرض بعد | تأكد من `show()` قبل `grab()` |
| `QFileDialog` لا يظهر | لم يتم استدعاء `exec()` | استخدم `getSaveFileName()` بشكل صحيح |
| ملف Excel فارغ | لم تُستخدم `with` أو `writer` | تأكد من إغلاق الـ Writer |

---

## 🔹 **5. تمارين تطبيقية**

1. احفظ DataFrame يحتوي على بيانات عربية إلى ملف CSV.
2. أنشئ تقرير Excel به ورقتين: "الإجماليات" و"التفاصيل".
3. أضف زرًا في واجهة PyQtGraph لحفظ لقطة من الرسم.
4. حوّل DataFrame إلى JSON جاهز لـ API.

---

## 🔹 **6. الربط بالواقع: تصدير تقرير شهري**

### 🎯 الهدف: إرسال التقرير للإدارة

```python
# افترض أن لديك نتائج تحليل
summary_report = df.groupby('القسم')['الراتب'].agg(['mean', 'sum', 'count'])

# 1. حفظ كـ CSV للتحليل الآلي
summary_report.to_csv('monthly_report.csv', encoding='utf-8-sig')

# 2. حفظ كـ Excel لتوزيعه على الإدارة
with pd.ExcelWriter('monthly_report_manager.xlsx') as writer:
    summary_report.to_excel(writer, sheet_name='الملخص')
    df.to_excel(writer, sheet_name='البيانات_الكاملة', index=False)

# 3. أخذ لقطة من الرسم البياني
plot_win.grab().save('salary_chart.png')

print("✅ التقرير والرسم تم تصديرهما بنجاح.")
```

> ✅ هذا هو الشكل النهائي لأي مشروع تحليل بيانات.

---

## 🔹 **7. نصائح احترافية**

1. ✅ استخدم دائمًا `index=False` ما لم تكن بحاجة للفهرس.
2. ✅ استخدم `utf-8-sig` لضمان ظهور العربية بشكل صحيح.
3. ✅ استخدم `QFileDialog` للسماح للمستخدم باختيار الموقع.
4. ✅ وثّق مسار الحفظ في تعليق: `# تم الحفظ في ./output/`
5. ✅ احفظ النتائج الوسيطة لتسهيل التصحيح.

---

## 🔹 **8. أسئلة مراجعة**

1. ما الفرق بين `utf-8` و `utf-8-sig`؟
2. كيف تُحفظ لقطة من `PlotWidget`؟
3. ما وظيفة `orient='records'` في `to_json()`؟
4. كيف تُنشئ ملف Excel به عدة أوراق؟
5. كيف تُظهر نافذة حفظ الملف للمستخدم؟

---

## 🔹 **9. مراجعة سريعة (ملخص الدرس)**

| الوظيفة | الكود |
|--------|------|
| حفظ CSV | `to_csv('file.csv', index=False, encoding='utf-8-sig')` |
| حفظ Excel متعدد الأوراق | `with pd.ExcelWriter(...) as writer:` |
| حفظ JSON | `to_json(..., force_ascii=False, orient='records')` |
| أخذ لقطة | `widget.grab().save('image.png')` |
| فتح نافذة حفظ | `QFileDialog.getSaveFileName()` |

بالطبع! إليك:

---

# 📘 **الدرس 18 (موسع): مشروع عملي**

> ✅ **عدد الكلمات: ~1600**

---

## 🔹 **مقدمة: لماذا نحتاج إلى مشروع عملي؟**

لقد تعلمت حتى الآن عشرات الأدوات والتقنيات في PyQtGraph.  
الآن حان الوقت لدمج كل ما تعلمته في **مشروع تطبيقي واقعي**.

هذا الدرس يُشبه "الامتحان النهائي"، حيث ستُبنى تطبيقًا متكاملًا يُظهر:
- عرض بيانات حية
- رسومات متعددة
- تفاعل مع المستخدم
- واجهة مستخدم مخصصة

> 🎯 **الهدف النهائي**: بناء تطبيق **مراقبة مستشعرات في الزمن الحقيقي**.

---

## 🔹 **1. فكرة المشروع: مراقبة مستشعرات في الزمن الحقيقي**

### 📌 **السيناريو**
تخيل أنك تعمل على نظام يراقب بيئة معمل أو مصنع.  
هناك 3 مستشعرات:
1. **درجة الحرارة** (°C)
2. **الرطوبة** (%) 
3. **الاهتزاز** (وحدة قياس وهمية)

البيانات تصل بشكل لحظي، ويجب عرضها على شاشة مراقبة تحتوي على:
- 3 رسومات منفصلة
- أزرار للتحكم (تشغيل/إيقاف، إعادة تعيين)
- عرض قيم حالية
- لون خلفية يُشير إلى حالة النظام (أخضر = طبيعي، أحمر = إنذار)

---

## 🔹 **2. هيكل المشروع**

```
monitoring_app.py
│
├── MainWindow (QMainWindow)
│   ├── Central Widget
│   │   ├── Main Layout (QVBoxLayout)
│   │   │   ├── Control Layout (QHBoxLayout)
│   │   │   │   ├── QPushButton: Start/Stop
│   │   │   │   ├── QPushButton: Reset
│   │   │   │   └── QLabel: القيم الحالية
│   │   │   ├── Temperature Plot (PlotWidget)
│   │   │   ├── Humidity Plot (PlotWidget)
│   │   │   └── Vibration Plot (PlotWidget)
│   │   └── QTimer: لتحديث البيانات
│   └── Data Buffer: لتخزين البيانات
```

---

## 🔹 **3. الكود الكامل للمشروع**

```python
import pyqtgraph as pg
from PySide6.QtWidgets import (
    QApplication, QMainWindow, QWidget, QVBoxLayout,
    QHBoxLayout, QPushButton, QLabel
)
from PySide6.QtCore import QTimer
from PySide6.QtGui import QFont
import numpy as np
import sys

class SensorMonitor(QMainWindow):
    def __init__(self):
        super().__init__()
        self.setWindowTitle("مراقبة المستشعرات اللحظية")
        self.resize(1200, 800)

        # العنصر المركزي
        central_widget = QWidget()
        self.setCentralWidget(central_widget)

        # التخطيط الرئيسي
        main_layout = QVBoxLayout(central_widget)

        # تخطيط عناصر التحكم
        control_layout = QHBoxLayout()
        self.btn_start = QPushButton("بدء المراقبة")
        self.btn_start.setCheckable(True)
        self.btn_start.setChecked(True)
        self.btn_start.toggled.connect(self.toggle_monitoring)

        self.btn_reset = QPushButton("إعادة تعيين")
        self.btn_reset.clicked.connect(self.reset_data)

        # عرض القيم الحالية
        self.current_values = QLabel("القيم الحالية: --, --, --")
        self.current_values.setFont(QFont("Arial", 12))
        self.current_values.setStyleSheet("background-color: #f0f0f0; padding: 10px; border-radius: 5px;")

        control_layout.addWidget(self.btn_start)
        control_layout.addWidget(self.btn_reset)
        control_layout.addWidget(self.current_values)
        main_layout.addLayout(control_layout)

        # إعداد المخزن المؤقت
        self.buffer_size = 200
        self.time = np.linspace(0, 20, self.buffer_size)  # 20 ثانية
        self.temp_data = np.zeros(self.buffer_size)
        self.humi_data = np.zeros(self.buffer_size)
        self.vibe_data = np.zeros(self.buffer_size)
        self.ptr = 0  # مؤشر الكتابة

        # إعداد الرسومات
        self.setup_plots(main_layout)

        # المؤقت
        self.timer = QTimer()
        self.timer.timeout.connect(self.update_plots)
        self.timer.start(100)  # كل 100 ميلي ثانية

    def setup_plots(self, layout):
        """إنشاء وإعداد الرسومات الثلاثة"""
        # درجة الحرارة
        self.temp_plot = pg.PlotWidget(title="درجة الحرارة (°C)")
        self.temp_plot.setLabel('left', 'درجة الحرارة')
        self.temp_plot.setLabel('bottom', 'الزمن (ثانية)')
        self.temp_plot.showGrid(y=True, alpha=0.3)
        self.temp_curve = self.temp_plot.plot(pen='r', name='درجة الحرارة')
        layout.addWidget(self.temp_plot)

        # الرطوبة
        self.humi_plot = pg.PlotWidget(title="الرطوبة (%)")
        self.humi_plot.setLabel('left', 'الرطوبة')
        self.humi_plot.setLabel('bottom', 'الزمن (ثانية)')
        self.humi_plot.showGrid(y=True, alpha=0.3)
        self.humi_curve = self.humi_plot.plot(pen='b', name='الرطوبة')
        layout.addWidget(self.humi_plot)

        # الاهتزاز
        self.vibe_plot = pg.PlotWidget(title="الاهتزاز")
        self.vibe_plot.setLabel('left', 'الاهتزاز')
        self.vibe_plot.setLabel('bottom', 'الزمن (ثانية)')
        self.vibe_plot.showGrid(y=True, alpha=0.3)
        self.vibe_curve = self.vibe_plot.plot(pen='m', name='الاهتزاز')
        layout.addWidget(self.vibe_plot)

    def generate_sensor_data(self):
        """توليد بيانات وهمية للمستشعرات"""
        # درجة الحرارة: 25 ± 5 مع تذبذب
        temp = 25 + 5 * np.sin(0.1 * self.ptr) + np.random.normal(0, 0.5)
        # الرطوبة: 60 ± 10
        humi = 60 + 10 * np.cos(0.08 * self.ptr) + np.random.normal(0, 1)
        # الاهتزاز: عادة منخفض، لكن به قفزات عرضية
        vibe = 0.5 + np.random.normal(0, 0.1)
        if np.random.rand() < 0.05:  # 5% فرصة لاهتزاز عالي
            vibe += np.random.rand() * 5

        return temp, humi, vibe

    def update_plots(self):
        """تحديث جميع الرسومات"""
        if not self.btn_start.isChecked():
            return

        temp, humi, vibe = self.generate_sensor_data()

        # تحديث المخزن
        self.temp_data[self.ptr] = temp
        self.humi_data[self.ptr] = humi
        self.vibe_data[self.ptr] = vibe

        # تحديث المنحنيات
        self.update_curve(self.temp_curve, self.temp_data)
        self.update_curve(self.humi_curve, self.humi_data)
        self.update_curve(self.vibe_curve, self.vibe_data)

        # تحديث العرض
        self.current_values.setText(
            f"القيم الحالية: {temp:.1f}°C, {humi:.1f}%, {vibe:.2f}"
        )

        # تغيير لون الخلفية إذا كانت هناك إنذار
        if vibe > 3.0:
            self.current_values.setStyleSheet("background-color: #ffcccc; padding: 10px; border-radius: 5px;")
        else:
            self.current_values.setStyleSheet("background-color: #ccffcc; padding: 10px; border-radius: 5px;")

        # تقدم المؤشر
        self.ptr = (self.ptr + 1) % self.buffer_size

    def update_curve(self, curve, data):
        """تحديث منحنى معين"""
        ptr = self.ptr
        # عرض البيانات من المؤشر إلى النهاية، ثم من البداية إلى المؤشر (للسلاسة)
        y_view = np.concatenate([data[ptr:], data[:ptr]])
        curve.setData(self.time, y_view)

    def reset_data(self):
        """إعادة تعيين جميع البيانات"""
        self.temp_data[:] = 0
        self.humi_data[:] = 0
        self.vibe_data[:] = 0
        self.ptr = 0
        self.current_values.setText("القيم الحالية: --, --, --")
        self.current_values.setStyleSheet("background-color: #f0f0f0; padding: 10px; border-radius: 5px;")

    def toggle_monitoring(self, checked):
        if checked:
            self.btn_start.setText("إيقاف المراقبة")
        else:
            self.btn_start.setText("بدء المراقبة")

if __name__ == '__main__':
    app = QApplication(sys.argv)
    window = SensorMonitor()
    window.show()
    app.exec()
```

---

## 🔹 **4. شرح الكود خطوة بخطوة**

### ✅ **1. الهيكل العام**
- `QMainWindow`: النافذة الرئيسية.
- `QVBoxLayout`: تخطيط رئيسي عمودي.
- `QHBoxLayout`: تخطيط أفقي للعناصر العليا.

### ✅ **2. عناصر التحكم**
- زر "بدء/إيقاف": يستخدم `setCheckable(True)` لتبديل الحالة.
- زر "إعادة تعيين": يعيد البيانات إلى الصفر.
- `QLabel`: يعرض القيم الحالية بلون خلفية ديناميكي.

### ✅ **3. إدارة البيانات**
- `buffer_size`: حجم المخزن (200 نقطة).
- `time`: مصفوفة زمن ثابتة.
- `ptr`: مؤشر يدور حول المخزن (Circular Buffer).

### ✅ **4. الرسومات**
- تم إنشاء 3 `PlotWidget` لكل مستشعر.
- تم تفعيل الشبكة (`showGrid`) لتحسين القراءة.

### ✅ **5. التحديث اللحظي**
- `QTimer` يُنفّذ `update_plots` كل 100 ميلي ثانية.
- `setData()` يُستخدم لتحديث البيانات بسرعة.
- `np.concatenate` يُستخدم لجعل الرسم يتدفق بشكل دائري.

---

## 🔹 **5. الأخطاء الشائعة والتصحيح**

| المشكلة | الحل |
|--------|------|
| الرسومات لا تُحدّث | تأكد من أن `timer.start()` يعمل |
| البيانات تتوقف عند 200 | تأكد من أن `ptr` يتم تدويره `% buffer_size` |
| الألوان لا تتغير | تأكد من `setStyleSheet()` |
| `QLabel` لا يعرض القيم | تأكد من `setText()` |
| المؤشر لا يظهر | تأكد من `show()` للنافذة |

---

## 🔹 **6. تمارين تطبيقية**

1. أضف مؤشرًا يُظهر "النظام طبيعي" أو "إنذار!" بناءً على الاهتزاز.
2. احفظ أحدث 1000 قيمة من البيانات إلى ملف CSV عند الإغلاق.
3. أضف خريطة لونية لعرض الاهتزاز في `ImageView`.
4. أضف زرًا لتصدير لقطة من كل رسم.

---

## 🔹 **7. توسيع المشروع (أفكار متقدمة)**

- **إضافة `ImageView`**: لعرض مصفوفة حرارة تمثل توزيع الحرارة.
- **إضافة `GLViewWidget`**: لعرض نموذج ثلاثي الأبعاد للمصنع.
- **ربط بمنفذ تسلسلي (Serial)**: لقراءة بيانات حقيقية من أجهزة Arduino.
- **إضافة تنبيه صوتي**: عند تجاوز الحدود.
- **تسجيل البيانات**: حفظها إلى قاعدة بيانات.

---

## 🔹 **8. نصائح احترافية**

1. ✅ فصل منطق البيانات عن واجهة المستخدم.
2. ✅ استخدام `Circular Buffer` للبيانات الحية.
3. ✅ استخدام `setData()` بدل `plot()` في الحلقات.
4. ✅ استخدام `QTimer` بدل `time.sleep()`.
5. ✅ توثيق الكود جيدًا.

---

## 🔹 **9. أسئلة مراجعة**

1. ما دور `ptr` في الكود؟
2. كيف تُحدث منحنى بشكل لحظي؟
3. ما الفرق بين `QVBoxLayout` و `QHBoxLayout`؟
4. كيف تُغير لون خلفية `QLabel` ديناميكيًا؟
5. لماذا نستخدم `np.concatenate` في `update_curve`؟

---

## 🔹 **10. مراجعة سريعة (ملخص المشروع)**

| العنصر | الوظيفة |
|-------|--------|
| `QMainWindow` | النافذة الرئيسية |
| `QTimer` | التحديث اللحظي |
| `Circular Buffer` | تخزين البيانات |
| `setData()` | تحديث الرسم بسرعة |
| `setStyleSheet()` | تغيير مظهر العناصر |
| `QLabel` | عرض القيم الحالية |

# ✅ **جدول مرجعي سريع: أهم دوال PyQtGraph**

| الدالة | الوصف |
|--------|------|
| `pg.plot()` | إنشاء رسم سريع |
| `pg.PlotWidget()` | حاوية رسم |
| `pg.GraphicsLayoutWidget()` | تخطيط متعدد الرسومات |
| `curve.setData()` | تحديث بيانات الرسم |
| `view.setMouseEnabled()` | التحكم في التفاعل |
| `scatter.sigClicked.connect()` | ربط حدث النقر |
| `imageView.setImage()` | عرض صورة |
| `imageView.setColorMap()` | تطبيق خريطة لونية |
| `GLViewWidget()` | نافذة 3D |
| `QTimer()` | التحديث اللحظي |