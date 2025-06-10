📘 Glossário do Projeto


Para este projeto, usamos uma base de dados brasileira recente: ATLANTIC FLOWER-INVERTEBRATE INTERACTIONS (Boscolo, 2023), que registra interações entre flores e invertebrados na Mata Atlântica. Os dados foram adaptados especialmente para esta disciplina e estão no anexo AtlanticForestInvertFloInteractionData_2022-07. Não utilize a versão original do GitHub.

🧪 Fase 1 – Análise Exploratória e Preparação
Nesta fase, o objetivo é explorar e entender os dados (EDA – Exploratory Data Analysis), analisando tipo de dados, atributos, escalas, frequência, distribuição, valores ausentes, etc.

Também é necessário limpar e transformar os dados, corrigir valores inconsistentes e escolher os atributos mais importantes para a classificação que será feita na Fase 2.

⚠️ Atributos com atenção especial:
temperature e relative_humidity: possuem valores como números e intervalos, e muitos valores ausentes. Precisam ser padronizados e tratados antes do uso.

🧹 Como preencher dados faltantes com K-means
Identifique os atributos faltantes (ex: temperature) e as linhas com esses dados ausentes.

Crie uma cópia do dataset sem os atributos faltantes (ex: sem a coluna temperature). Essa versão precisa estar completa (sem valores ausentes).

Aplique o algoritmo K-means nessa versão para encontrar clusters de registros parecidos. Defina o valor ideal de k.

Descubra em quais clusters estão as linhas com dados faltantes.

Preencha os valores ausentes com base na média, mediana ou moda dos registros similares no mesmo cluster.
