# Заголовки

# Заголовок H1

## Заголовок H2

### Заголовок H3

#### Заголовок H4

##### Заголовок H5

###### Заголовок H6

Alternative H1
=

Alternative H2
--

текст перед разделителем #

#

текст после разделителя #

# Выделения

###### Курсив (при помощи * или _ )
Lorem *ipsum* dolor sit amet, _consectetur_ adipiscing elit. Morbi vel accumsan odio, quis facilisis nunc. In suscipit elementum sem, vel blandit est lacinia a. Mauris ut viverra sem. Donec vitae rhoncus lectus. Sed eget venenatis lectus. Integer nec enim quis neque tristique imperdiet. Nunc commodo felis quis turpis scelerisque fringilla.

###### Жирный шрифт (при помощи ** или __ )
Lorem **ipsum** dolor sit amet, __consectetur__ adipiscing elit. Morbi vel accumsan odio, quis facilisis nunc. In suscipit elementum sem, vel blandit est lacinia a. Mauris ut viverra sem. Donec vitae rhoncus lectus. Sed eget venenatis lectus. Integer nec enim quis neque tristique imperdiet. Nunc commodo felis quis turpis scelerisque fringilla.

###### Зачеркнутый шрифт (при помощи ~~ )
Lorem ~~ipsum~~ dolor sit amet, **_consectetur_** adipiscing elit. ~~**_Morbi_**~~ vel accumsan odio, quis facilisis nunc. In suscipit elementum sem, vel ~~**blandit**~~ est lacinia a. Mauris ut viverra sem. Donec vitae rhoncus lectus. Sed eget venenatis lectus. Integer nec enim quis neque tristique imperdiet. Nunc commodo felis quis turpis scelerisque fringilla.

# Списки

## Несортированные списки

Несортированный список (* или -):
- Элемент списка 1
- Элемент списка 2
- Элемент списка 3

Сортированный список ( . или ) ):
1. Элемент списка 1
2. Элемент списка 2
    * Элемент 1 вложенного списка
    * Элемент 2 вложенного списка
    * Элемент 3 вложенного списка
3. Элемент списка 3

# Ссылки

[описание ссылки которая дальше внутри круглых скобок](https://job.ozon.ru/vacancy/)

[описание ссылки с подсказкой](https://job.ozon.ru/vacancy/ "это самая крутая подсказка")

![крутая картинка](https://media.istockphoto.com/id/945075532/ru/%D0%B2%D0%B5%D0%BA%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F/%D0%BA%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%BD%D0%B0%D1%8F-%D0%BA%D0%BB%D0%B0%D0%B2%D0%B8%D0%B0%D1%82%D1%83%D1%80%D0%B0.jpg?s=612x612&w=0&k=20&c=GN9-rfOyzu7jdx2HbEwRsHwNws6_qj15SLn6u69Q1cY= "ссылка с картинкой и подсказкой")

# Таблицы

| Name | Surname | Age |
| --- | --- | --- |
| Kazbek | Takaev | 20 |
| Alexander | Pushkin | 174 ? |
| Sergei | Ivanov | 33 |

# Цитаты

> Стремитесь не к успеху, а к ценностям, которые он дает

просто текст

> 1-я строка Цитаты
>
> 2-я строка Цитаты

# Блоки кода

The following is an example of a Pod which consists of a container running the image ``nginx:1.14.2``

```
apiVersion: v1
kind: Pod
metadata:
  name: nginx
spec:
  containers:
  - name: nginx
    image: nginx:1.14.2
    ports:
    - containerPort: 80
```