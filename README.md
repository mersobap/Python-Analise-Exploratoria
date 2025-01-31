<h1 align="center">
    <img src="./images/imgProjeto02.jpeg" alt="Análise Exploratória" width = "200" /><br />
    <b>Análise Exploratória de Dados com Python - AdventureWorks</b>
    <br />
      <a
        href="https://github.com/mersobap/Python-Analise-Exploratoria/actions/workflows/build.yml"
      >
        <img
          src="https://github.com/mersobap/Python-Analise-Exploratoria/actions/workflows/build.yml/badge.svg"
          alt=""
        />
      </a>
      <a href="https://github.com/mersobap/Python-Analise-Exploratoria/releases/latest">
        <img
          src="https://img.shields.io/github/v/release/mersobap/Python-Analise-Exploratoria"
          alt="Latest Release"
        />
      </a>
</h1>

Bem-vindo ao projeto de Análise Exploratória de Dados (EDA) utilizando Python, baseado no dataset **AdventureWorks.xlsx**. Aqui, vamos explorar um processo estruturado para compreender profundamente a fonte de dados, identificar padrões, visualizar informações e preparar a base para análises futuras.

## 📖 Sumário

- [Objetivo](#objetivo)
- [Descrição do Projeto](#descrição-do-projeto)
- [Fases do Projeto](#fases-do-projeto)
- [Técnicas Utilizadas](#técnicas-utilizadas)
- [Bibliotecas Utilizadas](#bibliotecas-utilizadas)
- [Links Úteis](#links-úteis)
- [Requisitos do Projeto](#requisitos-do-projeto)
- [Como Executar o Projeto](#como-executar-o-projeto)
- [Resultados Esperados](#resultados-esperados)
- [Contribuições](#contribuições)
- [Licença](#licença)
- [Contato](#contato)


## :atom: Objetivo

O principal objetivo deste projeto é demonstrar um fluxo básico para a realização de uma análise exploratória inicial e compreensão da fonte de dados, utilizando o Python como ferramenta principal. Além disso, buscamos apresentar o processo de execução desta análise de forma detalhada e intuitiva.

## 📓 Descrição do Projeto

Este projeto envolve a análise do dataset **AdventureWorks.xlsx**, que contém dados fictícios de uma empresa de vendas de equipamentos esportivos. Através da Análise Exploratória de Dados, pretendemos:

- Compreender a estrutura e o conteúdo do dataset.
- Identificar e tratar valores ausentes ou inconsistentes.
- Realizar análises estatísticas básicas.
- Visualizar os dados de forma clara e informativa.
- Preparar a base de dados para futuras análises ou modelos preditivos.

## 🪧 Fases do Projeto

1. **Importação de Bibliotecas**

   Iniciamos importando as bibliotecas essenciais para manipulação e visualização dos dados.

2. **Carga da Fonte de Dados**

   Carregamos o dataset **AdventureWorks.xlsx** para o ambiente de trabalho.

3. **Inspeção Inicial**

   Exploramos o dataset para entender sua estrutura, dimensões e tipos de dados.

4. **Personalização de Colunas**

   Renomeamos e reorganizamos colunas para melhorar a legibilidade e facilitar análises futuras.

5. **Analisando Dados Inválidos (Missing Values e NA)**

   Identificamos e tratamos valores ausentes ou inválidos, utilizando técnicas como exclusão ou imputação de dados.

6. **Análises de Dados com Agrupamento**

   Agrupamos os dados com base em categorias relevantes para identificar padrões e tendências.

7. **Apresentação em Gráficos**

   Utilizamos ferramentas de visualização para criar gráficos que ilustrem insights interessantes dos dados.

8. **Análise Estatística Básica e Explicações**

   Realizamos análises estatísticas simples para aprofundar nosso entendimento sobre o comportamento dos dados.

9. **Salvamento da Base de Dados Personalizada**

   Salvamos uma versão limpa e preparada do dataset para usos futuros.

## Técnicas Utilizadas

Neste projeto, aplicamos diversas técnicas fundamentais para a análise exploratória de dados:

- **Tratamento de Dados Ausentes**: Identificação e manipulação de valores nulos ou faltantes.
- **Análise Descritiva**: Cálculo de estatísticas básicas como média, mediana, moda e desvio padrão.
- **Visualização de Dados**: Criação de gráficos para identificar tendências e padrões ocultos.
- **Agrupamento de Dados**: Segmentação do dataset por categorias para análises mais detalhadas.
- **Limpeza e Preparação de Dados**: Remoção de inconsistências e padronização dos dados para análises futuras.

## 📖 Bibliotecas Utilizadas

As seguintes bibliotecas foram utilizadas neste projeto:

- **[Pandas](https://pandas.pydata.org/)**: Para manipulação e análise de estruturas de dados.
- **[Matplotlib](https://matplotlib.org/)**: Para criação de visualizações estáticas, animadas e interativas.
- **[Seaborn](https://seaborn.pydata.org/)**: Para visualizações estatísticas aprimoradas.

## Links Úteis

- **Documentação do Pandas**: [https://pandas.pydata.org/docs/](https://pandas.pydata.org/docs/)
- **Documentação do Matplotlib**: [https://matplotlib.org/stable/contents.html](https://matplotlib.org/stable/contents.html)
- **Documentação do Seaborn**: [https://seaborn.pydata.org/tutorial.html](https://seaborn.pydata.org/tutorial.html)
- **Tutorial de Análise Exploratória de Dados**: [Análise Exploratória de Dados com Python](https://www.datacamp.com/community/tutorials/exploratory-data-analysis-python)
- **Conceitos de Estatística Descritiva**: [Estatística Descritiva](https://pt.wikipedia.org/wiki/Estat%C3%ADstica_descritiva)

## Requisitos do Projeto

Antes de começar, certifique-se de que seu ambiente atenda aos seguintes requisitos:

- **Python 3.x**: Linguagem de programação principal utilizada.
- **Ambiente de Desenvolvimento**: Recomenda-se o uso de Jupyter Notebook, Google Colab ou qualquer IDE de sua preferência.
- **Bibliotecas Necessárias**:
  - Pandas
  - Matplotlib
  - Seaborn

## 🏃‍♂️ Como Executar o Projeto

1. **Pré-requisitos**

   Certifique-se de ter Python 3.x instalado em sua máquina. Utilize um ambiente virtual para gerenciar as dependências.

2. **Instalação das Bibliotecas**

   Instale as bibliotecas necessárias utilizando o *pip*:

   ```bash
   pip install pandas matplotlib seaborn
   ```

3. **Clonar o Repositório**

   Clone este repositório em sua máquina local:

   ```bash
   git clone https://github.com/mersobap/Python-Analise-Exploratoria.git
   ```

4. **Executar o Notebook**

   Abra o Jupyter Notebook e execute o arquivo `analise_adventureworks.ipynb` para reproduzir a análise passo a passo.

## 🏹 Resultados Esperados

- **Entendimento Profundo dos Dados**: Compreender a estrutura, as variáveis e o conteúdo do dataset.
- **Dados Limpos e Preparados**: Obter uma versão do dataset sem inconsistências ou valores ausentes.
- **Visualizações Informativas**: Gráficos que destacam insights significativos, como tendências e padrões.
- **Análises Estatísticas**: Estatísticas descritivas que resumem as principais características dos dados.
- **Base de Dados Personalizada**: Um arquivo pronto para ser utilizado em análises mais avançadas ou modelos de machine learning.

## 🤝 Contribuições

Contribuições são super bem-vindas! Se você tem sugestões de melhoria, encontrou algum problema ou deseja adicionar novas análises, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

## Licença

Este projeto está licenciado sob os termos da licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Se tiver alguma dúvida, sugestão ou quiser conversar sobre o projeto, entre em contato:

- **Email**: emersonbap@terra.com.br
- **LinkedIn**: Emerson de Oliveira Batista (https://www.linkedin.com/in/eng-emerson-batista/)
- **GitHub**: Mersobap (https://github.com/mersobap)

---
