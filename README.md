# Curso Sintaxe Java

#### O que é?

#### Para que serve?

## Ambiente Java

Java é uma linguagem independente de plataforma porque seus programas são compilados em um formato próprio denominado bytecodes, instruções de tamanho fixo
que constituem a linguagem da JVM, armazenados em arquivos de classe .class.

Em cada combinação específicas de hardware e sistema operacional deve existir uma JVM apropriada, capaz de interpretar os bytecodes ou de transformá-los em código 
nativo que possa ser execultado pelo processador do sistema.

A JVM sempre utiliza os serviços oferecidos pelo sistema operacional em uso.

Assim o ambiente Java é composto com a JVM, sua API e com as classes da aplicação

                                                    [Imagem]
                                                    
O desenvolvimento de programas em Java requer um editor, que permita salvar o programa-fonte como arquivos de extensão .java;

e um compilador Java para transformar os arquivos do programa-fonte em bytecodes, salvos em arquivos de classe de extensão .class.

Para execultar uma aplicação Java, é necessária uma JVM que interpretará ou conduzirá a execução dos arquivos de classe, usando direta ou indiretamente o código nativo do sistema.

                                                    [Imagem]
                                                    
Um ambiente mínimo é aquele que permite apenas a execução de aplicações Java, o que é possível com o uso do JavaRE (Java Runtime Environment).

## Recursos necessários

## Instalando e configurando o java

## Primeiro programa - Hello World

Em um programa em Java pode existir um ou mais arquivos-fonte, denominado unidade de compilação, os quais podem conter:

* uma declaração de pacote (package)
* uma ou mais diretivas de importação (import);
* uma ou mais declarações de classes (class), de interfaces (interface) ou de enumerações (enum).


                        [Imagem]

Apenas um dos elementos declarados pode ser público e seu nome define o nome do arquivo.

                        [Imagem]

As classes, interfaces e enumeração presentes nos arquivos são organizadas nos pacotes indicados, que por sua vez são dispostos em módulos.

                        [Imagem]

Todo programa deve ter no mínimo o método main(String []) que define seu início e é declarado public, statice void dentro de alguma de suas classes.

                        [Imagem]

Quando se omite a declaração de pacote, a classe é posicionada num pacote denominado default.

                        [Imagem]
                        
O código dessse programa pode ser digitado com qualquer editor de texto e salvo em um arquivo denominado P020HelloWorld.java (arquivo-fonte do programa) em um diretório como C:/JGP4/Cap02_Sintaxe/src ou outro de sua preferência.

## Uso de maiúsculas e minúsculas

O java é uma linguagem sensivel ao caixa, em toda as suas construções as letras minúsculas e maiúsculas são consideradas diferentes

* nome é diferente de NOME,
* assim como public é diferente de Public.

                        [Imagem]

## Comentários

Dentro dos programas é permitida a inclusão de comentários e fragmentos de texto que servem para registro de explicações, anotações ou outras informações necessárias.

Embora façam parte do arquivo de programa, são desconciderados pelo compilador, de modo que neles possa figurar qualquer caractere ou acentuação.

                        [Imagem]
                        
O comentário de linha é o mais simples, iniciado por duas barras //, em que o texto incluído após as barras até o final da linha é considerado como comentário.

                        [Imagem]
                        
O comentário de bloco delimita várias linhas consecutivas como um único comentário. Seu início é estabelecido com a combinação dos caracteres /* e seu final com */ como no trecho de programa

                        [Imagem]
                        
O 

## Compilação e execução

### Compilação

### Execução

### Execução direta

### Execução de caracteristicas de apresentação

## Console jshell

## Tipos de Dados Primitivos

### Tipos de Dados Inteiros

### Tipos de Dados Reais

### Tipos de Dados Lógico

### Tipos de Dados Caractere

### Tipos de Dados Cadeia de Caracteres

### Valores literais numéricos

### Caracteres especiais

## Variáveis

### Palavras reservadas

### Denominação de variáveis

## Declaração de variáveis

### Declaração e inicialização de variáveis

### Inferência de variáveis locais

## Escopo de variáveis

## Entrada e saída básicas

### Entrada não formatada 

### Saída não formatada

### Entrada formatada

### Saída formatada

## Operadores e expressões

### Operador de atribuição simples

### Operadores aritméticos

### Promoção e coerção

### Operadores relacionais

### Operadores lógicos

### Operadores de atribuição composta

### Operador ternário

### Operadores bitwise

### Precedência de avaliação de operadores

## Estruturas de controle
