# Análise Dados da Vacinação Covid-19 no estado de Amazonas
Este é um projeto de análise de dados utilizando os recursos do Open Data SUS com dados da vacinação de COVID-19 do estado de Amazonas.<br>
Neste projeto gostaríamos de conhecer mais a fundo sobre as fabricantes de vacinas mais utilizadas na imunização da população do estado de Amazonas e quem são as pessoas que foram imunizadas com a 1ª e 2ª dose. <br>
A partir disso, foi realizada uma Análise Exploratória e foram respondidas as perguntas:<br>
<li>Quais foram as vacinas mais utilizadas durante a 1ª e 2ª dose no Amazonas?</li>
<li>Quem são as pessoas (raça, faixa etária, sexo, municípios em que moram) que foram vacinadas com a 1ª e a 2ª dose no estado de Amazonas durante a pandemia de Covid-19?</li>

Para isso, foram utilizados: Python e as bibliotecas Pandas, Matplotlib.<br>

# Informações
Desenvolvido com:<br>
Anaconda, https://www.anaconda.com/;<br>
Jupyter
Utilizada linguagem Python 3.9, instaladas bibliotecas Pandas e Matplotlib;<br>
Dados de Vacinação COVID-19 do estado de Amazonas do site Open Data SUS, https://opendatasus.saude.gov.br/dataset/covid-19-vacinacao<br>

Este projeto será uma grande oportunidade para aprender a utilização do Anaconda e do Jupyter; melhorar a análise de dados utilizando as bibliotecas Pandas e Matplotlib do Python.



# Como Utilizar
Clonar este repositório para o seu Github.<br>
Importar o repositório para uma pasta de seu computador.<br>
Realizar a instalação do programa Anaconda, instalar o Python 3.9 e, dentro de Anaconda Navigator, realizar o download do Jupyter.<br>
Realizar o download do banco de dados e salvar na pasta do repositório: https://s3.sa-east-1.amazonaws.com/ckan.saude.gov.br/SIPNI/COVID/uf/uf%3DAM/part-00000-85a1fd67-abec-40c0-b3a4-72b667ce9b2c.c000.csv
No prompt do Anaconda, realizar o download das bibliotecas Pandas e Matplotlib.<br>
Abrir Jupyter Notebook no Anaconda.<br>
Procurar pela pasta do repositório.<br>
Abrir documento 'DadosPessoas_1dose.ipynb', DadosPessoas_2dose.ipynb' e 'Fabricantes_Vacinas.ipynb'.<br>
Apertar em 'RUN'.
Após este passo, o programa irá rodar todos as tabelas e gráficos disponíveis.


# Resultados
Conforme pudemos visualizar nos dados, no período de 02/01/21 - 02/03/23, as fabricantes de vacinas mais utilizadas na administração da 1ª e 2ª dose foram:1) Astrazeneca, 2) Pfizer, 3) Sinovac.<br>

Em relação à vacinação por faixa etária, em porcentagem:<br>
<br> 
Faixa_Etária Porcentagem (1ªdose)   Porcentagem (2ªdose)  <br>            
    0-11         12.420610                7.912831<br>
    12-17        12.767233               10.903854<br>
    18-29        23.954228               23.983011<br>
    30-39        17.200073               18.118315<br>
    40-49        14.338692               15.940065<br>
    50-59         9.503981               11.046735<br>
    60-69         5.980081                7.329847<br>
    70-79         2.668241                3.359766<br>
    80-89         0.975691                1.187898<br>
    90-99         0.191172                0.217678<br>
<br> 
Em relação à vacinação por raça, em porcentagem:<br>
RAÇA         Porcentagem (1ªdose)    Porcentagem (2ªdose) <br> 
PARDA             53.788231              53.734728<br> 
SEM INFORMACAO    18.890232              17.860690<br> 
AMARELA           16.203583              17.319105<br> 
BRANCA             6.210589              6.387922<br> 
INDIGENA           4.000769              3.750190<br> 
PRETA              0.906597              0.947365<br> 
<br> 
Em relação à vacinação por municípios, em porcentagem:<br>
MUNICÍPIO   PORCENTAGEM (1ªDOSE)   PORCENTAGEM (2ªDOSE)<br> 
MANAUS           54.75%                   52.44%<br> 
ITACOATIARA       2.61%                    2.94%<br> 
PARINTINS         2.42%                    3.08%<br> 
MANACAPURU        2.39%                    2.44%<br> 
TEFE              1.87%                    2.10%<br> 
<br> 

# Andamento do projeto:
Em andamento. <br>
Data de entrega: 08/03/23
