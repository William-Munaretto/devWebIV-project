# Projeto Desenvolvimento Web IV - TADS 2021 - 4º período

Instalação e configuração de ferramentas de desenvolvimento para as aulas da matéria de Desenvolvimento Web IV do curso de Tecnologia em Análise e Desenvolvimento de Sistemas do Instituto Federal do Paraná (CAMPUS FOZ DO IGUAÇU).

## Lista de ferramentas
Abaixo segue a lista das ferramentas que serão utilizadas ao longo do curso para desenvolvimento de projetos.

- Spring Tool Suite
- Java
- MySql
- Git
- Node.js
- Postman
- Httpie

## Definição de cada ferramenta

### Spring Tool Suite

O Spring Tool Suite é uma IDE baseada em Eclipse que dá algumas facilidades para trabalhos com o Spring. (Exemplo: Spring Boot).

_**Formatação do texto:**_

Texto *itálico* | Texto **negrito** | ~~Riscado~~

Uma lista:
- item 1
- item 2
- item 3

Lista numerada:
1. item A
1. item B
1. item C


### Criando um link:

sintaxe: `[rotulo](url)`

[link github](https://github.com)

---

Linha __horizontal__

---


### Código fonte (h3)
Sintaxe para código fonte.

Bloco de código genérico:
```
sudo apt-get install mcedit
```

Código fonte:
```js
function abc(){
  // javascript
  return "xyz";
}
```

```py
def main():
  # python
  pass
```

```java
class FileRequest implements JpaRepository {
  // some Java comment
}
```

---

#### Imagens

Via url:

![floppy text](https://github.com/fscheidt/dev/raw/master/assets/floppy.png)

```md
![floppy text](https://github.com/fscheidt/dev/raw/master/assets/floppy.png)
```

Com tag `<img>` e setando width

<img src="../assets/pie-icon.png" width="32">

```html
<img src="../assets/pie-icon.png" width="32">
```

---

#### Todo-list (h4)
Roteiro de implementação
- [ ] **Setup spring-boot project**
    - [X] configure spring-boot starters
    - [ ] configure [app.properties](https://github.com/fscheidt/dev/raw/master/assets/properties.txt) for H2, Thymeleaf and JPA settings.
    - [X] Create the model classes: Filme, Pessoa, Category(enum)
    - [ ] Create a `@Service` class `DataLoaderHelper` so we don't need to re-create the database every time during development time.
    - [ ] add some emoticons: ⛁ 📦 🗺️ 🧑 🎬 🟩

***

### Tabelas

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

***

### Citação

Usar `>` para iniciar um `blockquote`:

> This is a very long line that will still be quoted properly when it wraps.

<br><br>

<div id='final'>
<b>Mais sintaxe</b>: <a href="https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet">Markdown-Cheatsheet</a>
</div>
