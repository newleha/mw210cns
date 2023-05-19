# mw210cns
SNC based on mw 210

3-х осевой токарный ЧПУ, на на основе станка MW210 с мощным асинхронным двигателем 1100вт, с электронным управлением оборотами, на основе 3D печатных компонентов. Разрабатывался для себя на основе качественных компонентов cloudray (шаговых двигателей замкнутым контуром обратной связи 3nm и драйверов для них). С нуля такой станок разработать довольно сложно, так как нужно не только проектирование, но и тестирование 3D печатных деталей и доработка их. Вам это не придется делать.

За основу взята длинная версия станка MW210 с рабочим полем 800 мм. Максимальный диаметр обрабатываемой заготовки 130мм, длинна обрабатываемой заготовки 600 мм
Все оси подключены и работают. Так-же проведена интеграция контроллера с датчиком угла поворота и штатным частотным преобразователем, который управляет шпинделем. Управление шпинделем и всеми другими двигателями происходит из контроллера ЧПУ. В станке есть система подачи сож с баком, и 2мя независимыми соплами, так-же на станок установлен быстросьемный фиксатор инструмента NUMOBAMS 45, с 4-мя съемными держателями.

Управляет станком 6 осевой контроллер токарного станка - XC809T с панелью дополнительных кнопок и платой расширения для подключения периферии. В конструкции станка использованы 5 шаговых двигателей, 3 из которых управляет осями станка, а 2 двигателя управляют перемещением и фиксацией заднего центра для пошагового сверления длинных отверстий, теоретическая глубина сверления примерно 250-300мм.

Рама станка выполнена из станочного алюминиевого профиля, 40x80 на раму установлена гранитная плита 30x350x1300мм, на которую и прикручен станок, это снижает вибрации и увеличивает жесткость рамы станка.
Все элементы управления. установлены на раму станка. В составе есть блоки питания шаговых двигателей 24 вольта 15 ампер.Все элементы управления в месте с частотным преобразователем установлены в электричеком шкафу.
