# Mac mini M1 · Атлас конструкції D2.2

[Відкрити корпус у 3D](https://dvaderfun.github.io/mac-mini-m1-case-prototype/) · [задня панель: зняття й установлення](https://dvaderfun.github.io/mac-mini-m1-case-prototype/?view=rear) · [сторона друку](https://dvaderfun.github.io/mac-mini-m1-case-prototype/#panel-print) · [порівняння з D2.1](rear-comparison.jpg).

Задня панель опускається зверху в два пази боковин, спирається на полицю дна й фіксується верхньою кришкою. Від’єднайте кабелі, зніміть кришку та підніміть панель на 36 мм (CAD). STL панелі вже лежить видимою зовнішньою стороною на столі: у першому шарі всі вісім портів. Панель, дно й кришку беріть з однієї ревізії.

[STL і STEP](https://dvaderfun.github.io/mac-mini-m1-case-prototype/#downloads) · [файли у Git](downloads/d2.2/) · [перша примірка](downloads/d2.2/d2.2-first-fit.zip) · [корпус](downloads/d2.2/d2.2-cold-fit-kit.zip) · [збірка STEP](downloads/d2.2/d22-assembly.step). Одиниці — мм. Файли пройшли цифрову перевірку; фізичний друк і посадка ще попереду.

Сім видів, повний екран: [плата Mac](https://dvaderfun.github.io/mac-mini-m1-case-prototype/?view=board), [опори](https://dvaderfun.github.io/mac-mini-m1-case-prototype/?view=base), [PD trigger та Mini‑560](https://dvaderfun.github.io/mac-mini-m1-case-prototype/?view=power), [окрема PCB v1](https://dvaderfun.github.io/mac-mini-m1-case-prototype/?view=pcb). [GLB плати без антен](reference/mac-board-reference.glb); [рисунки двох знятих антен](https://dvaderfun.github.io/mac-mini-m1-case-prototype/#antennas). Розміри втулок і простір для джгута треба звірити на реальній платі. Тепло й RF ще не перевіряли.

Щоб отримати файли через Git:

~~~sh
git clone --depth 1 https://github.com/Dvaderfun/mac-mini-m1-case-prototype.git
cd mac-mini-m1-case-prototype/downloads/d2.2
~~~

[Архів D2.1 з боковим ходом](d2.1/?view=rear) · [D2](d2/?view=rear) · [D1](d1/) · [H1](h1/?mode=hybrid) · [джерела й ліцензії](ATTRIBUTION.md).
