#Глава 2. Марк

Привет, дневник. Ещё один сомнительный день в школе закончен и вот, с сумкой через плечо и аудиолекциями в наушниках, я, Марк Ольшевский, один из миллиона-с-хвостом жителей нашего города, возвращаюсь домой из средних веков в уютное будущее. Без ховерборда и хайперлупа, конечно, зато во вполне уютном автобусе с wifi. 

Я стараюсь ходить в школку раз-два в неделю сдавать обязательные работы, не чаше. Моя школа в глубоком маразме и явно не поможет мне поступить в MIT или Коламбию, лекции там скучнее скучного да и преподаватели по большей части унылые стареющие лузеры, исключение – преподаватель по Технологии Федор Валерьевич – отставной военный интегратор с военного завода в отставке. Не удивлюсь если к него импланты в голове еще советского производства. 

Крутой мужик лет 70, наверно, бодрый, шарящий но, основы технологии не делают погоды - потолок выпускников - это отставший на 15 лет технологический факультет какого нибудь столичного вуза из с 10 по 25 место, по крайней мере так говорит статистика. 

И это в то время когда я вполне мог бы делать проекты для нейроинтерфейсов, vr, беспилотников и микрохирургии. 

Мы с нашей группировкой - Крис , Норм, Эл и я как раз думали что делать и как поступить куда нибудь в крутое место, когда я наткнулся в чатике на стартап в Швейцарии, который помогает составить индивидуальные программы для талантливых абитуриентов, которые учатся в "неудовлетворительных условиях". О, неудовлетвориетльные - это же прямо про меня.

Интервью, оценки  способностей, слабых мест, ритмов, еженедельный план, адаптивное обучение, советы в реализацией и трекинг времени. Воу-воу. Наконец-то. Правда стоил план участия около $1000 за три месяца и это без ментора, так что моих сбережений хватило бы на месяц от силы. 

Однако, способ нашелся. Как раз примерно в этом рвемя мы пересеклись с дядей – а он продакт с массой знакомых, так что он поднял какие-то связи, отправил пару писем и прислал мне промокод. Теперь у меня подписка на год, недельный план и специальная штука для перетаскивания кусочков плана на каждый день. 

Сперва я потратил неделю на заполнение анкет и решение задач, выбрал самый простой факультет MIT с грантовой программой и мне показали всю глубину моей несостоятельности. Оу. Оу еще раз.

Система предложила потратить 1775 часов на доработку выступительных знаний и навыкоы, реализовать 2-3 собственных технологических проекта. Особенно не впечатлили её эссе на английском так что мне накинули полсотни тематических эссе по математическим личностным моделям  в психологии, гендерным вопросам ИИ, влиянии научной фантастики на изобретательность и влиянии силы воли на эффективность программирования. Каждое такое эссе при полном незнании предметной области занимает часов 10. 

Нереальный объем работы. Хотя, почему бы и не попробовать?

У меня есть в запасе полгода, я могу превратить их в полтора - зачислиться в любую вышку - физика, алгоритмы и алгебра везде одинаковые. И я начал потихоньку выполнять задания.

Моя ежедневная программа подготовки включает в себя тесты, чтение и видео, работу с задачами  и эссе.
Все выглядит круто и работает удобно – сейчас,спустя 2 месяца, я поймал ритм и начинаю чувствовать что у меня все получится. 

Группировка тоже вдохновилась и учится со мной вместе, особенно вдохновилась Эл. Программы личной у них нет, конечно, но они перестроили свой ритм6 начали писать эссешки и придумывают задачи сами. Иногда мы идём в барчик и 2-3 часа сидим перекидываясь парой слов за час, пишем тексты и читаем статьи.

Тем временем я почти дома. И вот я думаю: интересно, вся команда нашего богоугодного школьного заведения понимает степень своей безнадежности и отсталости?

Вчера Эл скинула мне статью про то как Компьютеры изменят обучения. Статье 30 лет уже, но никаких улучшений в нашей например школке ... В общем, эти дурни все ещё выходят на кафедру как будто они расскажут что то новое, что полезное а мы запомним что то из этого унылого радио. 

все у кого есть голова уже давно верят только в практику и проработку материал. 

Практика. Кстати, о ней. 


##Задание

1. Нарисуйте недельный интерфейс для Марка с прогрессом выполненных заданий и их оценкой в часах. 

Предметы: технология, философия науки, программирование, социальная психология, высшая алгебра, история Интернета 

2. Нарисуйте интерфейс ежедневного списка дел. Укажите время которое понадобится, оценку за каждое задание, покажите как задания отмечаются выполненными. 

Важно! Не создавайте навигационные решения – мы займемся этим позже.


##Дополнительные задания

3. Спроектируйте интерфейс распределения задний по дням недели. Неделя начинается всегда с понедельника.
Покажите, как система реагирует на заполнения больше, чем 8 часов в день учебными задачами.


##Объектная модель задания

- название
- тип (прочитать / тест / эссе )
- инструкция
- запланировано на день
- процент выполнения
- оценка ( для выполненных )

####Состояния

выполнено
выполняется
на проверке

##Объектная модель недели

- номер недели
- с
- по
- всего часов
- часов потрачено
- % выполнения заданий

####Состояния

опережение
норма
отставание






