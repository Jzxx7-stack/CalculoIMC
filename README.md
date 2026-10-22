# CalculoIMC

Atividade de Java sobre cálculo de IMC.

O código original apresentava um problema na chamada do método `calcularIMC`, porque o método foi criado para receber dois valores, `peso` e `altura`, mas estava sendo informado apenas o peso.

A correção foi feita passando os dois valores na chamada do método:

`calcularIMC(peso, altura)`

Também foi retirado um símbolo `<` que aparecia depois da declaração da variável peso.

Depois das correções, o programa calcula o IMC normalmente e exibe a classificação correspondente.
