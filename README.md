# Relatório de Testes de Unidade em C#

## Resumo:

Este arquivo documenta a criação e execução de testes de unidade para a classe *BankAccount* em C#. Os testes foram escritos usando a estrutura de teste de unidade da Microsoft e o Gerenciador de Testes do Visual Studio.

## Conceitos Aprendidos:

Testes de Unidade: São testes que verificam o comportamento de unidades individuais de código, como classes ou métodos.

Estrutura de Teste de Unidade: Fornece ferramentas e APIs para escrever e executar testes de unidade.

Gerenciador de Testes: Ferramenta para executar, organizar e visualizar os resultados dos testes de unidade.

Assert.AreEqual: Método para verificar se dois valores são iguais.

Assert.ThrowsException: Método para verificar se uma exceção específica é lançada.

Assert.Fail: Método para indicar que um teste falhou.

Refatoração: Processo de melhorar a estrutura e o design do código sem alterar sua funcionalidade.

## Etapas Realizadas:

1. Criado um projeto C# com a classe *BankAccount*.
2. Criado um projeto de teste de unidade para o projeto *Bank*.
3. Adicionado uma referência ao projeto Bank no projeto de teste *BankTests*.
4. Criado a classe de teste *BankAccountTests*.
5. Criado o método de teste *Debit_WithValidAmount_UpdatesBalance*.
6. Executado o teste e corrigido o bug no método *Debit*.
7. Criado os métodos de teste *Debit_WhenAmountIsLessThanZero_ShouldThrowArgumentOutOfRange* e *Debit_WhenAmountIsMoreThanBalance_ShouldThrowArgumentOutOfRange*.
8. Refatorado os métodos de teste para usar StringAssert.Contains e Assert.Fail.
9. Executado os testes e verificado se todos os testes foram aprovados.

## Conclusão:

Os testes de unidade foram eficazes para encontrar e corrigir bugs no código da classe *BankAccount*. O processo de refatoração dos testes de unidade também tornou eles mais robustos e informativos.

## Código em Execução

Os prints do código em execução estão no seguinte link:

https://docs.google.com/document/d/1bscD8kyufSuV-mCtfA5dcVft0ebZv_VTelcSfOQDO_U/edit?usp=sharing