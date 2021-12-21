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

<div style="text-align: justify"><p>O Spring Tool Suite é uma IDE baseada em Eclipse que dá algumas facilidades para trabalhos com o Spring. (Exemplo: Spring Boot).</p></div>

Site: [STS](https://spring.io/tools)

### Java

<div style="text-align: right"><p>Java é uma linguagem de programação orientada a objetos desenvolvida na década de 90 pela Sun Microsystems e adquirida posteriormente, em 2008, pela Oracle Corporation. Diferente das linguagens de programação compiladas para código nativo, Java é compilada para um bytecode que é interpretado por uma máquina virtual (Java Virtual Machine - JVM).</p></div>

Site: [Java](https://www.java.com/pt-BR/)

### MySql

<div style="text-align: justify">O MySQL é um sistema de gerenciamento de banco de dados (SGBD), que utiliza a linguagem SQL (Linguagem de Consulta Estruturada, do inglês Structured Query Language) como interface. É atualmente um dos sistemas de gerenciamento de bancos de dados mais populares da Oracle Corporation.</div>

Site: [MySql](https://www.mysql.com/)

### Git

<div style="text-align: justify">Git é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo.</div>

Site: [Git](https://git-scm.com/)

### Node.js

<div style="text-align: justify">Node.js é um software de código aberto, multiplataforma, baseado no interpretador V8 do Google e que permite a execução de códigos JavaScript fora de um navegador web.</div>

Site: [Node.js](https://nodejs.org/en/)

### Postman

<div style="text-align: justify">O Postman é um API Client que facilita aos desenvolvedores criar, compartilhar, testar e documentar APIs. Isso é feito, permitindo aos usuários criar e salvar solicitações HTTP e HTTPs simples e complexas, bem como ler suas respostas.</div>

Site: [Postman](https://www.postman.com/)

### Httpie

<div style="text-align: justify">HTTPie é um cliente HTTP de linha de comando com uma interface de usuário intuitiva, suporte a JSON, destaque de sintaxe, downloads semelhantes a wget, plug-ins etc. Seu objetivo é tornar a interação da CLI com os serviços da Web o mais amigável possível. Ele fornece um comando http simples que permite o envio de solicitações HTTP arbitrárias usando uma sintaxe simples e natural e exibe saída colorida. O HTTPie pode ser usado para teste, depuração e interação geral com servidores HTTP.</div>

Site [httpie](https://httpie.io/)

---

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
