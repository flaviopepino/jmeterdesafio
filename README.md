# Jmeter desafio


Compra de passagem aérea - Passagem comprada com sucesso.

## Description

* Montar teste de carga e teste  de pico.
* 250 requisições por segundo com um tempo de resposta 90th percentil inferior a 2 segundos.


## Getting Started

### Dependencies

* Jmeter
* Jmeter plugins
* Jmeter Custom Thread Group

### Installing

* Baixar jmeter jmeter.apache.org
* baixar plugins manager em https://jmeter-plugins.org
* NO Jmeter GUI , ir em Options -> Plugin Manager e baixar  Custom Thread Group


### Executing program

*  Abra o arquivo compra_passagem_area.jmx pela GUi do Jmeter, e habilite o Teste de Carga ou Teste de Pico. Salve o arquivo. 
* Rode jmeter -n -t caminho/compra_passagem_area.jmx -l resultado.jtl -e -o pastavazia , onde pastavazia é um diretório vazio para receber o relatório.


## Resultados

Teste de Carga
em jmeterdesafio/resultadocarga
analise.txt contém uma breve análise do teste.

Teste de Pico
em jmeterdesafio/resultadopico


Flavio Pepino






