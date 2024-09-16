# the-hunger-games
Trabalho avaliativo da matéria estrutura de dados I
<hr>

### Descrição do problema
Todos os anos, nas ruínas do que já foi a América do Norte, o Capitólio da nação de Panem obriga
cada um dos 12 distritos a enviar dois tributos (um menino e uma menina) entre 12 e 18 anos para
competir nos Jogos Vorazes: um evento em que os “tributos” lutam entre si até a morte até que
um sobrevivente permaneça. Mais uma edição dos Jogos Vorazes está para começar e, neste ano, o
presidente Coriolanus Snow fez questão de propor um desafio para os tributos. Em sua proposta,
cada tributo será colocado dentro de um labirinto junto com um ou mais bestantes. A arena terá
24 labirintos, um para cada tributo. Apenas os tributos que conseguirem sair vivos do seu labirinto
continuarão a competição. <br>

Para planejar o desenho de um labirinto, o número de bestantes que serão colocados nele e
as posições iniciais de cada bestante e do tributo no labirinto, o presidente Snow solicitou que
um programa fosse implementado para simular soluções possíveis para configurações de labirintos
fornecidas. O objetivo é que cada tributo tenha chances reais de sobreviver ao labirinto. Desta forma,
existirá a possibilidade de que todos os tributos sobrevivam aos labirintos e lutem na arena entre si.
No sistema de simulação deve-se considerar que, em um labirinto, quando um tributo der um
passo em alguma direção, cada bestante também pode dar um passo simultaneamente. O objetivo
do tributo é alcançar um dos quadrados limítrofes sem nunca compartilhar um quadrado com um
bestante. <br>

Sua tarefa é descobrir se a sobrevivência do tributo é possível e, se for, o programa deve imprimir
um caminho que o tributo possa seguir. Seu plano tem que funcionar em qualquer situação, mesmo
que os bestantes conheçam o caminho que o tributo escolher de antemão. <br>

Entrada:
A primeira linha de entrada possui dois inteiros n e m: a altura e a largura do labirinto, onde,
1 ≤ n, m ≤ 1000. Depois disso, existem n linhas de m caracteres descrevendo o mapa. Cada caractere
é . (chão), # (parede), A (posição inicial do tributo) ou M (bestante). Há exatamente um A na
entrada. <br>

Saída:
Primeiro imprima “YES” se seu objetivo for possível, e “NO” caso contrário. Se seu objetivo
for possível, imprima também um exemplo de caminho válido (o comprimento do caminho e sua
descrição usando os caracteres D, U, L e R). Você pode imprimir qualquer caminho, desde que seu
comprimento seja no máximo n · m passos.
