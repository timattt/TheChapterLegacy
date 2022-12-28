# Локации

## Летающий остров

Первая игровая локация происходит на летающем острове.
Его нужно полностью смоделировать.
Ориентировочно это должно выглядеть вот [так](https://github.com/timattt/Project-LWJGL-gamedev/blob/master/GDD/island1.obj) - это моделька с наброском острова.
У нас игра клеточная, нужно чтобы клетки были четко видны, как в [legacy](https://github.com/timattt/Project-LWJGL-gamedev/raw/master/imgs/Terrain_example1.png)
Нужно расставить по карте деревья. Нарисовать дорогу от края карты и до центра - там должно быть поселение. Туда надо поставить строения из наших ассетов. Обязательно 
надо добавить реки и водопады.   
   

Выглядеть это все должно как-то так:

![image](https://user-images.githubusercontent.com/25401699/208677583-3cf207f0-7602-45d3-89de-81088bc60c42.png)

![image](https://user-images.githubusercontent.com/25401699/208676418-c74f9e0e-887b-4d49-8662-bac78b89cadd.png)

![image](https://user-images.githubusercontent.com/25401699/206702764-ec6ca67c-63cd-4534-b598-243d8cceb6b4.png)

![image](https://user-images.githubusercontent.com/25401699/206702810-d9d90796-b421-4eec-a3a8-232f46e0dd94.png)

![image](https://user-images.githubusercontent.com/25401699/206702890-5cf7a9ee-e4ff-4727-bc05-6f5844678ff6.png)

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

![image](https://user-images.githubusercontent.com/25401699/209852954-1b76ed67-d5ce-465f-98ab-a5dd7d6c0d75.png)
