# Descrição do problema
Nesse EP, nosso objetivo é escrever um programa com um menu interativo
que permite visualizar as taxas de câmbio de diferentes moedas. Inicial
mente o programa deve solicitar ao usuário qual a moeda base a
ser utilizada. O usuário deverá fornecer uma sigla válida de moeda. Em
seguida, o programa deve pedir ao usuário para digitar o número correspon
dente à operação desejada:
0. Encerrar o programa
1. Salvar em um arquivo .txt o câmbio entre [moeda_base] e todas as moedas
disponíveis no dia atual.
2. Selecionar uma moeda desejada para conversão em relação a [moeda_base]
Se o usuário digitar 2, o programa deve solicitar ao usuário para digitar
a moeda desejada para conversão e em seguida deve mostrar as seguintes
opções:
0. Encerrar o programa
1. Mostrar conversão entre [moeda_base] e [moeda_selecionada] no dia
atual
2. Mostrar conversão entre [moeda_base] e [moeda_selecionada] em uma data específica
3. Gerar gráfico e estatísticas do histórico da taxa de câmbio
4. Trocar de moeda base
O seu programa deve substituir [moeda_base] e [moeda_selecionada] pelos
nomes completos das moedas correspondentes às siglas digitadas pelo usuário.
Enquanto não receber o comando 0, o programa fica em loop infinito mos
trando aos usuários as opções de comando disponíveis.
O programa deverá necessariamente utilizar a seguinte API:
https://github.com/fawazahmed0/exchange-api
# Funcionalidades do programa
O programa deve inicialmente solicitar uma moeda base até que o usuário
digite uma moeda válida. Isto é, se a moeda for inválida, o programa imprime
uma mensagem de erro e pede para o usuário digitar a moeda novamente. A
moeda deverá ser identificada pela sigla (por exemplo, a sigla dólar americado
é USDeadoreal brasileiro é BRL). O programa deve ignorar diferenças entre
maiúscula ou minúscula. Assim, por exemplo, tanto USD, quanto usd e Usd 
são entradas válidas para o dólar americano. Para isso, você pode converter
o texto digitado em minúscula utilizado função lower da classe string.
