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

O vídeo abaixo explica o último código:



 

