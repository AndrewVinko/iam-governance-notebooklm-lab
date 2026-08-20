# iam-governance-notebooklm-lab
Laboratório de IAM e Access Governance utilizando NotebookLM, normas e frameworks de cybersecurity para análise de cenários de controle de acesso e governança de identidades.

**Contexto e Objetivos**

**Contexto:**
Este projeto foi desenvolvido com foco em Identity and Access Management (IAM) e Governança de Segurança da Informação, utilizando o NotebookLM como ferramenta de apoio à análise, correlação e organização do conhecimento. 

O estudo parte de um cenário recorrente em ambientes corporativos: 
$\color{red}{\text{um usuário autenticado que não consegue visualizar determinada organização ou recurso dentro de um sistema.}}$
Embora inicialmente possa parecer um problema simples de acesso, o cenáro permite explorar diferentes camadas relacionadas à gestão de identidades, autorização, perfis de acesso, vínculo organizacional, políticas de segurança e governança.

Para construir a base de conhecimento do NotebookLM, foram selecionados materiais relacionados a IAM, RBAC, princípio do menor privilégio, Zero Trust, autenticação, autorização, controle de acesso e Governança de Segurança, incluindo conteúdos associados a referências como $\color{green}{\text{NIST SP 800-53, NIST SP 800-63, ISO/IEC 27001, ISO/IEC 27002 E OWASP.}}$

Além da análise técnica do problema, o projeto também busca avaliar o próprio comportamento da Inteligência Artificial diante de diferentes níveis de contexto.
Para isso, o mesmo cenário é submetido ao NotebookLM em diferentes etapas, permitindo comparar respostas obtidas $\color{green}{\text{sem fontes, após a curadoria de conteúdo e após o refinamento dos prompts.}}$

**Objetivo Geral**

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


**Curadaoria de Fontes** 

A curadoria de fontes foi realizada com o objetivo de construir uma base de conhecimento tecnicamente confiável para o NotebookLM, priorizando contéudos relacionados a : $\color{green}{\text{Identity and Access Management (IAM), Governança de Segurança da Informação, controle de acesso, autenticação, autorização e Zero Trust.}}$

Durante a primeira etapa do projeto, foram utilizados conteúdos audiovisuais para explorar diferentes perspectivas sobre os temas e observar o comportamento inicial do NotebookLM. 
Posteriormente, a curadoria passou a priorizar $\color{green}{\text{documentação técnicas, normas, frameworks e materiais provenientes de fontes reconhecidas na área de Segurança da Informação.}}$

**Critérios de Seleção**

As fontes foram selecionadas considerando os seguintes critérios: 

⚪ $\color{green}{\text{Autoridade:}}$ preferência por organizações e instituições reconhecidas na área de Cybersecurity;

⚪ $\color{green}{\text{Relevância:}}$ relação direta com IAM, controle de acesso, identitdade digital e Governança de Segurança;

⚪ $\color{green}{\text{Aplicabilidade:}}$ possibilidade de relacionar os conceitos apresentados ao cenário analisado no projeto;

⚪ $\color{green}{\text{Confiabilidade:}}$ preferência por documentação técnica e materiais oficiais em vez de conteúdos sem referência verificável;

⚪ $\color{green}{\text{Complementaridade:}}$ seleção de fontes capazes de abordar diferentes perspectivas do problema, evitando uma base de conhecimento excessivamente concentrada em um único conceito.

**Fontes Selecionadas**

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

Essa abordagem permite avaliar não apenas $\color{red}{\text{o que a IA responde}}$, mas principalmente $\color{red}{\text{em quais evidências ela fundamenta sua resposta.






