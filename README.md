### TCC - Rogerio Carlos Vieira Maciel
### PUC Minas - Abril de 2021
APRENDIZADO DE MÁQUINA APLICADO AO COMÉRCIO EXTERIOR

MODELO PREDITIVO PARA DETERMINAÇÃO DO LOCAL DE DESEMBARQUE DAS MERCADORIAS IMPORTADAS 

### Instruções:
O arquivo TCC_Rogerio.ipynb contém o notebook completo do TCC, que pode ser executado no Jupyter Notebook do Anaconda ou no ambiente colaborativo do Google (Google Colab).

Conforme explicado no item 2.1 do TCC, o dataset de importações (disponível no site do Ministério da Economia) possui mais de 2 GB. Por isso o notebook está configurado para fazer uso de uma versão reduzida (com 250 mil amostras) deste dataset, para a fase de análises exploratórias. Não há necessidade de modificar nenhuma variável global para utilizar essa configuração.


Caso haja interesse de utilizar o dataset completo (2 GB) para executar o notebook, poderá ser baixado em https://drive.google.com/file/d/1TOVgGzTaeq5p3JXoEERjtb-fatFDM1uA/view?usp=sharing

Apenas nesse caso (de haver interesse de usar o dataset de 2 GB), o arquivo deverá ser baixado localmente, e a variável global UTILIZAR_DATASET_REDUZIDO_PARA_ANALISES deverá ser alterada para False, para que o notebook busque o dataset completo, que deverá estar no caminho d:\\datasets\\IMP_COMPLETA.csv, no drive local.

Como as análises exploratórias foram realizadas com o dataset completo (de 2 GB), os gráficos e tabelas gerados com a versão reduzida podem ser um pouco diferentes daqueles apresentados no TCC.

### Resultados
Uma cópia do notebook, com todos os gráficos e tabelas gerados com o dataset completo, está disponível na pasta "resultados" deste repositório.
