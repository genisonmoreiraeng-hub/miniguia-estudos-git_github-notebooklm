# Miniguia Estudos Git-Github Notebooklm

## 1. Contexto e Objetivos
- **Assunto:** Mini guia prático de estudos com Git e GitHub, utilizando o NotebookLM
- **Objetivo:** Construir um “segundo cérebro” de aprendizado utilizando Inteligência Artificial como suporte para organizar conhecimentos, resumir conteúdos, gerar insights e acelerar a evolução em Git e GitHub de forma prática e eficiente.

## 2. Curadoria de Fontes
Materiais que utilizei para alimentar o NotebookLM:
1. [GitHub Basics Made Easy: A Fast Beginner's Tutorial!](https://www.youtube.com/watch?v=Oaj3RBIoGFc)
2. [How to create your first GitHub repository: A beginner's guide | Tutorial](https://www.youtube.com/watch?v=-RZ03WHqkaY)
3. [Tutorial GitHub para Iniciantes | Como usar o GitHub 2026 Atualizado](https://www.youtube.com/watch?v=BUGZZaChiYw)
4. [Curso de Git e Github COMPLETO 2025 | Iniciantes + Desafios + Muita Prática](https://www.youtube.com/watch?v=kB5e-gTAl_s )
5. [Git e Github Tutorial completo - Introdução prática para iniciantes](https://www.youtube.com/watch?v=_hZf1teRFNg)
6. [Configurando seu perfil](https://docs.github.com/pt/get-started/start-your-journey/setting-up-your-profile)
7. [Carregando um projeto para GitHubl](https://docs.github.com/pt/get-started/start-your-journey/uploading-a-project-to-github)
   

## 3. Engenharia de Prompts e "Cicatrizes"

- **Prompt Utilizado:** "Gerar um tutorial para iniciantes, com palavras claras e objetivas"
- **Dificuldade Encontrada:** A IA gerou uma apresentação muito superficial, com explicações genéricas e poucos detalhes técnicos. O conteúdo aparentava ser voltado para usuários que já tinham familiaridade com Git e GitHub, dificultando sua utilização como material de estudo para iniciantes.
- **Como resolvi:** Gerar uma apresentação completa e didática, cobrindo desde a instalação das ferramentas necessárias até a criação do primeiro projeto utilizando Git e GitHub. O conteúdo deve ser estruturado de forma progressiva, permitindo que iniciantes compreendam cada etapa do processo sem a necessidade de conhecimento prévio.
>  Observação : Subi uma apresentação gerada com o ultimo prompt

## 4. Miniguia de Estudo
### Resumos
**1. O que são Git e GitHub?**

**Git:** Ferramenta que salva o histórico do seu código. Funciona como uma máquina do tempo, permitindo voltar para versões anteriores se algo der errado.  
**GitHub:** Plataforma online onde você guarda seus projetos na nuvem e pode compartilhar com outras pessoas.

**2. Configuração Inicial**

Antes de usar o Git, informe seu nome e e-mail:  
git config --global user.name "Seu Nome"  
git config --global user.email "seu@email.com"  

**3. Comandos Mais Importantes**

|Comando	| Função|
|--------|-------|
|git init|	Inicia um projeto Git|
|git status|	Mostra as alterações feitas|
|git add .|	Prepara os arquivos para salvar|
|git commit -m "mensagem"|	Salva uma nova versão|
|git push|	Envia para o GitHub|
|git pull|	Baixa atualizações do GitHub|

**4. Trabalho em Equipe**

**Branch:** Cria uma cópia do projeto para testar alterações sem afetar a versão principal.  
**Merge:** Junta as alterações da Branch ao projeto principal.  
**Pull Request (PR):** Pedido para alguém revisar seu código antes de aceitar as mudanças.  
**Fork:** Cópia de um projeto de outra pessoa para sua conta.  

### Glossário

- **Git**: É o sistema de controle de versão que funciona como o "motor" do seu projeto, tirando "fotos" (snapshots) do código para registrar o histórico.  

- **GitHub**: Uma plataforma online que funciona como a "garagem" ou nuvem onde você guarda e compartilha seus projetos.  

- **Repositório** (Repo): É a pasta digital onde vivem todos os arquivos do seu projeto e o histórico completo de mudanças.  

- **Commit**: Representa uma versão salva do seu código. É como um ponto de restauração com uma mensagem explicando o que foi feito.  

- **Add** (Staging Area): Uma área temporária onde você coloca os arquivos que deseja incluir na próxima "foto" ou commit.  

- **Push**: O comando usado para "empurrar" as alterações do seu computador local para o servidor remoto no GitHub.  

- **Pull**: O comando para "puxar" as atualizações que estão no GitHub para o seu computador, mantendo seu código em dia.  

- **Branch** : Um caminho paralelo no projeto que permite testar novas ideias sem estragar a versão principal que já funciona.  

- **Merge**: O ato de unir as alterações de uma Branch de volta para outra (geralmente para a principal, chamada de Main). 

- **Clone**: Cria uma cópia exata de um projeto que está na internet (GitHub) para dentro do seu computador.  

- **Pull Request** : Um pedido formal para que suas alterações sejam revisadas por outras pessoas antes de serem integradas ao projeto principal.  

- **Gitignore**: Um arquivo de texto onde você lista tudo o que o Git deve ignorar, como senhas ou arquivos pessoais.  

- **README**: O arquivo de instruções que explica para que serve o seu projeto e como as pessoas devem usá-lo.  

- **Fork**: É quando você faz uma cópia de um projeto de outra pessoa para a sua própria conta do GitHub para poder modificá-lo livremente.  

- **SSH**: Uma "chave mágica" ou crachá digital de segurança que permite conectar seu computador ao GitHub sem precisar digitar senha toda hora.  

### Prompts Reutilizáveis
"Atue como um professor especialista em Git e GitHub, com experiência em ensinar iniciantes.  
Crie uma apresentação completa e detalhada sobre Git e GitHub, começando desde a instalação das ferramentas até a criação e publicação do primeiro projeto.  
Objetivos da apresentação:  
Ensinar Git e GitHub para pessoas sem qualquer conhecimento prévio.  
Utilizar uma linguagem simples, clara e didática, adequada para uma criança de 12 anos.  
Explicar todos os conceitos passo a passo, evitando assumir conhecimentos anteriores.  
Incluir exemplos práticos em cada etapa.  
Estrutura desejada:  
O que é Git?  
O que é GitHub?  
Diferença entre Git e GitHub.  
Por que desenvolvedores utilizam essas ferramentas?  
Instalação do Git no Windows.  
Configuração inicial do Git.  
Conceitos fundamentais:  
Repositório  
Commit  
Branch  
Merge  
Clone  
Push  
Pull  
Criando o primeiro repositório local.  
Criando o primeiro arquivo do projeto.  
Realizando o primeiro commit.  
Criando uma conta no GitHub.  
Criando um repositório remoto.  
Conectando o projeto local ao GitHub.  
Enviando o projeto para o GitHub.  
Atualizando arquivos e enviando novas versões.  
Projeto prático completo do início ao fim.  
Principais erros de iniciantes e como evitá-los.  
Resumo final dos conceitos aprendidos.  
Requisitos visuais:  
Utilize imagens, diagramas, fluxogramas e ilustrações para explicar os conceitos.  
Sempre que possível, represente visualmente o fluxo de trabalho do Git.  
Sugira imagens que ajudem a fixar o conteúdo.  
Requisitos pedagógicos:  
Explique cada termo técnico de forma simples.  
Use analogias do dia a dia para facilitar o entendimento.  
Inclua exemplos reais e exercícios rápidos de fixação.  
Gere um conteúdo aprofundado, evitando explicações genéricas ou superficiais.  
O resultado deve ser uma apresentação completa, organizada por slides, com títulos, subtítulos, conteúdo, sugestões de imagens e notas explicativas para cada slide."  
