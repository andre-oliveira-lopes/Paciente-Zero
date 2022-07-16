# Paciente-Zero
 Primeiro Teste de Versionamento de iniciante.

 Estou aprendendo a usar o Git e GitHub. 

As 4 liberdades básicas associadas ao software livre são:

        * A liberdade de executar o programa, para qualquer propósito 
        (liberdade nº 0).

        * A liberdade de estudar como o programa funciona, e adaptá-lo para as suas necessidades 
        (liberdade nº 1). 
        Acesso ao código-fonte é um pré-requisito para esta liberdade.

        * A liberdade de redistribuir cópias de modo que você possa ajudar ao seu próximo 
        (liberdade nº 2).

        * A liberdade de aperfeiçoar o programa, e liberar os seus aperfeiçoamentos, de modo que 
        toda a comunidade se beneficie 
        (liberdade nº 3). 
        Acesso ao código-fonte é um pré-requisito para esta liberdade. 

*Desafios de usar o VS Code*
 __________________________________________

**Aula 1 - Historia do VS Code**

Para que serve o GitHub?
Um repositório publico para programas 

	
O que é Git? 
	• Git = Software de controle de versão (VCS), ou seja, uma maquina do tempo.
	• versionamento de software e código. (versões)
	• muitas versões de uma mesma coisa. 
		
		Ex:  Quero que você crie um site pra mim pra apresentar meu produto.
		Vou lá, abrir meu editor de texto de preferencia. 
		
			֎ VS Code
			֎ Sublime
			֎ Notepad++
			֎ VIM
			
		Escrevi meu código HTML, e a primeira coisa é criar uma pasta HTML
		(Site-cliente) para organizar os arquivos de áudio, vídeo, texto e
		código html.
		Geralmente quando é identificado que está tudo certo com o programa 
		de teste 1.0
		O que você faz?
		Cria uma copia compactada em .zip para então começar o 2.0 e assim vai.
	
	Em 1972, o primeiro software de versionamento era Software de controle de 	
        versão centralizado ou linear. Com o avanço do tempo veio um mais moderno 	
        chamado de VCS distribuído, onde você tem varias pessoas trbalhando e 		
        mandando para um repositório local sem a necessidade de internet ou 	
        processamento de um servidor, mudando de repositório central para um
	repositório remoto, onde ao chegar em um break Ponit (ponto de meta), 
	você vai além do Commit, você vai jogar no repositório com um push.  
	você joga as versões do seu projetos. OBS: O Git é um VCS Distribuído.
	  
	O Git é seu repositório local, na sua maquina, então toda vez que você der
	um commit ele vai salvar a diferença de um arquivo para o outro. 
	
	Principais Vantagens:
		♦ Controle de Histórico = Você pode ver o código antes de qual 				
                quer modificação, controlar melhor, quem fez qual alteração no código 
		♦ Trabalho em equipe
		♦ Ramificação do projeto = Faz o coração do sistema, site ou projeto, 		
                ou seja, cada um vai ter seu ramo, seja ele designer, front-end e back-		
                -end. Depois eu vou juntar todas essas ramificações com um (Must) e 			
                fazer um (máster) que é o projeto principal. 
		♦ Segurança = Você só pode modificar aquela ramificação a qual vc 			
                pertence, sem modifica as dos outros.  
		♦ Otimização = Se você apagar algo enganado, você pode voltar em um 			
                Commit anterior e pegar o que foi apagado por engano, economizando 			
                trabalho. 
			
		
GitHub = Plataforma de Rede Social para Programadores e Desenvolvedores. 

	• O GitHub é meu repositório remoto
	• O GitHub é uma plataforma social para programadores
	• Você consegue subir código, colaborar e testar o código dos outros
	
		Ex:  Quero guardar os versionamentos do meu código para apresentar 			
                no meu perfil do GitHub.
		Vou lá, abrir meu repositor de código de preferencia. 
		
			֎ GitHub
			֎ GitLab
			֎ Bitbucket
			֎ Gogs 
			֎ Kallithea

		kkkkkkkkkkkkkkkkkk
	Principais Vantagens:	
		♦ Repositório = uma pasta que você coloca um projeto divulgado. há dois 		
                tipos: repositórios públicos e privados. Onde em cada um deles você 			
                pode fazer quantos projetos você quiser. Só tem um porém, para projetos 		
                privados você pode ter até 3 colaboradores.
		♦ Hospedagem de código-fonte = Ele vai guardar o código de programação 		
                de qualquer linguagem. 
		♦ Características de Redes Social: Você vai conhecer pessoas e projetos 		
                novos, você vai aprender com outros repositórios. 
		♦ GitHub Pages integrado: Ele vai deixar você hospedar html, css e 			
                javascript de forma básica pra hospedar um site utilizando meu 				
                repositório publico.
		♦ Colaboração: Você tem os projetos, os pacotes, você segue as pessoas. 
		♦ Forks: Você pode editar projetos de outra pessoas por conta própria 		
                contanto que você obedeça as licenças. 

Links:
---
Tipos de Octocat em desenhos
*https://octodex.github.com*

Empresas de tecnologias importantes
*https://www.forbes.com/cloud100/#4d8aa9c05f94*

Livros sobre GitHub recomendados 
*https://www.amazon.com.br/Pro-Git-Scott-Chacon/dp/1484200772*
---

**Aula 2 - Primiera execução no VS Code**

    /* Programa VS Code instalado */
    /* O programa minGW instalado + Configuração de Variavel de ambiente */
    /* Duas extenções: C/C++ e C/C++ Compile Run */

    *** Primeiro Erro - Terminal integrado padrão do VS Code
    *** Solução: Coloquei por padrão o "Promtp de comando" no VS code. 
    Fui na aba Ver > Terminal > Lauch Profile > Selecione o perfil padrão > Command Promtp.  

    /// Pelo que eu entendi o VS code tem varios terminais que eu posso escolher pra executar meus programas
    /// Tem o "Promtp de comando"; O "PowerShell" e o "Git Bast" do Git. 
    /// Fonte: https://www.alura.com.br/artigos/como-utilizar-terminal-integrado-visual-studio-code


**Aula 3 - Termos em Git e GitHub**

    **Repositório Central** 
    Quando você pega uma pasta, monitora ela e manda pra um repositório central, Nós fizemos um commit.
		    
    **Push** 
    Pegar o versionamento que esta na sua maquina e jogar no repositório. 

    **Issues** 
    São Problemas que você descobriu, mas não sabe como resolver.

    **Pull Requests** 
    Você viu um problema no software e cria uma fork, depois criar uma ramificação desse projeto e 
    concertar esse trabalho e então enviar sua solução para um desenvolvedor. Talvez você virar um 
    colaborar desse projeto, e pode colocar no seu curriculo. 

    **Branches ou ramificações**
    Um galho que vc pode criar uma incrementação auxiliar para não prejudicar a branch (galho) principal 
    do sistema. Utilizando vários multiversos pra você testar suas ideias. 

    **Branch máster**
    O ramo principal de produção, é o ramo final é minha versão corrente. Vantagem, com o software já 
    desenvolvido imagine que alguém abril uma Isseus relatando um problema, então você criar uma 
    ramificação pra resolver esse problema e depois commitar. 
    OBS: evite commitar tudo na sua Branch máster, e sim criar ramos. 

    **Merge**
    É utilizada para juntar varias branches testadas e aprovadas e joga-las 
    na ramificação do galho principal. 


**Aula 4 - Descobrindo o README.md é na verdade uma linguagem de marcação**

    /// A linguagem de Marcação Markdown que tem a terminação .md na verdade é uma irmã da HTML feita 
    com o objetivo de ser uma linguem de facil leitura e de fácil conversão para HTML. Vvamos agora 
    aprender a usar algumas guias (marcas) do Markdown, mas antes de tudo, onde eu posso usá-las? 
        /// README.md ; Issues ; Pull Requests. 

                                        **Marcações Simples**

    **NEGRITO** 
    Assim fazemos um negrito na linguagem de Marcação Markdown.

    *ITÁLICO*
    Assim fazemos um itálico na linguagem de Marcação Markdown.
 
    **NEGRITO** ou __NEGRITO__ 
    Assim fazemos um negrito na linguagem de Marcação Markdown. 

    *ITÁLICO* ou _ITÁLICO_
    Assim fazemos um itálico na linguagem de Marcação Markdown.
    
    ~~Texto Riscado~~
    Assim fazemos um Texto Riscado na linguagem de Marcação Markdown.
    
    # Título 
    Assim fazemos um Título do tipo 1 na linguagem de Marcação Markdown. 
    
    ## Título 
    Assim fazemos um Título do tipo 2 na linguagem de Marcação Markdown.
    
    ### Título 
    Assim fazemos um Título do tipo 3 na linguagem de Marcação Markdown. 
    
    --- ou ***
    Assim fazemos uma linha horizontal na linguagem de Marcação Markdown.
        
    1. Linhas numeradas
    Assim fazemos Linhas numeradas na linguagem de Marcação Markdown.
    
       1. Sublinhas em Romano
    Assim com 3 espaços fazemos Sublinhas em Romano na linguagem de 
    Marcação Markdown.
    
    * Lista demarcada
    Assim fazemos Listas demarcadas na linguagem de Marcação Markdown.
    
       * Sublistas Demarcadas
    
    Assim com 3 espaços fazemos Listas demarcadas na linguagem de 
    Marcação Markdown.
    
    -[x] Lista de Tarefas marcadas
    Assim fazemos Listas de Tarefas marcadas na linguagem de Marcação Markdown.
    
    Fazer upload de imagem 
    É arrastando para o comentário do GitHub, uma imagem de preferência pequena
    tipo uns 500 pixels e PNG ou JPG. O comentário que estiver dentro de [] é
    o nome da imagem. para fazer links, após o [] abra o () e digite o link. 
    
    | Como fazer Tabela |
    Assim fazemos uma Tabela na linguagem de Marcação Markdown.
    
    Num | Nome | Nota
    ---|---|---
    1 | Gustavo |8,5
    2 | José |10,0
    3 | Maria |9,0 
    
    'comando'
    Assim fazemos como especificar um comando no texto, destacando ele com outra
    letra e um fundo cinza.
    
    '''
    Texto entre 3 crases
    '''
    Assim vamos ter como especificar um comando de código no texto, destacando 
    uma parte do texto do comando em fundo cinza.
    
    :vul
    Como por emoji com os textos, tem um repositório dessa garota que tem todos
    os github.com/ikatyang.
    
    > responde a mensagem de alguém 
    Assim fazemos uma menção a uma resposta de alguém na linguagem de Marcação
    Markdown. 
    
    @pessoa
    Assim fazemos uma menção a uma pessoa na linguagem de Marcação Markdown.
    
     						**Marcações Compostas**
    				
    __*NEGRITO e ITÁLICO*__
    Assim fazemos um negrito e itálico na linguagem de Marcação Markdown.
