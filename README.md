# iam-governance-notebooklm-lab
Laboratório de IAM e Access Governance utilizando NotebookLM, normas e frameworks de cybersecurity para análise de cenários de controle de acesso e governança de identidades.

## **Contexto e Objetivos**

**Contexto:**
Este projeto foi desenvolvido com foco em Identity and Access Management (IAM) e Governança de Segurança da Informação, utilizando o NotebookLM como ferramenta de apoio à análise, correlação e organização do conhecimento. 

O estudo parte de um cenário recorrente em ambientes corporativos: 
$\color{red}{\text{um usuário autenticado que não consegue visualizar determinada organização ou recurso dentro de um sistema.}}$
Embora inicialmente possa parecer um problema simples de acesso, o cenáro permite explorar diferentes camadas relacionadas à gestão de identidades, autorização, perfis de acesso, vínculo organizacional, políticas de segurança e governança.

Para construir a base de conhecimento do NotebookLM, foram selecionados materiais relacionados a IAM, RBAC, princípio do menor privilégio, Zero Trust, autenticação, autorização, controle de acesso e Governança de Segurança, incluindo conteúdos associados a referências como $\color{green}{\text{NIST SP 800-53, NIST SP 800-63, ISO/IEC 27001, ISO/IEC 27002 E OWASP.}}$

Além da análise técnica do problema, o projeto também busca avaliar o próprio comportamento da Inteligência Artificial diante de diferentes níveis de contexto.
Para isso, o mesmo cenário é submetido ao NotebookLM em diferentes etapas, permitindo comparar respostas obtidas $\color{green}{\text{sem fontes, após a curadoria de conteúdo e após o refinamento dos prompts.}}$

## **Objetivo Geral**

Investigar como princípios de IAM e Governança de Segurança da Informação podem ser utilizados para analisar problemas de acesso em ambientes corporativos e, simultaneamente, avaliar como a $\color{green}{\text{curadoria de fontes e a engenharia de prompts influenciam a qualidade das respostas produzidas por uma IA baseada em fontes.}}$

**Objetivos Específicos**

⚪ Compreender a diferença entre $\color{green}{\text{autenticação, autorização, vínculo de identitdade, perfil/role e políticas de acesso;}}$

⚪ Estudar conceitos de $\color{green}{\text{RBAC, menor privilégio, segregação de funções e Zero Trust;}}$

⚪ Relacionar controles e boas práticas apresentados por referências como $\color{green}{\text{NIST, ISO/IEC e OWASP}}$ com cenários de controle de acesso;

⚪ Utilizar o NotebookLM para correlacionar informações provenientes de diferentes fontes de segurança; 

⚪ Comparar respostas geradas antes e depois da inclusão de fontes especializadas; 

⚪ Desenvolver e testar diferentes estruturas de prompts para aumentar a precisão das análises;

⚪ Identificar $\color{red}{\text{inferências, hipóteses excessivas e limitações</span> apresentadas pela IA}}$ durante a investigação; 

⚪ Documentar as chamadas **cicatrizes**, registrando erros, limitações e ajustes realizados durante o processo.

⚪ Construir ao final um miniguia de estudo reutilizável sobre $\color{blue}{\text{IAM e Governança de Segurança da Informação.}}$

**Resultado Esperado**

Ao final do projeto, espera-se obter uma base de conhecimento organizada capaz de apoiar estudos e análises sobre $\color{green}{\text{gestão de identidades e controle de acesso}}$, demonstrando não apenas conceitos técnicos de Cybersecurity, mas também a importância da $\color{green}{\text{qualidade das fontes, validação das evidências e construção adequada de prompts}}$ ao utilizar $\color{blue}{\text{Inteligência Artificial}}$ como ferramenta de apoio à análise técnica.


## **Curadaoria de Fontes** 

A curadoria de fontes foi realizada com o objetivo de construir uma base de conhecimento tecnicamente confiável para o NotebookLM, priorizando contéudos relacionados a : $\color{green}{\text{Identity and Access Management (IAM), Governança de Segurança da Informação, controle de acesso, autenticação, autorização e Zero Trust.}}$

Durante a primeira etapa do projeto, foram utilizados conteúdos audiovisuais para explorar diferentes perspectivas sobre os temas e observar o comportamento inicial do NotebookLM. 
Posteriormente, a curadoria passou a priorizar $\color{green}{\text{documentação técnicas, normas, frameworks e materiais provenientes de fontes reconhecidas na área de Segurança da Informação.}}$

## **Critérios de Seleção**

As fontes foram selecionadas considerando os seguintes critérios: 

⚪ $\color{green}{\text{Autoridade:}}$ preferência por organizações e instituições reconhecidas na área de Cybersecurity;

⚪ $\color{green}{\text{Relevância:}}$ relação direta com IAM, controle de acesso, identitdade digital e Governança de Segurança;

⚪ $\color{green}{\text{Aplicabilidade:}}$ possibilidade de relacionar os conceitos apresentados ao cenário analisado no projeto;

⚪ $\color{green}{\text{Confiabilidade:}}$ preferência por documentação técnica e materiais oficiais em vez de conteúdos sem referência verificável;

⚪ $\color{green}{\text{Complementaridade:}}$ seleção de fontes capazes de abordar diferentes perspectivas do problema, evitando uma base de conhecimento excessivamente concentrada em um único conceito.

## **Fontes Selecionadas**

As fontes selecionadas abaixo serão utilizadas como base documental principal do NotebookLM e disponibilizadas ou referenciadas neste repositório. 

1. $\color{blue}{\text{NIST SP 800-53 Rev.5}}$

**Tema:** Security and Privacy Controls for Information Systems and Organizations.

**Aplicação no projeto:** controles relacionados a acesso, identificação, autenticação, auditoria e gerenciamento de privilégios. 

**Fonte:** https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final}}$

2. $\color{blue}{\text{NIST SP 800-63}}$

**Tema:** Digital Identity Guidelines. 

**Aplicação no projeto:** conceitos relacionados à identidade digital, autenticação, credenciais e ciclo de vida das identidades. 

**Fonte:** https://csrc.nist.gov/pubs/sp/800/63/4/final

3. $\color{blue}{\text{NIST SP 800-207}}$

**Tema:** Zero Trust Architecture

**Aplicação no projeto:** análise de decisões de acesso baseadas em identidade, contexto, políticas e ausência de confiança implícita.

**Fonte:** https://csrc.nist.gov/pubs/sp/800/207/final

4. $\color{blue}{\text{ISO/IEC 27001 e ISO/IEC 27002}}$

**Tema:** Sistema de Gestão de Segurança da Informação e controles de segurança. 

**Aplicação no projeto:** governança, políticas de controle de acesso, gestão de identidades, privilégios e responsabilidades relacionadas à Segurança da Informação.

**Fonte:** https://www.iso.org/standard/27001 & https://www.iso.org/standard/75652.html

5. $\color{blue}{\text{OWASP}}$

**Tema:** Autenticação, autorização e controle de acesso.

**Aplicação no projeto:** apoio técnico para compreender falhas e boas práticas relacionadas à implementação de mecanismos de autenticação e autorização em aplicações.

**Fonte:** https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html & https://cheatsheetseries.owasp.org/cheatsheets/Authorization_Cheat_Sheet.html

**Papel das fontes no Experimento**

A utilização dessas fontes não tem apenas a finalidade de reunir conteúdo sobre Cybersecurity. Elas também funcionam como parte do próprio experimento realizado com o NotebookLM. 

Ao longo do projeto, respostas produzidas com diferentes níveis de contexto serão comparadas para observar como a $\color{red}{\text{qualidade, autoridade e especificidade das fontes}}$ influenciam a capacidade da IA de formular hipóteses, correlacionar conceitos e evitar inferências não sustentadas pelo material disponível.

Essa abordagem permite avaliar não apenas $\color{red}{\text{o que a IA responde}}$, mas principalmente $\color{red}{\text{em quais evidências ela fundamenta sua resposta.}}$

## $\color{red}{\text{ Engenharia de Prompts e Cicatrizes}}$

Esta etapa documenta a evolução dos prompts utilizados no NotebookLM, as respostas obtidas e as limitações identificadas durante os testes.

### $\color{red}{\text{Teste 01 - Prompt sem base de conhecimento}}$

#### $\color{red}{\text{Prompt utilizado}}$
Um usuário não consegue visualizar uma empresa em determinado sistema. 
Quais podem ser as causas?? 

#### $\color{red}{\text{Contexto do teste}}$ 
Este teste foi realizado antes da inclusão de qualquer fonte de conhecimento no NotebookLM. O objetivo foi estabelecer uma linha de base para observar como a ferramenta responderia ao cenário utilizando apenas o prompt, sem documentos, referências técnicas ou materiais previamente adicionados ao notebook. 

A resposta obtida nesta etapa serviria posteriormente como parâmetro de comparação para os testes realizados após a curadoria e inclusão de fontes especializadas sobre IAM, Governança e controle de acesso. 

#### $\color{red}{\text{Resultado obtido}}$
O NotebookLM informou que não havia fontes de informação disponíveis no notebook para responder à pergunta e sugeriu realizar uma pesquisa na web sobre possíveis causas relacionadas a acesso, permissão, parametrização, IAM e Governança.

**Resposta exata do NotebookLM:** Não há fontes de informação no seu notebook para responder a essa pergunta.
Gostaria que eu fizesse uma pesquisa na web para identificar as causas mais comuns de um usuário não conseguir visualizar uma empresa em um sistema (como problemas de permissão, parametrização ou regras de IAM e Governança)?

#### $\color{red}{\text{Análise crítica}}$

O teste demonstrou uma característica importante do NotebookLM: a qualidade e a profundidade da resposta dependem diretamente das fontes disponibilizadas no notebook

Sem uma base documental previamente estruturada, a ferramenta não conseguiu produzir uma análise fundamentada sobre o cenário apresentado.


#### $\color{red}{\text{ Cicatriz 01 - Ausência de contexto documental}}$
Um prompt, mesmo sendo pertinente ao problema, não é suficiente quando a IA não possui contexto documental adequado. 

#### $\color{red}{\text{Aprendizado}}$
Antes de aprimorar a engenharia do prompt, é necessário construir uma base de conhecimento confiável, relevante e alinhada ao problema que será analisado.

### $\color{red}{\text{Teste 02 - Mesmo prompt após a curadoria inicial de fontes}}$

#### $\color{red}{\text{Prompt utilizado}}$
Um usuário não consegue visualizar uma empresa em determinado sistema. 
Quais podem ser as causas??

#### $\color{red}{\text{Contexto do teste}}$
O mesmo prompt utilizado no $\color{red}{\text{Teste 01}}$ foi executado novamente após a inclusão de aproximadamente 20 fontes audiovisuais relacionadas a IAM, Governança, NIST, ISO 27001/27002, Zero Trust, autenticação e controle de acesso.

#### $\color{red}{\text{Resultado observado}}$
Diferentemente do primeiro teste, o NotebookLM passou a apresentar hipóteses técnicas fundamentadas nas fontes fornecidas. 

Entre as possibilidades levantadas estavam: 

- ausência de autorização ou privilégio adequado;
- aplicação do princípio do menor privilégio;
- políticas de acesso baseadas em contexto;
- restrições relacionadas a Zero Trust;
- dispositivo ou localização não autorizados;
- microsegmentação e Software Defined Perimeter;
- regras de segregação e conflito de interesses;
- expiração de sessão ou token;
- problemas relacionados a credenciais de integração.

#### $\color{red}{\text{Evolução observada}}$
A inclusão das fontes transformou significativamente a capacidade de análise do modelo. O NotebookLM deixou de apresentar ausência de contexto e passou a correlacionar o cenário com conceitos de IAM, Governança e arquitetura de segurança. 

#### $\color{red}{\text{Cicatriz 02 - Excesso de hipóteses}}$
Apesar da melhora técnica, a resposta apresentou hipóteses avançadas que não estavam necessáriamente sustentadas pelo cenário informado.

Conceitos cmo geolocalização, BYOD, microsegmentação, Brewer-Nash, JWT e credenciais de integração são tecnicamente possíveis, porém não havia evidências no prompt de que esses mecanismos estivessem implementados no ambiente analisado. 

#### $\color{red}{\text{Aprendizado}}$
Uma base de conhecimento mais rica não elimina a necessidade de uma boa engenharia de prompt. 

Quanto maior o corpus disponível, maior também a necessidade de delimitar contexto, escopo, evidências conhecidas e nível de confiança esperado da resposta. 


### $\color{red}{\text{Teste 03 - Prompt estruturado com mesma base de fontes}}$

#### $\color{red}{\text{Prompt utilizado}}$ 
Um usuário autenticado não consegue visualizar uma determinada empresa em um sistema corporativo.
Analise o cenário sob a perspectiva de Identity and Access Management (IAM) e Governança de Segurança.
Considere apenas hipóteses sustentadas pelas fontes disponíveis. Diferencie problemas de autenticação, autorização, vínculo entre identidade e organização, perfil/role e políticas de acesso. Para cada hipótese, informe qual evidência deveria ser verificada antes de considerá-la provável. Não assuma que mecanismos como Zero Trust, geolocalização, microsegmentação ou restrições de dispositivo estejam implementados sem evidências. Ao final, apresente uma ordem recomendada de investigação, partindo das causas mais simples e prováveis para as mais complexas. 

#### $\color{red}{\text{Contexto do teste}}$ 
Mesmo cenário do $\color{red}{\text{Teste 01 e Teste 02}}$. O usuário já está autenticado, porém determinada empresa não é exibida/disponibilizada no sistema.

#### $\color{red}{\text{Resultado observado}}$

Diferentemente do primeiro teste, o NotebookLM apresentou uma resposta significativamente mais estruturada, organizando as causas em oito hipóteses técnicas fundamentadas nas fontes fornecidas:

- ausência de autorização ou privilégio adequado;
- aplicação do princípio do menor privilégio;
- política de acesso baseadas em contexto;
- restrições relacionadas a Zero Trust;
- dispositivo ou localização não autorizado;
- microsegmentação e Software Defined Perimeter (SDP);
- regras de segregação e conflito de interesse;
- expiração de sessão ou token;
- problemas relacionados a credenciais de integração ou serviço.

#### $\color{red}{\text{Evolução observada}}$

A inclusão das fontes transformou significativamente a qualidade da resposta, com melhor cobertura de domínios de IAM e Governança, além da introdução de conceitos técnicos pertinentes como Zero Trust, microsegmentação, políticas contextuais e segregação de funções. 


#### $\color{red}{\text{Cicatriz 03 - Inferências não comprovadas mesmo após o refinamento do prompt}}$ 
O prompt estruturado reduziu significativamente hipóteses excessivamente amplas e melhorou a priorização da análise. Entretanto, o modelo ainda apresentou afirmações e componentes arquiteturais não confirmados pelo cenário, como considerar determinado erro "a causa mais comum" ou pressupor tecnologias específicas. Isso demonstrou que melhorar o prompt reduz alucinações contextuais, mas não elimina a necessidade de fontes primárias e documentação específica do ambiente.

#### $\color{red}{\text{Análise crítica}}$

- O modelo passou a organizar as hipóteses de forma lógica e técnica.
- Diferenciou claramente os domínios de IAM: autenticação, autorização, vínculo, perfil/role e políticas.
- Apresentou evidências especificas que devem ser verificadas para cada hipótese.
- Priorizou a investigação de forma alinhada às boas práticas de troubleshooting. 

#### $\color{red}{\text{Próximos passos}}$ 
* Refinar o prompt melhora a qualidade e a estrutura da resposta, porém a precisão e a confiabilidade dependem diretamente da qualidade, autoridade e aderência das fontes utilizadas.

* Adicionar fontes primárias e normativas (ex: NIST SP 800-53 Rev.5, NIST SP 800-63, NIST SP 800-207, ISO 27001/27002 E OWASP oficiais) e repetir exatamente o mesmo prompt para avaliar o impacto da autoridade do conteúdo na resposta.


### $\color{red}{\text{Teste 04 - Prompt estruturado com fontes normativas}}$ 

#### $\color{red}{\text{Prompt utilizado}}$
Um usuário autenticado não consegue visualizar uma determinada empresa em um sistema corporativo. Analise o cenário sob a perspectiva de Identity and Access Managemente (IAM) e Governança de Segurança. Considere apenas hipóteses sustentadas pelas fontes disponíveis. Diferencie problemas de autenticação, autorização, vínculo entre identidade e organização, perfil/role e políticas de acesso. Para cada hipótese, informe qual evidência deveria ser verificada antes de considerá-la provável. Não assuma que mecanismos como Zero Trust, geolocalização, microsegmentação ou restrições de dispositivo estejam implementados sem evidências. Ao final, apresente uma ordem recomendada de investigação, partindo das causas mais simples e prováveis para as mais complexas.

#### $\color{red}{\text{Contexto do teste}}$ 
Após os testes anteriores, a base de conhecimento do NotebookLm foi ampliada com documentos técnicos e normativos relacionados a Identity and Access Management (IAM), controle de acesso, identidade digital e governança de Segurança. 

Nesta etapa, foram adicionadas fontes documentais relacionadas às famílias NIST SP 800-53 e NIST SP- 800-63, além de materiais referentes às normas ISO/IEC 27001 e ISO/IEC 27002. 

#### $\color{red}{\text{Resultado observado}}$
A resposta apresentou uma análise mais estruturada e fundamentada, separando o problema em diferentes camadas de IAM: 

- autenticação;
- vínculo entre identidade e organização;
- perfil e Role-Based Access Control (RBAC);
- políticas de acesso;
- fluxo técnico de autorização. 

O NotebookLM também passou a relacionar algumas verificações a controles específicos, como AC-2 (Account Management) e AC-3 (Access Enforcement), além de diferenciar de forma mais clara autenticação e autorização.

A investigação foi organizada progressivamente, partindo da validação cadastral e dos atributos da identidade até verificações mais complexas relacionadas ao fluxo técnico de autorização.

#### $\color{red}{\text{Evolução observada}}$

Em comparação ao teste anterior, a inclusão de fontes normativas tornou a resposta mais alinhada aos conceitos formais de IAM e Governança de Segurança. 

A análise deixou de apresentar uma quantidade excessiva de tecnologias e mecanismos avançados como hipóteses principais e passou a priorizar vínculo organizacional, provisionamento, roles, políticas e autorização.

Também foi possível observar maior rastreabilidade entre determinadas recomendações e os controles presentes nas fontes utilizadas. 

#### $\color{red}{\text{Cicatriz 04 - Persistência de inferências não comprovadas}}$ 

Apesar da evolução observada, a resposta ainda apresentou algumas afirmações que não poderiam ser comprovadas exclusivamente pelo cenário ou pelas fontes disponibilizadas. 

Um exemplo foi classificar a inconsistência cadastral como "a causa mais comum de incidentes", embora não tenham sido apresentados dados estatísticos que sustentassem essa conclusão.

Também foram mencionadas tecnologias específicas, como JWT, SAML, LDAP, Active Directory, e API Gateway. Esses elementos são tecnicamente plausíveis como exemplos de implementação, mas sua existência no ambiente analisado não havia sido confirmada.

#### $\color{red}{\text{Aprendizado}}$ 

A inclusão de fontes normativas aumentou a precisão conceitual e a rastreabilidade da análise, mas não eliminou completamente a necessidade de avaliação humana sobre as conclusões produzidas pela IA. 

O experimento demonstrou que fontes confiáveis e prompts bem estruturados reduzem inferências excessivas, porém não garantem que todas as afirmações geradas estejam diretamente sustentadas por evidências. 

Em contextos de cybersecurity, especialmente IAM e Governança, a IA deve ser utilizada como ferramenta de $\color{green}{\text{apoio à análise}}$, enquanto a validação das evidências e a decisão final permanecem sob responsabilidade do profissional. 


### $\color{red}{\text{Teste 05 - Auditoria das afirmações geradas}}$ 

#### $\color{red}{\text{Prompt utilizado}}$
Foi solicitado ao NotebookLM que revisasse criticamente o miniguia produzido anteriormente utilizando exclusivamente as fontes disponíveis no notebook. 

A ferramenta deveria identificar afirmações normativas, requisitos obrigatórios, valores numéricos, prazos e recomendações apresentadas de forma absoluta. 

Para cada afirmação, foi solicitado: 

1. apresentar a afirmação original;
2. indicar a fonte utilizada;
3. informar a seção ou controle correspondente, quando disponível;
4. classificá-la como Suportada, Parcialmente suportada ou Não suportada;
5. justificar a classificação;
6. propor uma redação mais conservadora quando necessário. 

Também foi determinado que lacunas documentais não deveriam ser preenchidas com conhecimento externo. 

#### $\color{red}{\text{Contexto do teste}}$ 

Os experimentos anteriores demonstraram que a inclusão de fontes especializadas e documentos normativos aumentou significativamente a qualidade das respostas produzidas pelo NotebookLM. 

Entretanto, durante a geração do miniguia final, foram identificadas afirmações apresentadas como requisitos obrigatórios ou regras gerais que poderiam representar extrapolações das fontes utilizadas. 

O objetivo deste teste foi avaliar se, quando explicitamente solicitado a rastrear suas próprias afirmações até as evidências documentais, o NotebookLM seria capaz de identificar e corrigir essas extrapolações. 

#### $\color{red}{\text{Resultado observado}}$

O NotebookLM revisou oito grupos de afirmações consideradas sensíveis e classificou cada uma de acordo com o nível de sustentação encontrado nas fontes.

Entre os principais resultados: 

- o uso obrigatório de GUIDs foi classificado como parcialmente suportado;
- o uso isolado de biometria foi rejeitado dentro do contexto normativo analisado;
- a obrigatoriedade de MFA foi delimitada de acordo com os níveis AAL;
- o termo "desprovisionamento imediato" foi substituído por uma formulação dependente do período definido pela organização;
- o conceito de Just-In-Time foi separado entre sua utilização normativa relacionada à privacidade e sua aplicação operacional em elevação temporária de privilégios;
- a imutabilidade de logs foi tratada como mecanismo possível de proteção, e não como característica inerente das trilhas de auditoria;
- o modelo Brewer-Nash foi reposicionado como mecanismo dinâmico de controle relacionado a conflitos de interesse;
- o prazo de três meses atribuído ás credenciais de App Registrations foi identificado como uma interpretação incorreta: a fonte descrevia uma antecedência para alerta de expiração e não um período máximo de validade da credencial.


#### $\color{red}{\text{Evolução observada}}$ 

O teste demonstrou que a utilização de um processo explícito de auditoria e rastreabilidade permitiu ao NotebookLM identificar diferenças entre requisitos normativos, recomendações técnicas e práticas operacionais presentes nas fontes.

A ferramenta conseguiu revisar afirmações anteriormente apresentadas com excesso de certeza e produzir formulações mais conservadoras quando a evidência documental não sustentava o caráter absoluto da conclusão.

Essa etapa também evidenciou que a simples presença de uma informação nas fontes não garante que a relação estabelecida pela IA entre essa informação e a conclusão produzida esteja correta. 

#### $\color{red}{\text{Cicatriz 05 - Transformação de boas práticas em requisitos normativos}}$

Durante a geração do miniguia, algumas recomendações técnicas e práticas operacionais foram apresentadas pela IA como se fossem requisitos normativos obrigatórios. 

Um dos exemplos mais evidentes ocorreu com a expiração de credenciais de App Registrations. A fonte descrevia uma prática de monitoramento que antecipava em três meses o alerta de expiração, porém a resposta inicial transformou essa informação em um suposto prazo máximo de três meses para a validade das credenciais. 

Também foram observadas extrapolações semelhantes envolvendo GUIDs, Just-In-Time, MFA e desprovisionamento. 

O problema não estava necessariamente na ausência da informação dentro da base, mas na interpretação e na força normativa atribuída pela IA à informação recuperada. 


#### $\color{red}{\text{Aprendizado}}$

Fontes confiáveis e engenharia de prompts aumentam significativamente a qualidade das respostas, mas não eliminam a necessidade de rastreabilidade e validação das afirmações produzidas. 

Em documentos relacionados à Segurança da Informação e Governança, é fundamental distinguir: 

- requisitos normativos;
- recomendações técnicas;
- práticas de mercado;
- exemplos de implementação;
- interpretações produzidas pela IA.

O teste demonstrou que solicitar explicitamente fonte, seção, controle e nível de sustentação para cada afirmação é uma estratégia eficaz para reduzir extrapolações e aumentar a confiabilidade do conteúdo produzido com apoio de Inteligência Artificial.
Também foi observado que uma nova geração realizada após a auditoria pode introduzir novas afirmações ou extrapolações que não estavam presentes na versão anterior. Dessa forma, a correção de uma resposta por meio de prompting não elimina a necessidade de uma revisão humana final do conteúdo consolidado.

## $\color{red}{\text{Miniguia de estudos - IAM e Governança de Acessos}}$

### $\color{blue}{\text{1. Visão Geral}}$

O Gerenciamento de Identidade e Acesso (IAM) reúne processos, políticas e controles destinados a gerenciar identidades digitais e determinar como usuários e outras entidades acessam recursos organizacionais.

No contexto de Governança, Risco e Conformidade (GRC), o IAM contribui para a gestão de privilégios, rastreabilidade, redução de riscos de acesso indevido e atendimento a requisitos organizacionais e regulatórios.


### $\color{blue}{\text{2. Conceitos Fundamentais}}$

#### $\color{red}{\text{Sujeito}}$

Entidade humana ou não humana que solicita acesso a um recurso, como um usuário, serviço ou processo. 

#### $\color{red}{\text{Objeto}}$

Recurso sobre o qual o acesso é solicitado, como arquivos, aplicações, bancos de dados ou dispositivos.

#### $\color{red}{\text{Direitos de Acesso}}$

Definem quais operações um sujeito pode executar sobre determinado objeto, como leitura, escrita, execução ou exclusão.

### $\color{blue}{\text{3. Identidade Digital}}$

A identidade digital representa uma entidade em uma transação ou ambiente digital e permite que controles de autenticação, autorização e rastreabilidade sejam aplicados.

Em determinados cenários de federação de identidade, identificadores pseudônimos podem ser utilizados para reduzir a possibilidade de correlação da identidade entre diferentes serviços. 

GUIDs e UUIDs, por outro lado, são mecanismos técnicos comuns de identificação e não devem ser interpretados automaticamente como requisitos de privacidade ou pseudonimização.

### $\color{blue}{\text{4. Autenticação e Autorização}}$

Autenticação e autorização representam etapas distintas do controle de acesso. 

- **Autenticação:** verifica a identidade apresentada pelo usuário.
- **Autorização:** determina quais recursos e operações essa identidade pode acessar após ser autenticada.

A NIST SP 800-63B utiliza os Authenticator Assurance Levels (AAL) para representar diferentes níveis de garantia de autenticação.

A autenticação multifator é exigida nos níveis AAL2 e AAL3, enquanto o AAL1 admite autenticação de fator único ou multifator.

O uso de biometria deve ser analisado de acordo com os requisitos do mecanismo de autenticação adotado e não deve ser tratado isoladamente como equivalente a todos os demais tipos de autenticadores.

### $\color{blue}{\text{5. Gerenciamento de Contas}}$ 

Gerenciamento de contas envolve atividades como criação, alteração, suspensão e encerramento de identidades e seus respectivos acessos. 

O controle AC-2 da NIST SP 800-53 estabelece requisitos relacionados ao gerenciamento dessas contas ao longo de seu ciclo de vida. 

O prazo para desativação de acessos deve ser definido pela organização de acordo com su políticas, riscos e requisitos aplicáveis. 

### $\color{blue}{\text{6. RBAC - Role-Based Access Control}}$

O RBAC organiza permissões com base em papéis ou funções organizacionais. 

Em vez de conceder privilégios individualmente a cada usuário, permissões são associadas a roles, permitindo maior pradonização e facilitando administração e auditoria. 

$\color{green}{\text{Exemplo:}}$

Um usuário associado à role de "Analista Financeiro" pode receber somente as permissões necessárias para executar atividades relacionadas à sua função.


### $\color{blue}{\text{7. ABAC - Attribute-Based Access Control}}$

O ABAC utiliza atributos para apoiar decisões de acesso. 
Esses atributos podem estar relacionados a:

- sujeito;
- recuros;
- ambiente;
- ação solicitada.

Por ser baseado em atributos e contexto, o ABAC permite políticas de autorização mais granulares e dinâmicas do que modelos exclusivamente baseado em roles. 

### $\color{blue}{\text{8. Princípio do Menor Privilégio}}$

O princípio do menor privilégio determina que usuários e contas devem possuir somente os acessos necessários para executar suas funções. 

Na NIST SP 800-53, esse princípio está associado ao controle AC-6. 

A aplicação adequada do menor privilégio reduz a exposição de recursos e limita o impacto potencial do uso indevido de uma conta. 


### $\color{blue}{\text{9. Segregação de Funções - SoD}}$

A Segregação de Funções busca evitar que uma única pessoa concentre responsabilidades incompatíveis dentro de um processo crítico. 

Esse princípio aparece no controle AC-5 da NIST SP 800-53 e no controle 5.3 da ISO/IEC 27002:2022. 

$\color{green}{\text{Exemplo:}}$

Quem solicita determinado acesso não deveria necessariamente possuir autoridade para aprovar a própria solicitação.






