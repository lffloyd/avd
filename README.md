# avd
Trabalho para a disciplina de Avaliação de Desempenho da Universidade Federal Fluminense, período 2019/2.

## Pré-requisitos

* [Java 8](https://www.oracle.com/technetwork/pt/java/javase/downloads/jdk8-downloads-2133151.html) - necessário para executar a ferramenta JMT.
* [JMT](http://jmt.sourceforge.net/Download.html) - ferramenta de simulação utilizada para implementação e execução dos modelos.

## Instruções
Abra um dos arquivos de modelo em seu JMT. Você poderá realizar alterações no modelo ou simplesmente executar a simulação.

O modelo básico representa a idealização típica do sistema proposto, configurada de forma a ser consistente com sua contraparte no mundo real.

Já o modelo "além do básico" é mais experimental e é usado para trabalhar com conceitos menos usuais de simulação, como utilização de filas [LIFO](https://en.wikipedia.org/wiki/Stack_(abstract_data_type)) - <i>last in, first out</i> - ao invés das típicas filas [FIFO](https://en.wikipedia.org/wiki/FIFO_(computing_and_electronics)) - <i>first in, first out</i>.

Opcionalmente, você tem a opção de gerar gráficos por meio do script de criação ```simulation_graphs.ipynb``` presente no projeto. Para tal, você precisa ter [uma versão compatível do Python](https://www.python.org/downloads/) instalada em sua máquina.

## Autores

* [Luiz Felipe Matos](https://github.com/lffloyd) - implementação, simulação e documentação.
* [Rafael Dantas](https://github.com/dantasraf) - implementação, simulação e documentação.
