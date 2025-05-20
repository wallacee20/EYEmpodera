# EYEmpodera
# 🛒 Projeto Mercado Empodera – Análise de Dados e Arquitetura de Soluções

Este projeto foi desenvolvido como forma de **colocar em prática todo o conhecimento adquirido no programa EYEmpodera**, que abordou desde competências técnicas até habilidades de desenvolvimento pessoal e profissional. A iniciativa simula a construção de um mercado fictício chamado **Empodera**, abrangendo desde a definição do modelo de negócio até a análise de dados com visualização em dashboards.

## 🌟 Competências Aplicadas

Durante o desenvolvimento deste projeto, foram aplicados aprendizados nas seguintes áreas:

- **Engenharia e Governança de Dados**
- **Arquitetura de ETL na Azure (Data Factory, Delta Lake, Camadas Bronze/Silver/Gold)**
- **Modelagem de Dados (MER e Físico no SQL Server)**
- **Lógica de Programação e Python**
- **Estatística Aplicada**
- **Análises de Negócios**
- **Power BI para Visualização de Dados**
- **GitHub para Versionamento**
- **Mentalidade de Crescimento, Marca Pessoal e Carreira**
- **Automação Inteligente e Cultura Agile/DevOps**

## 🧱 Etapas do Projeto

### 1. 📈 Definição do modelo de negócio
O ponto de partida do projeto foi a criação de um modelo de negócio para um supermercado fictício, o Mercado Empodera, com o objetivo de simular operações reais de varejo. Essa simulação permitiu estruturar uma base sólida de dados, considerando processos operacionais, comerciais e estratégicos.

- Foram definidos os principais elementos que compõem a jornada de compra e gestão de um supermercado:

- Clientes: identificação de perfis de consumo, frequência de compras e ticket médio.

- Produtos: cadastro de itens comercializados com categorias, preços e status de estoque.

- Vendas: simulação de notas fiscais com data, horário, forma de pagamento e valor total.

- Itens de venda: detalhamento dos produtos vendidos por nota fiscal.

- Vendedores: registro de colaboradores responsáveis pelas vendas, com foco em performance.

Essa etapa foi essencial para garantir que a estrutura de dados refletisse os processos de negócio, possibilitando análises assertivas e visualizações estratégicas posteriormente. Além disso, contribuiu para a construção do modelo relacional e definição da arquitetura de dados adotada.

### 2. 📘 Modelagem Entidade-Relacionamento (MER)
Nesta etapa do projeto, foi realizada a modelagem lógica e física do banco de dados que representa o funcionamento do Mercado Empodera, com foco em refletir fielmente as regras de negócio de um supermercado.
Através da técnica de modelagem entidade-relacionamento (MER), foram definidos os principais componentes do sistema e suas interações, visando garantir consistência, integridade referencial e escalabilidade dos dados.

As tabelas principais criadas foram:

> Clientes: contendo informações como CPF, nome, idade, sexo, endereço e volume de compras.

> Produtos: com dados sobre código, nome, embalagem, tamanho, sabor e preço de lista.

> Notas Fiscais: registrando as compras realizadas, associadas a clientes e vendedores.

> Itens de Notas Fiscais: detalhando os produtos vendidos em cada nota com quantidade e valor unitário.

> Vendedores: com informações como matrícula, nome, percentual de comissão e data de admissão.

O banco de dados foi implementado no SQL Server, com as devidas chaves primárias, estrangeiras e relacionamentos normalizados. Esse modelo possibilita análises complexas de performance de vendas, comportamento de compra dos clientes e eficiência da equipe comercial.

![Relacionamento](imagens/relacionamento.png)

### 3. 🧩 Criação do banco de dados no SQL Server
Com base no modelo entidade-relacionamento (MER) definido, foi realizada a implementação do banco de dados relacional no SQL Server para dar suporte ao funcionamento do projeto Mercado Empodera.
As principais etapas desta fase foram:
![database](imagens/arquitetura.png)
- Criação do banco de dados MercadoEmpodera.
- Implementação das tabelas com base no modelo físico: Clientes, Produtos, NotasFiscais, ItensNotasFiscais e Vendedores.
- Definição de chaves primárias e estrangeiras para garantir integridade referencial entre as tabelas.
- Criação de relacionamentos entre os dados, refletindo a estrutura de um sistema de vendas real.
- Inserção de dados simulados nas tabelas, com base em cenários verossímeis de um supermercado:
- Clientes com diferentes perfis de consumo e localização.
- Produtos de diversas categorias com variações de tamanho e sabor.
- Vendedores com diferentes níveis de comissão.
- Notas fiscais simulando o histórico de compras.
- Itens das notas detalhando os produtos vendidos.

Esta etapa garante a base sólida para as etapas seguintes de ETL, análises e visualização, assegurando que os dados estejam bem estruturados e prontos para processamento.

### 4. ☁️ Arquitetura de Dados na Azure (Data Lake + Delta Lake)
Aplicação da arquitetura em camadas (Bronze, Silver, Gold) com refinamento via notebooks e orquestração usando Data Factory.

![Arquitetura Azure](imagens/arquitetura.png)

### 5. ⚙️ ETL e Consultas Analíticas
Pipelines de ETL com transformação dos dados usando Python e SQL, organizando em zonas de chegada, refinamento e curada.
![ETL](imagens/arquitetura.png)

### 6. 📊 Etapa de Analytics e Visualização
Criação de dashboards no Power BI com indicadores como:
- Produtos mais vendidos
> Faturamento por loja
![analise1](imagens/arquitetura.png)
> Desempenho de vendedores
![analise2](imagens/arquitetura.png)
- Perfil dos clientes e frequência de compra

## 🛠️ Tecnologias Utilizadas

- **SQL Server**
- **Python (Pandas, PySpark)**
- **Azure Data Factory**
- **Azure Data Lake / Delta Lake**
- **Power BI**
- **Git & GitHub**
- **Excel (auxiliar na análise)**

## 📌 Conclusão

Este projeto representa uma jornada completa desde a concepção até a entrega de valor via dados, consolidando os pilares desenvolvidos no EYEmpodera. Mais do que um exercício técnico, é um reflexo da minha **mentalidade de crescimento**, **visão analítica** e capacidade de **resolver problemas com propósito**.
