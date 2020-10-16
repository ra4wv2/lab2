Две новости считаются похожими, если косинусная мера сходства между ними выше заданного порога. Построить граф похожих новостей, в котором вершины представлены новостями, а дуги показывают косинусную меру сходства между ними. Выделить блоки новостей с высокой мерой кластерности.

http://vv-34.ru/

Насчет неприятного html: Сам текст статьи от старницы к странице содержится в разных тегах, то в span, то в p, то в span, который в p, и так далее. Плюс в некоторых местах атрибуты различаются чуть ли не в каждом абзаце, где-то вообще отсутсвтуют. Я сначала подумала, что было бы логично добавить содержание p/span с любыми атрибутами в список, проверяя на повторы, но без атрибутов текст вообще не записывался или записывался через \n. В итоге где-то 10% статей потеряли некоторые абзацы (обычно скорее оставался только первый). Писать все-все теги с разными атрибутами как-то не очень, их слишком много.
С автором иногда была такая же проблема, обычно он был в em, но этот em был и в p, и в span, и так далее, а иногда его вообще не было и автор был в том же теге, что и текст, поэтому он иногда пропадал, а иногда дублировался и в строке с текстом.
Плюс некоторые теги содержали в себе по несколько абзацей и они почему-то не сплитились по \n, в Ноутпаде этот перенос тоже как-то иначе отобрадался, не как обычный, и сдвигал весь абзац... Поэтому сплитить корпус по строкам и брать каждый седьмой элемент не получилось и пришлось брать строки, в которых нет слов типа 'Название источника: ', 'Автор: ' и остальных. 
