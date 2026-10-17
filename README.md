# 📊 Tratamento e Análise de Dados de Vendas — Oxetech Academy

Este repositório contém o projeto prático realizado durante a formação na **OxeTech Academy**, focado no tratamento de dados (Data Cleaning), validação estatística e Análise Exploratória de Dados (EDA) de uma base de vendas.

---

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** Python
- **Bibliotecas:** Pandas, NumPy
- **Ambiente:** Google Colab / Jupyter Notebook

---

## 📌 Contexto e Desafio
A base de dados continha informações sobre vendas de diversos produtos em estados brasileiros, apresentando inconsistências comuns do mundo real:
- Nomes de cidades e categorias desalinhados (espaços e letras maiúsculas/minúsculas).
- Registros duplicados.
- Tipos de dados inadequados (datas como texto, quantidades como string).
- Inconsistências em regras de negócio (descontos inválidos e quantidades zeradas).

---

## 💡 Evolução do Projeto & Feedback
Após a entrega inicial, o projeto passou por uma etapa de **refatoração** com base no feedback técnico recebido da professora.

### O que foi aprimorado na versão 2.0:
1. **Modelagem exata de desconto:** Subtituição de deduções lineares pela aplicação matemática direta na fórmula de negócio: `desconto = 1 - (valor_total / (quantidade * preço_unitário))`.
2. **Correção de quantidades zeradas:** Ajuste do pipeline de tratamento prévio à análise exploratória.
3. **Rigor conceitual:** Correção da terminologia de análise de *lucro* para **faturamento bruto**, alinhando os conceitos financeiros aos dados reais da base.

---

## 📈 Principais Insights Extraídos
- **Maior Faturamento:** A categoria de **Vestuário** liderou as vendas.
- **Forma de Pagamento:** O **Boleto** e o **Cartão de Crédito** foram as formas de pagamento mais recorrentes.
- **Análise de Outliers:** Identificação de compras atípicas com o método **IQR**, revelando compras de alto valor em calçados/tênis.

---

## 👁️ Visualização do Projeto
Como a base de dados utilizada é restrita ao escopo acadêmico da formação, o arquivo `.csv` não foi incluído neste repositório. No entanto, você pode **navegar livremente pelo arquivo `.ipynb` do projeto** para acompanhar todo o passo a passo da limpeza de dados, validação estatística e os gráficos da Análise Exploratória (EDA).

---

## 📫 Contato
* [LinkedIn](https://www.linkedin.com/in/edvaldo-neto-dados)
* [Email](mailto:edvaldo.fa.neto@gmail.com)
* [GitHub](https://github.com/edvaldo-f)
