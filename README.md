# Análise de Dados das Lojas Online

> **Este projeto faz parte do Challenge 1 DataScience da Alura One G8**

Este projeto realiza a análise de dados de vendas de quatro lojas online, usando Python, pandas e matplotlib. O script consolida os dados de diferentes CSVs, faz limpeza básica e gera visualizações para responder às seguintes perguntas:

1. **Análise do Faturamento**
   - Faturamento total por loja (gráfico de barras)
   - Faturamento mensal agregado (gráfico de linha)

2. **Vendas por Categoria**
   - Participação percentual de vendas por categoria (gráfico de pizza)

3. **Média de Avaliação das Lojas**
   - Nota média de avaliação por loja (gráfico de barras horizontais)

4. **Produtos Mais e Menos Vendidos**
   - Top 5 produtos mais vendidos (gráfico de barras)
   - 5 produtos menos vendidos (gráfico de barras)

5. **Frete Médio por Loja**
   - Frete médio por loja (gráfico de barras)

---

## Pré-requisitos

- Python 3.7 ou superior
- Bibliotecas Python:
  - pandas
  - matplotlib

Você pode instalar facilmente com:

```bash
pip install pandas matplotlib
```

## Estrutura de Arquivos

```
├── analise_lojas.py   # Script principal com todas as análises e gráficos
└── README.md         # Documentação deste projeto
```

## Como Executar

1. Clone este repositório ou baixe os arquivos.
2. No terminal, navegue até a pasta do projeto.
3. Execute:

```bash
python analise_lojas.py
```

Os gráficos serão exibidos um a um. Se desejar salvar cada gráfico em disco, adicione antes de `plt.show()`:

```python
plt.savefig('nome_do_grafico.png', dpi=300)
```

## Personalização

- Altere as URLs das variáveis `url1`, `url2`, `url3` e `url4` para apontar a diferentes fontes de dados.
- Ajuste nomes de colunas no script caso os CSVs tenham variações de cabeçalhos.
- Customize cores, estilos e tamanhos de figuras diretamente nas chamadas do matplotlib.

## Contribuição

Contribuições são bem-vindas! Abra um _issue_ ou _pull request_ para aprimorar análises, corrigir bugs ou sugerir novas visualizações.



