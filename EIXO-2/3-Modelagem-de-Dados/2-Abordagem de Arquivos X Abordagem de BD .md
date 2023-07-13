ABORDAGEM DE ARQUIVOS X ABORDAGEM DE BD
 
Vamos abordar os problemas do enfoque tradicional do armazenamento em arquivos que motivaram o surgimento da abordagem integrada de Banco de Dados com inúmeras vantagens. Você vai entender também a diferença entre BD (Banco de Dados) e SGBD (Sistema Gerenciador de Banco de Dados).

Ao final dessa sessão, você deverá:

Identificar as diferenças entre a abordagem centrada em arquivos e a abordagem de BD.
Entender o que é um BD e o que é um SGBD. 
NESTA SESSÃO
Um banco de dados (BD) ou base de dados é uma coleção de dados relacionados (ELMASRI & NAVATHE, 2010). Pode ser entendido também como um conjunto de dados integrados que tem por objetivo atender a uma comunidade de usuários. (HEUSER, 2001). Portanto, quando modelamos um banco de dados, devemos ter em mente em primeiro lugar quem vai usar esse BD e porque precisa usá-lo.

Já o SGBD (Sistema Gerenciador de BD) é um “software que incorpora as funções de definição, recuperação e alteração de dados em um banco de dados.” (HEUSER, 2001). Apesar de na vida prática muita gente confundir os dois termos, quando falamos de BD, o foco está no conteúdo e nos tipos de dados que vão ser armazenados (ex.: dados de clientes, dados de paciente, dados de materiais em estoque). Quando usamos o termo SGBD, o foco está nas tecnologias em si (ex.: Oracle, MySQL, Microsoft SQL Server, IBM DB2, Firebird).

Antes do aparecimento dos primeiros SGBDs, a única opção possível para manipular dados era o enfoque de arquivos. Nesta abordagem, os arquivos eram projetados tendo em mente apenas a sua aplicação específica (ex.: arquivo de clientes do sistema de contas-correntes do banco, arquivo de alunos do sistema da biblioteca). Isso gerava uma série de problemas tais como:

Redundância de dados.
Inconsistência de dados.
Dificuldade de aproveitamento de dados em novas aplicações.
Dificuldade no acesso a dados.
Falta da visão de Administração de Dados.
Com o surgimento da tecnologia de BD, esses problemas ficaram mais fáceis de serem resolvidos desde que se tenha uma atuação da Administração de Dados para prover uma visão de dados compartilhados entre aplicações (ex.: mesma base de dados de clientes usadas pelos sistemas de contas-correntes, cartão de crédito, seguros e cobrança de um banco).

 

[ABORDAGEM DE ARQUIVOS X ABORDAGEM DE BD]()

 

📌 Para entender melhor a importância da tecnologia de BD, sugerimos a leitura do Capítulo 1 do seguinte livro digital (e-book) disponível na biblioteca da PUCMinasLinks to an external site. e que está na bibliografia básica deste Microfundamento:

ELMASRI, Ramez; NAVATHE, Shamkant B. Sistemas de banco de dados. 7.ed. São Paulo: Pearson, 2018.

📌 Acesse também a apresentação: Abordagem de Arquivos X Abordagem de BD Download Abordagem de Arquivos X Abordagem de BD.
 

 
REFLEXÃO

Mesmo com a tecnologia de BD estando bastante consolidada há décadas, porque muitas empresas ainda enfrentam problemas de inconsistência de dados, redundância de dados e baixa qualidade de dados em geral?

 
MATERIAL COMPLEMENTAR

Conheça mais sobre os tipos de SGBD: What is Database & SQL? https://www.youtube.com/watch?v=FR4QIeZaPeM
Aprenda mais sobre a história dos SGBDs: History of Databases https://www.youtube.com/watch?v=KG-mqHoXOXY

ATIVIDADE

Assinale a expressão que NÃO representa uma característica do enfoque convencional de arquivos.

Informações duplicadas, gerando inconsistências entre os dados.

Forte cultura de Administração de Dados (AD), permitindo um controle centralizado.

Dados em diferentes formatos (ex: Nome do cliente sendo alfanumérico de 30, 40 ou 50 posições dependendo do arquivo).

Falta de ferramentas amigáveis para elaborar consultas ao banco de dados.
//////////////////
Forte cultura de Administração de Dados (AD), permitindo um controle centralizado.
Resposta correta.
Resposta CORRETA. Cultura de AD é característica do enfoque de Banco de Dados, não sendo assim típico do enfoque de arquivos.
