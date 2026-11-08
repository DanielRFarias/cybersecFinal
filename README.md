# cybersecFinal
The final part of the DIO cybersecurity course, about creating and using a a.i agent 

A parte final do curso sobre cybersegurança da DIO pede o uso de um harness em agente de i.a, tendo fornecido a base da própria DIO: https://github.com/digitalinnovationone/dio-agent

No momento dessa aula as 5 opções de harness que o próprio agente indica são:

Google Antigravity, Claude Code, Codex, OpenCode e Hermes

A recomendação é do Antigravity por ter mais recursos livres.

No harness usado bastou criar um projeto na mesma pasta em que estão os arquivos conseguidos no repositório do DIO agent, em teoria o uso dele é bastante similar em qualquer harness sugeridos, o importante é acessar a pasta do DIO agent, e também é bom lembrar de verificar atualizações do mesmo, provavelmente podendo ser pedido pelo próprio harness.

No caso do harness ser usado via terminal é importante abrir o terminal na pasta do agente para que ele possa ser encontrado sem que ocorra erro.

Para criar novas extensões é preciso criar uma pasta dentro da pasta skill do agent, de preferência com um nome que ajude a lembrar a o que se refere, e dentro dessa pasta criar um arquivo SKILL.md com a expecificação do que é esperado que o agente faça tudo em português.

Além disso é necessário criar um arquivo .md no diretório knowledge que fica dentro da pasta agent.

Esse arquivo contém como o nome da pasta indica conhecimentos que o agente deve ter sobre como agir, novamente toda a informação pode ser passada em português.

Outra mudança que deve ser feita é no próprio arquivo persona.md encontrado na pasta agent, no arquivo deve ser adicionado a informação que perguntas relacionadas a nova expecificação para ser resolvida deve ser referido a skill e o knowledge criados, isso pelo agente claro.

Finalmente no arquivo AGENTS.md do diretório raíz deve ser modificado a parte que explica skills do agente.

Outros arquivos desse repositório incluem os arquivos de skill e knowledge criados para teste bem como os arquivos que foram modificados por ter sido pedido. 

Decidi criar um agente para ajudar a otimizar código, algumas vezes principalmente quando estou aprendendo os códigos criados podem demorar ou usar funções desnecessárias, além disso caso exista uma forma mais simples é sempre bom aprender.

Esse arquivo explica onde devem ser colocados.
