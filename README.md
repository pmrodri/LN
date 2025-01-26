Análise de Sentimentos com Language Studio no Azure AI

Este projeto demonstra como utilizar o Language Studio do Azure AI para realizar análise de sentimentos em textos. A análise de sentimentos é uma técnica de processamento de linguagem natural (NLP) que identifica e classifica opiniões subjetivas como positivas, negativas ou neutras.

Índice

Introdução
Pré-requisitos
Configuração do Ambiente
Uso
Contribuição
Licença
Introdução

A análise de sentimentos é uma ferramenta poderosa para entender as opiniões e emoções expressas em textos. Este projeto utiliza o Language Studio do Azure AI para realizar essa análise de forma eficiente e precisa.

Pré-requisitos

Antes de começar, você precisará dos seguintes itens:

Uma conta no Azure
Acesso ao Language Studio no Azure AI
Python 3.6 ou superior
Bibliotecas Python: azure-ai-textanalytics, pandas, numpy
Configuração do Ambiente

Clone este repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
Crie um ambiente virtual e ative-o:

python -m venv venv
source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
Instale as dependências:

pip install -r requirements.txt
Configure suas credenciais do Azure:

Crie um arquivo .env na raiz do projeto e adicione suas credenciais:
AZURE_ENDPOINT=seu_endpoint
AZURE_KEY=sua_chave
Uso

Prepare seus dados de texto para análise. Você pode usar um arquivo CSV ou qualquer outra fonte de dados.
Execute o script de análise de sentimentos:
python sentiment_analysis.py
Os resultados serão salvos em um arquivo de saída especificado no script.
Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorias e correções.
