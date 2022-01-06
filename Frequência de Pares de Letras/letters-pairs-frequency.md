# FREQUENCIA DE PARES DE LETRAS

Escrever um algoritmo que conte o número de ocorrências de todos os pares de letras em determinado texto.
Como saída o algoritmo deve retornar os 100 pares mais frequentes, ordenando pelo percentual do total.
Além disso, o algoritmo deve mostrar o percentual que estes 100 pares representam do total de pares.


### Observações:
-	Espaços em branco não devem ser considerados;
-	Acentos não devem ser considerados;
-	A análise deve ser case insensitive, ou seja, não considerar a diferença entre letras maiúsculas e minúsculas.

### Requisitos:
- Aceitar texto como entrada;
- Desconsiderar espaços em branco;
- Desconsiderar acentos;
- Não diferenciar letras maiúsculas e minúsculas;
- Pode ser utilizada qualquer linguagem;
- Apresentar os 100 pares mais frequentes, ordenados pelo percentual do total;
- Apresentar o percentual dos 100 pares;


### Exemplo:

> “Grêmio campeão da américa”

Total de pares: 17
Pares que repetem:

am	“Grêmio campeão da américa”
ca	“Grêmio campeão da américa”	2	11,76%

| Sílaba | Frase | Qtde | % |
|---|---|---|---|
| am | “Grêmio c**am**peão da **am**érica” | 2 | 11,76% |
| ca | “Grêmio **ca**mpeão da améri**ca**” | 2 | 11,76% |