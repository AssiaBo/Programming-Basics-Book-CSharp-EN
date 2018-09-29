#### Reading the Input Data и изчисляване на разстоянието до най-близкич край на отсечката

Четем входа от конзолата.

![](/assets/chapter-8-1-images/03.Point-on-segment-04.png)

Тъй като не знаем коя **точка** е от ляво и коя е от дясно, ще си направим две променливи, които да ни отбелязват това. Тъй като **лявата точка** е винаги тази с по-малката **х координата**, ще ползваме **`Math.Min(…)`**, за да я намерим. Съответно, **дясната** е винаги тази с по-голяма **х координата** и ползваме **`Math.Max(…)`**. Ще намерим и разстоянието от **точката x** до **двете точки**. Понеже не знаем положението им една спрямо друга, ще използваме **`Math.Abs(…)`**, за да получим положителен резултат.

![](/assets/chapter-8-1-images/03.Point-on-segment-05.png)

По-малкото от двете **разстояния** ще намерим ползвайки **`Math.Min(…)`**.

![](/assets/chapter-8-1-images/03.Point-on-segment-06.png)