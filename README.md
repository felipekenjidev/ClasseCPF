# Classe C# para Validação de CPF
Uma Classe C# com métodos e propriedades para realizar a verificação do CPF (Cadastro de Pessoa Física), formatando seus dígitos e indicando se o documento digitado é Verdadeiro ou Falso.

# Preparação
Antes de poder utilizar a Classe CPF, é necessário importar para dentro do projeto, colocando o próprio arquivo `clsCPF.cs` dentro do projeto ou adicionando uma referência para a DLL `clsCPF.dll`.

# Como Funciona?
Para utilizar basta instanciar a Classe CPF, passando no parâmetro o CPF a ser verificado. Pode passar o CPF tanto com as pontuações como `696.197.530-54` ou sem como `69619753054`.

`CPF variavel = new CPF("69619753054");`

Após instanciar a Classe, apenas é preciso acessar o método `Validar()` que o resultado da verificação será gerado.

`bool resposta = variavel.Validar()`
