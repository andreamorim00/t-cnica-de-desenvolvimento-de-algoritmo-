# Avaliação A1 



# Nessa avaliação, foi solicitado fazer 4 tipos de programas, sendo cobrados as seguintes estruturas:

•ESTRUTURAS CONDICIONAIS:

•ESTRUTURAS DE REPETIÇÃO:

•LISTAS

•DICIONÁRIOS



# O QUE FOI FEITO EM CADA UM:

# 01 ESTRUTURAS CONDICIONAIS:

Neste programa, eu desenvolvi uma verificação simples para saber se uma pessoa pode entrar em um evento. Comecei pedindo que o usuário digitasse a idade. Depois, usei estruturas condicionais (if, elif, else) para analisar cada situação possível.

Primeiro verifiquei se a idade era negativa, o que não faz sentido — então exibo que a idade é inválida. Depois, tratei três cenários comuns: menores de 16 não entram, pessoas entre 16 e 17 só podem entrar acompanhadas e adultos têm entrada liberada. Esse exercício me ajudou a entender como decisões diferentes são tomadas pelo código dependendo do que o usuário digita.


# 02 ESTRUTURAS DE REPETIÇÃO: 

Nesse exercício, eu fiz um contador de 1 a 100 usando duas estruturas: for e while, mostrando somente os números pares.
 Na parte com for, usei `range(2, 101, 2)`. Esse comando já começa no 2 e vai pulando de 2 em 2 até chegar ao 100, então só aparecem números pares. Cada número é mostrado com `print(i)`.
 Na segunda parte, fiz a mesma coisa, mas usando o while. Comecei o contador em 2 e deixei o loop rodar enquanto o número fosse menor ou igual a 100. A cada volta, o programa verifica se o número é par usando `contador % 2 == 0`. Se for, ele é exibido. Depois disso, o contador é aumentado em 1 até chegar a 100.


# Listas: 

A ideia é criar um programa que peça ao usuário os nomes dos alunos e guarde tudo dentro de uma lista. Primeiro, o programa cria uma lista vazia para armazenar esses nomes. Depois, usa um while True, que faz o programa pedir novos nomes sem parar, até que o usuário decida encerrar. A cada vez que o usuário digitar um nome, ele será colocado na lista usando append(). Se o usuário apertar apenas Enter, sem digitar nada, o programa usa break para sair do loop. No final, o programa mostra a frase “Lista dos alunos informados:” e exibe todos os nomes que foram cadastrados.


# Dicionário: 


A proposta foi criar um programa básico para cadastrar produtos com nome e preço usando um dicionário. Primeiro, o programa cria um dicionário vazio chamado produtos, onde cada item será guardado no formato nome: preço. Depois disso, um loop while True permite que o usuário continue cadastrando quantos produtos quiser.
Em cada repetição, o usuário digita o nome do produto. Se apenas apertar Enter, o programa usa break para sair do cadastro. Se um nome for digitado, o programa pede o preço e o converte para número usando float().
Depois disso, o nome e o preço são adicionados ao dicionário usando produtos[nome] = preco. A cada produto salvo, o programa mostra uma mensagem de confirmação. Quando o loop termina, o programa exibe todos os produtos cadastrados, mostrando o dicionário completo.
