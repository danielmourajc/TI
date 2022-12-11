color default					"	Define o tema/cor padrao
filetype indent on				"	Carregue o arquivo de recuo para o tipo de arquivo, se houver
filetype on						"	Detecte e defina a opção de tipo de arquivo e acione o evento FileType
filetype plugin on				"	Carregue o arquivo de plug in para o tipo de arquivo, se houver
set autoindent					"	Novas linhas herdam o recuo das linhas anteriores
set autoread					"	Atualize o vim após a atualização do arquivo de fora
set background=dark				"	Use cores que combinem com um fundo escuro.
set backspace=indent,eol,start	"	Permite retrocesso sobre recuo, quebras de linha e início de inserção.
set backupdir=~/.cache/vim		"	Diretório para armazenar os arquivos de backup.
set cmdheight=2					"	Dê mais espaço para exibir mensagens em baixo
set colorcolumn=80				"	Linha vertical na coluna determinada
set colorscheme wombat256mod	"	altera o esquema de cores.
set complete-=i					"	Limita os arquivos pesquisados para autocompletar.
set confirm						"	Exibe uma caixa de diálogo de confirmação ao fechar um arquivo não salvo.
set cursorline					"	Realça a linha atualmente sob o cursor.
set dir=~/.cache/vim			"	Diretório para armazenar arquivos de troca.
set display+=lastline			"	Sempre tente mostrar a última linha de um parágrafo.
set encoding=utf-8				"	Use uma codificação que suporte unicode.
set expandtab					"	Ao pressionar tab, insira 4 espaços
set filetype indent on			"	Habilite as regras de recuo que são específicas do tipo de arquivo.
set foldmethod=indent			"	Dobre com base nos níveis de recuo.
set foldnestmax=3				"	Dobre apenas até três níveis aninhados.
set formatoptions+=j			"	Excluir caracteres de comentário ao unir linhas.
set hidden						"	Oculta arquivos em segundo plano em vez de fechá-los.
set hidden						"	Esconde o buffer atual quando um novo arquivo é aberto
set history=1000				"	Aumenta o limite de desfazer.
set hlsearch					"	Habilita o realce de pesquisa.
set ignorecase					"	Ignora maiúsculas e minúsculas ao pesquisar.
set incsearch					"	Pesquisa incremental que mostra correspondências parciais.
set is hls ic scs				"	Pesquisa Marcada
set laststatus=2				"	Sempre exibe a barra de status.
set lazyredraw					"	Não atualiza a tela durante a execução de macros e scripts.
set linebreak					"	Evite quebrar uma linha no meio de uma palavra.
set mouse=a						"	Habilita o mouse para rolagem e redimensionamento.
set mouse=r						"	Ativar suporte a mouse
set nobackup					"	Nenhum arquivo de backup
set noerrorbells				"	Desativa o bipe em caso de erros.
set nofoldenable				"	Desativa a dobra por padrão.
set nomodeline					"	Ignora as linhas de modo do arquivo; use as configurações do vimrc em vez disso.
set noswapfile					"	Desabilite os arquivos de troca.
set nowritebackup				"	Nenhum arquivo de backup
set nrformats-=octal			"	Interpreta octal como decimal ao incrementar números.
set nu							"	Ativar números de linha
set number						"	Mostra os números das linhas na barra lateral.
set relativenumber				"	Mostra o número da linha na linha atual e os números relativos em todas as outras linhas.
set rule						"	Sempre mostra a posição do cursor.
set scrolloff=1					"	O número de linhas da tela a serem mantidas acima e abaixo do cursor.
set scrolloff=8					"	Número mínimo de linhas a manter acima e abaixo do cursor
set shell						"	O shell usado para executar comandos.
set shiftround					"	Ao deslocar linhas, arredonde o recuo para o múltiplo mais próximo de “shiftwidth”.
set shiftwidth=4				"	Ao deslocar, recue usando quatro espaços.
set shiftwidth=4				"	Ao recuar com '>', use 4 espaços de largura
set sidescrolloff=5				"	O número de colunas da tela a serem mantidas à esquerda e à direita do cursor.
set signcolumn=yes				"	Adicione uma coluna à esquerda. Útil para linting
set smartcase					"	Alterna automaticamente a pesquisa para diferenciar maiúsculas de minúsculas
set smartindent					"	Insere automaticamente um nível extra de recuo em alguns casos
set smarttab					"	inserir tabulações no início de uma linha de acordo com a largura do deslocamento
set softtabstop=4				"	Mostrar guia existente com 4 espaços de largura
set spell						"	habilita a verificação ortográfica.
set splitbelow					"	Crie as divisões horizontais abaixo
set splitright					"	Crie as divisões verticais à direita
set tabpagemax=50				"	Número máximo de páginas de guia que podem ser abertas a partir da linha de comando.
set tabstop=4					"	Mostrar guia existente com 4 espaços de largura
set title						"	Defina o título da janela, refletindo o arquivo que está sendo editado.
set updatetime=100				"	Tempo em milissegundos para considerar as mudanças
set visualbell					"	Pisca a tela em vez de apitar sobre erros.
set wildignore+= .pyc, .swp		"	Ignora arquivos que correspondem a esses padrões ao abrir arquivos com base em um padrão glob.
set wildmenu					"	Exibe as opções completas da guia da linha de comando como um menu.
set wrap						"	habilita a quebra de linha.
sintaxe enable					"	Ativa o realce de sintaxe.
syntax on						"	Ativa destaque de sintaxe
