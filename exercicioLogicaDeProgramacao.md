Lógica de Programação Exercício
-------------------------
PARTE 01
Programação Procedural: 
  - A programação procedural se baseia na execução de procedimentos. 
  - Esses procedimentos são sequências de instruções que recebem dados de entrada, processam esses dados e retornam um resultado. 
  - A ênfase está na lógica e na sequência das operações a serem realizadas.
  - Exemplos de linguagens que suportam programação procedural incluem C e Pascal.
  - Não é muito utilizada atualmente (pela sua complexibilidade de manutenção e entendimento do código) e é utilizada para tarefas que podem ser divididas em uma série de passos lógicos em uma única classe.

Programação Orientada a Objetos (POO): 
  - A programação orientada a objetos se baseia no conceito de "objetos", que são instâncias de classes. 
  - Classes definem propriedades (atributos) e comportamentos (métodos) que os objetos podem ter.
  - Se concentra em organizar o código em objetos que interagem entre si, facilitando a reutilização e a manutenção do código.
  - Exemplos de linguagens orientadas a objetos incluem Java, C++ e Python.
  - É ideal para sistemas complexos e grandes, onde a modularidade e a reutilização de código são importantes, dividindo o código em códigos menores e várias classes, para facilitar a manutenção e entendimento do código.
  - Comumente usada atualmente na maioria dos projetos em desenvolvimento de software de larga escala, aplicativos de desktop e sistemas empresariais.
-------------------------
PARTE 02
Programa RotinaAoAcordar:

despertadorTocando:

se despertadorTocando = verdadeiro 
escreva("O despertador está tocando. Deseja continuar dormindo ou acordar? (escolha a opção: 1-Acordar 2-Dormir)"
leia(resposta)

se (resposta = 'dormir') 
 - escreva("Dormindo por mais 10 minutos...")

se (resposta - 'acordar')
 - escreva("Parando o despertador...")
 - escreva("Levantando da cama")
 - escreva("Indo ao banheiro")
 - escreva("Lavando o rosto")
 - escreva("Escovando os dentes")
 - escreva("Indo para a cozinha")
 - escreva("Preparando o café")
 - escreva("Pegando o filtro, pegando o café")
 - escreva("Esquentando a água")
 - escreva("Preparando o café")
 - escreva("Tomando o café")
 - escreva("Pronto para iniciar o dia")
    
senão despertadorTocando = falso 
  - acao
    - continuarDormindo 



