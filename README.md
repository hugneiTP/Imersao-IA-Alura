


![colab](https://github.com/user-attachments/assets/749e81df-a0a0-4150-9ede-2b58f822a862)

_________________________________________________________________________________________________________________________________________

🧠💹 AGENTE DE INTELIGÊNCIA PARA INVESTIMENTOS BUY/SELL ADVISOR


🔍 O que faz este agente?

O Buy/Sell Advisor é um agente inteligente criado com a SDK ADK da Google. Ele analisa dados do mercado financeiro, padrões de preço e indicadores para recomendar momentos ideais de compra e venda de ativos — tudo de forma empática, clara e acessível.

_________________________________________________________________________________________________________________________________________

🛠️ TECNOLOGIAS UTILIZADAS:

Gemini + Google ADK

Python (Google Colab)

Integrações com fontes de dados financeiros

_________________________________________________________________________________________________________________________________________

🎯 OBJETIVOS:

Ajudar investidores (iniciantes e experientes) a tomar decisões mais embasadas, com apoio de uma IA treinada para reconhecer oportunidades e evitar riscos.

📈 Exemplos de uso:

“Compre ações da PETR4 se o preço cair abaixo de R$30.”
“Venda ativos voláteis se o RSI ultrapassar 70.”
_________________________________________________________________________________________________________________________________________

ESTRUTURA PRINCIPAL:

Agente 1: Analisador de Notícias Financeiras
Busca as últimas notícias sobre empresas ou ativos específicos (ações, moedas, criptos, etc.). Filtra e resume os eventos que podem impactar os preços.

Agente 2: Analista Técnico
Analisa dados históricos de preço e volume. Pode usar APIs como Yahoo Finance ou Alpha Vantage (via requests) para obter dados e aplicar conceitos como Médias Móveis, RSI, MACD, etc.

Agente 3: Recomendador de Ação (Buy/Sell/Hold)
Com base nas notícias + análise técnica, sugere se o usuário deve comprar, vender ou manter. Deve justificar a recomendação.

Agente 4: Explicador para o Usuário Leigo
Explica em linguagem simples o motivo da recomendação. Ideal para quem está aprendendo sobre finanças.
