# Relatório sobre a Avaliação

## Item 5 - Comentários sobre trechos do código

### Navbar:
A barra de navegação implemeta os seguintes elementos:
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
bi:https://getbootstrap.com/docs/5.3/helpers/icon-link/
</ul>
</nav>
</header>
~~~
#### Classes:
* Navbar:
* Dropdown:
* Bi Chevron Down:
* Dropdown Indicator:

## Item 6 - Princípios de Desingn

### Consistência
* A consistência serve como forma de melhorar a experiência do usuário, e garantir uma curva de apredizagem rapída, utilizando de padrões, essa seria sua definição. Ao observarmos todas as paginas do site que abordam os sistema, mantém um mesmo padrão, gerando assim uma consistência entre elas, permitindo a melhor experiencia do usuário, o dando conforto por precisar descobrir e aprender apenas uma pagina.
### Affordance
* O affordance é a utilização de um item da vida real, e colocando seu uso na programação, um botão sendo apertado, ou uma seta para baixo ao lado de uma palavra fazer um dropdown surgir. Nosso site usa da lupa para pesquisa, uma seta para baixo para dropdown no menu de sistemas, e uma oposta que permite que o usuário volte para o topo da pagina.
### Visibilidade
* A visibilidade é a criação de prioridades, ou objetos chamativos, que fazem com que o usuário olhe o objeto, como exemplo a barra de pesquisa do google demonstrada no meio da tela. Nosso site possui um carrossel grande que faz com que o cliente o olhe, permitindo assim a clara visibilidade sobre o assunto que nosso site busca entregar, possuimo um menu centralizado na parte superior, permitindo a movimentação entre telas, e abaixo do carrosel possuindo todos os sistemas amostra, no footer temos novamente um menu para acessar os sistemas, o criadores do site, e as referências.
### Restrição
* A restrição seria utilizar de recurso para impedir o usuário de entrar em locais proibidos, ou o impedir de cometer erros, e caso cometa, existam formas de reverter. por exemplo o usuário se perde entre as pagina, clicando em inicio, ele voltaria para a home. Nosso site possui uma baixa indução a erro ja que, em caso do usuário se dirigir a um sistema errado, ele pode simplesmente escolher novamente o sistema, ou apertar no nome do site, o fazendo voltar para a home.
