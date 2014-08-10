## Глава 27. Научись любить обслуживание

Несколько лет назад я участвовал в создании с нуля центра разработки программного
обеспечения размером в 250 человек. Нам дали пустое здание и поставили задачу 
нанять сотрудников, чтобы полностью покрыть потребность организации в разработчиках.
В этом проекте мы столкнулись с испытанием, которого не ожидали. Каждый горел 
желанием создавать новые системы, но никто не хотел обслуживать старые. 
Мы хотели создать новую среду с энергичной культурой, поэтому надо было уделить 
внимание тому, чего _хотят_ наши новые работники, если мы планировали начать в 
правильном ключе.

Все любят быть творцами. Это тот момент, когда мы чувствуем, что получили возможность
действительно "поставить штампик" на часть работы. Чувствуем, что владеем
результатом. Что выражаем себя через создание. Мы также склонны верить в то, что
проекты — наиболее заметная часть для наших организаций. Люди, которые создают
новое поколение — это люди, которые должны получить всю славу, правильно?
Я знал, что такое отношение будет преобладать, исходя из предыдущего опыта работы
с программистами. Но имея дело с несколькими сотнями разработчиков, этой
[чашей Петри](http://ru.wikipedia.org/wiki/Чашка_Петри) из человеческих ресурсов,
я насмотрелся этого через край, гораздо больше, чем ожидал.

Хотя разработчики ПО обычно креативные и свободолюбивые люди, программерское
"сообщество" на удивление кастовое. Программисты хотят быть дизайнерами, которые
хотят быть архитекторами, и так далее. Работа по обслуживанию не сулит им
следующий уровень на пути к чёрному поясу и, ясное дело, к более значимой
роли (такой, как _архитектор_), о которой они смогут рассказать своим родителям
или приятелям из колледжа.

Итак, мотивирующие факторы — это возможность творить и шанс сделать шаги
к продвижению по карьерной лестнице. Забавное в этом то, что работа над
проектами — совсем _необязательно_ лучшее место для этого.

Работы по техническому обслуживанию обычно завалены старыми, загнивающими системами
и въедливыми конечными пользователями. Как только софт считается готовым,
IT-отделы обычно фокусируются на уменьшении издержек по обслуживанию
этих систем, поэтому они ищут самые дешёвые из возможных способов поддержания 
систем в рабочем состоянии.

Это обычно означает, что выделяется слишком малая доля ресурсов для наблюдения
за системами и отсутствуют значительные денежные вливания в обновление систем.

Работа над проектом, с другой стороны, — это то, где можно начать с прекрасного, 
чистого, зелёного поля. В хорошо организованной компании каждый проект вносит 
вклад в преумножение или сбережение денег, поэтому проекты обычно финансируются 
достаточно для выполнения необходимого объёма работ (хотя, и тут опыт может 
варьироваться). Здесь не существует минного поля из старого кода, через 
которое программисты вынуждены пробираться на цыпочках, чтобы правильно 
внедрить новые возможности с наименьшим количеством помех, как при работе с 
существующей системой. В двух словах, обстановка в области проектов обычно куда 
более идеальная.

Если я дам вам $1000 и попрошу принести мне чашечку кофе, то буду весьма разочарован,
если вы вернётесь без $1000 и без кофе. Я расстроюсь даже в том случае, если вы
принесёте мне на выбор несколько чашек действительно прекрасного кофе, но это займёт
у Вас 2 часа. Если я дам вам $0 и попрошу принести мне кофе, то буду крайне признателен,
если вы и вправду вернётесь с ним и пойму, если не вернётесь вообще. Проектная работа
происходит по первому сценарию. Работа по обслуживанию — по второму.

Когда нет ограничений в виде плохого унаследованного кода и отсутствия 
финансирования, с которыми мы должны иметь дело, менеджеры и заказчики вправе 
ожидать от нас большего. К тому же, от проектной работы ожидается развитие бизнеса. 
Если мы не достигнем его, мы провалились. Поскольку наши компании следят за этими 
улучшениями в бизнесе, они часто будут держать в ежовых рукавицах то, что именно, как и когда
создаётся. Внезапно, наша творческая игровая площадка начинает 
казаться военной операцией — каждое наше движение диктуется сверху.

*Обслуживание может быть местом для свободы и творчества.

Однако в режиме обслуживания всё, что от нас требуется — чтобы программное 
обеспечение работало гладко и за как можно меньшие деньги. Никто не ожидает чего-то 
сверхестественного от команды поддержки. Обычно, если всё идет 
хорошо, то заказчики остаются в стороне от ежедневного контроля за людьми, 
занимающимися поддержкой и за их деятельностью. Устранить проблемы, 
реализовать небольшие запросы на новый функционал и поддерживать всё это в рабочем 
состоянии — вот и всё, что вам необходимо делать.

А что, если баг обернётся необходимостью перепроектирования подсистемы приложения? 
Это всё — часть исправления проблемы, правильно? Дизайн может быть древним и 
покрытым плесенью, и по всей системе могут быть разбросаны «разбитые окна»[^10]. 
Зато у вас есть возможность протестировать ваши рефакторинговые изменения. 
Насколько превосходной может быть эта система? Насколько быстрее вы сможете исправить 
или улучшить этот участок в следующий раз благодаря рефакторингу, который делаете 
в данный момент?

До тех пор, пока вы поддерживаете систему работоспособной и своевременно 
отвечающей запросам пользователей, режим поддержки — это место для свободы и 
творчества. Ты руководитель проекта, архитектор, дизайнер, программист 
и тестировщик. Ты можешь применять свои творческие способности, как тебе нравится, 
и все измеримые успехи или провалы системы касаются тебя. 

В процессе поддержки системы вы можете планировать и более заметные улучшения.
Ваша веб-система трёхлетней давности вряд ли поддерживает новые модные "фишки"
пользовательского интерфейса, доступные в современных браузерах. Если вы сможете
заняться этим в промежутках между поддержкой работоспособности системы и 
правкой багов, то можете значительно улучшить уровень пользовательского взаимодействия 
с системой. Добавление нескольких уместных наворотов, которых не ожидали увидеть 
заказчики, сродни тому, как муж удивляет супругу букетом цветов или как ребёнок 
делает приборку в доме, пока родители ушли в магазин. И ещё, без бюрократии полноценного 
процесса разработки проекта, вы будете удивлены тем, как много таких пробелов вы можете
заполнить. Ваши заказчики будут не менее удивлены.

Скрытая привилегия занятия поддержкой — это то, что в отличие от бюрократичной 
среды многих современных проектных команд, обслуживающий программист часто имеет 
возможность непосредственного взаимодействия с заказчиками. Это означает, что больше 
людей будут знать вас в лицо и что у вас будет шанс накопить больше защитников 
в вашем деле. Вы также находитесь в отличном месте для реального изучения 
внутренних бизнес-процессов. Если вы ответственны за бизнес-приложение целиком,
всегда работая с его конечными пользователями сквозь проблемы и вопросы, есть 
вероятность, что даже без особых усилий вы придёте к пониманию того, что реально 
делает приложение, настолько же хорошо, насколько и его бизнес–пользователи. 
Бизнес-правила закодированы в логике приложения, так что пользователи обычно не 
могут их прочесть. Я видел немало ситуаций, когда только разработчики полностью 
понимали, как работает тот или иной бизнес-процесс в компании. Никто другой не может 
напрямую соприкасаться с официальным кодом этой бизнес-логики.

Ирония противостояния между работой над проектом и его сопровождением в том,
что на самом деле работа над проектом и есть его сопровождение. Как только команда, 
работающая над проектом, написала первую строку, каждая следующая функциональность 
будет вживляться в уже имеющуюся кодовую базу. Конечно, код может быть чище, или 
его может быть меньше, чем если бы вы работали над тем, что досталось в наследство, 
но действия те же. Новый функционал и исправление ошибок добавляются к уже имеющейся 
кодовой базе. Кому не знать лучше, как сделать это эффективнее и быстрее, чем тому, 
кто действительно понял сопровождение и посвятил жизнь изучению того, как можно делать 
это хорошо?

##### Действуй!

1. _Измеряйте, улучшайте, снова измеряйте_ — для наиболее критичного приложения
    или кода, который вы обслуживаете, сделайте список _измеряемых_ факторов,
    которые отражают качество приложения. Это может быть время отклика, количество
    необработанных исключений, возникающих в процессе выполнения, время
    непрерывной работы приложения. Или, если вы занимаетесь поддержкой
    непосредственно, не оценивайте непосредственно качество _приложения_.
    Время обработки запроса в техподдержку (насколько быстро вы отвечаете и
    решаете проблемы) является важной частью впечатления пользователей от приложения.
 
    Отберите самые важные характеристики и начните измерять их. После того, как получите 
    достаточное количество исходных данных, установите реалистичную цель и улучшайте 
    поведение вашего приложения (или своё собственное) для соответствия этой цели. 
    После того, как сделали какое-либо усовершенствование, проведите измерения заново, 
    чтобы удостовериться в том, что вы действительно улучшили то, что хотели. Если вы это
    сделали, поделитесь достижением с Вашей командой и заказчиками.

    Отметьте следующую метрику и сделайте это снова. После первого улучшения, каждое 
    последующее покажется Вам развлечением, вы втянетесь в игру. Внесение таких измеряемых
    улучшений становится хорошей привычкой.

[^10]: Больше информации о теории разбитых окон в издании
    [Программист-прагматик](http://pragprog.com/the-pragmatic-programmer) [HT00].