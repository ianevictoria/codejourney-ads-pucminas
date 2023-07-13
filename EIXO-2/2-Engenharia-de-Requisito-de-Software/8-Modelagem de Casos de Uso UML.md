MODELAGEM DE CASOS DE USO UML
 
O objetivo desta sessão de estudos é apresentar o diagrama de caso de uso UML. Este diagrama é utilizado na Modelagem dos Requisitos Funcionais do sistema.

Ao final desta seção, você será capaz de identificar:

Atores
Casos de Uso
Tipos de Ligações entre Atores e Casos de Uso. 

NESTA SESSÃO
O diagrama de caso de uso é um dos mais importantes diagramas da UML. Ele é muito usado na modelagem de requisitos, pois possui uma notação fácil que auxilia o diálogo com os usuários.

O diagrama de caso de uso é usualmente o primeiro diagrama UML utilizado na fase de requisitos, sendo um diagrama de alto nível de abstração utilizado nas reuniões de levantamento com os usuários. O diagrama de caso de uso permite detalhar os Requisitos Funcionais identificados na etapa de elicitação. Não se utiliza diagramas de caso de uso para requisitos não-funcionais.

O diagrama de caso de uso também pode servir como um contrato entre as partes, pois ele delimita o escopo do sistema, isto é, o que está dentro do sistema e o que está fora do sistema, que são as interfaces do sistema que você está desenvolvendo com outros sistemas.

O diagrama de caso de uso tem 3 elementos principais: Atores, Casos de Uso e Relacionamentos. Os relacionamentos podem ser entre atores e caso de uso, ou entre caso de uso e caso de uso ou ainda entre atores e atores.

O ator representa aquelas entidades que interagem com o sistema. São exemplos de atores os usuários, clientes, funcionários, alunos, empresas, órgãos do Governo ou outros tipos de pessoas que se relacionam com o sistema. Atores também podem ser sensores ou outros sistemas, tais como sistema de contabilidade, sistema de RH.

 É importante lembrar que o próprio sistema não deve ser ator se você estiver modelando este sistema.

Já o caso de uso é uma transação realizada pelo sistema para atender a uma solicitação de um ator. Um Diagrama de Caso de uso vai conter vários casos de uso.

É importante lembrar que o diagrama de caso de uso não tem a ideia de sequência. Portanto, a ordem em que os eventos ocorrem não é indicada.

No vídeo a seguir, vamos falar sobre modelagem de casos de uso UML.

[MODELAGEM DE CASOS DE USO UML - PARTE 1]()

Os relacionamentos podem ser de Associação, Generalização, Inclusão e Extensão.

O relacionamento de Associação é o relacionamento mais comum representado por uma seta que liga atores a casos de uso. Esta seta com a ponta aberta não pode ser usada para ligar ator com ator nem caso de uso com caso de uso. Você pode também ligar atores com casos de uso simplesmente com uma reta, pois a UML também permite isso. No entanto, preferimos sempre usar a seta para ser mais legível na indicação do fluxo de informação.

O ator que inicia a ação do caso de uso é chamado Ator Primário. O ator que é afetado pela ação é chamado Ator Secundário. Um caso de uso pode ter zero ou vários atores secundários.

O relacionamento de Herança pode acontecer entre elementos iguais, ou seja, entre ator e ator e também entre caso de uso e caso de uso, mas é mais comum entre ator e ator. A Generalização ocorre quando um elemento herda o comportamento do pai.

Para diferenciar da Associação, a seta é com ponta fechada na Generalização sempre no sentido do filho para o pai. Podemos ter Generalização entre casos de uso quando um caso de uso herda comportamentos de outro caso de uso.

O relacionamento de Inclusão, também chamado de Include que só ocorre entre casos de uso. Ele é muito usado quando temos rotinas comuns entre as várias transações do sistema. Ele é representado por uma seta pontilhada escrita include do caso de uso que o ativa para a rotina geral.

O relacionamento de Extensão é representado por uma seta pontilhada, mas com o estereótipo extend. Ele é usado para tratar exceções, casos especiais. Ao contrário do include que tem ativação obrigatória, no extend, a ativação é opcional.

No vídeo a seguir, vamos continuar a falar sobre os componentes do diagrama de caso de uso.

[MODELAGEM DE CASOS DE USO UML - PARTE 2]()

REFLEXÃO

Por que é interessante ter vários casos de uso com include no Diagrama de Casos de Uso? 

 
MATERIAL COMPLEMENTAR

Conheça mais sobre o diagrama de use-case UML e como desenhá-lo em uma ferramenta assistindo o seguinte vídeo:

[All About Use Case Diagrams - What is a Use Case Diagram, Use Case Diagram Tutorial, and More (legendas disponíveis)](https://youtu.be/Omp4RbHbB0s)

ATIVIDADE

Marque a alternativa FALSA sobre o Diagrama de Caso de Uso da UML.

O diagrama de caso de uso detalha a ordem em que os eventos serão realizados.

Idealmente, o diagrama de caso de uso deve ser o primeiro dos diagramas da UML a ser construído.

O diagrama de caso de uso auxilia no detalhamento dos requisitos funcionais do sistema.

A execução de um caso de uso incluído (<<include>>) é obrigatória.

Resposta correta.
O diagrama de caso de uso detalha a ordem em que os eventos serão realizados.

Resposta correta. A afirmativa é falsa, pois o diagrama de caso de uso não especifica a ordem em que os eventos ocorrem.
