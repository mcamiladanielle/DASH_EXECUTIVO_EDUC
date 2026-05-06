# PROMPT – DASHBOARD EXECUTIVO EDUCACIONAL

# P - PERSONA
Desenvolvedor Front-end Sênior e Especialista em BI SaaS.

# A - AÇÃO
Gerar um arquivo `index.html` completo que leia um arquivo dados-educacao.csv local e calcule todos os indicadores dinamicamente via JavaScript puro.

# C - CONTEXTO
O setor é Educação.

A empresa simulada chama-se:
Instituto Brasileiro de Educação Estratégica

O CSV contém dados mensais (12 meses completos) com as seguintes dimensões:

- mes
- regiao
- modalidade (Graduação, Pós-Graduação, Cursos Livres)
- canal (Online, Presencial, Híbrido)
- unidade
- matriculas
- meta_matriculas
- receita
- custo_operacional
- taxa_evasao
- taxa_conclusao
- satisfacao_media

Regras implícitas do negócio:
- Existem picos de matrícula em início de semestre (Fev/Mar e Ago/Set).
- Dezembro apresenta queda sazonal.
- Receita depende diretamente do volume de matrículas.
- Custo operacional representa entre 55% e 70% da receita.
- Taxa de evasão impacta diretamente sustentabilidade financeira.
- Satisfação média influencia retenção e reputação institucional.

# I - INTENÇÃO
Criar um Dashboard Executivo para Diretoria Educacional com TEMA LIGHT, utilizando:

- Tailwind CSS
- ApexCharts
- Layout moderno, limpo e sofisticado
- Design executivo e minimalista
- Tipografia elegante
- Cards bem distribuídos
- Responsivo

Foco total em tomada de decisão estratégica.

# F - FORMATO

## 1. Cabeçalho
Exibir:
Instituto Brasileiro de Educação Estratégica
Subtítulo: Dashboard Executivo Educacional

## 2. KPIs Estratégicos (calculados dinamicamente)

Definir automaticamente os KPIs mais relevantes para o setor:

- Total de Matrículas (ano)
- Atingimento da Meta de Matrículas (%)
- Receita Total
- Margem Operacional (%)
- Taxa Média de Evasão
- Taxa Média de Conclusão
- Satisfação Média Geral

## 3. Gráficos Estratégicos

Selecionar automaticamente os gráficos mais adequados:

- Linha: Evolução mensal de matrículas
- Linha dupla: Receita vs Custo Operacional
- Coluna: Atingimento de meta por mês
- Barra horizontal: Matrículas por Modalidade
- Barra empilhada: Distribuição por Canal
- Heatmap ou ranking: Desempenho por Região
- Linha: Evolução da taxa de evasão

## 4. Rankings

Se fizer sentido, criar:

- Ranking de modalidades por receita
- Ranking de regiões por volume de matrículas
- Ranking de unidades por margem operacional

## 5. Alertas Estratégicos Automáticos

Implementar lógica para gerar alertas como:

- Se evasão > 10% → alerta crítico
- Se margem < 30% → alerta financeiro
- Se satisfação < 8.5 → alerta reputacional
- Se meta < 95% atingida → alerta de performance

Exibir alertas em destaque visual.

## 6. Filtros Dinâmicos

Criar filtros interativos:

- Filtro por Região
- Filtro por Modalidade
- Filtro por Canal
- Filtro por Unidade
- Filtro por Período

Todos recalculando os KPIs e gráficos em tempo real.

## 7. Lógica Técnica

- Ler CSV via fetch()
- Processar agregações via JavaScript
- Não usar backend
- Código organizado e comentado
- Estrutura limpa e escalável

Objetivo final:
Entregar uma visão executiva clara, estratégica e acionável para tomada de decisão da diretoria educacional.

Gerar o arquivo index.html completo.


/*Preciso das suas habilidade de Front end  e Especialista em BI SaaS.
Qual é o modelo ideal de prompt devo lhe passar para que você possa criar um dashboard com atualização em tempo real, responsivo, kpis calculados dinamicamente, filtros dinâmicos/interativos, rankings, alertas estratégicos automáticos, elaborar gráficos, considerando as regras de negócio pre-definidas, para que me entregue um dashboard com uma visão executiva clara, estratégica e acionável para tomada de decisão da diretoria*/
