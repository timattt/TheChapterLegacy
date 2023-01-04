## Поселения

### Схема дорог и городов

![image](https://user-images.githubusercontent.com/25401699/209849313-85922c66-7129-44c2-8c4a-e04f34906f5b.png)

### Правила расположения дорог

Каждая игровая клетка либо содержит дорогу - либо нет. Поэтому, стык двух дорожных клеток должен происходить по центру ребра между клетками. Не должно быть такого,
чтобы дорога сливалась с пересечением клеток.

![image](https://user-images.githubusercontent.com/25401699/209850773-30e957db-fcef-4686-b6d7-40e0b22482c0.png)

### Структура городов

Город - это многоклеточная структура.
По краям идут стены.

**Пример из Humankind**
(только у нас не гексы, а четырехугольники)

![image](https://user-images.githubusercontent.com/25401699/209850968-0273d1cf-050e-4cf7-b477-75f2ddd6635e.png)

### Прямоугольные стены

Тут все просто - стена идет вдоль границы города.

Фактически нужны следующие сегменты стены:
прямая стена, башня, ворота - это все можно стыковать друг с другом.

![image](https://user-images.githubusercontent.com/25401699/209852280-5bcba21d-f611-45df-9635-4d8a2e26bbea.png)

Тут на схеме соответственно обозначены: точками - башни, двумя полосами - ворота, зеленым - граница города, синим - сама стена.

Примеры из других игр:

![image](https://user-images.githubusercontent.com/25401699/209852562-19d31c58-f930-4bcc-8b26-270196c6c9f0.png)

![image](https://user-images.githubusercontent.com/25401699/209852660-d57639a8-f2fc-47e4-8252-336c6a24c9dd.png)

**Но ориентироваться надо вот на это:**
(Тульский кремль)

![image](https://user-images.githubusercontent.com/25401699/209852954-1b76ed67-d5ce-465f-98ab-a5dd7d6c0d75.png)

![image](https://user-images.githubusercontent.com/25401699/209853050-1321a985-628a-468f-9a7d-c1a2abc31594.png)

### Дома внутри города

Нам нужно три вида домов.
Стиль: русская архитектура 17 века.

![image](https://user-images.githubusercontent.com/25401699/209853363-71e3b1fb-5ce9-421c-a946-45915727b803.png)

![image](https://user-images.githubusercontent.com/25401699/209853450-f2c3fbf0-bc1c-4a27-bbad-3d8f95a091e4.png)

Дома нужно рандомно расмещать внутри крепостных стен.

**Дворец**

В центре города должно быть главное здание.

![image](https://user-images.githubusercontent.com/25401699/209854349-add8b769-6205-4cff-ab87-6b3845a86544.png)

### Дороги внутри города

Внутри города должна быть тоже дорога - продолжение дороги из вне через ворота.

**Возможная схема города такая:**

![image](https://user-images.githubusercontent.com/25401699/209854682-b26ca59f-b9d3-4411-94d5-123f3a39f849.png)

## TODO

- [ ] Сегмент стены: прямая линия
- [ ] Сегмент стены: башня
- [ ] Сегмент стены: ворота
- [ ] Дворец
- [ ] Дом 1
- [ ] Дом 2
- [ ] Дом 3