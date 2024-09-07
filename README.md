# PRÁTICA DE POO EM JAVA

Este repositório conterá arquivos que deverão ser completados. Dentro da pasta "src" é onde você criará uma pasta (package) com o nome "solução: seu nome" e para cada tópico irá criar uma outra pasta (dentro da pasta solução) e dentro dela deixar as soluções específicas. 

## Exercícios de lógica:

1- Faça um programa que receba um número inteiro e verifique se ele é par ou ímpar.

2- Faça um algortimo que repita 3 vezes uma contagem regressiva para o ano novo (10, 9, 8... FELIZ ANO NOVO!!). Faça usando while, for e do-while. 

3- Escreva um algoritmo que receba 10 números e diga qual o maior e menor valor informado.

4- Crie um programa que crie um vetor de 10 posições, preencha esse vetor e organize ele com o algoritmo bubble sort. Deverá aparecer na tela o vetor antigo e em baixo o organizado.

## Encapsulameto


OBS: para cada classe, crie um arquivo (classe) MAIN, para testar o encapsulamento.
Ex: se existe a classe Animal, crie uma classe MainAnimal, onde fará o teste e conterá o método main.

1- Crie uma classe chamada Funcionario que contenha os atributos nome, salario e cargo. Todos os atributos devem ser privados. Em seguida, crie métodos públicos (getters e setters) para acessar e modificar esses atributos, respeitando as seguintes regras:

    - O nome pode ser lido e modificado livremente.
    - O salário pode ser lido, mas só pode ser modificado se o novo salário - - for maior que o atual.
    - O cargo só pode ser modificado se o novo cargo for diferente do atual.

2- Desenvolva uma classe chamada ContaBancaria que tenha os atributos numeroConta, saldo e titular. Todos os atributos devem ser privados. Implemente métodos públicos para:

    - Depósito: Permitir adicionar um valor ao saldo.
    - Saque: Permitir a retirada de um valor do saldo, mas apenas se o saldo for suficiente.
    - Transferência: Transferir um valor de uma conta para outra, respeitando as mesmas regras do saque.

3- Crie uma classe chamada Estoque com os atributos privados quantidade e produto. Implemente métodos públicos para:

    - Adicionar itens ao estoque, aumentando a quantidade.
    - Remover itens do estoque, diminuindo a quantidade, mas somente se houver estoque - suficiente.
    - Consultar a quantidade atual em estoque.
    - Definir o produto do estoque, mas apenas uma vez (durante a criação do objeto).


## Herança

OBS: CRIE A CLASSE MAIN E TESTE A HERANÇA

1- Crie uma classe base chamada "Pagamento" com os atributos "valor" e "data". Implemente métodos para calcular o valor total do pagamento e exibir as informações básicas. A seguir, crie subclasses chamadas "PagamentoCartao", "PagamentoBoleto" e "PagamentoPix", que herdam de Pagamento. Cada subclasse deve ter um atributo específico (numeroCartao, codigoBarras, chavePix) e deve sobrescrever o método de cálculo do valor total para incluir taxas específicas (por exemplo, uma taxa para pagamentos com cartão).

2- Implemente uma classe base chamada "Funcionario" com os atributos "nome", "salarioBase" e "cargo". Crie métodos para exibir as informações básicas do funcionário e calcular o salário total. Em seguida, crie subclasses chamadas "Gerente", "Vendedor" e "Estagiario", que herdam de Funcionario. Cada subclasse deve ter um método que calcula o salário total com base no salário base e benefícios específicos (por exemplo, comissões para Vendedor, bônus para Gerente, e desconto para Estagiario).

3- Implemente uma classe base chamada "Conta" com os atributos "numeroConta", "saldo" e "titular". Crie métodos para depositar e sacar dinheiro da conta, bem como para exibir o saldo. A seguir, crie subclasses chamadas "ContaCorrente" e "ContaPoupanca" que herdam de Conta. A ContaCorrente deve ter um método adicional para cobrar uma taxa de manutenção mensal, enquanto a ContaPoupanca deve ter um método para aplicar um rendimento mensal ao saldo.


## Polimorfismo

1- Crie uma classe base chamada "FormaGeometrica" com um método abstrato "calcularArea()". Em seguida, crie subclasses Circulo, Quadrado e Retangulo, cada uma implementando o método "calcularArea()" de forma apropriada. Crie uma função em uma classe principal que receba uma lista de "FormaGeometrica" e calcule a área de cada forma, utilizando o polimorfismo para determinar qual implementação de "calcularArea()" deve ser chamada.