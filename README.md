# udesc-template-a5
Modelo Latex para Dissertações de Mestrado em A5 - Computação Aplicada

Uma das melhores formas de trabalhar com o template é fazer o upload desses arquivos para o [Sharelatex](https://www.sharelatex.com?r=42e77376&rm=d&rs=b). Você pode operar com o diretório template sem problemas, mas se quiser reduzir os warnings, sugiro mover os arquivos do template para o diretório raiz. Nesse caso, altere a importação do package conforme a sua organização:

```
\usepackage{udesc-dissertacao}
```
ou 
```
\usepackage{Template\udesc-dissertacao}
```

Defina o arquivo 0.Main.tex como root do projeto e organize a dissertação através dos comandos de entrada:
```
\input{1.0.Introducao}
\input{2.0.Conceitos}
\input{3.0.Correlatos}
\input{4.0.Proposta}
\input{5.0.Experimentos}
\input{6.0.Conclusoes}
```

Para facilitar, todas as páginas de definições estão em "Pré-textual", assim é possível trabalhar na dissertação sem compilar essas páginas. Basta comentar a entrada \input{0.PreTextual}

Coloque todas as referências em X.Referencias.

Os anexos utilizam o mesmo conceito do Pré-Textualm, ou seja, basta usar comando input e colocar os textso na pasta Apêndice.
