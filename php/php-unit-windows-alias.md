#### Rodar PHP Unit com mais facilidade:

Crie o seguinte script com o nome test.bat

```

@ECHO OFF
set "test=phpunit -c app/"
%test% %1

```

Adicione o script ao $PATH do sistema e rode os testes da seguinte maneira

```

$ test path/to/TestFiles/

```

Para criar o relatório de testes com facilidade crie outro arquivo test-cov.bat

```

@ECHO OFF
set "test-cov=phpunit -c app/ --coverage-html=cov"
%test-cov% %1

```

Adicione o script ao $PATH do sistema e rode os testes da seguinte maneira

```

$ test-cov path/to/TestFiles/

```