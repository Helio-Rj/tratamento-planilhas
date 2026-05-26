## 📌 Visão Geral

Este projeto contém um notebook em Python para tratamento e limpeza de planilhas Excel usando `pandas`. Ele carrega dados, faz inspeções iniciais, renomeia colunas, padroniza valores, trata nulos e duplicados e exporta o resultado final para um novo arquivo Excel.

## 🚀 O que o notebook faz

- Carrega um arquivo Excel para um DataFrame
- Exibe amostras e informações gerais do dataset
- Renomeia colunas para nomes mais legíveis
- Converte datas para o formato correto
- Padroniza textos como nomes, bairros e emails
- Trata valores nulos com preenchimento padrão
- Remove linhas duplicadas
- Exporta o DataFrame final para um novo arquivo Excel

## 🧩 Arquivos

- `main.ipynb` — notebook principal com todo o fluxo de tratamento de dados.
- `README.md` — documentação do projeto.

## 📥 Pré-requisitos

Certifique-se de ter instalado:

- Python 3.8+ (recomendado)
- pandas
- numpy
- openpyxl (para leitura/escrita de Excel)

## ⚙️ Instalação rápida

```bash
pip install pandas numpy openpyxl
```

## ▶️ Como usar

1. Coloque o arquivo Excel de entrada na mesma pasta do notebook ou informe o caminho correto.
2. Abra `main.ipynb` no Jupyter ou no VS Code.
3. Execute as células na ordem, do início ao fim.
4. O arquivo final será gerado no caminho configurado em `exportar_para_excel`.

## 💡 Dicas

- Ajuste `coluna_para_excluir` se quiser remover outra coluna.
- Verifique o mapeamento de colunas em `corrigir_colunas` para manter os nomes consistentes.
- Se quiser exportar para outro caminho, altere a variável `caminho` no final do notebook.

## 📝 Estrutura do fluxo

1. Leitura e inspeção inicial
2. Exclusão de colunas indesejadas
3. Renomeação de colunas
4. Formatação de datas
5. Padronização de textos
6. Tratamento de valores nulos
7. Remoção de duplicados
8. Exportação para Excel

## 💾 Comandos Git úteis

```bash
git add .
git commit -m "Atualiza notebook de tratamento de planilhas"
git push origin main
```

## 📍 Observação

Este README foi criado para facilitar o uso e a manutenção deste projeto de tratamento de planilhas em Excel. Se necessário, personalize as funções internas do notebook conforme o formato dos seus arquivos de dados.
