# Tipos VAZIO
programa<br>
{<br>
  funcao inicio()<br>
  {<br>
    imprime_linha()<br>
    informações("Portugol", 2.0, "UNIVALI")<br>
    imprime_linha()<br>
    informações("Java", 1.7, "Oracle")<br>
    imprime_linha()<br>
    informações("Ruby", 2.0, "ruby-lang.org")<br>
    imprime_linha()<br>
    informações("Visual Basic", 6.0, "Microsoft")<br>
    imprime_linha()<br>
  }<br>

  funcao vazio imprime_linha()<br>
  {<br>
    escreva("\n------------------------------------------------------------")<br>
  }<br>

  funcao vazio informacoes(cadeia nome, real versao, cadeia fornecedor)<br>
  {<br>
    se(nome == "Visual Basic")<br>
    {<br>
      retorne<br>
    }<br>
    escreva("\n")<br>
    escreva("A linguagem")<br>
    escreva(nome)<br>
    escreva("encontra-se em sua versão")<br>
    escreva(versao)<br>
    escreva("e é fornecida pelo(a)")<br>
    escreva(fornecedor)<br>
  }<br>
}
