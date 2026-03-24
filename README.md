O que é CSS interno:

O CSS interno ou incorporado requer que você adicione a tags <style> na seção <head> do seu documento HTML.Este estilo de CSS é um método efetivo de estilizar uma única página. Contudo, usar esse estilo em múltiplas páginas pode consumir muito tempo, já que você precisa definir as regras CSS para cada página do seu site.

O que é CSS externo:

O CSS externo envolve a criação de um arquivo .css separado que contém todas as regras de estilo e, em seguida, vinculá-lo ao documento HTML usando a tag <link>.

Seletores CSS:

Seletores do CSS são responsáveis por determinar quais elementos do HTML receberão estilização, ou seja, é um padrão que determina qual recurso será estilizado na sua página ou aplicação. Deixando-a mais atrativa e responsiva para as diferentes telas de visualização entre os mais diversos dispositivos de internet, como, tablets, smartphones e entre outros.

5 Tipos de seletores CSS:

- Seletor de elemento(tag):
Como usar:
p {
  color: blue;
}

Aplica o estilo a todas as tags <p> da página.

- Seletor de classe(.classe):
Como usar:
No HTML:

<p class="destaque">Texto importante</p>

Aplica o estilo a qualquer elemento com class="destaque".

- Seletor de (#id):

#cabecalho {
  font-size: 24px;
}

Como usar:
No HTML:

<div id="cabecalho">Título</div>

Usado para um único elemento na página.

- Seletor descendente (espaço):

div p {
  color: green;
}

Como usar:
Seleciona todos os <p> que estão dentro de <div>, em qualquer nível.

- Seletor de classe combinado:

.botao.ativo {
  border: 2px solid red;
}

Como usar:
No HTML:

<button class="botao ativo">Clique</button>

Aplica o estilo somente quando o elemento tem as duas classes.
