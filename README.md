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


**Instalação via terminal Ubuntu 20.04.3 LTS:**

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

**Versão Instalada:** sts-4.13.0.RELEASE.

---
### Java

Java é uma linguagem de programação orientada a objetos desenvolvida na década de 90 pela Sun Microsystems e adquirida posteriormente, em 2008, pela Oracle Corporation. Diferente das linguagens de programação compiladas para código nativo, Java é compilada para um bytecode que é interpretado por uma máquina virtual (Java Virtual Machine - JVM).

Site: [Java](https://www.java.com/pt-BR/)

**Instalação via terminal Ubuntu 20.04.3 LTS:**

- Digite **Ctrl + Alt + T** para abrir o terminal;
- Após, digite o seguinte comando para iniciar a instalação:
```
sudo apt-get install openjdk-11-jdk
```

**Versão Instalada:**
- openjdk 11.0.13 2021-10-19;
- OpenJDK Runtime Environment (build 11.0.13+8-Ubuntu-0ubuntu1.20.04);
- OpenJDK 64-Bit Server VM (build 11.0.13+8-Ubuntu-0ubuntu1.20.04, mixed mode, sharing).

---
### MySql

O MySQL é um sistema de gerenciamento de banco de dados (SGBD), que utiliza a linguagem SQL (Linguagem de Consulta Estruturada, do inglês Structured Query Language) como interface. É atualmente um dos sistemas de gerenciamento de bancos de dados mais populares da Oracle Corporation.</div>

Site: [MySql](https://www.mysql.com/)

**Instalação via terminal Ubuntu 20.04.3 LTS:**

- Digite **Ctrl + Alt + T** para abrir o terminal;
- Após, digite o seguinte comando para iniciar a instalação:
```
sudo apt install mysql-server
```

**Versão instalada:** mysql  Ver 8.0.27-0ubuntu0.20.04.1 for Linux on x86_64 ((Ubuntu)).

---
### Git

<div style="text-align: justify">Git é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo.

Site: [Git](https://git-scm.com/)

**Instalação via terminal Ubuntu 20.04.3 LTS:**

- Digite **Ctrl + Alt + T** para abrir o terminal;
- Após, digite o seguinte comando para iniciar a instalação:
```
sudo apt install git
```

**Versão instalada:** git version 2.25.1.

---
### Node.js

Node.js é um software de código aberto, multiplataforma, baseado no interpretador V8 do Google e que permite a execução de códigos JavaScript fora de um navegador web.

Site: [Node.js](https://nodejs.org/en/)

**Instalação via terminal Ubuntu 20.04.3 LTS:**

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

**Versão instalada:** v10.19.0

---
### Postman

O Postman é um API Client que facilita aos desenvolvedores criar, compartilhar, testar e documentar APIs. Isso é feito, permitindo aos usuários criar e salvar solicitações HTTP e HTTPs simples e complexas, bem como ler suas respostas.

Site: [Postman](https://www.postman.com/)

**Instalação via terminal Ubuntu 20.04.3 LTS:**

- Digite **Ctrl + Alt + T** para abrir o terminal;
- Após, digite o seguinte comando para iniciar a instalação:
```
sudo snap install postman
```

**Versão instalada:** Version 9.8.2

---
### Httpie

HTTPie é um cliente HTTP de linha de comando com uma interface de usuário intuitiva, suporte a JSON, destaque de sintaxe, downloads semelhantes a wget, plug-ins etc. Seu objetivo é tornar a interação da CLI com os serviços da Web o mais amigável possível. Ele fornece um comando http simples que permite o envio de solicitações HTTP arbitrárias usando uma sintaxe simples e natural e exibe saída colorida. O HTTPie pode ser usado para teste, depuração e interação geral com servidores HTTP.

Site [httpie](https://httpie.io/)

**Instalação via terminal Ubuntu 20.04.3 LTS:**

- Digite **Ctrl + Alt + T** para abrir o terminal;
- Após, digite o seguinte comando para iniciar a instalação:
```
sudo snap install httpie
```

**Versão instalada:** httpie 2.6.0

---
