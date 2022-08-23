---
title: Por que criar um blog pessoal? E por que com Jekyll?
layout: post
date: '2022-08-18 14:00:00'
categories: jekyll
---

Este mês comecei uma nova fase da minha vida profissional como desenvolvedor Python na BairesDev.  Desde o início de Agosto estou oficialmente trabalhando nessa empresa que me surpreendeu muito (de forma positiva) com o seu processo de seleção e  onboarding de novos funcionários. Mas isso é assunto para outro post...

O que eu queria tirar disso é que,  devido a essa mudança empresa, neste mês eu ganhei alguns dias para fazer o que eu quissesse enquanto o meu primeiro projeto ainda não começava. 

Como não estou com a vida ganha e sou novo na empresa, aproveitei esse tempo para aprender alguma coisa nova. No início da semana estudei um pouco de Python, mas esse uso utilitarista do meu "tempo livre" não estava muito motivador. 


Então lembrei de uma ideia antiga, e nada original, de fazer um blog pessoal para mim. Queria fazer um blog para organizar as coisas que estudo e pra falar um pouco de bobagem também -- ninguém é tão chato que não tenha uma bobagem para falar.


### Tá! Mas e o Jekyll?
Sei que usar o WordPress para fazer blogs é mais rápido e fácil porque já tem tudo pronto e tals. O que acontece é que eu não queria o caminho mais fácil. Tsc, tsc, tsc... Brincadeira!  Hehehe. Eu tenho blogs no WP e não tenho nada contra. 

É que há um ano atrás li um artigo sobre como publicar uma página padrão no GitHub Pages ([https://pages.github.com](https://pages.github.com){:target="_blank" }) e achei muito interessante como tudo funciona.   

Aí fiquei com vontade de criar uma página dessas para mim, claro! E comecei a pesquisar o assunto. Na época, até consegui escolher um tema padrão e fazer o deploy no GitHub Pages.  
Fiquei orgulhoso no dia!   
Eis a página (spoiler: não é nada de mais): [https://claudiosiervi.github.io/github-page-with-theme](https://claudiosiervi.github.io/github-page-with-theme){:target="_blank" }.

Então agora nessa semana, conversando com a minha esposa e amiga Luciana, que também é programadora, ela lembrou que tinha feito um blog no GitHub Pages há uns três anos atrás. E então fui dar uma olhada: [https://lucianalml.github.io/abap-library](https://lucianalml.github.io/abap-library){:target="_blank" }. E me inspirei na ideia. :heart:

E de forma "resumida", o GitHub gera as páginas estáticas do Pages usando o framework Jekyll [https://jekyllrb.com](https://jekyllrb.com){:target="_blank" }.  :shipit:


A principal vantagem de um página estática é que esta não usa APIs ou serviços externos para funcionar. Isso aumenta a segurança dessas páginas tanto para quem as mantém no ar quanto para quem acessa o seu conteúdo.   

Por outro lado, o WP usa diversas APIs e pacotes externos para manter um blog no ar. E essas APIs, pacotes e o próprio WP precisam ser atualizadas regularmente, o que raramente acontece. E é por isso que a maioria dos sites da plataforma está vulnerável a agentes maliciosos. Para entender mais sobre essa questão de vulnerabilidades no WP dá uma olhada nesse site aqui: [https://kinsta.com/blog/wordpress-statistics/](https://kinsta.com/blog/wordpress-statistics/){:target="_blank" }.

No próximo capítulo trarei um resumo de como desenvolver um blog de forma muito rápida com o Jekyll e Docker. E outros resumos de como eu fiz outras coisas aleatórias.