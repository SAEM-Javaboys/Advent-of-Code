# --- Dia 1: Histeria do Historiador ---

O **historiador-chefe** está sempre presente para o grande lançamento do trenó de Natal, mas ninguém o vê há meses! A última vez que alguém o viu, ele estava visitando locais historicamente significativos no Polo Norte; um grupo de historiadores experientes pediu que você os acompanhasse enquanto verificam os lugares que acham mais prováveis de serem visitados.

À medida que cada local for verificado, eles marcarão na lista com uma **estrela**. Eles acham que o historiador-chefe deve estar em um dos primeiros cinquenta lugares que procurarão, então, para salvar o Natal, você precisa ajudá-los a obter cinquenta estrelas na lista antes que o Papai Noel decole no dia 25 de dezembro.

Colete estrelas resolvendo desafios. Dois desafios estarão disponíveis a cada dia no calendário do Advento; o segundo desafio é desbloqueado quando você completa o primeiro. Cada desafio concede **uma estrela**. Boa sorte!

Você ainda nem saiu e o grupo de historiadores experientes elfos já encontraram um problema: a lista de locais a serem verificados está **vazia**. Por fim, alguém decide que o melhor lugar para verificar primeiro seria o escritório do historiador-chefe.

Ao entrar no escritório, todos confirmam que o historiador-chefe realmente não está lá. Em vez disso, os elfos descobrem uma variedade de anotações e listas de locais historicamente significativos! Esse parece ser o planejamento que o historiador-chefe estava fazendo antes de partir. Talvez essas anotações possam ser usadas para determinar quais locais devem ser verificados?

Por todo o escritório do chefe, os locais historicamente significativos são listados não por nome, mas por um número exclusivo chamado de **ID do local**. Para garantir que não perderão nada, os historiadores se dividem em dois grupos, cada um procurando no escritório e tentando criar sua própria lista completa de IDs de locais.

Há apenas um problema: ao segurar as duas listas **lado a lado** (seu input no desafio), fica claro que as listas não são muito semelhantes. Talvez você possa ajudar os Historiadores a reconciliar suas listas?

Por exemplo:

Por exemplo:

<table>
  <tr><td>3</td><td>4</td></tr>
  <tr><td>4</td><td>3</td></tr>
  <tr><td>2</td><td>5</td></tr>
  <tr><td>1</td><td>3</td></tr>
  <tr><td>3</td><td>9</td></tr>
  <tr><td>3</td><td>3</td></tr>
</table

Talvez as listas estejam apenas um pouco diferentes! Para descobrir, emparelhe os números e meça o quão distantes eles estão. Emparelhe o **menor número da lista da esquerda** com o **menor número da lista da direita**, depois o **segundo menor número da esquerda** com o **segundo menor número da direita** e assim em diante.

Em cada par, descubra **qual é a distância** entre os dois números; você precisará **somar todas essas distâncias**. Por exemplo, se você emparelhar um `3` da lista da esquerda com um `7` da lista da direita, a distância entre eles é `4`; se você emparelhar um `9` com um `3`, a distância entre eles é `6`.

Na lista de exemplo acima, os pares e as distâncias seriam os seguintes:

- O menor número da lista da esquerda é `1`, e o menor número da lista da direita é `3`. A distância entre eles é `2`.
- O segundo menor número da lista da esquerda é `2`, e o segundo menor número da lista da direita é outro `3`. A distância entre eles é `1`.
- O terceiro menor número em ambas as listas é `3`, então a distância entre eles é `0`.
- Os próximos números a serem emparelhados são `3` e `4`, uma distância de `1`.
- Os quintos menores números em cada lista são `3` e `5`, uma distância de `2`.
- Finalmente, o maior número na lista da esquerda é `4`, enquanto o maior número na lista da direita é `9`; eles estão a uma distância de `5`.

Para encontrar a distância total entre a lista da esquerda e a lista da direita, some as distâncias entre todos os pares que você encontrou. No exemplo acima, isso é `2 + 1 + 0 + 1 + 2 + 5`, uma distância total de `11`!

Sua lista real da esquerda e da direita contêm muitos IDs de locais. Qual é a distância total entre suas listas?

Link: [Day 1: Historian Hysteria](https://adventofcode.com/2024/day/1)
