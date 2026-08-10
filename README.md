🎟️ Eventus — Sistema de Gestão de Eventos
Projeto de especificação de requisitos para o sistema de gerenciamento de eventos corporativos, congressos e workshops da empresa Eventus.

---

📌 Contexto
A empresa Eventus organiza eventos e atualmente utiliza formulários e planilhas para inscrições, o que dificulta o controle de vagas, pagamentos, cancelamentos e emissão de certificados.
Este projeto propõe um sistema centralizado para melhorar a experiência dos participantes e dar maior controle aos organizadores.

🎯 Objetivo da Atividade
Atuar como engenheira de requisitos, analisando o documento de elicitação fornecido e produzindo artefatos de especificação consistentes.
A IA generativa foi utilizada como apoio para:

Identificação de requisitos funcionais e não funcionais.

Refinamento de regras de negócio.

Sugestão de artefatos adequados (histórias de usuário, casos de uso, critérios de aceitação).

Revisão e ajustes para reduzir ambiguidades.

📂 Artefatos Produzidos
Os artefatos estão organizados na pasta especificacao/:

Histórias de Usuário

Casos de Uso

Critérios de Aceitação

✅ Exemplos
História de Usuário
Como participante, quero cancelar minha inscrição sem precisar entrar em contato com a organização,
para que eu tenha autonomia e praticidade.

Caso de Uso
Emitir Certificado

Ator: Participante

Fluxo principal: acessar área de certificados → selecionar evento concluído → sistema gera PDF → participante baixa ou imprime.

Alternativa: presença não confirmada → sistema bloqueia emissão.

Critérios de Aceitação
O certificado só pode ser emitido após o evento ser concluído.

O sistema deve verificar presença confirmada antes da emissão.

O certificado deve ser gerado em formato PDF.

🤖 Reflexão sobre o Uso da IA
Ferramenta utilizada: Microsoft Copilot.

Sugestões aceitas: estrutura de histórias de usuário e critérios de aceitação.

Sugestões modificadas: casos de uso simplificados para evitar redundância.

Sugestões descartadas: diagramas UML complexos, não necessários para o escopo atual.

Justificativa dos artefatos escolhidos: garantem clareza, objetividade e testabilidade dos requisitos, representando bem as necessidades dos stakeholders.
