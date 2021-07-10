# Projeto CENIPA

<p align="center">
<img src="https://raw.githubusercontent.com/elladarte/Python_Pandas/main/Projeto%20CENIPA/images/cenipa.jpg"/> </br>
<img src="https://img.shields.io/static/v1?label=Status&message=Em_andamento&color=yellow&style=for-the-badge"/>
</p>

O objetivo desse projeto é praticar o processo de ETL (extração, transformação, carregamento) de dados, utilizando a linguagem de programação Python. Será utilizado a base de dados de ocorrências aeronáuticas, gerenciada pelo Centro de Investigação e Prevenção de Acidentes Aeronáuticos (CENIPA) - órgão do Comando da Aeronáutica responsável pelas atividades de investigação de acidentes aeronáuticos da aviação civil e da Força Aérea Brasileira. Constam nesta base de dados as ocorrências aeronáuticas notificadas ao CENIPA nos últimos 10 anos e que ocorreram em solo brasileiro.

## Tabelas (arquivos)

As tabelas(arquivos encontram-se no diretorio [data](). Segue abaixo uma breve descrição dos dados presentes em cada uma delas.

- OCORRÊNCIA.csv - Informações sobre as ocorrências.
- OCORRÊNCIA_TIPO.csv - Informações sobre o tipo de ocorrência.
- AERONAVE.csv - Informações sobre as aeronaves envolvidas nas ocorrências.
- FATOR_CONTRIBUINTE.csv - Informações sobre os fatores contribuinte das ocorrências que tiveram investigações finalizadas.
- RECOMENDAÇÃO.csv - Informações sobre as recomendações de segurança geradas nas ocorrências.
Fonte: Sistema DÉDALO.

## Relacionamento entre as Tabelas

<p align="center">
<img src="https://raw.githubusercontent.com/elladarte/Python_Pandas/main/Projeto%20CENIPA/images/modelo_dados.png"/> </br>
</p>
