Пример ООП и принципов SOLID
+ Класс : 
Гитара.

+ Обьект: 
 Акустическая гитара. 
 
+ Наследие: 
Басс гитара или электро гитара, от обычной  они унаследовали: форму, струны,гриф, колки, принцип работы.

+ Инкапсуляция: 
Пользователю не обьязательно знать как все устроено в работе гитары(электро). 

+ Полиморфизм: 
Издавать звуки может и гитара и магнитофон. Мы услышим одну и ту же мелодию с разных устройств. Но методы воспроизведения разные.

+ SOLID :

-Принцип единственной ответственности - Главная задача извлечение звука.
 
-Принцип открытости/закрытости - В гитаре можно заменить струны, колки но это не помешает гитаре выполнять свои фунции. 
-Принцип подстановки Барбары Лисков - акоррды , они подходят как для акустической так и для елекро-гитары потому что они подходят как для базового класса так и для его наследователя.
-Принцип разделения интерфейса - у каждой гитары может быть разное строение корпуса для большего удобства, есть гитары с вырезами, есть с тонким или широким грифом, для правши или для левши. Но если их не будет то суть гитары как объекта не поменяется. Можно и на обычной акустике лабать дай боже и без всяких примочек.
-Принцип инверсии зависимостей - нота Ля не зависит от того какая конструкция или строение гитары. Если она нота Ля то она нота Ля. Главное чтобы гитара была правильно настроена.