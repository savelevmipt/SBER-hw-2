Создадим базу данных и заполным ее отзывами о различном программном обеспечении:

<img width="627" alt="image" src="https://user-images.githubusercontent.com/100207961/229271132-4643d03b-4c12-46ba-b0ff-a59ecd04780b.png">

<img width="1280" alt="image" src="https://user-images.githubusercontent.com/100207961/229271170-56db20b2-dbc0-4364-9c85-4054156c50a9.png">

<img width="992" alt="image" src="https://user-images.githubusercontent.com/100207961/229273137-d43cb1d2-1b77-41b7-afae-8189d86be7f0.png">


Выполним операцию поиска

<img width="542" alt="image" src="https://user-images.githubusercontent.com/100207961/229275553-336ea6ba-486a-4e5e-87a8-e50be78dcc1b.png">

Время выполения 101 мс:

<img width="959" alt="image" src="https://user-images.githubusercontent.com/100207961/229275593-3e80b4b0-c315-4810-8788-13a9db79fab4.png">

Операция вставки:

<img width="1277" alt="image" src="https://user-images.githubusercontent.com/100207961/229275911-31c510e9-84c4-4fe9-bc2e-2505ffb8ea65.png">

Время выполнения 2 мс:

<img width="1279" alt="image" src="https://user-images.githubusercontent.com/100207961/229275897-378cbc15-a036-4670-a05c-263a10f1f512.png">

Удаление: 

<img width="714" alt="image" src="https://user-images.githubusercontent.com/100207961/229276150-1a4835e1-b8b1-43c1-984e-209739ef4e80.png">

Время: 3 мс

<img width="823" alt="image" src="https://user-images.githubusercontent.com/100207961/229276182-0454ba96-7f65-423d-95ac-a390c5904f7a.png">

Обновление:  

<img width="772" alt="image" src="https://user-images.githubusercontent.com/100207961/229276501-b492064b-eab1-40ec-9fc6-044dd0a2bf26.png">

Время 254 мс

<img width="806" alt="image" src="https://user-images.githubusercontent.com/100207961/229276511-4038f9b4-feb0-4c66-8125-0acd54ef17ee.png">

**Теперь создадим индекс**

<img width="364" alt="image" src="https://user-images.githubusercontent.com/100207961/229276908-a66f910e-13c4-4044-93e1-53dc7fd1e9e3.png">

Запрос поиска 

<img width="1272" alt="image" src="https://user-images.githubusercontent.com/100207961/229277000-6f1e54b8-4f7c-42a0-bc0c-53cb28ada567.png">

Время выполнения запроса поиска сократилось с 101 до 14 мс - на целый порядок!

<img width="818" alt="image" src="https://user-images.githubusercontent.com/100207961/229277062-0dcbf813-62c0-4764-9174-0b6f616235ed.png">

Вставка:

<img width="1280" alt="image" src="https://user-images.githubusercontent.com/100207961/229277184-a2063e4d-ba50-432a-acf9-28773c3742c6.png">

Время вставки не изменилось: 

<img width="1280" alt="image" src="https://user-images.githubusercontent.com/100207961/229277232-13275c74-2140-4e33-b568-2d5fe848a121.png">

Удаление:

<img width="683" alt="image" src="https://user-images.githubusercontent.com/100207961/229277285-137f534c-deaa-4652-ad7e-1da6ed279f9b.png">

Время удаления даже уменьшилось!

<img width="806" alt="image" src="https://user-images.githubusercontent.com/100207961/229277331-13c3e49b-fc7a-4da3-baf0-dcb72ff49f9d.png">

Обновление: 

<img width="760" alt="image" src="https://user-images.githubusercontent.com/100207961/229277362-6079a3c8-d070-4bc8-bdd4-c40574bdcc12.png">

Время обновления уменьшилось на целых два порядка: c 254 до 2 мс

<img width="828" alt="image" src="https://user-images.githubusercontent.com/100207961/229277450-8182b7a9-7eb4-47ec-a201-93fc27639e1d.png">
