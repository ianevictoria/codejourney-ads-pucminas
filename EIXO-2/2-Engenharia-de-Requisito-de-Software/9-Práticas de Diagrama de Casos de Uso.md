PRÁTICAS DE DIAGRAMA DE CASOS DE USO
 
O objetivo desta sessão de estudo é ilustrar a construção passo-a-passo de um Diagrama de Caso de Uso UML utilizando uma ferramenta CASE (Computer Aided Software Engineering). Esta sessão auxilia fixar os conceitos do Diagrama de Caso de Uso de uma maneira prática.

Ao final da sessão, você será capaz de utilizar uma ferramenta CASE para modelar casos de uso.

NESTA SESSÃO
Nesta sessão de estudos, o seguinte Diagrama de Caso de Uso UML deve ser modelado. Após ler o enunciado, você pode fazer o diagrama em um rascunho e depois assistir o vídeo. Ou se preferir, pode assistir o vídeo e depois fazer o diagrama por conta própria. O diagrama contempla as principais ligações previstas entre casos de uso e atores.

Construa o diagrama de caso de uso UML para o seguinte sistema de seguradora.

O cliente cadastra inicialmente seus dados pessoais, depois cadastra os dados do veículo e finalmente cadastra uma proposta de seguros para a Seguradora.

Alguns clientes são clientes especiais do programa de fidelidade da Seguradora e então cadastram uma proposta de seguros com descontos.

A seguradora formata a proposta de seguros, consultando para tanto o cadastro de veículos. Posteriormente, o cliente paga as prestações do seguro.

Caso algum cliente não pague, a seguradora cancela o seguro, comunicando o cliente.

Em caso de acidente, o cliente comunica o sinistro à seguradora. A seguradora paga as despesas de conserto, consultando para tanto o cadastro de veículos. Em casos raros de sinistros mais graves, a seguradora paga ao cliente o valor da perda total do veículo.

Agora assista ao vídeo onde construiremos um diagrama de caso de uso.

[PRÁTICAS DE DIAGRAMA DE CASOS DE USO]()


REFLEXÃO

Qual é a vantagem de se usar uma ferramenta CASE baseada em UML em relação a um desenhador padrão de diagramas que não seja baseado em UML? 

 
MATERIAL COMPLEMENTAR

Assista o vídeo abaixo para rever os conceitos do Diagrama de Caso de Uso e aprender o uso de outra ferramenta.

[Tutorial de Caso de Uso UML – Lucid Chart](https://youtu.be/ab6eDdwS3rA)
 
ATIVIDADE

No exercício da Seguradora, temos vários tipos de ligações. Marque a ligação que é representada no Diagrama de Caso de Uso.

Extend entre o Caso de Uso “Pagar Perda Total” e o Caso de Uso “Pagar Conserto”

Include entre Atores

Herança entre o Caso de Uso “Cadastrar Dados Pessoais” e “Cadastrar Proposta de Seguros”

Include entre o Caso de Uso “Pagar Perda Total” e o Caso de Uso “Pagar Conserto”

///////////////
Extend entre o Caso de Uso “Pagar Perda Total” e o Caso de Uso “Pagar Conserto”
Resposta correta.
Resposta correta. Pagar perda total é uma situação excepcional do pagamento do conserto.
