# Desafio_API_Python-Generation

🎵 Desafio 01 · Festival de Música

Este projeto consiste na automação e geração de uma base de dados fictícia para o tema Festival de Música, utilizando Python no Google Colab e integrando diretamente com o Google Sheets API.

O objetivo principal é estabelecer a conexão via API, estruturar as tabelas conforme o esquema fornecido e popular a base com volumetria fictícia para análises futuras.

🛠️ Tecnologias Utilizadas

Python 3

Google Colab

Google Sheets API & Google Drive API

gspread (para manipulação de planilhas via Python)

Faker (geração de dados fictícios/mockados)

📋 Estrutura de Dados

O projeto conta com duas tabelas integradas no Google Sheets:

atracoes (Tabela Dimensão)

Armazena o cadastro de atrações/artistas do festival.

ingressos_vendidos (Tabela Fato)

Registra os ingressos e vendas efetuadas para os shows.

🚀 Como Executar o Projeto

Configuração na Google Cloud:

Crie um projeto no Google Cloud Console.

Ative as APIs: Google Sheets API e Google Drive API.

Crie uma Conta de Serviço (Service Account) com o nome desafio1-python.

Baixe a chave no formato JSON.

Preparação da Planilha:

Crie uma planilha no Google Sheets com o nome Desafio_01_Festival_Musica.

Compartilhe a planilha com o e-mail da Conta de Serviço (client_email) dando permissão de Editor.

Execução no Google Colab:

Abra o Google Colab e adicione o conteúdo do JSON nas Secrets (GCP_SA_JSON).

Execute o notebook Desafio1_API_Python para:

Autenticar a sessão.

Criar e renomear as abas/tabelas (atracoes e ingressos_vendidos).

Inserir os cabeçalhos padrão.

Gerar e popular as tabelas em lotes via biblioteca Faker.

📌 Status do Projeto

[x] Configuração da credencial e conexão via API

[x] Estruturação da tabela dimensão (atracoes)

[x] Estruturação da tabela fato (ingressos_vendidos)

[x] Teste inicial de escrita na planilha

[x] Validação e verificação dos dados gerados
