# E-commerce-Funnel-Performance-Weekly-conversion-and-revenue-overview
E-commerce Funnel Performance Weekly conversion and revenue overview
## Business Task — Бізнес-завдання
На яких етапах E-commerce-воронка втрачає найбільше сесій та які сегменти потребують першочергового дослідження?
## My Task
На якому етапі E-commerce-воронки спостерігаються найбільші абсолютні втрати сесій?<br>
Які переходи між етапами мають найнижчу конверсію (Step CVR) та потребують першочергової уваги?<br>
Наскільки відрізняється ефективність конверсії в покупку залежно від типу пристрою?<br>
Які джерела залучення генерують значний обсяг трафіку, але демонструють низьку Purchase CVR?<br>
Як змінюються виручка (Revenue) та конверсія в покупку (Purchase CVR) протягом досліджуваного періоду?<br>
Чим пояснюється різниця між загальною Purchase CVR та конверсією на фінальному етапі послідовної воронки?<br>
<br>
Task 1. На якому етапі E-commerce-воронки спостерігаються найбільші абсолютні втрати сесій?<br>
Для цього завдання недостатньо знайти перехід із найбільшим Drop-off за один тиждень. Потрібно визначити, де втрачається найбільше сесій, чи повторюється ця проблема в різні періоди та чи свідчить вона про погіршення ефективності воронки.
1. Методологія аналізу<br>
У Google BigQuery я сформувала послідовну E-commerce-воронку із шести етапів:<br>
<img width="945" height="37" alt="image" src="https://github.com/user-attachments/assets/a4ca3dad-e523-4de8-a0e0-dbdb9acff6e0" /><br>
Для кожного переходу використала три показники:<br>
<img width="1847" height="522" alt="image" src="https://github.com/user-attachments/assets/af4d59ad-0f4a-4607-aff1-d79e8f05dd12" />
<img width="982" height="651" alt="image" src="https://github.com/user-attachments/assets/844007d3-6192-4ab5-b6c6-d78979e6448e" />


<img width="943" height="645" alt="image" src="https://github.com/user-attachments/assets/843c2ab5-9761-473e-87cc-30f832cd6da0" /><br>
<br>
Аналіз E-commerce Funnel Performance
Період: 16.11.2020–25.01.2021 (11 тижнів)<br>
За аналізований період зафіксовано 305 365 початкових сесій, з яких лише 2 529 (0,83%) пройшли всі етапи воронки до Purchase.
<img width="981" height="395" alt="image" src="https://github.com/user-attachments/assets/c845c078-bdf1-4c68-9542-bee547e326ad" />




<img width="1465" height="607" alt="image" src="https://github.com/user-attachments/assets/ddc18ddd-3444-4f51-beae-10cd418688d7" />

