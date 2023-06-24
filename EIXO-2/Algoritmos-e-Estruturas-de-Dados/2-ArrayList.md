[![Typing Animation](https://readme-typing-svg.herokuapp.com?color=DBB6EEFF&size=28&duration=7200&center=true&vCenter=true&width=1000&lines=UNIDADE+1;+Tema+2;ArrayList;)](https://git.io/typing-svg)


Esta sessão de estudos apresenta a Collection [ArrayListLinks](https://learn.microsoft.com/pt-br/dotnet/api/system.collections.arraylist?view=net-5.0) do C#. No final desta sessão, você deverá:

- Criar programas usando a referida classe, seus métodos e propriedades.

Esta sessão apresenta a classe ArrayList em C#. Ela é uma implementação da estrutura de dados lista em que podemos inserir/remover elementos em qualquer posição de nossa estrutura. 

O vídeo abaixo apresenta a referida classe:

[ArrayList - Video Aula]()

Veja o conjunto de slides utilizado nesse vídeo:

[ArrayList - PDF]()

<h3> 📚 Exercício</h3>

Agora, faça o exercício solicitado no qual você deve fazer um programa que usa todos os métodos mostrados para ArrayList. A resposta desse exercício será diferente para cada aluno. O importante é utilizar os métodos apresentados.

<img src="https://media.giphy.com/media/WMRb9p6N4mtIRtE2zr/giphy.gif" width="200">

Abaixo você encontrará 3 Exercícios Resolvidos:

No primeiro gabarito é interessante observar que o ArrayList não é fortemente tipado uma vez que um mesmo ArrayList pode conter elementos de tipos diferentes. 

Veja o gabarito do exercício resolvido 1. 

[ArrayList ER3 V1 int - Gabarito](https://replit.com/@maxdovalmachado/ExercicioResolvido03)

O vídeo abaixo mostra a explicação do gabarito 1 proposto.

[ArrayList ER3 V1 int - Explicação]()

A segunda opção de gabarito seria considerar apenas elementos do tipo string.

Veja o gabarito do exercício resolvido 2.

[ArrayList ER3 V2 string - Gabarito](https://replit.com/@maxdovalmachado/ExercicioResolvido03-V2-ComString)

O vídeo abaixo mostra a explicação do gabarito 2 proposto contendo um ArrayList de strings: 

[ArrayList ER3 V2 string - Explicação]()

A terceira possibilidade de resposta seria se tivéssemos um ArrayList de Alunos. Nesse caso, implementamos uma classe Aluno e, em seguida, nosso ArrayList de Alunos. 

Veja o gabarito do exercício resolvido 3.

[ArrayList ER3 V3 Aluno - Gabarito](https://replit.com/@maxdovalmachado/ExercicioResolvido03-V3-ComAluno)

Abaixo, temos 2 vídeos: um discutindo o conceito de referências em C#:

[Referência em C# -Video Aula]()

E outro, explicando o terceiro gabarito proposto para o Exercício Resolvido 3:

[ArrayList ER3 V3 Aluno - Explicação]()

O gabarito da terceira solução não apresentou os métodos Sort e BinarySearch, pois tais métodos dependem da definição de uma chave de pesquisa. Por exemplo, dado um ArrayList de alunos, precisamos definir qual será o atributo que o Sort ordenará os elementos: nome, matrícula ou e-mail. Da mesma forma, recebido um objeto do tipo aluno, precisamos definir qual dos atributos será usado pelo método de BinarySearch. Efetuamos essa definição criando uma classe de comparação que herda de IComparer e que possui um método int Compare. 

Veja o código apresentado, o mesmo utiliza os métodos Sort e BinarySearch com o ArrayList de alunos: 

[ArrayList ER3 V4 AlunoSort e PB - Gabarito](https://replit.com/@maxdovalmachado/ExercicioResolvido03-V3-ComAlunoSortBinarySearch)

O vídeo abaixo explica o último código:

[ArrayList ER3 V4 AlunoSort e PB - Explicação]()

---

<h3> 📚 EXERCÍCIO DE FIXAÇÃO</h3>

A seguir, temos uma bateria de exercícios e gabaritos envolvendo ArrayList.

1 - A maioria dos sistemas computacionais que você terá a oportunidade de desenvolver ou trabalhar em sua vida profissional terá um cadastro de elementos. Em outras palavras, uma lista contendo as operações de inserir, ler, atualizar e apagar elementos. Na área de programação de computadores, esse minicadastro é chamado de CRUD, sigla em inglês para as palavras Create, Read, Update e Delete. Traduzindo, temos: criar, ler, atualizar e apagar, respectivamente. Neste exercício, faça um programa contendo um ArrayList que armazena números inteiros e mostra as seguintes opções de escolha para o usuário: 1 - inserir elemento; 2 - remover elemento; 3 - listar elementos; 4 - pesquisar elemento; 5 - ordenar elementos; e 6 - sair. Quando o usuário escolher uma das opções, o programa realiza a operação escolhida no ArrayList.
 
[GABARITO 1](https://replit.com/@maxdovalmachado/ExercicioComplementarU01-S02-EC01)
   
2 - Faça um programa contendo um ArrayList que armazena palavras e mostra as seguintes opções de escolha para o usuário: 1 - inserir elemento; 2 - remover elemento; 3 - listar elementos; 4 - pesquisar elemento; 5 - ordenar elementos; e 6 - sair. Quando o usuário escolher uma das opções, o programa realiza a operação escolhida no ArrayList.

[GABARITO 2](https://replit.com/@maxdovalmachado/ExercicioComplementarU01-S02-EC02)

3 - Faça um programa contendo um ArrayListque armazena Alunos (considere a classe Aluno apresentada nesta sessão) e mostra as seguintes opções de escolha para o usuário: 1 - inserir elemento; 2 - remover elemento; 3 - listar elementos; 4 - pesquisar elemento; 5 - ordenar elementos; e 6 - sair. Quando o usuário escolher uma das opções, o programa realiza a operação escolhida no ArrayList.    

[GABARITO 3](https://replit.com/@maxdovalmachado/ExercicioComplementarU01-S02-EC03)

4 - Faça o método public ArrayList CopiarArrayList(ArrayList origem) que copia todos os elementos do ArrayList origem e retorna um novo ArrayList. Neste exercício não é permitido o uso dos métodos Clone() nem CopyTo().

[GABARITO 4](https://replit.com/@maxdovalmachado/ExercicioComplementarU01-S02-EC04)

5 - Faça o método public ArrayList CopiarParteArrayList(ArrayList origem, int início, int final) que recebe um ArrayList origem e os inteiros início e final e retorna outro ArrayList contendo todos os elementos dentro do intervalo determinado pelos parâmetros início e final. Se o ArrayList origem tiver menos posições do que determinado pelo parâmetro final, copie até a sua última posição. Se o parâmetro início for maior que a quantidade de elementos do ArrayList origem, retorne um ArrayList vazio. Por fim, se o parâmetro início for maior que o parâmetro final, indique que o usuário deseja copiar os dados na ordem invertida. Neste exercício não é permitido o uso dos métodos Clone() nem CopyTo().

[GABARITO 5](https://replit.com/@maxdovalmachado/ExercicioComplementarU01-S02-EC05)

6 - Faça o método public void ApagarArrayList(ArrayList origem, int início, int final) que apaga todos os elementos no intervalo determinado pelos parâmetros início e final. Neste exercício não é permitido o uso do método RemoveRange(); use somente os métodos Remove() e RemoveAt(). Por exemplo, a chamada ApagarArrayList(al, 7, 10) apaga os elementos entre as posições 7 e 10.  

[GABARITO 6](https://replit.com/@maxdovalmachado/ExercicioComplementarU01-S02-EC06)
    
7 - Faça o método public void ApagarArrayList2(ArrayList origem, int início, int qtde) que apaga todos os qtde elementos a partir da posição determinada pelo parâmetro início. Neste exercício não é permitido o uso do método RemoveRange(); use somente os métodos Remove() e RemoveAt(). Por exemplo, a chamada ApagarArrayList2(al, 7, 5) apaga 5 elementos a partir da posição 7, ou seja, os elementos das posições 7, 8, 9, 10 e 11.

[GABARITO 7](https://replit.com/@maxdovalmachado/ExercicioComplementarU01-S02-EC07)
    
8 - Faça o método public ArrayList ConcatenaArrayList(ArrayList al1, ArrayList al2) que recebe dois objetos ArrayList al1 e al2 e retorna outro ArrayList concatenando todos os elementos de al1 e al2. Por exemplo, se os valores dos dois ArrayLists passados por parâmetro forem [19, 33, 2, 4] e [1, 2, 3, 4, 5], o ArrayList retornado será [19, 33, 2, 4, 1, 2, 3, 4, 5].    

[GABARITO 8](https://replit.com/@maxdovalmachado/ExercicioComplementarU01-S02-EC08)
    
9 - Faça o método public void ConcatenaArrayList2(ArrayList al1, ArrayList al2, ArrayList al3) que recebe três objetos ArrayList al1, al2 e al3, concatena os todos os elementos de al1 e al2 em al3. Por exemplo, se os valores dos dois primeiros ArrayLists passados por parâmetro forem [19, 33, 2, 4] e [1, 2, 3, 4, 5], o valor final de al3 será [19, 33, 2, 4, 1, 2, 3, 4, 5].

[GABARITO 9](https://replit.com/@maxdovalmachado/ExercicioComplementarU01-S02-EC09)

10 - Faça o método public ArrayList Intersecao(ArrayList al1, ArrayList al2) que recebe dois ArrayLists e retorna outro contendo os elementos em comum armazenados em al1 e al2, sem repetição.

[GABARITO 10](https://replit.com/@maxdovalmachado/ExercicioComplementarU01-S02-EC10)

11 - Faça o método public ArrayList Uniao(ArrayListal1, ArrayListal2) que recebe dois ArrayLists e retorna outro contendo todos os elementos armazenados em al1 e al2, sem repetição. 

[GABARITO 11](https://replit.com/@maxdovalmachado/ExercicioComplementarU01-S02-EC11)

12 - Faça o método public void ApagaRepetidos(ArrayList al) que recebe um ArrayList e apaga todas as ocorrências repetidas, mantendo apenas a primeira ocorrência de cada elemento.

[GABARITO 12](https://replit.com/@maxdovalmachado/ExercicioComplementarU01-S02-EC12)

13 - Faça o método public ArrayList OcorrenciasDe(ArrayList al, Object elemento) que recebe um ArrayList al e um Object elemento e retorna outro ArrayList contendo todas as posições em que o elemento aparece em al.

[GABARITO 13](https://replit.com/@maxdovalmachado/ExercicioComplementarU01-S02-EC13)
    
14 - Faça o método public int QtdeOcorrencias(ArrayList al, Object elemento) que retorna o número de vezes que o Object elemento aparece no ArrayList al.   

[GABARITO 14](https://replit.com/@maxdovalmachado/ExercicioComplementarU01-S02-EC14)

---
<h3>📚 MATERIAL COMPLEMENTAR</h3>
<img src= "https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYjRkbnFodTRyeTN4YmxqZjQ4cGs1Mm5vbmZyZjA2dDRxbWducTZ3YSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/xhuy5rw9ZrB2jn8VFR/giphy.gif" width="200" >

- [Documentação da classe ArrayList](https://learn.microsoft.com/pt-br/dotnet/api/system.collections.arraylist?view=net-5.0)





 

