<p align="center"><img src="assets/LogoOkakua.webp" alt="Okakua — Biblioteca escolar, acervo e empréstimo gratuito" width="560"></p>

# Okakua — Biblioteca portátil

O Okakua é um sistema portátil para catalogação de livros, cadastro de pessoas e controle de empréstimos. O aplicativo é um HTML independente e guarda os dados em um arquivo JSON escolhido pelo usuário no pendrive.

## História do nome e da marca

Okakua foi pensado para representar **“A Casa do Saber”**. Na narrativa da marca, *Oka* remete a casa e acolhimento, e *Kua* a saber e conhecer. A ideia é fazer da biblioteca um espaço próximo da comunidade, onde o conhecimento está ao alcance de todos.

O símbolo reúne uma casa e um livro aberto: o livro é a base do aprendizado; o broto representa ideias que crescem. O verde remete à natureza e à esperança, o terracota ao acolhimento e à comunidade, e o dourado à inspiração.

## Capturas de tela

### Login

![Tela de login do Okakua](docs/screenshots/Okakua_Tela_Login.png)

### Início e alertas de devolução

![Tela inicial do Okakua com alertas e visão geral](docs/screenshots/Okakua_Tela_inicio.png)

### Acervo

![Catálogo do acervo e opções de importação e exportação](docs/screenshots/Okakua_Tela_Acervo.png)

### Pessoas

![Cadastro de pessoas](docs/screenshots/Okakua_Tela_Pessoas.png)

### Empréstimos

![Controle de empréstimos e devoluções](docs/screenshots/Okakua_Tela_Emprestimos.png)

### Configurações

![Identidade visual, arquivo de dados e usuários](docs/screenshots/Okakua_Tela_Configuracoes.png)

## Versões incluídas

- **Windows:** entre em `Windows` e execute `Instalar_Okakua.bat`. O instalador copia o aplicativo para o pendrive e cria um atalho na Área de Trabalho que aponta para os arquivos do próprio pendrive.
- **Linux:** entre em `Linux` e execute `bash Instalar_Okakua_Linux.sh`. O instalador cria as pastas no pendrive e um atalho para o aplicativo.
- **ChromeOS:** entre em `ChromeOS`, copie os arquivos para o pendrive pelo app Arquivos e abra `Okakua.html` no Chrome. O ChromeOS não executa os instaladores de desktop do Windows ou Linux.

## Primeiro acesso

Na tela de acesso, selecione **Abrir dados do pendrive** e escolha `Dados/Okakua_Dados.json`. O usuário inicial é `okakua`, com senha temporária `Admin#2026`; o sistema exige a troca no primeiro acesso. Selecione o arquivo de dados em cada nova sessão para manter as alterações no pendrive.

## Código-fonte

- `Aplicativo/BibliotecaPortatil.html` é o código principal: HTML, CSS, JavaScript e logo incorporado.
- `assets/Okakua_Logo.png` é o logo em PNG.
- `Windows/` contém o instalador Windows e uma cópia do aplicativo para distribuição.
- `Linux/` contém o instalador Linux e uma cópia do aplicativo para distribuição.
- `ChromeOS/` contém o pacote pronto para copiar ao pendrive.

Os instaladores não sobrescrevem um arquivo de dados JSON já existente no pendrive.

## Requisitos

Windows, Linux ou ChromeOS com Microsoft Edge, Google Chrome ou Chromium compatível. Alguns recursos de arquivos locais dependem das permissões concedidas pelo navegador.

## Licença

A licença de distribuição ainda não foi definida.



