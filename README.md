#Gestao do tempo 

atividade do Alan

fontes : facabook e google

Atividade 1: Desvendando a História dos Projetos - A Lógica do Git

Análise de um Histórico de Commits
Repositório escolhido: https://github.com/facebook/react Projeto: React – Biblioteca JavaScript para construção de interfaces de usuário

Commit 1

Mensagem do commit: Fix bug in useEffect cleanup function when dependencies change

Arquivos modificados:

packages/react-reconciler/src/ReactFiberHooks.js

Intenção do desenvolvedor: Corrigir um problema no comportamento da função de limpeza (cleanup) do hook useEffect. A mudança visa garantir que os efeitos colaterais sejam corretamente limpos ao atualizar dependências.

Commit 2

Mensagem do commit: Add support for useEvent hook (experimental)

Arquivos modificados:

packages/react/src/ReactHooks.js

packages/shared/ReactFeatureFlags.js

Intenção do desenvolvedor: Introduzir um novo hook experimental, useEvent, para facilitar a manipulação de eventos com melhor performance e controle.

Commit 3

Mensagem do commit: Refactor event system to reduce code duplication

Arquivos modificados:

packages/react-dom/src/events/DOMPluginEventSystem.js

Intenção do desenvolvedor: Refatorar o sistema de eventos para reduzir redundâncias e tornar o código mais limpo e manutenível.

Evolução do Projeto com os Commits:

Essa sequência mostra a progressão contínua do projeto:

Correção de bugs em hooks existentes

Adição de novos recursos experimentais

Melhoria interna da estrutura do código

Com essas etapas, o projeto React evolui para se manter eficiente, moderno e confiável.

A Importância das Mensagens de Commit
Importância: Mensagens de commit são uma forma de comunicação técnica. Boas mensagens ajudam a:

Entender o propósito de cada alteração

Realizar "git blame" e "git revert" com confiança

Colaborar com desenvolvedores em times grandes

Boas práticas incluem:

Verbo no imperativo (ex: fix, add, refactor)

Mensagens curtas no título e mais detalhes na descrição, quando necessário

Relacionar a issues ou pull requests relevantes

Exemplos:

Boas mensagens:

refactor: simplify context provider logic

fix: handle null values in reducer edge case

Mensagens fracas:

things fixed

123 (sem contexto algum)

O Conceito de Branching
Definição de branch: Uma branch é uma linha paralela de desenvolvimento que permite trabalhar em alterações sem afetar o código principal.

Finalidade: Facilitar o desenvolvimento isolado de:

Novas funcionalidades

Correções de bugs

Experimentações e testes

Como ajuda o projeto:

Branches permitem que múltiplas pessoas ou times desenvolvam em paralelo. Isso reduz conflitos e evita que código incompleto vá para produção.

Exemplo hipotético:

Em um projeto de aplicativo de receitas, uma nova funcionalidade de "modo escuro" será criada. Para isso, é criada a branch feature/dark-mode. O design, testes e ajustes são feitos nessa branch sem interferir no aplicativo em produção. Depois de pronta e testada, essa branch é mesclada (merge) na main.
