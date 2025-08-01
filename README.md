<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=30&duration=2000&pause=1000&color=4169E1&center=true&vCenter=true&width=700&height=60&lines=Desenvolvedor+Python+|+Análise+de+Dados;Transformando+Dados+em+Insights;Bem-vindo+ao+meu+GitHub!">
</p>

# 👨🏻‍💻 Guilherme Rodrigues Almeida Rosa

### Estudante de Análise e Desenvolvimento de Sistemas | Analista de Dados | Data Science

---

💻 **Sobre Mim**:
Estudante de Análise e Desenvolvimento de Sistemas (2º semestre), com foco em aprender e aplicar conhecimentos em **Python**, **lógica de programação**, **estruturas de dados**, **POO** e **Análise de Dados**. Tenho noções iniciais de **SQL** e busco consolidar a prática por meio de projetos próprios, documentando minha evolução por aqui.

<p align="center">
  <a href="https://guilhermerodriguestech.netlify.app/" target="_blank">
    <img src="https://img.shields.io/badge/Acesse_meu_Portfólio-4169E1?style=for-the-badge&logo=googledocs&logoColor=white" alt="Acesse meu Portfólio">
  </a>
</p>

---

# 🚀 Meus Projetos de Data Science & Análise de Dados

Esta seção apresenta alguns dos projetos que desenvolvi, demonstrando minhas habilidades em análise de dados e desenvolvimento de soluções baseadas em dados.

<br>

### 📈 Projeto 1: Sistema de Análise e Geração de Relatórios de Vendas para E-commerce

Este é meu primeiro projeto mais profissional, onde apliquei um **pipeline completo de Data Science** utilizando **Python**. O objetivo foi transformar dados brutos de vendas em insights acionáveis através de um sistema robusto e modular.

#### 💡 Funcionalidades Chave:

* **Manipulação de Dados (Pandas):** Carregamento, pré-processamento, limpeza e criação de métricas (ex: `Valor_Total_Venda`).
* **Análise e Visualização (Matplotlib, Seaborn):** Geração de insights por meio de agrupamentos e criação de gráficos claros para vendas por categoria, região e tendências mensais, com exportação para PNG.
* **Persistência de Dados (SQLite):** Implementação de um banco de dados para armazenamento e recuperação de informações, simulando um ambiente real de dados.
* **Arquitetura POO:** Estruturação do código em classes (`DataManager`, `DatabaseManager`) para modularidade, escalabilidade e fácil manutenção.

**Detalhes do Projeto:**

* **Acesse o Repositório Completo:** [Link para o repositório do projeto de E-commerce](https://github.com/Guilh-Code/Gerador_de_Relatorios_Personalizados_para_E-commerce_com_Dashboard)
* **Explore a Documentação Detalhada (Jupyter Notebook):** [Link para o Jupyter Notebook no seu repositório](https://github.com/Guilh-Code/Gerador_de_Relatorios_Personalizados_para_E-commerce_com_Dashboard/blob/main/Analise_E-commerce_Explicada.ipynb)

<br>
---
<br>
<br>

### 📉 Projeto 2: Análise de Churn de Cartão de Crédito: Prevenindo o Cancelamento de Clientes

Este projeto foca na identificação e compreensão dos fatores que levam clientes a cancelar seus cartões de crédito em uma grande empresa. Utilizei **Python** para analisar dados de clientes e extrair insights acionáveis para estratégias de retenção.

#### 🎯 Objetivo Principal:

* Identificar as principais razões por trás do aumento significativo no número de cancelamentos de cartões.
* Determinar quais perfis de clientes têm maior tendência a cancelar o cartão.
* Propor ações estratégicas para evitar o churn e minimizar prejuízos.

#### 💡 Insights e Metodologia:

* **Análise Exploratória de Dados (EDA):** Visualização e interpretação de diversos atributos dos clientes (ex: categoria de cartão, tempo de cliente, inatividade, limite de crédito) para identificar padrões de cancelamento.
* **Identificação de Fatores Chave:** Descobri que a categoria do cartão (`Blue`), o tempo de relacionamento (primeiros 35 meses), a inatividade, o número de contatos do banco e o limite de crédito são fatores críticos para o churn.
* **Recomendações Estratégicas:** Com base nos insights, foram propostas soluções como revisão de benefícios, programas de retenção, ações de reativação para clientes inativos, otimização da comunicação e revisão da política de limites.



**Detalhes do Projeto:**

* **Acesse o Repositório Completo:** [Link para o repositório do projeto de Churn](https://github.com/Guilh-Code/Reducao_de_Churn_em_Cartoes_de_Credito-Uma_Analise_Preditiva)
* **Explore a Análise Detalhada (README do projeto):** [Link para o README do projeto de Churn](https://github.com/Guilh-Code/Reducao_de_Churn_em_Cartoes_de_Credito-Uma_Analise_Preditiva/blob/main/README.md)

<br>
---
<br>
<br>

### ✈️ Projeto 3: Previsão do Preço de Passagens Aéreas: Otimizando Custos de Viagem

Este projeto concentra-se no desenvolvimento de um modelo de Machine Learning capaz de **prever o preço de passagens aéreas**, utilizando Python e bibliotecas como Pandas, Matplotlib, Seaborn e Scikit-learn. O objetivo principal é auxiliar na tomada de decisão estratégica para a compra de passagens, visando a otimização de custos.

#### 🎯 Objetivo Principal:

* Construir um modelo preditivo robusto para estimar o preço de passagens aéreas com base em características do voo.
* Identificar os fatores mais influentes na precificação de passagens para fornecer insights de negócio acionáveis.
* Auxiliar empresas e indivíduos a planejar compras de passagens de forma mais econômica.

#### 💡 Insights e Metodologia:

* **Análise Exploratória de Dados (EDA):** Realizamos uma análise aprofundada para entender a distribuição dos preços e o impacto de fatores como **companhia aérea**, **antecedência da compra (`days_left`)**, **horários de partida e chegada**, **cidades de origem e destino**, e, principalmente, a **classe do voo (Economy vs. Business)**.
    * **Insights Chave:** Descobrimos que a **classe de voo** é o fator com maior impacto (Business class é 8-9x mais cara); comprar com pouca antecedência encarece a passagem; e companhias aéreas como Vistara e Air India têm preços significativamente mais altos.
  
* **Pré-processamento de Dados:** Aplicamos técnicas essenciais como **transformação logarítmica** na variável `price` (para lidar com a assimetria), **One-Hot Encoding** para variáveis categóricas e **escalonamento** para variáveis numéricas. Uma etapa crucial foi a remoção da coluna `flight` para reduzir a dimensionalidade e otimizar o modelo.

* **Modelagem Preditiva:** Desenvolvemos um modelo de **Regressão Linear** que, mesmo sendo um modelo linear simples, alcançou um **R-quadrado (R2 Score) de mais de 91%** na escala logarítmica. Na escala original dos preços, o modelo obteve um **Erro Médio Absoluto (MAE) de aproximadamente R$ 4.573,64**. Este MAE é um excelente resultado, considerando a ampla gama de preços das passagens, indicando que o modelo é altamente preciso para o contexto.

**Detalhes do Projeto:**

* **Acesse o Repositório Completo:** [link para o repositório do projeto](https://github.com/Guilh-Code/Previsao_do_preco_de_passagem_aerea)
* **Explore a Análise Detalhada (README do projeto):** [LINK_PARA_O_README_DETALHADO_DO_PROJETO](https://github.com/Guilh-Code/Previsao_do_preco_de_passagem_aerea/blob/main/README.md)
* **Confira o Código Fonte e a Metodologia Completa (Jupyter Notebook):** [LINK_PARA_O_JUPYTER_NOTEBOOK_DO_PROJETO](https://github.com/Guilh-Code/Previsao_do_preco_de_passagem_aerea/blob/main/projeto.ipynb)

---
<br>

🌱 **Atualmente aprendendo**:
* Aprofundamento em **Programação Orientada a Objetos** e design de software.
* Técnicas avançadas de **Análise e Visualização de Dados**.
* **SQL** e otimização de consultas de banco de dados.
* Boas práticas de **versionamento com Git** para colaboração e organização de projetos.

---

💬 **Vamos conectar!**
Aberto para colaborações e oportunidades de estágio onde eu possa contribuir e crescer como desenvolvedor.

<p align="center">
  <a href="https://www.instagram.com/guiznxrr/" target="_blank">
    <img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
  </a>
  <a href="mailto:guilhermerar2005@gmail.com">
    <img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>
  <a href="https://www.linkedin.com/in/guilhrodrigues/" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
  <a href="https://drive.google.com/file/d/1uLiug4wa4E-R7DTPks8W6PCOqwZDEoUf/view?usp=sharing" target="_blank">
    <img src="https://img.shields.io/badge/-Currículo-%2300C896?style=for-the-badge&logo=readme&logoColor=white" alt="Currículo">
  </a>
  <a href="https://github.com/guilh-code" target="_blank">
  <img src="https://komarev.com/ghpvc/?username=guilh-code&label=Profile%20views&color=0e75b6&style=for-the-badge" alt="Profile views" />
</a>
</p>

---

<h3 align="center">🤖 Linguagens e Tecnologias</h3>

<p align="center">
  <img 
    alt="HTML"
    title="HTML" 
    width="50px" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" 
  />&nbsp;&nbsp;&nbsp;&nbsp;
  <img 
    alt="CSS" 
    title="CSS"
    width="50px" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" 
  />&nbsp;&nbsp;&nbsp;&nbsp;
  <img 
    alt="Python" 
    title="Python"
    width="50px" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" 
  />&nbsp;&nbsp;&nbsp;&nbsp;
  <img 
    alt="Git" 
    title="Git"
    width="50px" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" 
  />&nbsp;&nbsp;&nbsp;&nbsp;
  <img
    alt="Pandas"
    title="Pandas"
    width="50px"
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg"
  />&nbsp;&nbsp;&nbsp;&nbsp;
  <img
    alt="Matplotlib"
    title="Matplotlib"
    width="50px"
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original.svg"
  />&nbsp;&nbsp;&nbsp;&nbsp;
  <img
    alt="SQLite"
    title="SQLite"
    width="50px"
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azuresqldatabase/azuresqldatabase-original.svg"
  />
</p>

---

<p align="center">
  <img src="https://github.com/guilh-code/guilh-code/blob/output/github-snake.svg" alt="Snake animation" />
</p>

---
##

