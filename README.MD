
### Trabalho Final – Parte 2 - Cristopher Braatz Cardoso e Lucas Amaral

- A ideia desse experimento é utilizar o modelo de Malthus para calcular em quanto tempo a população de Santa Catarina estará vacinada do covid19.
- Foi utilizado uma base de dados diários do covid19 no Brasil, com informações de quantidade de vacinados por dia.
- Com essas informações, foi calculado uma média de vacinados por dia, considerando apenas o último mês de vacinação (Abril/21). Essa média foi utilizada como taxa de vacinação.
- Foram feitas iterações, onde cada iteração representa um dia. Foi calculado quantas pessoas estariam vacinadas naquele dia.
- A cada 30 dias, foi feito uma calibragem de 5% no percentual, considerando que a quantidade de vacinas aplicadas sempre vai aumentando.
- Com isso, foi obtido que em 452 dias, toda população de Santa Catarina estará vacinada.
- Para executar o código, basta abrir o google colab e importar o arquivo `VacinacaoCovidSC.ipynb`
- Para visualizar os resultados do trabalho, basta abrir o arquivo `VacinacaoCovidSC.ipynb` ou o `VacinacaoCovidSC.pdf`
