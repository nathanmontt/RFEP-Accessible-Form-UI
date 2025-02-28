# *RFEP - roadmap.sh Frontend Projects*
Projeto de Frontend do site <a href="https://roadmap.sh/">roadmap.sh</a>

---

### ÍNDICE

* [Sobre o Projeto](#about)
* [Habilidades Necessárias](#abilities)
* [Requisitos Chave](#key-requirements)
* [Pontos Importantes](#key-points)
* [Links Úteis](#links)
* [Créditos](#credits)


<h1 id="about">Sobre o Projeto</h1>

Como o nome do repositório menciona, **RFEP-Accessible-Form-UI** é um projeto de Frontend, trago pelo site <a href="https://roadmap.sh/">roadmap.sh</a>, onde o objetivo é criar um formulário acessível aos usuários.


<h1 id="abilities"> Habilidades Necessárias </h1>

* HTML
* CSS (*vanila*)


<h1 id="fut-feats"> <em>Features</em> Futuras </h1>

Para futuras <em>features</em>, alguns opções serão levadas em consideração:

*Feature* | Motivo/Explicação
:---------: | :------:
**Futuro** | De acordo com o próprio site, o projeto terá alterações mais a frente
**Imagens** | Lembrar de adicionar a tela do projeto, já que neste o _deploy_ **não será feito**


<h1 id="key-requirements"> Requisitos Chave </h1>


O projeto informa alguns pontos-chave a serem seguidos, como:

Requisito | Explicação
:---------: | :------:
**Labeling** | Fazer com que cada campo tenha a tag <label> associada corretamente
**Focus State** | Estilizar o estado de *focus* de cada campo para que o usuário, quando navegar com o teclado, possa ver o campo ativo atual
**Error Messaging** | Considerar a adição de uma mensagem de erro para quando o usuário colocar um dado errado
**ARIA Attributes** | Usar atributos ***ARIA*** (Accessible Rich Internet Applications) necessário
**Color Contrast** | Certificar que a cor de contraste entre o texto e o *background* seja suficiente para atender ao ***WCAG*** (Web Content Accessibility Guidelines)
**Interactive Elements** | Ter a certeza de que o botão de *show/hide*, para as senhas, seja acessível via teclado


<h1 id="key-points"> Pontos Importantes </h1>

Vale resaltar alguns pontos para lembrar no decorrer do projeto:
* Como é um *forms*, na hora de usar `<input type="radio">`, e tivermos, por exemplo, 17 opções, primeiro colocamos, como um de seus atributos, o `name="igual_em_todos"`. O motivo é para que, assim que marcarmos uma opção, ela não ficará marcada por si só, e sim alternará entre as existentes;
* Outro ponto sobre o atribuito name é que, dependendo da _action_ (`form action="" method="get/post"`), na parte do _server-side_, é possível acessar os dados submetidos pelo **_name_**;

<h1 id="links"> Links Úteis </h1>


A seção abaixo foi adicionada para caso queira verificar algum conteúdo de estudo. Se for de seu interesse e também quiser recomendar algum outro, fique à vontade!

*Tipo do Estudo* | Nome do Artigo
:---------: | :------:
**HTML: forms** | <a href="https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms/Your_first_form">Your first form</a> <br> <a href="https://www.w3schools.com/html/html_forms.asp">HTML Forms</a>
**CSS (and others)** | <a href="https://www.w3schools.com/cssref/css3_pr_clip-path.php">CSS clip-path Property</a> <br> <a href="https://www.youtube.com/watch?v=SKU2gExpkPI&t=194s"> How to make Circular Progress Bar in HTML CSS & JavaScript | Skills Bar </a>
**git** | <a href="https://github.com/github/docs/blob/main/content/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax.md">basic-writing-and-formatting-syntax.md</a>
**roadmap.sh** | O link do projeto pode ser encontrado <a href="https://roadmap.sh/projects/accessible-form-ui">aqui</a>


<h1 id="credits"> Créditos </h1>

Copyright © 2024, Nathan Monteiro
