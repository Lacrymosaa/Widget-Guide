# Guia de Widgets para GitHub Profile
Olá! Algumas pessoas vem me perguntando como utilizar os Widgets no profile do GitHub, então explicarei da forma mais simples quanto possivel como utiliza-los e dar alguns exemplos e demonstrações. 

Caso queira adicionar/complementar o que foi dito aqui, sinta-se livre para enviar seu Pull Request! Faço este documento com base no meu conhecimento e no que vi até o presente momento.

**Aviso de antemão que não possuo propriedade sobre nenhum widget utilizado como exemplo aqui, apenas irei usa-los com intuito de educar e ilustrar.**

# Como usar?
Primeiramente há dois tipos (que são de meu conhecimento) de Widgets para perfil: Os simples e os que dependem do Vercel.

## Os simples
Os simples são os que você apenas necessita de uma linha de código. Usarei como exemplo o <a href=https://github.com/anuraghazra/github-readme-stats>GitHub Stats</a>:
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=marianvulpes&theme=dracula)
```

![GitHub stats](https://github-readme-stats.vercel.app/api?username=marianvulpes&theme=dracula)

Este é um widget simples e facilmente customizável. A maioria dos widgets se comportam como elementos HTML, mas partiremos do básico:
**Para ele se tornar seu você apenas deve colocar seu username do github após "username="**, simples assim. Isso serve para todos os widgets categorizado como simples. Pegue o código e troque para seu username e ele se torna seu.

## Mas o que é o ![Github stats] antes do link?
Ele é apenas um marcador responsavel por manifestar a imagem no link a seguir.

## Como trocar o tema?
Para trocar o tema basta editar o "**theme=**" para o <a href="https://github.com/anuraghazra/github-readme-stats/blob/master/themes/README.md">tema</a> desejado.

## Quais customizações mais eu posso fazer?
As variações são poucas entre cada widget, e como eu disse anteriormente, eles se comportam como elementos HTML, ou seja, podem ser facilmente afetados por CSS em seu link.

Assim como mudar o "**theme=**" afeta sua coloração, mexer em outros aspectos pode **possivelmente** modificá-lo.

Para modificar um item é necessário utilizar o "**&**" para juntar a próxima caracteristica ao link, como é feito em:
'''
username=marianvulpes&theme=dracula
'''

## Alguns exemplos, utilizando ainda o GitHub Stats, são:
- ### Título: title_color
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=marianvulpes&theme=dracula&title_color=00ffff)
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=marianvulpes&theme=dracula&title_color=00ffff)
- ### Texto: text_color 
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=marianvulpes&theme=dracula&text_color=00ffff)
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=marianvulpes&theme=dracula&text_color=00ffff)
- ### Fundo: bg_color
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=marianvulpes&theme=dracula&bg_color=000)
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=marianvulpes&theme=dracula&bg_color=000)
- ### Borda: border_color
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=marianvulpes&theme=dracula&border_color=00ffff)
```
![GitHub stats](https://github-readme-stats.vercel.app/api?username=marianvulpes&theme=dracula&border_color=00ffff)

Essas classes não são universais, então, outros widgets podem utilizar de tags diferentes, como por exemplo background_color para o fundo, ao invés de bg_color. Então verifique as configurações possiveis dentro do repositório oficial do widget. 

Em muitos casos talvez não haja todas as personalizações possiveis descritar, então tente você mesmo!



