# Tipos VAZIO
```Portugol
programa
{
  funcao inicio()
  {
    imprime_linha()
    informacoes("Portugol", 2.0, "UNIVALI")
    imprime_linha()
    informacoes("Java", 1.7, "Oracle")
    imprime_linha()
    informacoes("Ruby", 2.0, "ruby-lang.org")
    imprime_linha()
    informacoes("Visual Basic", 6.0, "Microsoft")
    imprime_linha()
  }

  funcao vazio imprime_linha()
  {
    escreva("\n------------------------------------------------------------")
  }

  funcao vazio informacoes(cadeia nome, real versao, cadeia fornecedor)
  {
    se(nome == "Visual Basic")
    {
      retorne
    }
    escreva("\n")
    escreva("A linguagem")
    escreva(nome)
    escreva("encontra-se em sua versão")
    escreva(versao)
    escreva("e é fornecida pelo(a)")
    escreva(fornecedor)
  }
}
```
