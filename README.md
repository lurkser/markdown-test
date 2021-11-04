🔰Diretório feito para testar o markdown do github e aprender a usar projetos e issues🔰
# Test de markdown
## Exemplos
### texto
É muito fácil deixar umas palavras em **negrito** e outras em *itálico*, dá até pra ***misturar*** e [linkar pra qualquer site](https://www.privacytools.io)
### lista
Numerada:
1. Um
2. Dois
3. Três

Pontuada:
* Só usar asterisco

Alternativamente,

- Traços também funcionam
- E com sub pontos é só dar 2 espaços antes do traço ou asterisco
  - Assim
### Imagens
Acopla-se imagens assim:
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
# Documentos Estruturados
É útil ter vários níves de header para estruturar os documentos, linhas com # ficam maiores e podem ir até 6 deles, diminuindo com cada # subsequente

### Esse é o de terceiro nível

Se quiser citar alguém, use > antes da linha:
>Liberte-se do café 
> - [Jeff Delaney](https://www.youtube.com/watch?v=Guk29oT7c5M)

### Código
Se for pequeno, crase é o suficiente `var example = true`.
Maior que isso pode usar quatro espaços, que irá indentar:

    if(isAwesome){
      return true
    }

Também existe code fencing, múltiplas linhas sem indentar:

```
if (isAwesome){
  return true
}
```
E se quiser usar marcação de síntaxe, inclua a língua:

```javascript
if (isAwesome){
  return true
}
```

# Extras
Github permite refenciar e linkar alguém, prefixando com um @: Ei @lurkser - amei sua camisa!

E também listas de tarefas:

- [x] Esse é um item completo
- [ ] Esse é um item incompleto

E claro, emoji: 🌲🏆

## Tabelas
É possível criar tabelas dividindo palavras com - (para a primeira linha) e cada coluna com |

First Header | Second Header
------------|-------
Conteudo 1 | Conteudo 2
Conteudo primeira coluna | Conteudo segunda coluna

### Issue referência


lurkser[#1](https://github.com/lurkser/markdown-test/issues/1)

lurkser/markdown-test[#1](https://github.com/lurkser/markdown-test/issues/1)

### Link automático
Toda URL vai se tornar um link clicável https://www.github.com

### Strikethrough
Qualquer palavra com 2 tils antes e depois tipo ~~assim~~
