# 📊 Dashboard de Recursos Humanos (Power BI)

## 📌 Sobre o Projeto
Este projeto apresenta um **dashboard de Recursos Humanos** desenvolvido em **Power BI**, com foco em **monitorar e analisar a força de trabalho da empresa**.  
O objetivo é fornecer insights estratégicos e operacionais sobre **admissões, demissões, turnover, diversidade e distribuição da equipe**, apoiando a gestão de pessoas na tomada de decisões.  

---

## 🗂️ Fonte dos Dados
O dataset utilizado contém informações de funcionários, incluindo:  
- **Nome do Funcionário**  
- **Data de Admissão**  
- **Data de Demissão**  
- **Cargo**  
- **Departamento**  
- **Idade**  
- **Gênero**  
- **Salário**  

---

## 📏 Métricas Calculadas
O dashboard contém as seguintes métricas principais:  

- **Funcionários Ativos** → total de colaboradores atualmente na empresa.  
- **Admissões** → número de contratações em determinado período.  
- **Demissões** → número de desligamentos no período.  
- **Turnover (%)** → relação entre demissões e média de headcount do período.  
- **Permanência Média** → tempo médio de permanência dos funcionários antes do desligamento.  
- **Idade Média** → idade média do quadro de colaboradores.  
- **Média Salarial** → salário médio dos colaboradores ativos.  

---

## 📊 Visualizações do Dashboard
O dashboard foi dividido em seções para facilitar a análise:

1. **KPIs principais** (cards no topo):  
   - Funcionários Ativos  
   - Média Salarial  
   - Turnover (%)  
   - Idade Média  

2. **Admissões X Demissões (Linha Temporal)**  
   - Gráfico de linhas mostrando a evolução das contratações e desligamentos entre 2020–2024.  

3. **Distribuição de Gênero**  
   - Gráfico de rosca comparando proporção de Feminino, Masculino e Não-binário.  

4. **Funcionários por Departamento**  
   - Gráfico de colunas exibindo a quantidade de ativos em cada área (ex.: Vendas, TI, Produção).  

5. **Distribuição Etária**  
   - Gráfico de barras horizontais com funcionários divididos por faixas etárias (18-30, 31-45, 46-60, 60+).  

6. **Detalhamento por Funcionário (Tabela)**  
   - Lista individual com Nome, Cargo, Departamento, Data de Admissão e Data de Demissão.  

7. **Diversidade por Departamento**  
   - Gráfico comparando gênero dentro de cada área da empresa.  

---

## 🔎 Insights Extraídos
- O **turnover está em 26,3%**, considerado elevado comparado a benchmarks de mercado.  
- O **departamento de TI** apresenta alta rotatividade, com admissões quase iguais às demissões.  
- A **faixa etária predominante** é **31-45 anos**, representando mais de 30% dos ativos.  
- A **distribuição de gênero** é relativamente equilibrada entre Feminino, Masculino e Não-binário.  
- A **permanência média de 20 meses** sugere que muitos colaboradores não permanecem na empresa por mais de 2 anos.  

---

## 🛠️ Tecnologias Utilizadas
- **Power BI** (modelagem e visualização)  
- **DAX** (cálculos de métricas como turnover, headcount, permanência média)  
- **Power Query (M)** (tratamento e limpeza dos dados)  

---

## 🚀 Como Usar
1. Baixe este repositório.  
2. Abra o arquivo `.pbit` no **Power BI Desktop**.  
3. Conecte-se à sua base de dados (caso queira atualizar os dados).  
4. Publique no **Power BI Service** para compartilhamento com stakeholders.  

---

## 📌 Melhorias Futuras
- Inclusão de **benchmarks externos** para comparar turnover com o setor.  
- Implementação de **análise preditiva de demissões** usando Machine Learning.  
- Criação de uma aba específica para **diversidade e inclusão**.  

---

✍️ **Autora:** Giselle Freitas Moura  
📧 **Contato:** gisellinhapb@gmail.com
