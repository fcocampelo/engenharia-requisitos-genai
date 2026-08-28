# Requisitos não funcionais

## Requisitos não funcionais explicitamente definidos

O documento de elicitação informa expressamente:

> “Não foram levantados requisitos relacionados à segurança, desempenho, disponibilidade, acessibilidade e privacidade dos dados.”

Portanto, não existem requisitos não funcionais suficientemente definidos para receber identificadores RNF definitivos.

Seria incorreto, por exemplo, estabelecer tempos máximos de resposta, percentual de disponibilidade ou regras específicas de criptografia, pois nenhuma dessas informações foi fornecida pelos stakeholders.

## Requisitos não funcionais que precisam ser definidos

| Área                 | Classificação         | Questão que precisa ser definida                                                     |
| -------------------- | --------------------- | ------------------------------------------------------------------------------------ |
| Segurança            | RNF a definir/validar | Como serão realizados autenticação, autorização e proteção contra acessos indevidos? |
| Privacidade/LGPD     | RNF a definir/validar | Quais dados pessoais serão armazenados e como serão tratados?                        |
| Desempenho           | RNF a definir/validar | Qual tempo de resposta será considerado aceitável?                                   |
| Disponibilidade      | RNF a definir/validar | Qual nível de disponibilidade o sistema deverá oferecer?                             |
| Acessibilidade       | RNF a definir/validar | Quais critérios ou padrões de acessibilidade deverão ser atendidos?                  |
| Usabilidade          | RNF a definir/validar | Quais características de facilidade de uso serão necessárias?                        |
| Confiabilidade       | RNF a definir/validar | Como garantir consistência no controle de vagas, inscrições e pagamentos?            |
| Escalabilidade       | RNF a definir/validar | Quantos eventos e usuários simultâneos deverão ser suportados?                       |
| Compatibilidade      | RNF a definir/validar | Quais dispositivos, navegadores e plataformas deverão ser suportados?                |
| Auditoria            | RNF a definir/validar | Quais operações precisam manter histórico de alterações?                             |
| Rastreabilidade      | RNF a definir/validar | Quais operações deverão registrar usuário, data, horário e alteração realizada?      |
| Backup e recuperação | RNF a definir/validar | Como ocorrerá a recuperação de dados em caso de falha?                               |

Esses itens não são requisitos definitivos. São assuntos que devem fazer parte de uma nova rodada de elicitação.
