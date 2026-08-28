# Sistema de Gestão de Eventos — Especificação de Requisitos

## Sobre a atividade

Esta atividade teve como objetivo analisar o resultado da elicitação de requisitos de um Sistema de Gestão de Eventos e, a partir dessas informações, escolher e elaborar artefatos adequados para representar os requisitos do projeto.

O cenário envolve a empresa Eventus, que atualmente utiliza formulários on-line e planilhas para controlar eventos, inscrições, vagas, pagamentos, cancelamentos e certificados.

A proposta é desenvolver um sistema capaz de centralizar essas informações e facilitar tanto o trabalho dos organizadores quanto a utilização pelos participantes.

## Utilização de Inteligência Artificial Generativa

A ferramenta de Inteligência Artificial Generativa que utilizei durante a atividade foi o **ChatGPT**.

Utilizei a IA principalmente como uma ferramenta de apoio durante a análise do documento de elicitação. Ela ajudou a organizar as informações coletadas nas entrevistas, separar requisitos funcionais, possíveis regras de negócio e pontos que ainda precisavam ser discutidos com os stakeholders.

Outro apoio importante foi na identificação de ambiguidades. Algumas funcionalidades eram mencionadas nas entrevistas, mas não estavam completamente definidas. Foi o caso do cancelamento das inscrições, reembolsos, lista de espera, certificados e tratamento de conflitos de horário entre workshops.

Nessas situações, procurei não utilizar a resposta da IA como uma decisão definitiva. Em vez disso, os pontos foram registrados como pendências e transformados em perguntas que deveriam ser apresentadas aos stakeholders em uma nova rodada de elicitação.

## Sugestões aceitas

Entre as sugestões apresentadas pela IA, considerei adequadas para o projeto:

- histórias de usuário;
- critérios de aceitação;
- casos de uso;
- diagrama de casos de uso;
- regras de negócio;
- matriz de rastreabilidade.

Escolhi as histórias de usuário porque permitem representar as necessidades dos diferentes usuários do sistema de maneira simples e objetiva.

Os critérios de aceitação complementam essas histórias, ajudando a tornar os requisitos mais claros e verificáveis.

Os casos de uso foram utilizados somente nos processos considerados mais importantes, como inscrição, cancelamento e emissão de certificado. Dessa forma, foi possível detalhar esses fluxos sem criar documentação excessiva.

Também considerei útil o diagrama de casos de uso porque ele apresenta uma visão geral dos atores e das principais funcionalidades do sistema.

Por fim, a matriz de rastreabilidade foi utilizada para verificar a relação entre requisitos, regras de negócio e os demais artefatos produzidos.

## Sugestões descartadas ou modificadas

Algumas sugestões da IA não foram utilizadas nesta etapa.

Os protótipos de interface, por exemplo, poderiam ajudar na validação do sistema com os usuários, mas considerei que ainda existem muitas regras de negócio sem definição. Criar telas neste momento poderia fazer com que decisões ainda não tomadas pelos stakeholders fossem incorporadas ao projeto.

Também optei por não desenvolver um modelo de domínio detalhado porque o foco principal desta atividade está na especificação dos requisitos.

Os diagramas de atividade e de estados também foram avaliados, mas não foram produzidos. Apesar de poderem ser úteis para representar processos como inscrição, pagamento, lista de espera e cancelamento, esses processos ainda possuem regras que precisam ser esclarecidas.

A recomendação sobre casos de uso também foi modificada. Em vez de documentar todas as funcionalidades como casos de uso detalhados, decidi utilizar esse formato somente nos processos mais importantes. Isso evitou duplicação de informações com as histórias de usuário.

## Motivo da escolha dos artefatos

Considerei que a combinação de histórias de usuário, critérios de aceitação, casos de uso, regras de negócio, diagrama de casos de uso e matriz de rastreabilidade atende bem às características do projeto.

As histórias de usuário representam as necessidades de participantes, organizadores, equipe financeira e palestrantes.

Os casos de uso ajudam a detalhar os fluxos que possuem mais interação entre o usuário e o sistema.

As regras de negócio permitem manter separadas as condições relacionadas a vagas, cancelamentos, pagamentos e reembolsos.

Já a matriz de rastreabilidade permite verificar se os requisitos identificados durante a análise estão sendo considerados na especificação.

Dessa forma, procurei produzir uma documentação suficiente para representar o sistema sem adicionar artefatos apenas para aumentar o volume da entrega.

## Cuidados durante a utilização da IA

Um dos principais cuidados que tive durante a utilização da IA foi não considerar automaticamente suas sugestões como requisitos.

Em vários momentos, a IA poderia completar informações que pareciam fazer sentido, mas que não estavam presentes no documento de elicitação.

Por exemplo, seria possível assumir que o certificado somente deve ser emitido para quem teve presença confirmada. Apesar de parecer uma regra razoável, isso não foi definido pelos stakeholders.

O mesmo acontece com a lista de espera. Poderíamos assumir que o primeiro participante da fila receberia automaticamente a vaga liberada, mas o documento não informa se essa será realmente a regra utilizada.

Por isso, sempre que uma informação não estava definida, procurei tratá-la como uma pendência ou hipótese para validação.

Esse cuidado foi importante para manter a diferença entre utilizar a IA como ferramenta de apoio e deixar que ela tome decisões de negócio.

Na minha avaliação, a principal contribuição da Inteligência Artificial durante a atividade foi ajudar na organização, análise e revisão das informações. Entretanto, a decisão sobre quais requisitos devem fazer parte do sistema e quais regras devem ser adotadas continua sendo responsabilidade do engenheiro de requisitos em conjunto com os stakeholders.

---

# 13. Conclusão

A análise da elicitação mostrou que a Eventus possui uma necessidade clara de centralizar a gestão dos seus eventos, principalmente em relação a inscrições, vagas, pagamentos, cancelamentos e certificados.

Foi possível identificar um conjunto inicial de requisitos funcionais e regras de negócio. Entretanto, também ficou evidente que diversas decisões importantes ainda não foram tomadas.

Os principais pontos que precisam de uma nova rodada de elicitação estão relacionados ao funcionamento da lista de espera, regras de cancelamento, reembolso, confirmação de presença, certificados, conflitos de horários e processamento de pagamentos.

Além disso, praticamente toda a dimensão de requisitos não funcionais ainda precisa ser discutida, incluindo segurança, privacidade, LGPD, desempenho, disponibilidade e acessibilidade.

A utilização da GenAI foi útil principalmente para estruturar a análise, identificar lacunas, organizar requisitos e sugerir artefatos. Entretanto, as sugestões precisaram ser avaliadas criticamente antes de serem incorporadas à especificação.

A escolha de histórias de usuário, critérios de aceitação, casos de uso selecionados, regras de negócio, diagrama de casos de uso e matriz de rastreabilidade apresentou um bom equilíbrio entre simplicidade e nível de detalhamento.

Dessa forma, a IA foi utilizada como apoio ao trabalho de Engenharia de Requisitos, enquanto as decisões que dependem das regras e necessidades da organização permaneceram identificadas para posterior validação com os stakeholders.
