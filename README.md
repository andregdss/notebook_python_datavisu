# Notebook Didático de Data Visualization em Python

Este repositório apresenta um guia detalhado sobre as principais ferramentas de **visualização de dados em Python**.  
O foco central é demonstrar como transformar gráficos básicos em **instrumentos eficazes de comunicação visual**, utilizando bibliotecas clássicas, recursos interativos e técnicas avançadas de estilização de tabelas.

O material está organizado em um notebook didático, combinando fundamentos teóricos, exemplos práticos e boas práticas de design informacional.

## 📚 Conteúdo do Notebook

O arquivo `python_data_visualization.ipynb` está dividido em quatro seções fundamentais, abrangendo bibliotecas amplamente utilizadas tanto no meio acadêmico quanto no mercado.

### 1. Matplotlib

Considerada a biblioteca base para visualização em Python, esta seção explora a construção de gráficos desde os níveis mais fundamentais até customizações avançadas.

- **Criação de Gráficos**
  - Gráficos de linha, barras (verticais e horizontais), histogramas, boxplots, dispersão e gráficos de pizza
- **Ajustes de Eixos e Legendas**
  - Configuração de títulos, rótulos (`xlabel`, `ylabel`)
  - Definição de limites (`xlim`, `ylim`)
  - Posicionamento estratégico de legendas
- **Anotações e Texto**
  - Inserção de anotações personalizadas em pontos de interesse
  - Destaque de informações relevantes diretamente no gráfico
- **Metodologia de Subplots**
  - Uso da estrutura `fig, ax`
  - Criação e organização de múltiplos gráficos em uma mesma figura
  - Ajustes refinados de layout

### 2. Seaborn

Interface de alto nível construída sobre o Matplotlib, voltada à criação de **gráficos estatísticos claros e esteticamente consistentes**.

- **Temas e Paletas**
  - Padronização visual com `set_theme()` e `set_palette()`
- **Simplificação Visual**
  - Uso do `despine()` para remoção de elementos visuais redundantes
  - Melhoria da legibilidade e do *data-ink ratio*

### 3. Plotly Express

Biblioteca focada em **visualizações interativas**, com forte integração a aplicações web e dashboards.

- **Gráficos Dinâmicos**
  - Gráficos de linha interativos
  - Treemaps hierárquicos
- **Personalização de Traces e Layout**
  - Ajuste de margens, fontes e estrutura visual
  - Configuração de informações exibidas ao passar o mouse (*hover*)
- **Exportação**
  - Salvamento em HTML interativo
  - Exportação para imagens estáticas ou estruturas JSON

### 4. Pandas Styler

Seção dedicada à **estilização visual de tabelas (DataFrames)** diretamente no ambiente de visualização.

- **Formatação Condicional**
  - Uso de `highlight_max()`, `highlight_min()` e `background_gradient()`
- **Estilização via CSS**
  - Aplicação de seletores HTML/CSS para personalização de cabeçalhos, cores e fontes
- **Recursos Visuais Internos**
  - Inserção de barras de progresso em células com o método `.bar()`

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Matplotlib**
  - Construção de gráficos base e customizações detalhadas
- **Seaborn**
  - Estilização estatística de alto nível
- **Plotly**
  - Visualizações interativas e hierárquicas
- **Pandas (Styler)**
  - Formatação visual e estilização de tabelas

## 🚀 Como Utilizar

1. Clone o repositório
2. Instale as dependências necessárias:
   ```bash
   pip install matplotlib seaborn plotly pandas
3. Abra o notebook em um ambiente como Jupyter Notebook ou Google Colab
4. Execute as células sequencialmente para acompanhar os exemplos e aplicações
