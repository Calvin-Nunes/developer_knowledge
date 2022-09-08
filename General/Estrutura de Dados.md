# Estrutura de Dados

> Queue (Fila):
* * São estruturas lineares onde os dados são inseridos ao final e removidos do início, por exemplo, uma fila que suporte 5 elementos/nós:
temos uma fila: 
[1,2,3,4, empty]
1 = primeiro da fila
4 = ultimo da fila

adicionamos um valor novo: [1,2,3,4,5]
1 = primeiro da fila
5 = ultimo da fila

ao fazer algum processamento ou realizar alguma ação, remove-se o primeiro da fila: [empty,2,3,4,5]
2 = primeiro da fila
5 = ultimo da fila

* * Note que o primeiro espaço ainda existe, porém está vazio. O computador na verdade marca quem é o primeiro e quem é o último da fila.
Portanto, se um novo valor for inserido agora, ele ocupará a primeira posição, porém será considerado o último da fila:

[6,2,3,4,5]
2 = marcado como primeiro da fila
6 = marcado como último da fila

