# Trabalho Prático – Análise de Dados do Setor de Fast Food nos EUA (2019)

<div style="background: linear-gradient(135deg, #1e3c72, #2a5298); padding: 20px; border-radius: 10px; color: white; text-align: center;">
    <p style="font-size:18px;"><b>Disciplina:</b> Lógica de Programação</p>
    <p style="font-size:18px;"><b>Curso:</b> Administração - ESPM</p>
</div>

## 📌 Sobre o Projeto
Este projeto foi desenvolvido como atividade avaliativa prática para aplicar conceitos de manipulação, tratamento e visualização de dados em **Python**. O objetivo principal é extrair insights estratégicos de negócios a partir de um conjunto de dados real do setor de *fast food* norte-americano no ano de 2019.

## 👨‍💻 Desenvolvedores
* **Lucas Tinoco**
* **Leonardo Gil**

## 📊 Estrutura do Dataset Analisado
O notebook processa e analisa indicadores-chave das maiores redes de fast food, incluindo:
* `company`: Nome da rede
* `category`: Segmento de atuação (ex: *burger, snack, chicken, global*)
* `sales_in_millions_2019`: Faturamento total em milhões de dólares
* `sales_per_unit_thousands_2019`: Eficiência de vendas (faturamento médio por unidade instalada)
* `total_units_2019`: Total de lojas ativas
* Divisão operacional de lojas franqueadas (`franchised_units_2019`) versus lojas próprias (`company_owned_units_2019`).

## 📈 Principais Conclusões & Insights Obtidos
A partir das análises estatísticas e das plotagens visuais desenvolvidas no código, observou-se que:

1. **Concentração de Mercado:** O faturamento total está altamente concentrado nas maiores marcas, mas o desempenho por categoria difere bastante.
2. **Eficiência Operacional:** Ter o maior número de pontos de venda não se traduz necessariamente na maior eficiência. Redes com menor capilaridade territorial demonstraram performance média de vendas por loja superior a gigantes do setor.
3. **Modelos de Expansão:** O modelo de franquias predomina massivamente entre os líderes de mercado, consolidando-se como o motor principal para escala e crescimento acelerado.

**Resultado Geral:** Decisões de expansão e gestão de canais precisam ponderar o trade-off entre o ganho de escala física e a manutenção da eficiência por unidade comercial.

## 🛠️ Tecnologias Utilizadas
* **Python 3**
* **Pandas** (Tratamento e estruturação dos dados)
* **Matplotlib / Seaborn** (Criação de gráficos e mapas visuais)
* **Jupyter Notebook / Google Colab** (Ambiente de desenvolvimento)

## 🚀 Como Executar o Projeto
O projeto pode ser visualizado e executado diretamente pelo navegador através do Google Colab, sem a necessidade de instalar nada no seu computador.

Clique no botão abaixo para abrir o notebook interativo:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dERvLmYNbgRBdzm8cMbYwlwqdMOqlbOR?usp=sharing)
