# Layout CSS

`justify-content` <br>
Propriedade que alinha os itens horizontalmente e aceita os seguintes valores:

> *flex-start*: os itens são alinhados ao lado esquerdo do contêiner. <br>
*flex-end*: os itens são alinhados ao lado direito do contêiner. <br>
*center*: os itens são alinhados no centro do contêiner. <br>
*space-between*: Os itens são exibidos com espaçamento igual entre eles. <br>
*space-around*: os itens são exibidos com espaçamento igual ao seu redor.

`align-items` <br>
Esta propriedade CSS alinha os itens verticalmente e aceita os seguintes valores:

> *flex-start*: os itens são alinhados à parte superior do contêiner. <br>
*flex-end*: os itens são alinhados à parte inferior do contêiner. <br>
*center*: os itens são alinhados no centro vertical do contêiner. <br>
*baseline*: os itens são exibidos na linha de base do contêiner. <br>
*stretch*: os itens são esticados para caber no contêiner.

`align-self` <br>
Esta propriedade pode ser usada para itens específicos e aceita os mesmos valores de align-items
<br>

`flex-direction` <br>
Esta propriedade CSS define a direção em que os itens são colocados no contêiner e aceita os seguintes valores:

> *row*: os itens são colocados na mesma direção do texto. <br>
*row-reverse*: os itens são colocados na direção oposta à do texto. <br>
*column*: Os itens são colocados de cima para baixo. <br>
*column-reverse*: Os itens são colocados de baixo para cima.


`flex-wrap` <br>
Esta propriedade distribui os itens e aceita os seguintes valores::

> *nowrap*: Cada item cabe em uma única linha. <br>
*wrap*: os itens são agrupados em linhas adicionais. <br>
*wrap-reverse*: os itens são contornados em linhas adicionais ao contrário.

`flex-flow` <br>
As duas propriedades flex-direction flex-wrap são usadas juntas com tanta frequência que a propriedade abreviada flex-flow foi criada para combiná-las. Esta propriedade abreviada aceita o valor das duas propriedades separadas por um espaço.

> *column wrap*; <br>
*row nowrap*;


`order` <br>
Às vezes, reverter a ordem das linhas ou colunas de um contêiner não é suficiente. Nestes casos, podemos aplicar a order propriedade a itens individuais. Por padrão, os itens têm o valor 0, mas podemos usar esta propriedade para defini-lo também como um valor inteiro positivo ou negativo.

>*(-2, -1, 0, 1, 2)*

`align-content` <br>
Pode ser usada para definir como as linhas são espaçadas umas das outras aceitando os valores:

> *flex-start*: as linhas são embaladas na parte superior do contêiner.
*flex-end*: as linhas são embaladas no fundo do contêiner.
*center*: as linhas são embaladas no centro vertical do contêiner.
*space-between*: as linhas são exibidas com espaçamento igual entre elas.
*space-around*: as linhas são exibidas com espaçamento igual ao seu redor.
*stretch*: as linhas são esticadas para caber no contêiner.
