# Projeto: Análise de Acessibilidade e Usabilidade Digital em Portais Acadêmicos

## 1. Introdução

O avanço constante da tecnologia e a digitalização dos serviços tornaram a internet a principal via de acesso à informação, educação e serviços essenciais. No entanto, o desenvolvimento de ecossistemas digitais muitas vezes negligencia diretrizes e padrões de acessibilidade web, gerando barreiras que excluem uma parcela expressiva da população.

Este projeto tem como foco a análise de acessibilidade e usabilidade em sites e portais web, tomando como estudo de caso a página institucional da PUC (Pontifícia Universidade Católica). O problema central reside no fato de que diversas plataformas digitais não são projetadas considerando a diversidade de necessidades funcionais e cognitivas dos usuários, dificultando ou impedindo a navegação de Pessoas com Deficiência (PcD), idosos e indivíduos com baixo letramento digital.

O objetivo do trabalho é realizar um diagnóstico detalhado das barreiras de acesso existentes no portal, identificando descumprimentos das Diretrizes de Acessibilidade para Conteúdo Web (WCAG) e propondo soluções e recomendações que tornem o ambiente digital inclusivo. A justificativa fundamenta-se na garantia de direitos fundamentais, nos Objetivos de Desenvolvimento Sustentável (ODS da ONU) e no impacto social da inclusão digital. O público-alvo contempla pessoas com deficiências (visuais, motoras, auditivas e cognitivas), idosos e pessoas com baixo acesso/oportunidade tecnológica.

## 2. Problema

A aceleração da transformação digital não foi acompanhada de forma equitativa pelo design inclusivo. Atualmente, diversos sites e portais governamentais, acadêmicos e corporativos apresentam arquiteturas de informação complexas, interfaces poluídas e falta de suporte a tecnologias assistivas (como leitores de tela, navegação por teclado e contraste adequado).

No contexto de portais de ensino e instituições de ensino superior (como o portal da PUC), alunos, professores, colaboradores e a comunidade externa dependem diariamente da plataforma para consultar matrículas, materiais didáticos, editais, notícias e serviços administrativos. Contudo, a ausência de recursos acessíveis cria entraves significativos:

    * Pessoas com deficiência visual enfrentam imagens sem texto alternativo (alt), botões não rotulados e links genéricos ("clique aqui") que impossibilitam a leitura por leitores de tela (ex.: NVDA, TalkBack).

    * Pessoas com deficiência motora encontram dificuldades quando a navegação exige o uso exclusivo do mouse, sem suporte sequencial e lógico pela tecla Tab.

    * Pessoas idosas ou com baixos níveis de letramento digital são impactadas por tipografias pequenas, contraste insuficiente entre texto e fundo, menus confusos e excesso de informações visuais sem hierarquia clara.

Esse cenário reflete uma lacuna no desenvolvimento de software, onde a acessibilidade é tratada como um elemento secundário ou opcional, em vez de um requisito fundamental desde a fase de concepção da interface.

## 3. Objetivos

### **Objetivo Geral**

Analisar a acessibilidade e a usabilidade do portal institucional da PUC, identificando as principais barreiras de navegação e propondo recomendações de melhorias baseadas nas normas nacionais e internacionais de acessibilidade web.

### ***Objetivos Específicos***

    1. Mapear e avaliar a conformidade do portal em relação às Diretrizes de Acessibilidade para Conteúdo Web (WCAG 2.1/2.2) em níveis A e AA, bem como ao Modelo de Acessibilidade em Governo Eletrônico (eMAG).
    2. Identificar gargalos de usabilidade na jornada de navegação dos usuários, com foco especial em navegação por teclado, compatibilidade com leitores de tela e contraste de cores.
    3. Elaborar um relatório de diretrizes e boas práticas de UI/UX inclusivo para servir de guia na adequação e reformulação de portais acadêmicos e educacionais.

## 4. Justificativa

A acessibilidade digital não é apenas um diferencial técnico, mas uma obrigação legal e legalmente respaldada no Brasil pela Lei Brasileira de Inclusão da Pessoa com Deficiência (Lei nº 13.146/2015), que em seu artigo 63 determina a obrigatoriedade de acessibilidade nos sítios da web mantidos por empresas, órgãos públicos e instituições de ensino.

### ***Impacto Quantitativo do Problema***

    * Segundo dados do Censo Demográfico do IBGE (2022) e pesquisas da Pesquisa Nacional por Amostra de Domicílios (PNAD Contínua), aproximadamente 8,9% da população brasileira (cerca de 18,6 milhões de pessoas) possui algum tipo de deficiência.

    * De acordo com o relatório anual do WebAIM (Web Accessibility In Mind, 2023), que analisa o 1 milhão de páginas iniciais mais acessadas do mundo, 96,3% dos sites apresentavam falhas detectáveis de acessibilidade segundo as WCAG, sendo os problemas mais comuns o baixo contraste de texto (83,6%) e a falta de texto alternativo em imagens (58,2%).

    * Além disso, a população idosa no Brasil ultrapassa 32 milhões de pessoas (IBGE, 2022), grupo que frequentemente enfrenta declínio visual, motor e cognitivo natural da idade, exigindo interfaces simplificadas e adaptáveis.

### ***Relação com os Objetivos de Desenvolvimento Sustentável (ODS)***

Este projeto alinha-se diretamente com a Agenda 2030 da Organização das Nações Unidas (ONU):

    * ODS 4: Educação de Qualidade

        * Subobjetivo 4.a: Construir e melhorar instalações físicas e digitais propícias à educação, que sejam sensíveis às crianças, deficiências e gênero, e que proporcionem ambientes de aprendizagem seguros, não violentos, inclusivos e eficazes para todos.

        * Contribuição do projeto: Assegurar que os materiais e informações acadêmicas do portal da PUC estejam acessíveis a todos os estudantes e comunidade, eliminando barreiras digitais no ensino.

    * ODS 10: Redução das Desigualdades

        * Subobjetivo 10.2: Até 2030, empoderar e promover a inclusão social, econômica e política de todos, independentemente da idade, gênero, deficiência, raça, etnia, origem, religião ou condição econômica.

        * Contribuição do projeto: Promover a equidade no acesso às tecnologias digitais, impedindo que a falta de acessibilidade perpetue a exclusão de grupos vulneráveis.

## 5. Público-Alvo

O público-alvo do estudo e dos impactos do projeto engloba diversos perfis de usuários do portal, caracterizados por suas diferentes necessidades e níveis de familiaridade com a tecnologia:

    * Pessoas com Deficiência (PcD):

        * Perfil: Pessoas com deficiência visual (cegueira, baixa visão, daltonismo), motora (dificuldade de precisão nos membros superiores), auditiva ou cognitiva.

        * Relação com a tecnologia: Utilizam intensamente tecnologias assistivas, como leitores de tela (NVDA, JAWS, TalkBack), ampliadores de tela, navegadores adaptados, softwares de reconhecimento de voz e navegação restrita via teclado.

        * Necessidades: Elementos de interface semânticos, bom contraste, descrições textuais precisas e atalhos operáveis.

    * Pessoas Idosas:

        * Perfil: Usuários com 60 anos ou mais, que utilizam o portal para cursos de extensão, eventos ou acompanhamento familiar.

        * Relação com a tecnologia: Utilização frequente de dispositivos móveis ou computadores, mas com menor flexibilidade cognitiva para interfaces complexas, reduzida acuidade visual e reflexos motores menos precisos.

        * Necessidades: Fontes legíveis e ajustáveis, navegação direta, linguagem clara e feedback visual/sonoro evidente para suas ações.

    * Indivíduos com Baixo Letramento Digital e Acesso Tecnológico Limitado:

        * Perfil: Pessoas que tiveram pouca oportunidade de contato regular com tecnologias da informação ou que acessam a rede exclusivamente por dispositivos antigos e conexões lentas.

        * Relação com a tecnologia: Conhecimento básico/empírico, dificuldades para interpretar termos técnicos ou arquiteturas de informação muito ramificadas.

        * Necessidades: Interfaces intuitivas, menus organizados, tempo razoável de resposta e pouca poluição visual.
