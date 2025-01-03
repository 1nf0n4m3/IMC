# IMC (Índice de Massa Corporal)

Este projeto é uma aplicação simples em C# para calcular o Índice de Massa Corporal (IMC) de uma pessoa com base em seu peso e altura. O programa utiliza uma classe chamada `Pessoa` para armazenar os dados e realizar os cálculos.

## Funcionalidades

- Entrada de peso e altura do usuário.
- Cálculo do IMC utilizando a fórmula:

  ```
  IMC = peso / (altura * altura)
  ```

- Verificação do resultado com base nas faixas de classificação:
  - Abaixo do Peso
  - Peso Normal
  - Acima do Peso
  - Obesidade I
  - Obesidade II
  - Obesidade III

## Estrutura do Código

### Classe `Pessoa`

A classe `Pessoa` contém:

1. **Propriedades**:
   - `peso`: Armazena o peso da pessoa.
   - `altura`: Armazena a altura da pessoa.

2. **Métodos**:
   - `CalculoImc`: Calcula o IMC usando o peso e altura da pessoa.
   - `VerificadorImc`: Retorna uma string indicando a classificação do IMC.
   - `Mensagem`: Exibe os detalhes do peso, altura, IMC e classificação no console.

### Exemplo de Uso

```csharp
using System;

class Program
{
    public static void Main()
    {
        Pessoa Cassio = new Pessoa();

        Cassio.altura = 1.80;
        Cassio.peso = 80;
        Cassio.Mensagem();
    }
}
```

### Saída Esperada

```plaintext
Seu peso é: 80 
Sua altura é: 1.8 
Seu IMC é de 24.69 - Peso Normal
```

## Tecnologias Utilizadas

- Linguagem: **C#**
- Framework: **.NET**

## Como Executar o Projeto

1. Copie o código para um arquivo `.cs` (ex.: `IMC.cs`).

2. Compile o código usando o compilador `csc` ou execute diretamente em uma IDE como **Visual Studio**.

3. Execute o programa e insira os valores de peso e altura.

## Melhorias Futuras

- Receber os dados do usuário via entrada no console.
- Validação para evitar valores inválidos de peso e altura.
- Adicionar uma interface gráfica para maior interatividade.

### Autor

Desenvolvido por [1nf0n4m3](https://github.com/1nf0n4m3). Sinta-se à vontade para contribuir ou sugerir melhorias!
