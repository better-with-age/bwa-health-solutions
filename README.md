# Project
heport

# Description
Lang: pt-br

Plataforma Colaborativa de Suporte a Decisões Clínicas e Gestão Inteligente de Recursos para Saúde com paradigma de 'subsistema operacional' e interface amigável para processos de atenção a demandas de saúde com escopo, especialidade e nível de complexidade múltiplos abrangendo variados aspectos do cuidado à saúde com arquitetura modular adaptável a demandas e cenários diversos; potencializados por aprendizado de máquina, ciência de dados e outras tecnologias capazes de gerar  informação altamente contextualizada e disponível ponta a ponta.

# Módulos
Ambientes que abstraem processos da rotina de profissionais de saúde e gestores de recursos de saúde, como:
    • divulgação conteúdos empíricos e científicos, bem como de produtos e serviços;
    • sala de espera com confirmação e autenticação biométrica (ex. digitais, reconhecimento facial);
    • agendamento (agenda com suporte a funcionalidades cálculo de horas, estimativas de ganhos, datas especiais, condições climáticas vigentes e outras);
    • escala de profissionais (com suporte a trocas, divisões ao estilo app ‘pega plantão’)
    • atendimentos com recursos de teleconsultoria, controle de acesso, avaliação por pares, rankeamento e feedback de profissionais e organizações pelos clientes internos e externos
    • prontuário com «foco assistido» por design minimalista ao estilo 'Kanban' compondo dashboards com componentes multiparamétricos.

# Componentes multiparamétricos
Componentes com desenvolvimento e versionamento independentes, como plugins ou ad-ons com suporte a parâmetros e subparâmetros específicos, tais como:
    » dados de identificação;
    » pendências classificáveis em níveis de prioridade;
    » notas e alertas;
    » agenda dieta, sono e outras atividades;
    » parâmetros monitorados e curvas métricas (pa, temperatura, dextro etc.);
    » ferramentas úteis por especialidade (ex medicina de família - episódios de cuidado, genograma, grafos(*), linhas temporais e ecomapa), mas que podem ser utilizadas por qualquer profissional;
    » radar epidemiológico;
    » escores de risco, vulnerabilidade etc.;
    » laudos automatizados;
    » histórico de exames;
    » interações medicamentosas;
    » canais de comunicação com pacientes (telemedicina);
    » conectividade remota com dispositivos IoT (Internet of Things)
    » biometria otimizada por IA (Inteligência Artificial)
    » buscas automatizadas em bases indexadas de evidências por papers, pré-prints e publicações compartilhadas por outros usuários da plataforma que sejam relevantes para cada caso clínico (filtro por palavras-chave)
    » tabelas de procedimentos
    » testagem de hipóteses casuísticas
    » compartilhamento de resultados, presets, parâmetos, cards ou outros dados com indivíduos ou grupos de pacientes, profissionais da plataforma ou da comunidade via redes sociais
    » ferramentas gráficas com potencial impacto sobre decisões terapêuticas ou gerenciais.

# A abstração
Os componentes (cards ou widgets) ficam dispostos como registros resumidos e rotulados com tags e apresentando de forma simplificada o(s) atributos definidos como semre visíveis e, apenas quando selecionados expõem todo o seu conteúdo com atributos e funcionalidades ajustáveis. Juntos, os componentes formam um layout flexível compatíveis com presets para determinados tipos atendimento, indivíduo ou grupo em uma ampla mesa de trabalho.

# Sobre os componentes
O componente chave é o de busca, que aceita quaiquer parâmetros efetivamente registrados (ex. data ou período de atendimento, medicação em uso, imc, data da última menstruação etc) como filtro de busca e múltiplos pacientes; os vários parâmetros podem ser usados como comparativo entre pacientes. 

Porém, para comparativos envolvendo outros componentes e seus subparâmetros, poderá ser usado um componente específico para comparação de vários cards multiparamétricos de um ou mais pacientes.

# Impressos
Os impressos são traduzíveis  e enriquecidos com pictogramas para acessibilidade (analfabetos funcionais, estrangeiros, portadores de limitações visuais, auditivas, déficits cognitivo-sensoriais, físicos etc.).

# Versões da plataforma
Para profissionais e pacientes, sendo útil para ambos no cuidado à saúde. Os cards serão desenvolvidos separadamente pela comunidade e serão classificados por tags de tipo - profissional, paciente, comunidade.