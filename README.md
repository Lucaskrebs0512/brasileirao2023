# ⚽ Brasileirão 2023 — Dashboard com Interface Dinâmica

Dashboard desenvolvido no Power BI para analisar os resultados do Campeonato Brasileiro Série A de 2023, com foco em Dataviz, UX e apresentação das informações na camada Gold.

O principal diferencial é a **identidade visual dinâmica**: ao selecionar um time, o relatório adapta suas cores e layout ao clube escolhido e apresenta os indicadores correspondentes.

## 🎯 Objetivo

Reunir informações do campeonato em uma única página interativa, permitindo explorar a classificação, os resultados e o desempenho dos clubes por time, rodada e período.

## 🎨 Interface personalizada por clube

Na visão geral, o dashboard apresenta a identidade visual do Brasileirão. Ao filtrar um time, a interface adapta elementos como:

- Cores e fundos.
- Escudo e identificação do clube.
- Elementos de layout.
- Indicadores e jogos apresentados.

Os elementos gráficos foram elaborados no Canva e integrados aos visuais e às interações do Power BI.

## 📊 Indicadores

- Quantidade de partidas no contexto selecionado.
- Gols feitos e sofridos.
- Média de gols por jogo.
- Pontos acumulados.
- Saldo de gols.
- Aproveitamento como mandante e visitante.
- Posição no campeonato.
- Média de gols feitos e sofridos.
- Taxa de clean sheets — jogos sem sofrer gols.
- Maior vitória e maior derrota.

## 🔎 Análises disponíveis

### Classificação

Tabela com posição, clube, vitórias, empates, derrotas, gols feitos, gols sofridos, saldo de gols e pontos.

As cores identificam as faixas de Libertadores, Pré-Libertadores, Sul-Americana e rebaixamento.

### Gols feitos × sofridos por rodada

Comparação do desempenho ofensivo e defensivo ao longo das rodadas.

### Últimos jogos

Consulta das partidas com clubes, escudos, placares e datas, conforme os filtros aplicados.

### Resumo do campeonato

Cartões com médias de gols, taxa de clean sheets, maior vitória e maior derrota.

### Resultados

Distribuição de vitórias, empates e derrotas, acompanhada de um indicador percentual de desempenho.

### Faixa de gols por partida

Distribuição das partidas conforme a quantidade total de gols.

## 🎛️ Filtros

- **Rodada:** seleção das rodadas analisadas.
- **Time:** seleção do clube e adaptação da identidade visual.
- **Data:** definição do período de análise.

## ⚙️ Desenvolvimento

### 1. Origem dos dados

Foi utilizada uma base CSV já pronta com informações do Brasileirão 2023, importada para o Power BI.

### 2. Preparação no Power Query

Foram adicionadas colunas no próprio Power Query, utilizando a interface e a linguagem M, para apoiar as análises do relatório.

### 3. Dimensão calendário

A tabela `dCalendário` foi criada em M para apoiar a análise temporal e os filtros de período.

### 4. Indicadores

Os indicadores foram desenvolvidos no Power BI com medidas DAX e configuração das interações entre filtros e visuais.

### 5. Construção visual

O Canva foi utilizado na elaboração dos fundos e elementos gráficos. No Power BI, esses elementos foram integrados aos cartões, tabelas, gráficos e filtros.

O relatório possui uma única página, com apresentação visual adaptada ao time selecionado.

## 🥇 Foco na camada Gold

O foco do projeto foi a camada Gold: organização das informações para análise, construção de indicadores e apresentação dos resultados ao usuário.

A partir de uma base CSV pronta, o trabalho concentrou-se na preparação necessária dos dados e, principalmente, na construção de uma experiência visual clara, interativa e personalizada por clube.

## 🛠️ Ferramentas

| Ferramenta | Aplicação |
| --- | --- |
| CSV | Fonte dos dados |
| Power BI | Relatório, indicadores e interações |
| Power Query | Preparação dos dados e criação de colunas |
| M | Transformações e dimensão calendário |
| DAX | Medidas e indicadores |
| Canva | Fundos e elementos visuais |

## 🧠 Aprendizados

O projeto permitiu praticar a preparação de dados no Power Query, a criação de uma dimensão calendário em M e o desenvolvimento de medidas no Power BI.

O principal aprendizado foi combinar Dataviz e UX com uma identidade visual dinâmica, conectando os dados apresentados ao clube selecionado.

## 👤 Autor

**Lucas Krebs**  
Analista de Dados | Power BI | SQL | Business Intelligence

[LinkedIn](https://www.linkedin.com/in/lucaskrebs05) · [GitHub](https://github.com/Lucaskrebs0512)
