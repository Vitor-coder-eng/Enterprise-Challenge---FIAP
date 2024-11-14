![Logo FIAP](https://github.com/Vitor-coder-eng/Enterprise-Challenge---Solubio/blob/main/logo-fiap.png)

# Enterprise-Challenge - Solubio
O Enterprise Challenge - Solubio é uma iniciativa da FIAP em parceria com a Solubio, uma empresa do setor de Bioinsumos. Este projeto acadêmico hands-on tem como objetivo desenvolver as habilidades dos alunos, que irão criar uma solução de chatbot hospedada em nuvem.

### Arquitetura de Solução para Chatbot
![Arquitetura de solução para chatbot](https://github.com/Vitor-coder-eng/Enterprise-Challenge---Solubio/blob/main/Arquitetura%20de%20Solu%C3%A7%C3%A3o%20para%20ChatBot.png)

### Descrição dos elementos da arquitetura e suas funções 

Mensagem do Usuário 

Função: Atuar como ponto de entrada, capturando a interação do usuário e enviando-a para o sistema. 

Pré-processamento 

Função: Limpar e normalizar o texto da mensagem, preparando-o para as próximas etapas. Inclui remoção de ruídos, normalização de termos e segmentação. 

Classificação de Intenção 

Função: Identificar a intenção do usuário, utilizando modelos de machine learning (ML) ou processamento de linguagem natural (NLP). 

Utilização de Contexto e Geração de Respostas 

Função: Manter informações importantes de conversas anteriores, garantindo continuidade nas interações. 

Função: Com base na intenção detectada, cria ou seleciona uma resposta. 

Selecionador de Respostas 

Função: Selecionar a melhor resposta dentre as candidatas, com base em critérios como contexto e relevância. 

### Previsão de custos mensal de cada elemento 

Para implementar essa solução de chatbot, projetamos alguns custos mensais, distribuídos entre os principais componentes necessários. Em primeiro lugar, a hospedagem em nuvem, fundamental para garantir escalabilidade e segurança, representa uma parte significativa do custo, estimada entre R$100 e R$500 por mês, dependendo do volume de interações e da demanda por capacidade de processamento. Outro ponto essencial é o serviço de Processamento de Linguagem Natural (NLP), que permitirá ao chatbot entender e responder às mensagens dos usuários com precisão. Esse serviço, utilizando opções como o Dialogflow ou IBM Watson, pode custar entre R$200 e R$500 mensais. A maioria das plataformas de NLP oferece planos gratuitos com limites, úteis para o início, mas que, ao serem excedidos, passam a gerar custos adicionais. 

Além disso, será necessário um banco de dados em nuvem, com um custo mensal de cerca de R$50, para armazenar o histórico e o contexto das interações. Esse armazenamento permitirá ao chatbot manter continuidade e fluidez nas conversas, melhorando a experiência do usuário. A infraestrutura de Machine Learning, embora mais básica, exige um custo médio de R$200 mensais para manter a atualização do modelo de classificação de intenções e respostas, o que ajuda a manter a precisão do atendimento. E, por fim, APIs externas que integrem o chatbot com os dados específicos da Solubio podem ser usadas. Algumas são gratuitas, mas com limites de uso que, uma vez superados, podem gerar cobranças extras. 

O custo total estimado para manter a solução mensalmente seria de aproximadamente R$900. 

### Resultados Esperados e Impacto na Solubio 

Com essa arquitetura, esperamos resultados positivos em várias frentes. Em termos de atendimento, o chatbot estará disponível 24 horas por dia, sete dias por semana, permitindo uma automação significativa e proporcionando respostas rápidas e eficientes para dúvidas comuns. Isso reduz a carga do atendimento humano em questões rotineiras e libera os colaboradores para focar em atividades de maior valor, como atendimentos personalizados e suporte avançado. 

No modelo de negócios da Solubio, a proposta deve agregar valor principalmente em duas áreas: automação e agilidade no atendimento ao cliente. Com a possibilidade de escalar rapidamente o número de interações atendidas, o chatbot contribui para uma experiência mais satisfatória e eficiente para os clientes, além de reduzir os custos operacionais associados a atendimentos de baixa complexidade. Com o passar do tempo, a expectativa é que os ganhos superem os custos iniciais, levando a uma operação mais econômica e ágil, enquanto as perdas são mínimas, limitando-se ao investimento inicial e ao custo de manutenção para acompanhar as mudanças nas necessidades de atendimento. 
