\page 112, "ЧАСТЬ 1 : КЛАССЫ"
## Волшебник
\class wizard
Одетая в серебряные одежды, обозначающие её статус, эльфийка закрывает глаза, приглушает в своём сознании суматоху боя и начинает свой тихий напев. Движениями рук она сплетает перед собой заклинание и запускает крошечный шарик огня во вражеские ряды, где он взрывается потоками пламени, которые охватывают солдат.

Проверив и перепроверив свои наброски, человек рисует затейливый магический круг мелом на голом каменном полу, затем посыпает железным порошком все линии и изящные кривые. Когда круг готов, он начинает монотонно читать длинное заклинание. Внутри круга появляется проход, из которого тянет запахом серы из потустороннего мира.

Припав к полу на перекрёстке в подземелье, гном бросает небольшие костяшки с мистическими символами, бормоча над ними слова силы. Закрыв глаза, чтобы прочитать видения более чётко, он медленно кивает, затем открывает глаза и указывает на проход слева от себя.

Волшебники — адепты высшей маги, объединяющиеся по типу своих заклинаний. Опираясь на тонкие плетения магии, пронизывающей вселенную, волшебники способны создавать заклинания взрывного огня, искрящихся молний, тонкого обмана и грубого контроля над сознанием. Их магия вызывает чудовищ с других планов бытия, предсказывает будущее и обращает поверженных врагов в зомби. Их самые могущественные заклинания могут превращать одно вещество в другое, вызывать метеориты с небес и открывать порталы в другие миры.

### Адепты магии
Дикая и загадочная, разнообразная по форме и функциям, магия привлекает учеников, которые стремятся достичь мастерства в её тайнах. Некоторые хотят уподобиться богам, изменять саму реальность. И хотя для сотворения обычного заклинания требуется лишь произношение нескольких странных слов, совершение пары мимолётных жестов, а иногда щепотка или комок экзотических материалов, эти поверхностные проявления не могут показать опыт, достигнутый долгими часами ученичества и бессчётными часами исследований. Волшебники живут и умирают со своими заклинаниями.

Всё остальное вторично. Они учат новые заклинания, экспериментируя и становясь опытнее. Они также могут узнать их от других волшебников, из древних томов или свитков, и от древних существ (таких как феи), которые погружены в магию.

### Соблазн знаний
Жизнь волшебников редко бывает обыденной. Наиболее близки к простой жизни, вероятно, те из волшебников, которые работают знатоками или лекторами в библиотеке университета, обучая других секретам мультивселенной. Другие волшебники предлагают свои услуги в качестве прорицателей, служат в вооружённых силах, или проводят жизнь в преступлениях и стремлении к власти.

Но соблазн знаний и силы зовёт даже самых обделённых смелостью волшебников из безопасности их библиотек и лабораторий в разрушенные руины и потерянные города. Большинство волшебников считает, что их коллеги из древних цивилизаций знали секреты магии, которые были потеряны навек, и открывшие эти секреты смогут владеть силами, недоступными в нынешнем веке.

\page 113, "ЧАСТЬ 1 : КЛАССЫ"
### Создание волшебника
При создании персонажа волшебника в его истории обязательно должно быть некое выдающееся событие. Как ваш персонаж впервые встретился с магией? Как он открыл свою предрасположенность к ней? Владелец ли он природного таланта или же достиг всего усердной учёбой и постоянной практикой? Или же произошла неожиданная встреча с магическим существом или древней книгой, что могли обучить его основам магического искусства?

Что привлекло вас к жизни в обучении? Сподвиг ли вас на большее вкус первого обретённого магического знания? Постигли ли вы слова тайного хранилища знаний, ещё не разграбленного другими волшебниками? Возможно, вы просто желаете противопоставить обретённые магические навыки опасностям для проверки своих сил.

#### Быстрое создание
Вы можете быстро создать волшебника, следуя этим рекомендациям. Во-первых, у вашего Интеллекта должно быть наивысшее значение. Следующим по величине должно быть значение Телосложения или Ловкости. Если вы планируете присоединиться к школе Очарования, сделайте вторым по величине значение Харизмы. Во-вторых, выберите предысторию «мудрец». В-третьих, выберите заговоры волшебная рука, луч холода и свет, а также заклинания 1 уровня для вашей книги за клинаний: волшебная стрела, доспехи мага, огненные ладони, очарование личности, падение пёрышком и усыпление.

### Классовые умения
Волшебники обладают следующими классовыми умениями.

\spells.ability int
\spells.levels full
\spells.cantrips 3, [4, 10]
\spells.prepared lvl => lvl + int
\spells.known lvl => 4 + 2 * lvl

### Хиты
\hitdice 1d6

### Владение
\proficient.armor
\proficient.weapon dagger, dart, sling, quarterstaff, light_crossbow
\proficient.saves int, wis
\proficient.skill {choose: {count:2, from: [investigation, history, arcana, medicine, insight, religion]}}

### Снаряжение
Вы начинаете со следующим снаряжением в дополнение к снаряжению, полученному за вашу предысторию:
\equipment {a: [{item: quarterstaff}], b: [{item: dagger}]}
\equipment {a: [{item: component_pouch}], b: [{item: arcane_focus}]}
\equipment {a: [packs.scholar], b: [packs.explorer]}
\equipment {_: [{item: spellbook}]}
• а) боевой посох или б) кинжал
• а) мешочек с компонентами или б) магическая фокусировка
• а) набор учёного или б) набор путешественника
• Книга заклинаний

### Использование заклинаний
\feature 1
Являясь учеником тайной магии, вы обладаете книгой, содержащей заклинания, показывающие первые проблески вашей истинной силы. Общие правила по использованию заклинаний смотрите в главе 10, а в главе 11 вы найдёте список заклинаний, доступных волшебнику.

\page 114, "ЧАСТЬ 1 : КЛАССЫ"
#### Заговоры
На 1 уровне вы знаете три заговора на ваш выбор из списка заклинаний волшебника. Вы узнаёте дополнительные заговоры волшебника на более высоких уровнях, как показано в колонке «известные заговоры».

#### Книга заклинаний
На 1 уровне у вас есть книга заклинаний, содержащая шесть заклинаний волшебника 1 уровня по вашему выбору. Заговоры в ней не хранятся.

> #### Ваша книга заклинаний
> Заклинания, которые вы добавляете в свою книгу заклинаний, получая уровни, отражают исследования, которые вы проводите, а также интеллектуальные прорывы в изучении природы вселенной, сделанные вами. Вы также можете найти другие заклинания во время прик лючений. Вы можете обнаружить заклинание, записанное на свитке в сундуке злого волшебника, или, например, в пыльном фолианте в древней библиотеке.
> 
> ##### Копирование заклинания в книгу
> Если вы находите заклинание волшебника 1 или более высокого уровня, вы можете добавить его в свою книгу заклинаний, если оно имеет такой уровень, заклинания которого вы можете подготавливать, и у вас имеется свободное время для его расшифровки и копирования.
> 
> Копирование заклинания в вашу книгу включает воспроизведение основной формы заклинания, а также расшифровку уникальной системы обозначений, используемой волшебником, который записал его. Вы должны подобрать нужные жесты и звуки, после чего записываете его в свою книгу заклинаний, используя собственные обозначения.
> 
> За каждый уровень заклинания процесс занимает 2 часа и стоит 50 золотых монет. Стоимость представляет собой материальные компоненты, которые вы расходуете на эксперименты с заклинанием, чтобы им овладеть, а также высококачественные чернила для записи текста. После того как вы потратили время и деньги, вы можете подготавливать это заклинание как и свои прочие заклинания.
> 
> ##### Замена книги
> Вы можете копировать заклинание из своей книги заклинаний в другую, например, если хотите сделать запасную копию. Это делается так же как и простое копирование заклинаний, но быстрее и проще, так как вы понимаете свои собственные обозначения и уже знаете, как творить это заклинание. Вам необходимо потратить только по 10 золотых монет и 1 часу для каждого уровня копируемого заклинания.
> 
> Если вы потеряли свою книгу заклинаний, вы можете использовать ту же процедуру для записи заклинаний, которые у вас подготовлены, в новую книгу заклинаний. Для заполнения оставшейся части книги заклинаний потребует найти новые заклинания, чтобы вернуть всё как прежде. По этой причине многие волшебники держат запасные книги заклинаний в безопасном месте.
> 
> Внешний вид книги. Ваша книга заклинаний является уникальным сборником заклинаний, со своими декоративными завитушками и ремаркам. Это может быть обычная, обтянутая кожей книга, которую вы получили в подарок от наставника, или оплетённый золотом том, который вы нашли в древней библиотеке, или даже разрозненная коллекция записей, собранная вместе после потери предыдущей книги заклинаний в результате несчастного случая.

#### Подготовка и сотворение заклинаний
Таблица «Волшебник» показывает, какое количе ство ячеек для сотворения заклинаний у вас есть на первом и более высоких уровнях. Для сотворения одного из этих заклинаний вы должны потратить ячейку заклинаний того же уровня или выше, что и само заклинание. Вы восстановите все потраченные ячейки, когда завершите продолжительный отдых.

Вы подготавливаете список заклинаний волшебника, доступных для сотворения. При этом вы выбираете число заклинаний волшебника из своей книги заклинаний, равное модификатору Интеллекта + уровень волшебника (минимум одно заклинание). Уровень заклинаний не должен превышать уровень самой высокой имеющейся у вас ячейки заклинаний.

Например, если вы волшебник 3 уровня, то у вас есть четыре ячейки заклинаний 1 уровня и две ячейки 2 уровня. При Интеллекте 16 ваш список подготовленных заклинаний может включать в себя шесть заклинаний 1 или 2 уровня, в любой комбинации, выбранных из вашей книги заклинаний. Если вы подготовили заклинание 1 уровня волшебная стрела, вы можете сотворить его, используя ячейку 1 уровня или ячейку 2 уровня. Сотворение заклинания не удаляет его из списка подготовленных заклинаний.

Вы можете изменить список подготовленных заклинаний, когда завершаете продолжительный отдых. Подготовка нового списка заклинаний волшебника требует времени, проведённого в изучении книги заклинаний и запоминания слов и жестов, которые вы должны совершить, чтобы сотворить заклинание: не менее 1 минуты за уровень заклинания для каждого заклинания в вашем списке.

#### Базовая характеристика заклинаний
При создании заклинаний волшебник использует Интеллект, так как вы узнаёте свои заклинания специальными исследованиями и запоминанием. Вы используете Интеллект в случаях, когда заклинание ссылается на базовую характеристику. Кроме того, вы используете модификатор Интеллекта при определении Сл спасбросков от ваших заклинаний волшебника, и при броске атаки заклинаниями.

Сл спасброска = 8 + бонус мастерства + модификатор Интеллекта

Модификатор броска атаки = бонус мастерства + модификатор Интеллекта

#### Ритуальное колдовство
Вы можете сотворить заклинание волшебника как ритуал, если у этого заклинания есть ключевое слово «ритуал», и оно есть в вашей книге заклинаний. Вам не нужно иметь это заклинание подготовленным.

#### Фокусировка заклинания
Вы можете использовать магическую фокусировку (смотрите в главе 5) в качестве заклинательной фокусировки для заклинаний волшебника.

#### Известные заклинания первого и более высоких уровней
Каждый раз, когда вы получаете уровень волшебника, вы можете добавить два заклинания волшебника по вашему выбору в книгу заклинаний. Уровень этих заклинаний не должен превышать уровень самой высокой имеющейся у вас ячейки заклинаний. Во время приключений вы можете найти другие заклинания, которые сможете добавить в книгу заклинаний (смотрите врезку «Ваша книга заклинаний»).

\page 115, "ЧАСТЬ 1 : КЛАССЫ"
### Магическое восстановление
\feature 1
Вы знаете как восстанавливать часть магической энергии, изучая книгу заклинаний. Один раз в день, когда вы заканчиваете короткий отдых, вы можете восстановить часть использованных ячеек заклинаний. Ячейки заклинаний могут иметь суммарный уровень, который не превышает половину уровня вашего волшебника (округляя в большую сторону), и ни одна из ячеек не может быть шестого уровня или выше.
Например, если вы волшебник 4 уровня, вы можете восстановить ячейки заклинаний с суммой уровней не больше двух. Вы можете восстановить одну ячейку заклинаний 2 уровня, или две ячейки заклинаний 1 уровня.

### Магические традиции
\feature 2
Когда вы достигаете 2 уровня, вы выбираете магическую традицию, формирующую вашу магическую практику посредством одной из восьми школ: Воплощения, Вызова, Иллюзии, Некромантии, Ограждения, Очарования, Преобразования или Прорицания. Подробнее о школах можно прочесть в конце описания класса.

Ваш выбор даёт вам умения на 2, 6, 10 и 14 уровнях.

### Увеличение характеристик
\generic.feature.asi 4, 8, 12, 16, 19

### Мастерство заклинателя
\feature 18
На 18 уровне вы достигаете такого мастерства в отношении некоторых заклинаний, что можете творить их неограниченное количество раз. Выберите одно заклинание волшебника 1 уровня и одно заклинание волшебника 2 уровня, которые есть в вашей книге заклинаний. Вы можете использовать эти заклинания без увеличения их уровня, не тратя ячеек заклинаний, при условии, что вы их подготовили. Если вы хотите увеличить уровень этих заклинаний, вы должны потратить ячейку заклинаний как обычно.

Потратив 8 часов на обучение, вы можете изменить одно или оба этих заклинания по своему усмотрению на заклинания тех же уровней.

### Фирменное заклинание
\feature 20
Когда вы достигаете 20 уровня, вы получаете власть над двумя мощными заклинаниями и можете творить их без усилий. Выберите два заклинания волшебника 3 уровня из своей книги заклинаний в качестве фирменных заклинаний. Для вас эти заклинания всегда считаются подготовленными, они не учитываются в количестве подготовленных заклинаний, и вы можете сотворить каждое из этих заклинаний 3 уровня, не тратя ячейку заклинаний. Когда вы так поступаете, вы не можете сотворить их повторно таким же образом, пока не завершите короткий или продолжительный отдых.

Если вы хотите сотворить заклинание более высокого уровня, вы должны потратить ячейку заклинаний как обычно.

### Магические традиции
Изучение волшебства старо настолько, что простирает корни к самым ранним открытиям магии смертных. Магия опирается на различные традиции, посвящённые её комплексному изучению.

Наиболее распространённые магические традиции в мультивселенной вращаются вокруг школ магии. Волшебники на протяжении веков каталогизировали тысячи заклинаний, группируя их по восьми так называемым школам, как описано в главе 10. В некоторых местах эти традиции в буквальном смысле являются школами; один волшебник может пройти обучение в школе Иллюзии, а другой будет обучаться в городе со школой Очарования. В других учреждениях школы больше похожи на факультеты, соперничающие за студентов и финансирование. Даже волшебники-одиночки, которые учат в своих башнях, используют разделение магии по школам в учебном процессе, так как заклинания каждой школы требуют различного рода мастерства и методов.

\file wizard/Abjuration.md
\file wizard/Conjuration.md
\file wizard/Divination.md
\file wizard/Enchantment.md
\file wizard/Evocation.md
\file wizard/Illusion.md
\file wizard/Necromancy.md
\file wizard/Transmutation.md
