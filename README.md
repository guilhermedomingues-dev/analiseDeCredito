Este projeto consiste em um script de automação para análise preliminar de crédito, ideal para ser implementado em empresas que necessitam dessa análise.

🚀 Propósito
O objetivo principal é permitir que a empresa realize uma triagem de crédito automática antes mesmo do cliente ter contato direto com um vendedor, por exemplo. Isso otimiza o tempo da equipe de vendas e fornece uma resposta imediata ao cliente sobre sua viabilidade financeira para a compra.

🛠️ Tecnologias e Ferramentas
Linguagem: Python
Ambiente de Desenvolvimento: Google Colab
Bibliotecas Utilizadas: google.colab (para limpeza de interface)

📋 Funcionalidades
O algoritmo solicita informações básicas do cliente e aplica regras de negócio baseadas em:
* Score de Crédito: Decisão imediata baseada na pontuação do cliente.
* Tempo de Inatividade: Verificação de contas correntes paradas.
* Relação Renda x Crédito: Validação se o valor solicitado ultrapassa 30% da renda mensal.
* Estabilidade Empregatícia: Análise do tempo de trabalho atual.

💻 Como executar
Por ter sido desenvolvido no Google Colab, você pode executar o projeto diretamente no navegador sem necessidade de configuração local:
* Abra o notebook no Colab.
* Execute a célula principal.
* Siga as instruções no console para inserir os dados do cliente.
* Este projeto foi desenvolvido como uma prova de conceito para automação de processos financeiros.
