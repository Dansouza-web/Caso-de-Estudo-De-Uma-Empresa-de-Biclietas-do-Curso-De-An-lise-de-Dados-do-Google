# Caso-de-Estudo-De-Uma-Empresa-de-Biclietas-do-Curso-De-An-lise-de-Dados-do-Google

*Estudo de Caso de Compartilhamento de Bicicletas para Ciclistas*

##📝 Inicio
O estudo de caso do sistema de compartilhamento de bicicletas Cyclistic Bike Share é um projeto final para o Certificado Profissional em Análise de Dados do Google na Coursera. Neste projeto, seguirei o processo de análise de dados que aprendi no curso:perguntar, preparar, processar, analisar, compartilhar e agirAnalisar os dados.

💬 Cenário
A Cyclistic é uma empresa de compartilhamento de bicicletas com sede em Chicago que lançou um programa de sucesso em 2016. Ao longo dos anos, o programa expandiu-se significativamente, contando agora com uma frota de 5.824 bicicletas e uma rede de 692 estações geolocalizadas espalhadas pela cidade. Com a grande quantidade de bicicletas em diversas estações, os clientes podem alugar bicicletas em uma estação e devolvê-las em qualquer outra da rede, conforme sua conveniência. Isso incentiva as pessoas a optarem pela bicicleta como meio de transporte, contribuindo, assim, para o sucesso do programa de compartilhamento de bicicletas da Cyclistic.

A estratégia de marketing da Cyclistic tem se concentrado, até o momento, em aumentar o reconhecimento da marca e atrair diversos segmentos de consumidores. A empresa oferece planos de preços flexíveis que atendem às diversas necessidades dos usuários, incluindo passes para viagens individuais, passes diários e assinaturas anuais. Além disso, disponibiliza bicicletas reclináveis, triciclos adaptados e bicicletas de carga, acolhendo com sucesso pessoas com deficiência e aquelas que não conseguem andar em bicicletas convencionais de duas rodas. De acordo com o banco de dados da empresa, os usuários da Cyclistic geralmente usam a plataforma para lazer, mas cerca de 30% a utilizam para ir ao trabalho diariamente. Embora as bicicletas tradicionais continuem sendo a opção mais popular, cerca de 8% dos usuários optam pelas alternativas adaptadas.

O diretor de marketing da empresa acredita que o sucesso futuro da empresa depende da maximização do número de assinaturas anuais. Portanto, como analista de dados júnior, minha equipe e eu precisamos entender como os usuários ocasionais e os assinantes anuais utilizam as bicicletas da Cyclistic de maneiras diferentes. Com base nessas informações, desenvolveremos uma nova estratégia de marketing para converter usuários ocasionais em assinantes anuais.
■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■

ETAPAS:

**1-❓ASK/PERGUNTE**:**[A parte de perguntas é essencial para extrair os insights desejados pelos altos cargos da empresa]**

Tarefa de Negócio

Analisar como membros anuais e usuários casuais utilizam as bicicletas da Cyclistic de maneira diferente para ajudar a equipe de marketing a criar estratégias que convertam usuários casuais em membros.
Questões para orientar o futuro programa de marketing:

**|De que maneiras diferentes os membros anuais e os ciclistas ocasionais usam as bicicletas Cyclistic?

  |Por que ciclistas ocasionais comprariam assinaturas anuais da Cyclistic?
  
  |Como a Cyclistic pode usar as mídias digitais para influenciar ciclistas ocasionais a se tornarem membros?**

■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■

**2-🔄️PREPARAR**:**[Coleta da Base de Dados]**

FONTE USADA: [divvy-tripdata](https://divvy-tripdata.s3.amazonaws.com/index.html)

**[Lembrando que Os dados foram disponibilizados pela Motivate International Inc[MIT]**. [sobre esta licença](https://github.com/Dansouza-web/Caso-de-Estudo-De-Uma-Empresa-de-Biclietas-do-Curso-De-An-lise-de-Dados-do-Google/blob/main/Licen%C3%A7a) 

Cada registro inclui informações como:

**ID da viagem**

**Tipo de bicicleta**

**Data e horário de início da viagem**

**Data e horário de término da viagem**

**Estação de início**

**Estação de destino**

**TiPo de usuário (membro ou casual)**

**Estrutura dos Dados**

**Os dados estão armazenados em arquivos no formato CSV.**

**Ferramentas Usadas🛠️:**
Limpeza e Processamento de Dados : **Google Colab**
Visualização de Dados : **Google Colab**
■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■

**3-PLANEJAMENTO DO PROJETO**
O Projeto No Geral Está divido em 4 passos antes de analisar e extrair insights:

**1.[PROCESSAR OS DADOS](Processo.ipynb)**

**2.[EXPLORANDO OS DADOS |EDA|](https://github.com/Dansouza-web/Caso-de-Estudo-De-Uma-Empresa-de-Biclietas-do-Curso-De-An-lise-de-Dados-do-Google/blob/main/Explora%C3%A7%C3%A3o.ipynb)**

**3.LIMPEZA DE DADOS(CLEANING)**

**4.ANÁLISE DE DADOS(ANALYSIS)**

**💻PROCESSAR**: 
Antes da minha análise, precisei realizar um processo de limpeza e preparação dos dados para garantir o uso correto.
#Etapas de Limpeza de Dados No Data Set:
**Remoção de registros com valores ausentes ou inconsistentes**

**Conversão das colunas de data para o formato de data e hora**

**Criação de uma nova coluna chamada duração_da_viagem**

**Criação de uma coluna chamada dia_da_semana para identificar padrões de uso**

**Remoção de viagens com duração negativa ou irreal**

■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■

**4-EXPLORANDO OS DADOS:**
