📊 Tratamento de Planilhas com Pandas/Python

Automação inteligente para limpeza, padronização e transformação de planilhas Excel e CSV utilizando Python.

🚀 Sobre o Projeto

O Tratamento de Planilhas nasceu para resolver um problema extremamente comum em empresas:

planilhas desorganizadas
dados inconsistentes
colunas fora do padrão
informações duplicadas
arquivos vindos de diferentes sistemas
horas de trabalho manual

A proposta do projeto é transformar arquivos brutos em bases organizadas e prontas para:

Power BI
dashboards
relatórios
análises de dados
automações
pipelines de ETL
🧠 O Problema

Em muitos ambientes corporativos, os dados chegam assim:

Nome	telefone	DATA	valor
HELIO	(21)9999	12/1/26	1.000
helio	219999	2026-01-12	1000
vazio	NULL	erro	-

Isso gera:

erros em dashboards
retrabalho
perda de produtividade
relatórios inconsistentes
dificuldade de análise
✅ A Solução

O projeto automatiza o tratamento dessas informações utilizando Python e Pandas.

✔ Funcionalidades
Limpeza de dados
Padronização de colunas
Tratamento de valores nulos
Remoção de duplicidades
Conversão de datas
Organização de arquivos CSV e Excel
Preparação para BI e análise de dados
Automação de tarefas repetitivas
⚙️ Tecnologias Utilizadas
Python
Pandas
OpenPyXL
NumPy
CSV
Excel (.xlsx)
📂 Estrutura do Projeto
tratamento-planilhas/
│
├── data/                # Arquivos brutos
├── output/              # Arquivos tratados
├── scripts/             # Scripts principais
├── notebooks/           # Estudos e análises
├── requirements.txt
├── README.md
🔄 Fluxo da Aplicação
Planilha Bruta
       ↓
Python + Pandas
       ↓
Tratamento de Dados
       ↓
Padronização
       ↓
Base Limpa
       ↓
Power BI / Dashboard / Relatórios
📈 Objetivo

Automatizar processos que normalmente consomem horas de trabalho manual.

O foco do projeto é:

produtividade
organização de dados
automação operacional
preparação de bases analíticas
melhoria na qualidade dos dados
🧪 Exemplo de Tratamento
Antes
cliente	telefone	data
JOAO	219999	12/1
joão	(21) 9999	2026/01/12
Depois
cliente	telefone	data
João	21999999999	2026-01-12
📊 Possíveis Aplicações

Este projeto pode ser utilizado para:

Empresas que trabalham com Excel
Pequenos negócios
Times de BI
Analistas de dados
Processos administrativos
Organização financeira
Padronização de bases
ETL inicial
🔥 Diferenciais

Ao invés de trabalhar com datasets perfeitos, o projeto foi pensado para lidar com o cenário real:

dados quebrados
arquivos despadronizados
inconsistências
planilhas vindas de múltiplas fontes
informações incompletas

Isso aproxima o projeto de problemas reais encontrados em empresas.

🛠 Como Executar
Clone o repositório
git clone https://github.com/Helio-Rj/tratamento-planilhas.git
Acesse a pasta
cd tratamento-planilhas
Instale as dependências
pip install -r requirements.txt
Execute o projeto
python main.py
📌 Roadmap
Próximas melhorias
Interface com Streamlit
Upload automático de arquivos
Tratamento inteligente de colunas
Geração automática de relatórios
Integração com Power BI
Pipeline de ETL
Logs automáticos
Tratamento avançado de erros
API com FastAPI
📚 Aprendizados

Este projeto envolve conceitos importantes de:

análise de dados
limpeza de dados
engenharia de dados
automação
ETL
manipulação de planilhas
produtividade empresarial
👨‍💻 Autor

Desenvolvido por Hélio do Nascimento Silva.

GitHub: https://github.com/Helio-Rj

LinkedIn: https://www.linkedin.com/in/ultimatehelio/

⭐ Considerações Finais

O objetivo deste projeto não é apenas tratar planilhas.

A ideia é demonstrar como Python pode transformar processos manuais demorados em fluxos automatizados, organizados e escaláveis.

Porque no mundo real, os dados quase nunca chegam perfeitos.

E é exatamente aí que começa o verdadeiro trabalho com dados.