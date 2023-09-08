# Conceitos Básicos CSS3

## Seletores e Declarações

<section align="center">
<img src="imagens/seletores.png" alt="Seletores">

</section>
<p align ="justify">Uma regra CSS é representada por um seletor ou um grupo de seletores, no nosso caso é o '<\a>', então dentro de um par de chaves adicionamos as declarações, no exemplo acima estamos alterando cor e tamanho da fonte dessa âncora, as declarações são formadas por uma propriedade e um valor.<br> Percebam que podemos colocar vários seletores em uma regra separando-os por vírgula.
E há um último detalhe nesse exemplo: a pseudo-classe. <br> Elementos HTML sofrem alterações causadas pela interação do usuário, como mover o mouse por cima ou clicar nesse elemento. <br>
O 'a:hover' do exemplo significa que a âncora também terá essa aparência quando o usuário passar o mouse por cima de um hyperlink.</p>

## ID x Classe
<section align="center">
    <img src="imagens/criando-id-class-no-css.webp" alt="IDs e Classes">
</section>

<p align ="justify">
<strong>ID:</strong> é representado pelo símbolo # (hash) seguido de um nome para esse ID.

Classe: a classe é representada de forma parecida do ID, mas é precedida por um ponto em vez do hash.

E a diferença mais importante entre eles é a forma como devem ser usados: o ID só pode ser usado uma vez em uma página HTML enquanto a classe não tem restrições.
</p>

## Box-Model
Quando estamos criando o layout de um site o navegador representa cada elemento HTML  como uma caixa retangular, isso é o box-model. E com CSS nós alteramos a aparência dessa caixa (largura, altura, cor de fundo, etc.). Essa caixa é composta por 4 áreas: o conteúdo, o padding, a borda e a margem.

- As margens (***margin***) são espaçamentos entre elementos;
- As bordas (***border***) ;
- O padding é um espaçamento entre as bordas e o conteúdo, a diferença para as margens é que declarações de imagem de fundo funcionam nele;
- O conteúdo (***content***) é o que o seu bloco representa, um texto, uma imagem, um vídeo;

