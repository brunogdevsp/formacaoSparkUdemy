Requisitos do problema do curso spark - by Profº Fernando Amaral (Udemy) Cap 3


Resolva com dataframes, faça joins se necessario.
Utilizando os arquivos de dowload na pasta atividades com os arquivos: Clientes, ItensVendas, Produtos, Vendas, Vendedores:

1. Crie uma consulta que mostre nesta ordem, Nome, Estados e Status dos clientes

+--------------------+------+--------+
|             Cliente|Estado|  Status|
+--------------------+------+--------+
|Adelina Buenaventura|    RJ|  Silver|
|        Adelino Gago|    RJ|  Silver|
|     Adolfo Patrício|    PE|  Silver|
|    Adriana Guedelha|    RO|Platinum|
|       Adélio Lisboa|    SE|  Silver|
|       Adérito Bahía|    MA|  Silver|
|       Aida Dorneles|    RN|  Silver|
|   Alarico Quinterno|    AC|  Silver|
|    Alberto Cezimbra|    AM|  Silver|
|    Alberto Monsanto|    RN|    Gold|
+--------------------+------+--------+

2. Crie uma consulta que mostre apenas os clientes do status platinum e gold

+-------------------+--------+
|            Cliente|  Status|
+-------------------+--------+
|   Alberto Monsanto|    Gold|
|      Anna Carvajal|    Gold|
|      Bento Quintão|    Gold|
|      Carminda Dias|    Gold|
|      Cláudio Jorge|    Gold|
|    Dionísio Saltão|    Gold|
|   Firmino Meireles|    Gold|
|Honorina Villaverde|    Gold|
|  Iracema Rodríguez|    Gold|
|   Adriana Guedelha|Platinum|
|      Flor Vilanova|Platinum|
|    Ibijara Botelho|Platinum|
|         Joana Ataí|Platinum|
+-------------------+--------+

4. Demonstre quanto cada status de clientes representa em vendas

Status       Total por categoria

Platinum          9467.31
  Silver        2673780.0
    Gold         21479.62



