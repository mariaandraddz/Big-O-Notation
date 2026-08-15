# Big-O-Notation
<p>Representa o limite superior do custo de um algortimo</p>
<p> A imagem abaixo demostra o funcionamento</p>
<img src="https://media.licdn.com/dms/image/v2/D4E12AQEvsKZNftrL5w/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1734702748422?e=2147483647&v=beta&t=Mp0AfdcOaVE6TQlsFmj-CIw9i9C0hXvAWk61IYqeH9w" width="500">
--------------------

### O(n) 
- Acessa n vezes
  
Ex.: Em uma lista, que há n itens esses n itens são acessados

| Input Size | Cost |
| --- | --- |
| 1 | 1 |
| 100 | 100 |
| 1000 | 1000 |
| 10000 | 10000 |

O custo vai crescendo conforme o tamanho da entrada vai crescendo também, em alguns casos que você tem noção do tamanho da sua entrada não seja interessante utilizar.

-----------------------------------
### O(1)

| Input Size | Cost |
| --- | --- |
| 1 | 1 |
| 100 | 1 |
| 1000 | 1|
| 10000 | 1 |

O custo é o mesmo independemente do tamanho do input

----------------------------
### O(n²)

| Input Size | Cost |
| --- | --- |
| 1 | 1 |
| 10 | 100 |
| 1000 | 1000000 |
| 10000 | 100000000 |

---------------------------------
O(log n)

| Input Size | Cost |
| --- | --- |
| 1 | 1 |
| 10 | 1 |
| 1000 | 3 |
| 1000000 | 6 |
