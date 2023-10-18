PROBLEMA

Elabore um algoritimo para calcular o salário líquido de 5 pessoas.

Solicite ao Usuário que digite seu nome e o valor de seu salário bruto.

Peça também para o usuário digitar a quantidade de dependentes.

Para cada um dos dependentes deve ser solicitado o ganho mensal, esse valor deve ser adicionado ao salário bruto.

Calcule a renda familiar per capita.

Caso a renda para cada membro da familia seja menor que R$ 500,00 a pessoa ficará isenta de imposto de renda, ou seja, não será calculado dentre as faixas salarias e o seu valor será 0.

Caso a renda para cada membro da familia seja maior ou igual a R$ 500,00 o imposto de renda a ser descontado do salário bruto deve considerar as seguintes regras: 



* Salário bruto (de 0,00 até 1.903,98): 5%
* Salário bruto (de 1.903,99 até 2.826,65): 7.5%
* Salário bruto (a partir de 2.826,66): 15%
* 
Armazene os salários líquidos em uma coleção indexada [array].

Depois calcule a média de todos os salários líquidos.
Posteriormente, mostre a média dos salários líquidos e quantas pessoas estão abaixo desse valor médio.


Refatore seu código. Para isso, crie 2 funções, a saber:

* Função para calcular IR: esta função deve receber como parâmetros o salário bruto e a renda per capta, e, retornar ao final o valor do ir.
* Função para calcular a quantidade de salários liquidos menores que a média: esta função deve receber como parâmetros o array de salários líquidos e a média dos salários líquidos, e retornar a quantidade de salários líquidos menosres que a média.

Versão: 12 -  Funções.
