# Altura e Peso

## Tratamento de dados

Inicialmente fora encontrado alguns dados em ambas as tabelas com valores 'NR' então as células correspondentes foram excluidas. Assim como também outliers no caso do peso um peso muito grande, podendo ser interpretado como um erro de digitação e tentar arrumar ou manter como um outlier e o boxplot mostraria normalmente. Mas mantendo como outlier outros gráficos de distribuições ficariam muito distorcidos, então optei pela exclusão desse dado ao invés de assumir um erro de digitação. Além disso, para padronização alguns dados estavam como "1,75" e "1.75" no caso por prática transformei todos os dados com "," para "." utilizando uma linha de código no próprio console do navegador conforme figura seguinte.

<br></br>
<img src="https://github.com/Daniel-Boll/Statistic-work1/blob/master/Images/tratamento_dado.png" alt="Tratamento de dados"/> 
<br></br>
Acabou que optei pela escolha de uma junção em lista para criação futura do box plot, mas poderia novamente juntar para inserir na célula com a modificação do trecho

```js
.join('\n')
```

Pegando o output e colocando no lugar que peguei


## Distribuição peso por altura

Analisando os dados de peso e altura diretamente nos valores absolutos de menos e maiores podemos ver que a diferença do maior para o menor no peso é muito mais perceptível. Quando montado um gráfico de distribuição da altura pelo peso notamos que de fato a distribuição de altura é bem pequena, enquanto com peso a oscilação é o que dá forma para o gráfico.
<br></br>
<img src="https://github.com/Daniel-Boll/Statistic-work1/blob/master/Images/Distribui%C3%A7%C3%A3o%20de%20altura%20por%20peso.svg" alt="Altura pro peso"/> 
<br></br>

## Boxplot
Fazendo agora o boxplot podemos notar o quão bem distribuido os dados da altura está em detrimento do peso.

Box plot - Peso
<br></br>
<img src="https://github.com/Daniel-Boll/Statistic-work1/blob/master/Images/peso_box.png" alt="Box plot peso"/> 
<br></br>

Box plot - Altura
<br></br>
<img src="https://github.com/Daniel-Boll/Statistic-work1/blob/master/Images/altura_box.png" alt="Box plot peso"/> 
<br></br>

## Análise dos dados
A distribuição de altura fica entre a média de fato de altura brasileira conforme [BBC](https://www.bbc.com/portuguese/geral-36892772) e a maior parte do peso segue a média conforme [Gazeta](https://www.semprefamilia.com.br/saude/qual-o-peso-medio-de-homens-e-mulheres-em-diferentes-paises-do-mundo/), contudo contendo alguns valores acima disso indicando possíveis ocorrências de obesidade. 
