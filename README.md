# Boas-vindas ao fim do mundo
Vou corregir este re-me.
 realizar o projeto, atente a cada passo descrito a seguir. Se tiver qualquer dúvida, nos envie por Slack! #vqv 🚀
Criptografia RSA
Testando a vulnerabilidade do método RSA
O nosso teste vai partir da premissa que o conjunto dos números primos é consideravelmente menor que o conjunto dos números naturais.
Permitindo assim, aplicar o método de “Força Bruta ou tentativa e erro” e obter um resultado em menos de 6 dias.
Venha comigo entrar neste mundo de tentações.

De quantas formas diferentes você consegue fazer o número 100?
Mas apenas com dois números naturais e multiplicando!
Vamos fazer juntos:
1 x 100 = 100
2 x 50 = 100
4 x 25 = 100
5 x 20 = 100
10 x 10 = 100
Eu só lembrei destes casos. Alguém lembra de mais algum?
Lembre, o número tem que ser inteiro, não vale “vírgula:’,’”.
Agora você pára e pensa. E se os 2 números da multiplicação só pode ser par.
Já exclui a possibilidade de “1 x 100” e “5 x 20”.
Percebeu que as possibilidades diminuíram significativamente!

Você viu a toca do coelho! agora vamos entrar nela!

De quantas formas diferentes você consegue fazer o número 143?

1º - algoritmo: Verificar as possíveis divisões dele.
1.1 É divisível por 2 : Cada função desta, deve está fora do contexto e ser acessível! 
1.2 É divisível por 3 : Cada função desta, deve está fora do contexto e ser acessível!
1.3 É divisível por 5 : Cada função desta, deve está fora do contexto e ser acessível!
1.4 É divisível por 7 : Cada função desta, deve está fora do contexto e ser acessível!
1.5 É divisível por [ Primo Base* ]

É imprescindível criar um Banco de Dados, para guardar os números primos.

Primo Base: é um array com todos os números possíveis da nossa tecnologia atual.

Eita! É preciso explicar [ Primo Base* ].
Já deu pra perceber que é um array de números primos.
Mas ele precisa crescer….

Isso tá muito abstrato e você não está entendendo mais nada.
Mas vou começar a mostrar caso a caso.
Você entende que dois números, multiplicados dão 143?
Quais são as nossas opções?
1 x 143 = 143.
De forma espontânea e de cabeça não consigo resolver isso.
Então de forma intuitiva, vou tentar.
Só que eu já crie as funções fundamentais dos números primos (ffnp)
E elas me respondem assim: 
Vamos usar as funções anteriores.
div2(143)=false : 71,5
div3(143)=false : 47,667
div5(143)=false : 28,6
div7(143)=false : 20,42…

div(Primo Base*) = ???

“Preciso explicar melhor…”A ideia da base primo é listar todos os números menores do que seu número natural.””
Então seria a lista de todos os números primos menores que 143.
Caso 1: não termina em 0;2;4;6;8
Caso 2: A soma de 1+4+3 =8, não é múltiplo de 3
Caso 3: Não termina com 5, logo não é múltiplo de 5
Caso 4: Não divide por 7.

Agora você entende que temos que entrar em um “loop infinito” ?

Agora eu revelo a pergunta da esfinge “Quais dos números primos de mais de 100 caracteres .









 


