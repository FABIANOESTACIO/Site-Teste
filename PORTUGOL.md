img> PORTUGOL.md
algoritmo "nome programa"
Inicio - Inicia
escreva -exibe a mensagem na tela
fim - determina o inicio e fim do nome_programa
inteiro -Ex. 10, 5, -3 (int)
Reais - Ex. 3.12 .  5.12 (float)
Caracteres - "João" , "Al" (string)
Logicos - Valores Booleanos (true, false)
Var
Algoritmo "OPERAÇOES"
VAR
    num1, num2, soma: inteiro
INICIO
    Escreva("Digite o primeiro numero: ")
    Leia(num1)
    Escreva("Digite o segundo numero: ")
    Leia(num2)
    soma<- num1 + num2
    escreva("A soma é: ", soma)
fim



algoritmo "Maioridade"
var
    idade: inteiro
inicio
escreva("Digite sua idade: ")
leia(idade)
se idade >= 18 entao
    escreva("voce é maior de idade.")
senao
    escreva("voce é menor de idade.")
    fimse
fim

algoritmo"contagem"
var 
    i: inteiro
inicio
    i <- 1
    enquanto i <= 10 faça
    escreva (i, " ")
    fimenquanto
fim