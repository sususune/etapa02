# Relatório sobre a Avaliação

## Site:

O site foi feito com fins acadêmicos e visa um ensino sobre os sistemas do corpo humano e o aprendizado dos desenvolvedores sobre interface e design.
Autores do site: Sofia Lima e João Victor Araújo
Template utilizado: ZenBlog - Bootstrap

## Item 5 - Comentários sobre trechos do código

### Navbar:
#### A barra de navegação implemeta os seguintes elementos:
* Um dropdown de Sistemas, com links que levam para cada um dos sistemas do site, facilitando a navegação
* Um link para o sobre nós, onde mostramos os criadores da página e os objetivos
* Um link para as referências utilizadas para fazer o site
* Os ul e li são usados para listas, o ul do dropdown possui uma li para cada sistema e a ul de cima possui lis para as páginas Sobre e Referências
* A tag nav, dentro da tag header cria a navbar
* Dentro dela temos duas uls, uma para o dropdown dos sistemas e outra para o Sobre e Referências
~~~html
<header>
<nav class="navbar">
<ul>
	<li class="dropdown"><a href="#"><span>Sistemas</span> <i class="bi bi-chevron-down dropdown-indicator"></a></i>
	<ul>
	<li><a href="sistema-digestorio.html">Sistema Digestório</a></li>
	<li><a href="sistema-respiratorio.html">Sistema Respiratório</a></li>
	<li><a href="sistema-circulatorio.html">Sistema Circulatório</a></li>
	<li><a href="sistema-nervoso.html">Sistema Nervoso</a></li>
	<li><a href="sistema-locomotor.html">Sistema Locomotor</a></li>
	<li><a href="sistema-endocrino.html">Sistema Endócrino</a></li>
	<li><a href="sistema-excretor.html">Sistema Excretor</a></li>
	</ul>
	<li><a href="about.html">Sobre</a></li>
	<li><a href="referencias.html">Referências</a></li>
</ul>
</nav>
</header>
~~~

#### Classes:
* Navbar: A classe navbar é uma classe para navbar do bootstrap que implementa uma barra de navegação responsiva dentro do header
* Dropdown: A classe dropdown implementa um "menu suspenso", que é aberto na navbar e mostra sub-itens de um item, como no caso: os sistemas dentro do item Sistema
* Bi Chevron Down e Dropdown Indicator: São classes que implementam o ícone de seta presente no dropdown, para indicar que é um menu suspenso

## Item 6 - Princípios de Desingn

### Consistência
* A consistência serve como forma de melhorar a experiência do usuário e garantir uma curva de apredizagem rapída utilizando de padrões. Ao observarmos todas as paginas do site que abordam os sistemas, o mesmo padrão é mantido, gerando assim uma consistência entre elas, permitindo a melhor experiencia e conforto ao usuário, fazendo ele não precisar de muito esforço para entender as páginas.
### Affordance
* O affordance é a utilização de um item da vida real, e colocando seu uso na programação, um botão sendo apertado, ou uma seta para baixo ao lado de uma palavra fazer um dropdown surgir. Nosso site usa da lupa para pesquisa, uma seta para baixo para dropdown no menu de sistemas e uma oposta que permite que o usuário volte para o topo da pagina.
### Visibilidade
* A visibilidade é a criação de prioridades, ou objetos chamativos, que fazem com que o usuário olhe o objeto, como exemplo a barra de pesquisa do google demonstrada no meio da tela. Nosso site possui um carrossel grande que faz com que o cliente já bata o olho e entenda sobre o que se trata o site, possuindo um menu centralizado na parte superior, permitindo a movimentação entre telas, e abaixo do carrosel com todos os sistemas a mostra, no footer temos novamente um menu para acessar os sistemas, o criadores do site, e as referências.
### Restrição
* A restrição consiste em utilizar de recursos para impedir o usuário de entrar em locais proibidos, ou o impedir de cometer erros, e caso cometa, existam formas de reverter. Por exemplo: se o usuário se perder entre as páginas, ele pode clicar em início e voltar para a página inicial. Nosso site possui uma baixa indução a erro, visto que em caso do usuário se dirigir a um sistema errado ele pode simplesmente escolher novamente o sistema, ou apertar no nome do site para voltar para a página inicial por meio do header.
