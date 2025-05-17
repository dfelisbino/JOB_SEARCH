🚀 Project Job Search - Busca e Classificação de Vagas com Google Gemini 🚀

✨ Apresentação do Projeto ✨
Este projeto, desenvolvido como parte do curso de IA da Alura, é uma ferramenta inovadora para auxiliar na busca e análise de oportunidades de emprego. Ele utiliza a potência da SDK do Google Gemini e o framework ADK (Agent Development Kit) para criar um sistema de agentes inteligentes que automatiza e aprimora o processo de encontrar a vaga ideal.

Em muitos casos, a busca por emprego pode ser uma tarefa complexa e demorada, com a necessidade de analisar inúmeras vagas, identificar requisitos e adaptar candidaturas. Este projeto nasce da necessidade de tornar esse processo mais eficiente e direcionado.

A utilidade reside em oferecer uma ferramenta que não apenas busca vagas, mas também as classifica, analisa, estima pretensões salariais e até sugere mensagens personalizadas para contato com recrutadores, tudo de forma integrada. Isso demonstra o potencial da IA generativa para criar soluções práticas e ricas em tempo real para desafios do mundo real.

💡 A Solução
A solução proposta é um sistema composto por quatro agentes distintos, cada um com uma função específica no fluxo de busca por vagas, orquestrados para entregar uma análise completa e personalizada para o usuário:

Agente 1: Busca de Vagas: Atua como um "buscador" especializado, utilizando a ferramenta de busca do Google (Google Search) para encontrar as oportunidades de emprego mais recentes e relevantes com base na vaga desejada pelo usuário. Ele prioriza critérios como empresas consolidadas, benefícios claros, salários definidos, vagas recentes (última semana ou 15 dias) e modelos de trabalho flexíveis (remoto, híbrido, presencial). O objetivo é trazer as 5 melhores oportunidades que se encaixem nestes critérios.

Agente 2: Palavras-Chave e Análise: Este agente, com a persona de um "tech recruiter", recebe a lista de vagas do agente anterior e realiza uma análise detalhada. Ele identifica as palavras-chave mais relevantes, soft skills e competências técnicas exigidas para cada vaga. Além disso, utiliza a ferramenta Google Search para obter informações adicionais sobre as empresas e criar um plano de quais pontos importantes devem ser abordados em um currículo personalizado para cada oportunidade. Ao final, ele ordena as vagas com base no número de exigências e na sua adequação a um perfil hipotético, apresentando um resumo dos pontos importantes, palavras-chave, faixa salarial, modelo de trabalho e uma avaliação resumida da empresa.

Agente 3: Faixa Salarial: Especializado em "Remuneração e Benefícios", este agente avalia as vagas e as competências para determinar a faixa salarial esperada para cada cargo. Com base nas informações fornecidas e em pesquisas de mercado (utilizando Google Search quando necessário), ele sugere uma pretensão salarial para cada vaga. O resultado é uma tabela comparativa com o nome da vaga, empresa, salário oferecido e a pretensão salarial sugerida.

Agente 4: Mensagem de Conexão: Assumindo a persona de um "candidato", este agente cria mensagens personalizadas e profissionais para serem enviadas a recrutadores via LinkedIn ou WhatsApp. As mensagens são concisas, educadas e buscam gerar conexão ao incorporar palavras-chave relevantes da vaga. O objetivo é despertar a curiosidade do recrutador e incentivá-lo a buscar mais informações sobre o candidato.

A eficácia da solução reside na colaboração desses agentes, que transformam a busca por vagas em um processo estruturado e inteligente, fornecendo ao usuário informações valenciais e ferramentas para otimizar suas candidaturas.

🔧 Como Configurar e Executar
O projeto é projetado para ser executado em um ambiente Python que suporte ipywidgets, como o Google Colab.

Obtenha o Código: Copie o arquivo Project Job Search - Alura + Google Gemini.ipynb para o seu Google Drive ou acesse a versão original.
Instale as Bibliotecas: As bibliotecas necessárias (google-genai e google-adk) são instaladas na primeira célula do notebook.
Configure a API Key: Configure sua Chave de API do Google Cloud com acesso à API Gemini. No Google Colab, utilize a funcionalidade "Secrets" para configurar a variável de ambiente GOOGLE_API_KEY.
Execute as Células: Conecte o notebook e execute todas as células em ordem. A última célula iniciará a interação com o usuário.
Interaja com o Projeto: O projeto solicitará o nome da vaga desejada. Após fornecer a informação, os agentes entrarão em ação sequencialmente, apresentando os resultados de cada etapa: vagas encontradas, análise de palavras-chave, tabela salarial e sugestões de mensagens para recrutadores.

🧠 Modelo de IA e Ferramentas
Este projeto utiliza o modelo Gemini 2.0 Flash para alimentar os agentes e gerar as respostas dinâmicas ao longo do processo. A ferramenta principal utilizada pelos agentes é o Google Search, que permite a busca por informações atualizadas sobre vagas, empresas e dados de mercado.



🚀 Possíveis Melhorias Futuras
Algumas melhorias que podem ser implementadas incluem:

Adicionar a funcionalidade de salvar e carregar o estado da busca para que o usuário possa retomar de onde parou.
Desenvolver uma interface de usuário mais rica e visualmente atraente.
Explorar a integração de outras ferramentas para os agentes, como análise de currículo e simulação de entrevistas.
Implementar opções de acessibilidade para tornar a ferramenta mais inclusiva.

🙏 Créditos
Este projeto foi proposto como uma tarefa do curso de IA da Alura + Google Gemini. Agradecemos à Alura e ao Google pela iniciativa e oportunidade de aprendizado.

Projeto desenvolvido por: Dionei Adriano Felisbino (dfelisbino@gmail.com)

Agradecimentos:
Fabricio Carraro - Program Manager (destacando a agilidade na digitação).
Valquíria Alencar - Instrutora de Data Science (destacando os insights durante as aulas) 
Luciano Martins - Developer Advocate, Google IA (destacando o conhecimento técnico)

Desenvolvido com a assistência do modelo Gemini.
