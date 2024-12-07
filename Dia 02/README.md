# --- Dia 2: Relatórios de Nariz Vermelho ---

Felizmente, o primeiro local que os historiadores querem procurar não fica longe do escritório do historiador-chefe.

Embora a [usina de fusão/fissão nuclear da Rena do Nariz Vermelho](https://adventofcode.com/2015/day/19) não aparenta conter nenhum sinal do historiador-chefe, os engenheiros de lá correm para você assim que o vêem. Aparentemente, eles **ainda** falam da vez em que Rudolph foi salvo através da síntese molecular de um único elétron.

Eles logo acrescentam que, como você já está aqui, gostariam muito da sua ajuda para analisar alguns dados incomuns do reator Nariz Vermelho. Você se vira para verificar se os historiadores estão esperando por você, mas eles parecem já ter se dividido em grupos que estão vasculhando todos os cantos da instalação. Você se oferece para ajudar com os dados incomuns.

Os dados incomuns (sua entrada no quebra-cabeça) consistem em vários **relatórios**, um relatório por linha. Cada relatório é uma lista de números chamados **níveis**, separados por espaços. Por exemplo:

<table>
  <tr><td>7 6 4 2 1</td></tr>
  <tr><td>1 2 7 8 9</td></tr>
  <tr><td>9 7 6 2 1</td></tr>
  <tr><td>1 3 2 4 5</td></tr>
  <tr><td>8 6 4 4 1</td></tr>
  <tr><td>1 3 6 7 9</td></tr>
</table>

Os dados deste exemplo contêm seis relatórios, cada um com cinco níveis.

Os engenheiros estão tentando descobrir quais relatórios são seguros. Os sistemas de segurança do reator Nariz Vermelho só podem tolerar níveis que estejam aumentando ou diminuindo gradualmente. Portanto, um relatório só é considerado seguro se ambas as afirmações a seguir forem verdadeiras:

- Os níveis estão todos **aumentando** ou todos **diminuindo**.
- Quaisquer dois níveis consecutivos diferem em **pelo menos um** e **no máximo três**.

No exemplo acima, os relatórios podem ser considerados seguros ou inseguros ao verificar essas regras:

- `7 6 4 2 1`: **Seguro** porque os níveis estão todos diminuindo em 1 ou 2.
- `1 2 7 8 9`: **Inseguro** porque `2 7` é um aumento de 5.
- `9 7 6 2 1`: **Inseguro** porque `6 2` é uma diminuição de 4.
- `1 3 2 4 5`: **Inseguro** porque `1 3` está aumentando, mas `3 2` está diminuindo.
- `8 6 4 4 1`: **Inseguro** porque `4 4` não é nem um aumento nem uma diminuição.
- `1 3 6 7 9`: **Seguro** porque todos os níveis estão aumentando em 1, 2 ou 3.

Portanto, neste exemplo, `2` relatórios são **seguros**.

Analise os dados incomuns dos engenheiros. Quantos relatórios são seguros?

Link: [Day 2: Red-Nosed Reports](https://adventofcode.com/2024/day/2)
