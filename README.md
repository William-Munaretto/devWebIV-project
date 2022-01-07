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

## Definição e procedimentos de instalação de cada tecnologia/ferramenta:


### Spring Tool Suite

O Spring Tool Suite é uma IDE baseada em Eclipse que dá algumas facilidades para trabalhos com o Spring. (Exemplo: Spring Boot).

Site: [STS](https://spring.io/tools)


**Instalação via terminal ubuntu:**

- Faça download da versão atualizada no site <https://spring.io/tools>;

<img src="../assets/Sts_download.png" width="400" height="400">

- Após, clique com o botão direito do mouse sobre a pasta que contem o arquivo e selecione **"Abrir Terminal"**;

descompactar o arquivo:
```
sudo tar sxvf spring-tool-suite-4-4.13.0.RELEASE-e4.22.0-linux.gtk.x86_64.tar.g
``` 
acessar a pasta **sts-4.13.0.RELEASE**:
```
cd sts-4.13.0.RELEASE
```

executar o programa:
```
sudo ./SpringToolSuite4
```

---
### Java

Java é uma linguagem de programação orientada a objetos desenvolvida na década de 90 pela Sun Microsystems e adquirida posteriormente, em 2008, pela Oracle Corporation. Diferente das linguagens de programação compiladas para código nativo, Java é compilada para um bytecode que é interpretado por uma máquina virtual (Java Virtual Machine - JVM).

Site: [Java](https://www.java.com/pt-BR/)

**Instalação via terminal ubuntu:**

- Digite **Ctrl + Alt + T** para abrir o terminal;
- Após, digite o seguinte comando para iniciar a instalação:
```
sudo apt-get install openjdk-11-jdk
```

---
### MySql

O MySQL é um sistema de gerenciamento de banco de dados (SGBD), que utiliza a linguagem SQL (Linguagem de Consulta Estruturada, do inglês Structured Query Language) como interface. É atualmente um dos sistemas de gerenciamento de bancos de dados mais populares da Oracle Corporation.</div>

Site: [MySql](https://www.mysql.com/)

---
### Git

<div style="text-align: justify">Git é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo.

Site: [Git](https://git-scm.com/)

**Instalação via terminal ubuntu:**

- Digite **Ctrl + Alt + T** para abrir o terminal;
- Após, digite o seguinte comando para iniciar a instalação:
```
sudo apt install git
```

---
### Node.js

Node.js é um software de código aberto, multiplataforma, baseado no interpretador V8 do Google e que permite a execução de códigos JavaScript fora de um navegador web.

Site: [Node.js](https://nodejs.org/en/)

**Instalação via terminal ubuntu:**

- faça download da versão atualizada no site <https://nodejs.org/en/>

<img src="../assets/node.png" width="400" height="400">

- Após, clique com o botão direito do mouse sobre a pasta que contem o arquivo e selecione **"Abrir Terminal"**;

Descompactar o arquivo:
```
sudo tar sxvf node-v16.13.1-linux-x64.tar.xz  
``` 
Acessar a pasta **node-v16.13.1-linux-x64**:
```
cd node-v16.13.1-linux-x64/
```
aAessar a pasta /bin, onde está o executável do node.js:
```
cd bin/
```
Executar o programa:
```
sudo ./node
```

---
### Postman

O Postman é um API Client que facilita aos desenvolvedores criar, compartilhar, testar e documentar APIs. Isso é feito, permitindo aos usuários criar e salvar solicitações HTTP e HTTPs simples e complexas, bem como ler suas respostas.

Site: [Postman](https://www.postman.com/)

**Instalação via terminal ubuntu:**


---
### Httpie

HTTPie é um cliente HTTP de linha de comando com uma interface de usuário intuitiva, suporte a JSON, destaque de sintaxe, downloads semelhantes a wget, plug-ins etc. Seu objetivo é tornar a interação da CLI com os serviços da Web o mais amigável possível. Ele fornece um comando http simples que permite o envio de solicitações HTTP arbitrárias usando uma sintaxe simples e natural e exibe saída colorida. O HTTPie pode ser usado para teste, depuração e interação geral com servidores HTTP.

Site [httpie](https://httpie.io/)

**Instalação via terminal ubuntu:**


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
