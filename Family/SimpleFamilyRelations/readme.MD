# Simple Family Relations
O objetivo é compreender de forma didática a definição de conceitos por meio de restrições sobre propriedades e, também, os axiomas sobre propriedades.
## Classes
- **AoMenosUmaFilha**: pessoas que têm pelo menos uma filha (Existencial)
- **AoMenosUmaFilhaNaCreche**: pessoas que têm pelo menos uma filha matriculada em uma creche (Existencial qualificado)
- **Creche**: crianças que estão na creche (Atômica)
- **FilhasSomenteNaCreche**: pessoas cujas filhas estão todas na creche (utiliza universal qualificado; ver como 'fechar' o mundo nos indivíduos)
- **JovensAdultas**: pessoas entre 18 e 35 anos (restrição sobre data properties)
- **JovensAdultasComFilhasNaCreche***: Uma interseção entre as classes JovensAdultas e AoMenosUmaFilhaNaCreche, representando jovens adultas que têm filhas em creches (Interseção)
- **RMãeDe_y1**: Uma classe que identifica a mãe de um indivíduo específico, y1 (Restrição por 'value of')
## Propriedades de objetos
Interessante notar a hierarquia de propriedades e os axiomas definidos sobre elas (transitividade, antirreflexiva).
éFilhaDe: Esta propriedade indica que "x é filha de y". 
éIrmãDe: Relaciona duas irmãs de maneira simétrica: "x é irmã de y é uma propriedade simétrica porque y também é irmã de x".
éMãe: Esta propriedade é usada para definir a relação "x é mãe de y". É irreflexiva, ou seja, uma pessoa não pode ser mãe de si.
éPróximo: Define uma relação de afinidade ou proximidade entre pessoas
éTiaMaterna: se utiliza de uma cadeia de propriedades: "x é irmã de y" e "y é mãe de z", resultando em "x é tia materna de z". 
