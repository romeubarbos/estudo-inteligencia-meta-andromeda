# estudo-inteligencia-meta-andromeda
Obejtivo deste material é entender o comportamento do novo algortimo de anúnios dos Meta Ads, com isso foi criado um modelo no NotebookLM, com fontes confiaveis para entender melhor o comportamento do algoritmo

Fonte: 
https://engineering.fb.com/2024/12/02/production-engineering/meta-andromeda-advantage-automation-next-gen-personalized-ads-retrieval-engine/

Contexto: O ecossistema de anúncios da Meta passou por uma revolução silenciosa com a introdução do Meta Andromeda, um sistema proprietário de aprendizado de máquina (ML) focado na etapa de "recuperação" (retrieval) de anúncios. Este caderno temático explora as inovações técnicas desse novo paradigma, que utiliza redes neurais profundas e hardwares como o Superchip NVIDIA Grace Hopper para lidar com o crescimento exponencial de anúncios criados por Inteligência Artificial. 

Objetivos de Estudo:

  Compreender tecnicamente como funciona o algoritmo Andromeda na fase de recuperação de anúncios.
  Analisar o impacto da Indexação Hierárquica e da IA Generativa (GenAI) no volume de criativos.
  Traduzir essa documentação técnica de engenharia em estratégias práticas e acionáveis para a estruturação de campanhas e aumento de ROAS (Retorno sobre Investimento em Publicidade).

2. Curadoria de Fontes
As seguintes fontes oficias de engenharia da Meta foram selecionadas e processadas:

    "Meta Andromeda.pdf": Documento oficial traduzido detalhando a arquitetura, desafios de latência, capacidade computacional e a integração com o Advantage+.
    "Meta Andromeda: Supercharging Advantage+ automation with the next-gen personalized ads retrieval engine": Artigo do blog Engineering at Meta, detalhando inovações em ML, representação de recursos e algoritmos. 

3. Prompts exploratórios
 
Durante o estudo, o principal desafio foi traduzir um jargão altamente técnico de engenharia de software e hardware em estratégias práticas de marketing.

    Prompt 1 (Exploratório): "Como de fato funciona o novo algoritmo, como aplica-lo de forma mais estratégica?"
        Resposta obtida: A IA explicou que o Andromeda atua na filtragem rápida de milhões de anúncios para milhares. A aplicação estratégica envolve abraçar a automação do Advantage+ e focar agressivamente na diversificação de criativos.
        
  Cicatrizes (Troubleshooting): Inicialmente, a documentação falava muito sobre "interconexão CPU-GPU" e "gargalos de largura de banda". Foi necessário direcionar a IA para focar no "como aplicar" para extrair a recomendação prática de parar de usar segmentação manual.
        
    Prompt 2 (Aprofundamento Prático): "Na prática como aplicar isso nas estratégia da estrutura de campanha"
        Resposta obtida: A estruturação exige consolidação de campanhas via Advantage+, delegando segmentação e orçamento para a máquina, e focando totalmente no volume massivo de criativos no nível do anúncio, escalados com IA Generativa.

        
  Cicatrizes (Troubleshooting): Evitar que o resumo soasse como um "manual genérico de Facebook Ads". A resposta precisou ser amarrada com a inovação técnica da "Indexação Hierárquica" do Andromeda, que é o que permite processar milhares de anúncios simultaneamente.

4. Miniguia de Estudo
   
A. Resumos Estruturados do Assunto

  O Problema (O Gargalo Antigo): O sistema antigo usava regras heurísticas manuais e sofria com restrições de latência. Ele não conseguia processar a enorme quantidade de anúncios que os anunciantes queriam testar.
  A Solução (Andromeda): A Meta criou um mecanismo de recuperação usando redes neurais profundas e hardware de ponta (Grace Hopper Superchip). A grande inovação é a Indexação Hierárquica, que organiza anúncios em camadas, processando um volume gigante de criativos rapidamente e de forma mais barata (custo de inferência sublinear).
   O Impacto (Resultados): A automação do Advantage+ apoiada por esse algoritmo aumentou o ROAS em 22%. Com as ferramentas de GenAI (Inteligência Artificial Generativa), os anunciantes estão produzindo milhões de anúncios por mês.

B. Glossário

  Recuperação (Retrieval): A primeiríssima fase do sistema de recomendação de anúncios. Filtra rapidamente dezenas de milhões de candidatos para apenas alguns milhares relevantes, antes de passar para os modelos de classificação final.
  
  Indexação Hierárquica: Método usado pelo Andromeda para organizar anúncios em um índice de múltiplas camadas. Permite que o algoritmo ignore anúncios irrelevantes e foque apenas nos "nós" mais valiosos, acelerando o processo.
  
  Advantage+: Suite de automação da Meta que assume o controle da alocação de orçamento, segmentação de público-alvo e lances.
    GenAI (IA Generativa): Ferramentas de inteligência artificial usadas pelos anunciantes para criar e otimizar conteúdo publicitário em massa e de forma rápida.
    MTIA / Superchip NVIDIA Grace Hopper: Aceleradores e hardwares físicos de inteligência artificial que fornecem o poder computacional paralelo massivo necessário para rodar o Andromeda em tempo quase real.

C. Prompts Reutilizáveis (Para futuras revisões)
Para continuar testando e revisando os conceitos, utilize os seguintes prompts no seu assistente de IA:

    "Atue como um Engenheiro da Meta. Explique para um leigo de marketing digital o que é a etapa de 'Recuperação' (Retrieval) e por que ela é o principal foco do Andromeda."
    
    "Com base nos dados do Meta Andromeda, justifique o motivo pelo qual campanhas com alta fragmentação (muitos conjuntos de anúncios pequenos) prejudicam a inteligência do Advantage+."
    
    "Crie um checklist de 5 passos para um gestor de tráfego adaptar a sua produção criativa de anúncios utilizando GenAI, visando alimentar a Indexação Hierárquica do novo algoritmo."
