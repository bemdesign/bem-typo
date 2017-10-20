# Типографика


Основная часть интерфейса это типографика. Поэтому мы вынесли блок .text с модификаторами на цвет размер, регистр, жирность, межбуквенный интервал, которые можно использовать в различных комбинации. Получается, что манипулируя достаточно небольшим количеством комбинаций мы получаем все необходимые вариации текста.

В интерфейсе типографика встречается двух типов:
- У интерфейсных элементов;
- Самодостаточные текстовые блоки (на текстовых страницах).

В первом случае мы ко всем текстовым элементам примиксовываем блок .text с нужными модификаторами.
Во втором к самостоятельным текстовым блокам добавляем еще один модификатор (_type_..) с учетом семантики, на который прописаны относительные отступы (они высчитываются с учетом типографических правил для удобного восприятия текста).
