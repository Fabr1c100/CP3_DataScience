### Desenvolvimento e Entrega do 3º Checkpoint - Data Science e Statistical
 
**Nomes + RM dos integrantes:**
- Guilherme Akio - 98582
- Matheus Motta - 550352
- Fabrício Saavedra - 97631
 
**Turma:** 2ESPW
 
**Ano:** 2024

> Link do repositório: https://github.com/Fabr1c100/CP3_DataScience.git
___
 
### Descrição do Projeto
O projeto Checkpoint 3 de Análise de Dados visa conduzir uma análise detalhada do conjunto de dados "US Accidents (2016-2023)", utilizando técnicas de inteligência artificial e aprendizado de máquina para examinar diversos parâmetros apresentados na base. Ao longo do projeto, serão formuladas 10 questões de pesquisa que orientarão a análise e a interpretação dos dados, permitindo extrair insights significativos e identificar tendências relevantes nos acidentes de trânsito.

### Executando o projeto

Para executar o projeto é necessario baixar o dataset "US Accidents 2021-2023" e acrescentar o caminho do mesmo(caso esteja em uma pasta avulsa) dentro do codigo em "Travamento de base"

> Base: https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

```
df = pd.read_csv('US_Accidents_March23.csv')
```

Após isso basta executar todas as celulas em sequencia

> Etapa necessaria apenas caso queira executar o codigo, as informações ja sao exibidas ao abrir o arquivo

### Conclusões

A análise dos dados sobre acidentes registrados entre 2021 e 2023 revela uma concentração alarmante em estados com alta densidade populacional, sendo a Califórnia a líder absoluta com mais de 600.000 acidentes, representando 22,44% do total nacional. O Texas segue com mais de 400.000 acidentes (7,80%), enquanto Flórida, Nova York e Pensilvânia também apresentam números elevados, embora em menor escala. Essa distribuição destaca a necessidade de um foco renovado em medidas de segurança viária, especialmente em áreas urbanas onde o tráfego é intenso, já que acidentes em cruzamentos, que representam 9,8% do total, e as altas taxas de ocorrências noturnas (31,6%) indicam pontos críticos que requerem intervenção imediata.

Em Los Angeles, a situação é particularmente preocupante, com a cidade registrando mais que o dobro de acidentes em comparação com outras grandes cidades californianas, como Sacramento e San Diego. As rodovias I-10 W e I-10 E são as mais perigosas, com mais de 2.000 acidentes cada, o que ressalta a necessidade de melhorias na infraestrutura viária, sinalização e fiscalização. A prevalência de acidentes de gravidade 2, que constitui a maioria dos registros, e a tendência de aumento nos meses finais do ano, sugere que, embora os acidentes mais graves sejam menos frequentes, quando ocorrem, impactam de maneira significativa o tempo de resolução, especialmente aqueles classificados como gravidade 4, que levam em média 27,24 horas para serem finalizados.

Além das questões de tráfego e infraestrutura, as condições climáticas também desempenham um papel importante na segurança viária. Embora a correlação entre precipitação e visibilidade seja fraca, o aumento de condições climáticas adversas, como "Cloudy" e "Light Rain", coincide com a gravidade dos acidentes, especialmente nos níveis mais altos. A predominância de acidentes durante o dia (68,4%) em comparação com a noite reforça a ideia de que a visibilidade e a infraestrutura adequada são fundamentais para prevenir acidentes. Portanto, é essencial implementar medidas que considerem tanto o comportamento dos motoristas quanto as condições do ambiente para melhorar a segurança nas vias.
