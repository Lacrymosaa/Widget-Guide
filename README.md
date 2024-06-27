# Guia de Widgets para GitHub Profile
Olá! Algumas pessoas vem me perguntando como utilizar os Widgets no profile do GitHub, então explicarei da forma mais simples quanto possivel como utiliza-los e dar alguns exemplos e demonstrações. 

Caso queira adicionar/complementar o que foi dito aqui, sinta-se livre para enviar seu Pull Request! Faço este documento com base no meu conhecimento e no que vi até o presente momento.

**Aviso de antemão que não possuo propriedade sobre nenhum widget utilizado como exemplo aqui, apenas irei usá-los com intuito de educar e ilustrar.**

# Como usar?
Para utilizar um widget basta utilizar o link dele em seu README desta forma:
```
![Titulo Dele](Link Dele)
```
E caso queira que ele redirecione o usuário:
```
[![Titulo Dele](Link Dele)](Link de Redirecionamento)
```
Mas antes há dois tipos (que são de meu conhecimento) de Widgets para perfil: Os simples e os que dependem do Vercel. 

# Os simples
Os simples são os que você apenas necessita do link. Usarei como exemplo o <a href=https://github.com/anuraghazra/github-readme-stats>GitHub Stats</a>:
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=Lacrymosaa&theme=dracula)
```

![GitHub stats](https://github-readme-stats.vercel.app/api?username=Lacrymosaa&theme=dracula)

Este é um widget simples e facilmente customizável, mas como é possivel ver: ele possui um link com o "**username=**". **Para ele se tornar seu você apenas deve colocar seu username do github após "username="**, simples assim. Isso serve para todos os widgets categorizados como simples. Pegue o código e troque para seu username e ele se tornará seu.

## Mas o que é o ![Github stats] antes do link?
Ele é apenas um marcador responsavel por manifestar a imagem no link a seguir.

## Como trocar o tema?
Para trocar o tema basta editar o "**theme=**" para o <a href="https://github.com/anuraghazra/github-readme-stats/blob/master/themes/README.md">tema</a> desejado.

## Quais customizações mais eu posso fazer?
As variações são poucas entre cada widget, todos eles se comportam como elementos HTML, ou seja, podem ser afetados por CSS em seu link.

Assim como mudar o "**theme=**" afeta sua coloração, mexer em outros aspectos pode modificá-lo.

Para modificar um item é necessário utilizar o "**&**" para juntar a próxima caracteristica ao link, como é feito em:
```
username=Lacrymosaa&theme=dracula
```

## Alguns exemplos, utilizando ainda o GitHub Stats, são:
- ### Título: title_color
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=Lacrymosaa&theme=dracula&title_color=00ffff)
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=Lacrymosaa&theme=dracula&title_color=00ffff)
- ### Texto: text_color 
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=Lacrymosaa&theme=dracula&text_color=00ffff)
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=Lacrymosaa&theme=dracula&text_color=00ffff)
- ### Fundo: bg_color
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=Lacrymosaa&theme=dracula&bg_color=000)
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=Lacrymosaa&theme=dracula&bg_color=000)
- ### Borda: border_color
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=Lacrymosaa&theme=dracula&border_color=00ffff)
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=Lacrymosaa&theme=dracula&border_color=00ffff)

Essas classes não são universais, então, outros widgets podem utilizar de tags diferentes, como por exemplo background_color para o fundo, ao invés de bg_color. Então verifique as configurações possiveis dentro do repositório oficial do widget. 

Em muitos casos talvez não haja todas as personalizações possiveis descritas, então tente você mesmo!

# Os que dependem do Vercel
Antes de qualquer coisa caso você não saibe o que é Vercel: 
Vercel é uma plataforma voltada para a hospedagem de aplicações de forma prática. Grande parte dessas aplicações são feitas em React. 

Até hoje apenas vi um único widget que dependa do Vercel, mas não descarto a possibilidade de existirem mais. Então usaremos de exemplo:
https://github.com/novatorem/novatorem
```
[![Spotify](https://now-playing-pqytlme7u-diabolicwitch.vercel.app/api/spotify?background_color=0d1117&border_color=ffffff)](https://open.spotify.com/user/ewt4ywvzbhdhx4uhrparn3rxt)
```
[![Spotify](https://now-playing-pqytlme7u-diabolicwitch.vercel.app/api/spotify?background_color=0d1117&border_color=ffffff)](https://open.spotify.com/user/ewt4ywvzbhdhx4uhrparn3rxt)

> [!NOTE]\
> O /user/ com muitos caracteres aleatórios depois é o usuário do spotify.

Não vou explicar toda a metodologia para fazer um desses (caso esteja interessado veja o <a href="https://github.com/novatorem/novatorem/blob/main/SetUp.md">SetUp</a>), mas após tudo pronto você terá que colocar seu repositório para rodar dentro do Vercel e utilizar o link assim como feito anteriormente.

Ele também é customizável, e pela minha experiência, até mais maleável que o outro.

> [!NOTE]\
> A maneira que você terá que configurar cada um é diferente, então, sempre leia o README. -> Valido para o Snake Game de Perfil.

## Em resumo

A diferença entre os dois é apenas o esforço despendido por um link. Alguns você só copia, e outros você tem que dar <a href="https://docs.github.com/pt/get-started/quickstart/fork-a-repo">Fork</a> no repositório e upa-lo para o Vercel com as configurações.

Em todos os casos, tudo que deve ser feito é abrir o seu README no repositório com o mesmo nome de seu usuário e inserir o link no mesmo formato mostrado.
```
![Titulo Dele](Link Dele)
```

Agora basta achar um de seu agrado e usá-lo!



