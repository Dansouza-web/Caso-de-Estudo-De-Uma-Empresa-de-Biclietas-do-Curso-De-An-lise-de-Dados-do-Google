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

**2.[EXPLORANDO OS DADOS |EDA|](Exploração.ipynb)**

**3.[LIMPEZA DE DADOS|CLEANING|](Limpeza.ipynb)**

**4.ANÁLISE DE DADOS(ANALYSIS)**

#[Processando os dados](Processo.ipynb):

vejo que a base de dados é de *Março De 2026* e há 197428 linhas e 15 colunas
■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■

2.##[Explorando os Dados](Exploração.ipynb):

Eu Importei A base de Dados e verifiquei se havia **dados nulos, inconsistências, e erros** dentro da base de dados
■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■

3.##[Limpando os Dados](Limpeza.ipynb)

Para eu realizar a limpeza de dado, somei todos os valores nulos e duplicados e deletei, depois mudei o tipo de dado de "started at" que é uma coluna de horas para tipo de data datetime64[ns].

depois realizei uma abreviação no nomes das colunas para ficar mais facil de realizar as análises usando os str.low.

e depois adicionei colunas úteis como  a de dia e hora.

■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■

4.ANÁLISE

    {ANÁLISE DE DADOS}

A questão análtica é:

    De que maneiras os membros anuais e os ciclistas ocasionais usam as bicicletas Cyclistic?


<img width="651" height="556" alt="Captura de tela 2026-03-17 164817" src="https://github.com/user-attachments/assets/9df9a4f7-3b90-41b7-83e3-65f07fd4ef2a" />

Aqui podemos ver que a taxa de ciclistas membros tem uma atividade maior doque ciclistas casual

Assim a taxa de ciclistas **membros** tendo uma taxa de 59.4% das corridas totais de 2026.

■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■

-*Tipos de Bicicletas*

O tipo de bicicletas usadas nas viagens.

<img width="1131" height="634" alt="Captura de tela 2026-03-17 165817" src="https://github.com/user-attachments/assets/30add031-2ac5-45ba-8b5e-38f06fa4d727" />

*Podemos concluir que há uma preferência por bicicletas elétricas*.


-*Estações Mais Usadas*


<img width="749" height="669" alt="Captura de tela 2026-03-17 170125" src="https://github.com/user-attachments/assets/8cfe0ea2-9f6e-4cac-8cfa-15d6a62cb1d7" />


Conseguimos concluir que a estação usada é O *Canal St e Madison St* e a menos Usada é O *Wells St e Concord Ln*.


-*Viagens Por Dias Da Semanas Por Tipo De Ciclistas*

<img width="635" height="699" alt="Captura de tela 2026-03-17 173314" src="https://github.com/user-attachments/assets/9934b54f-caa6-4927-9658-1e3bb36a5add" />

Podemos ver que quarta feira é o dia que mais ciclistas viajam.



#*5. COMPARTILHAR*

