# Exploração e Pré-Processamento dos dados utilizando PySpark 

<div>
Esse repositório é dedicado à tarefa de Exploração e Pré-Processamento dos dados utilizando PySpark, incluindo consultas, tarefas de gerenciamento, resumos numéricos e gráficos.
</div>
<div>

Foi utilizado uma máquina virtual Cloudera configurada com ambiente Hadoop para a execução dos script em python.

Você deve descompactar o arquivo .zip chamado (`arquivos_de_tabalho.zip`) diretamente na pasta em `file:/home/cloudera/` (caso contrário o ambiente não ficará bem definido). Certifique-se de que os arquivo  `commons-csv-1.4.jar e spark-csv_2.10-1.5.0.jar` estejam nesse diretório antes de iniciar.

Você também precisa instalar a biblioteca python **seaborn**. Esta biblioteca é instalada automaticamente ao executar a seguinte instrução do terminal:

    pip install seaborn

</div>

## Banco de dados

<div>


Este estudo de caso se concentrará no estudo de atrasos de voos.
A base de dados que vamos usar como referência consiste em analisar atrasos de voos nos Estados Unidos em dezembro de 2016, e isso significa analisar dados da ordem de 500.000 registros e cada um deles contém informações sobre cerca de 30 variáveis.

Originalmente, esses dados foram produzidos para uma competição e os dados originais podem ser baixados no link [https://bit.ly/3Kx6YIu](https://bit.ly/3Kx6YIu)
</div>

## Arquivos

1. **Leitura_de_dados_e_inspecao_inicial.ipynb** => Dedicado a leitura dos dados via PySpark e SQL.
2. **Análise Exploratória de Dados (1).ipynb** => Dedicado a exploração dos dados qualitativos e quantitativos.
3. **Pré-Processamento.ipynb ** => Dedicado a validação dos dados, Revisão de valores anômalos, Revisão de valores ausentes e inconsistências.

