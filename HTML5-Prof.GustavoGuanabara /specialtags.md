# SPECIAL TAGS

- ```<wbr>``` wbr - criar quebra de palavras 
- ```&nbsp;``` - it is "space" 
- ```<i>``` - Itálico
- ```<b>``` - para negrito
- ```<em>``` - enfase
    - ```<i> e <em>``` os dois fazem as palavras ficarem inclinada, mas semanticamente ```<em>``` estar dizendo para navegador que vc quer enfatizar esse termo, não somente a palavra inclinada
- ```<u>``` - a tag underline foi depreciada no HTML5, era usado no HTML3, hj underline é utilizado com CSS
- ```<del>``` - <del> é a palavra riscada
- ```<span>``` - utilizada para formatar pequenos texto
    - ex: ```<span style="text-decoration: underline;>``` linha underline
    - ```<span style="text-decoration: line-through;>``` é o riscado igual o ```<del>```, mas com significado sematico diferente
    - ```<span   style="text-decoration: overline;">``` linha acima do texto
    - ```<span style="text-decoration: none;">``` que não altera em nada o texto, mas semanticamente, ele bloqueia alteração que vem no CSS por exemplo.
    - ```<span style="font-weight:normal;">``` o paramento font-weight vai criar a quantidade de negrito que palavra terá
        - ```normal``` - sem efeito
        - ```bold``` - negrito
        - ```bolder``` - mais negrito
        - ```100 até 900``` - usando de 100 até 900 de % negrito
- ```style``` - para alinhamento, antigamente se usava ```align```. 
    - ```<h2 style:"text-align: left;">``` usando para esquerda
        - ```right``` para direita
        - ```center``` para centralizar  
        - ```justify```estilo justificado 
- ```text-indent:``` é utilizado para paragrafo, sendo 1 até 100
    - ```<h2 style:"text-align: left; text-indent:50">``` 



````
<p>Exemplos de <sup>Formatação</sup></p>```
<p> x<sup> 2</sup> e H<sub>2</sub>O</p>```
````
<p>Exemplos de <sup>Formatação</sup></p>
<p> x<sup> 2</sup> e H<sub>2</sub>O</p>


- ```<code>```serve para exibir codigo no navegador
- ```<pre>```é usado para deixa o pré formatado
    - ```&lt```é para < 
    - ```&gt```é para >
 ```
 // Código de C++

 <pre> 
 <code>
 #include &lt;iostream&gt;
 int main() {
     cout << "Olá Mundo!";
     return 0;
 }
</code>
</pre>
```

## Color CSS
-``` color: rgba(0,0,0,0.5);```  RGB = vermelho/red (60), verde/green (45) e azul/blue (3E) - Cada valor é representado em base hexadecimal. ```A``` representa alpha, que vai de 0 até 1.
-  ```background-color: hsla(165, 81%, 93%, 0.5);```   hls() cria cores utilizando a representação percentual de Matiz (Hue), saturação (Saturation) e luminosidade (Brightness). Tbm podendo utilizar hlsa() ```A``` representando o Alpha.

## Símbolos especiais
<p>
    video&shy;con&shy;ferên&shy;cia - &shy  gera a separação de sílabas com hifenização. (-)
    &lt; menor que... 
    <br>
    &gt; maior que...
    <br>
    &le; menor igual a...
    <br>
    &ge; maior igual a...
    <br>
    &pound; pound simbolo
    <br>
    &yen; yen simbolo
    <br>
    &euro; euro símbolo...
    <br>
    &copy; copiright simbolo
    <br>
    &reg; marca registrada simbolo
    <br>
    &trade; Trademark simbolo
    <br>
    &permil; porcentagem dividido por mil
    <br>
    &sum; simbolo de soma
    <br>
    &infin; infinito simbolo 
    <br>
    &times; simbolo de multiplicação
    <br>
    &plusmn; simbolo de mais ou menos
    <br>
    &oplus; simbolo mais dentro de um circuferência
    <br>
    &radic; raiz quadrada
    <br>
    &ne; não igual
    <br>
    &delta; delta minúsculo
    <br>
    &Delta; DELTA maiúsculo
    <br>
    &omega; omega simbolo
    <br>
    &phi; simbolo phi
    <br> 
    &larr; left arrow - seta para esquerda
    <br>
    &rarr; right arrow - seta para direita
    <br>
    &uarr; up arrow - seta para cima
    <br>
    &darr; down arrow - seta para baixo
    <br>
    &harr; seta para os dois lados
    <br>
    &Larr; &Larr se a primeira letra for maisucula o sinal da seta fica diferente
    <br> 
    &spades;
    &clubs;
    &hearts;
    &diams; naipes das cartas
</p>
