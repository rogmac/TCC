### TCC - Rogerio Carlos Vieira Maciel
#### PUC Minas - Abril de 2021
APRENDIZADO DE MÁQUINA APLICADO AO COMÉRCIO EXTERIOR

MODELO PREDITIVO PARA DETERMINAÇÃO DO LOCAL DE DESEMBARQUE DAS MERCADORIAS IMPORTADAS 

#### Instruções:
O arquivo **TCC_Rogerio.ipynb** contém o notebook completo do TCC, que pode ser executado no Jupyter Notebook do Anaconda ou no ambiente colaborativo do Google (Google Colab). O notebook carrega automaticamente os datasets disponibilizados neste repositório do GitHub. A execução do script no ambiente padrão do Google Colab leva cerca de 20 minutos.


#### Comentários sobre o dataset completo
Conforme explicado no item 2.1 do TCC, o dataset de importações (disponível no site do Ministério da Economia) possui mais de 2 GB. Por isso o notebook está configurado para fazer uso de uma versão reduzida (com 250 mil amostras) deste dataset para a fase de análises exploratórias. Não há necessidade de modificar nenhuma variável global para utilizar essa configuração padrão.


Entretanto, caso haja interesse de utilizar o dataset completo (2 GB) para executar o notebook, o arquivo poderá ser baixado em https://drive.google.com/file/d/1TOVgGzTaeq5p3JXoEERjtb-fatFDM1uA/view?usp=sharing

Apenas nesse caso (de haver interesse de usar o dataset de 2 GB), o arquivo deverá ser baixado localmente, e a variável global UTILIZAR_DATASET_REDUZIDO_PARA_ANALISES (primeira célula do notebook) deverá ser alterada para False, para que o script busque o dataset completo, que deverá estar no caminho d:\\datasets\\IMP_COMPLETA.csv, no drive local.

Os gráficos e tabelas apresentados no TCC, relativos às análises exploratórias, foram obtidos a partir do dataset completo (de 2 GB). Por essa razão, os gráficos e tabelas gerados com a versão reduzida podem ser ligeiramente diferentes daqueles apresentados no TCC.

#### Resultados (output do script)
Uma cópia do notebook, com todos os gráficos e tabelas gerados com o dataset completo, está disponível na pasta **/resultados** deste repositório.
