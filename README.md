# dashboard-vendas-excel
Projeto DIO Criando um Dashboard de Vendas do Xbox com Excel

# Dashboard de Vendas

## 🎯 Objetivo
O objetivo deste desafio é **criar um dashboard de vendas**, com foco na organização e visualização de dados.  
A meta é transformar dados brutos de assinaturas em **informações visuais claras e úteis**, permitindo uma análise eficaz do desempenho de vendas e a tomada de decisões baseadas em dados.

---

## 📊 Dados Utilizados
Os dados de entrada são referentes a assinaturas de diferentes planos (Core, Standard e Ultimate), contendo:

- **Subscriber ID**: Identificação única do assinante  
- **Nome**: Nome do assinante  
- **Plano**: Core, Standard ou Ultimate  
- **Data de início**: Data da assinatura  
- **Autorrenovação**: Sim ou Não  
- **Preço da assinatura**: Valor do plano  
- **Tipo de assinatura**: Mensal, Trimestral ou Anual  
- **Season Pass EA Play**: Inclusão ou não  
- **Season Pass Minecraft**: Inclusão ou não  
- **Valores de cupons aplicados**  
- **Valor total da assinatura**

---

## ❓ Perguntas de Negócio
O dashboard deve responder às seguintes perguntas:

1. **Qual faturamento total de vendas de planos anuais (com todas as assinaturas agregadas)?**  
2. **Qual faturamento total de vendas dos planos anuais, separados por autorrenovação (Não e Sim)?**  
3. **Qual plano (Core, Standard ou Ultimate) gera maior receita total considerando todas as assinaturas?**

---

## 🛠️ Passo a Passo para Reprodução

1. **Importar os dados**  
   - Abra o Excel e importe o arquivo com os dados brutos de assinaturas.  
   - Organize os dados em uma tabela estruturada.  

2. **Criar colunas auxiliares**  
   - Identifique quais assinaturas são **anuais**.  
   - Crie colunas para calcular valores agregados (ex.: receita total por tipo de plano).  

3. **Construir Tabelas Dinâmicas**  
   - Crie uma tabela dinâmica para calcular o **faturamento total de planos anuais**.  
   - Crie outra tabela dinâmica para separar o faturamento por **autorrenovação (Sim/Não)**.  
   - Crie uma tabela dinâmica para comparar a **receita total por plano (Core, Standard, Ultimate)**.  

4. **Criar Gráficos Dinâmicos**  
   - Gráfico de colunas para faturamento total dos planos anuais.  
   - Gráfico de barras para faturamento separado por autorrenovação.  
   - Gráfico de pizza ou colunas para receita por plano.  

5. **Montar o Dashboard**  
   - Crie uma aba chamada **Dashboard**.  
   - Insira os gráficos e KPIs de forma organizada e visualmente clara.  
   - Adicione filtros interativos (ex.: por período ou tipo de plano).  

---

## 📂 Estrutura do Arquivo Excel
O arquivo Excel final deve conter:
- **Aba Dados Brutos**: dados originais das assinaturas.  
- **Aba Tabelas Dinâmicas**: cálculos e consolidações.  
- **Aba Dashboard**: gráficos e indicadores principais.  

---

## 🚀 Instruções de Uso
1. Abra o arquivo Excel fornecido.  
2. Vá até a aba **Dashboard**.  
3. Explore os gráficos e KPIs para responder às perguntas de negócio.  
4. Utilize os filtros para análises adicionais.  

---

## ✅ Resultado Esperado
Um dashboard interativo que permita:
- Visualizar o **faturamento total de planos anuais**.  
- Comparar o faturamento por **autorrenovação (Sim/Não)**.  
- Identificar qual plano gera **maior receita total**.  
