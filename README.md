# Análise Dados da Vacinação Covid-19
Este é um projeto de análise de dados utilizando os recursos do Open Data SUS com dados da vacinação de COVID-19 do estado de Amazonas.<br>
Neste projeto gostaríamos de conhecer mais a fundo sobre as fabricantes de vacinas mais utilizadas na imunização da população do estado de Amazonas e quem são as pessoas que foram imunizadas com a 1ª e 2ª dose. <br>
A partir disso, foi realizada uma Análise Exploratória e foram respondidas as perguntas:<br>
<li>Quais foram as vacinas mais utilizadas durante a 1ª e 2ª dose no Amazonas?</li>
<li>Quem são as pessoas (raça, faixa etária, sexo, municípios em que moram) que foram vacinadas com a 1ª e a 2ª dose no estado de Amazonas durante a pandemia de Covid-19?</li>

Para isso, foram utilizados: Python e as bibliotecas Pandas, Matplotlib.<br>

# Informações
Desenvolvido com:<br>
<li>Anaconda, https://www.anaconda.com/;</li>
<li>Jupyter</li>
<li>Utilizada linguagem Python 3.9, instaladas bibliotecas Pandas e Matplotlib;</li>
<li>Dados de Vacinação COVID-19 do estado de Amazonas do site Open Data SUS, https://opendatasus.saude.gov.br/dataset/covid-19-vacinacao</li>

Este projeto será uma grande oportunidade para aprender a utilização do Anaconda e do Jupyter; melhorar a análise de dados utilizando as bibliotecas Pandas e Matplotlib do Python.



# Como Utilizar
Clonar este repositório para o seu Github.<br>
Importar o repositório para uma pasta de seu computador.<br>
Realizar a instalação do programa Anaconda, instalar o Python 3.9 e, dentro de Anaconda Navigator, realizar o download do Jupyter.<br>
Realizar o download do banco de dados e salvar na pasta do repositório: https://s3.sa-east-1.amazonaws.com/ckan.saude.gov.br/SIPNI/COVID/uf/uf%3DAM/part-00000-85a1fd67-abec-40c0-b3a4-72b667ce9b2c.c000.csv
Atenção!!<br>
Você pode utilizar o banco de dados de outros municípios neste repositório, busque o estado desejado em https://opendatasus.saude.gov.br/dataset/covid-19-vacinacao e modifique a segunda linha dos projetos:<br>

dados = pd.read_csv(r'C:\Users\Usuário\Documents\GitHub\Analise_Dados\DadosVacinaAM.csv', sep=";")<br>

No prompt do Anaconda, realizar o download das bibliotecas Pandas e Matplotlib.<br>
Abrir Jupyter Notebook no Anaconda.<br>
Procurar pela pasta do repositório.<br>
Abrir documento 'DadosPessoas_1dose.ipynb', DadosPessoas_2dose.ipynb' e 'Fabricantes_Vacinas.ipynb'.<br>
Apertar em 'RUN'.
Após este passo, o programa irá rodar todos as tabelas e gráficos disponíveis.


# Resultados
Conforme pudemos visualizar nos dados, no período de 02/01/21 - 02/03/23, as fabricantes de vacinas mais utilizadas na administração da 1ª e 2ª dose foram:1) Astrazeneca, 2) Pfizer, 3) Sinovac.<br>

Em relação à vacinação por faixa etária, em porcentagem, pudemos perceber que a faixa etária entre 18-29 teve a maior porcentagem de indivíduos vacinados, seguidos pela faixa dos 30-39 e dos 40-49 em ambas as doses da vacina.<br>

Em relação à vacinação por raça, em porcentagem, os dados mostram que aproximadamente, 53,8% são indivíduos pardos, entre 16,2-17,4% são indivíduos amarelos, entre 6,21 -6,38% são brancos, 3,75 - 4% são indígenas e 0,9-0,95% são pretos.<br>

Em relação ao município dos vacinados, os municípios que mais vacinaram são Manaus, Itacoatiara, Parintins, Manacapuru e Tefe.


# Andamento do projeto:
Entregue. <br>
