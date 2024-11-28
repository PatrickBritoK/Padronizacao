# Padronização de commits

### git commit -m "[Número do card/ticket]tipo de alteração: descrição curta"

Exemplo: git commit -m "[874]feat: creating a new login screen"

## Tipos de Alteração

### `test`
- **Descrição:** Indica qualquer tipo de criação ou alteração de códigos de teste.
- **Exemplo:** Criação de testes unitários.

### `feat`
- **Descrição:** Indica o desenvolvimento de uma nova feature ao projeto.
- **Exemplo:** Acréscimo de um serviço, funcionalidade, endpoint, etc.

### `refactor`
- **Descrição:** Usado quando houver uma refatoração de código que não tenha qualquer tipo de impacto na lógica/regras de negócio do sistema.
- **Exemplo:** Mudanças de código após um code review.

### `style`
- **Descrição:** Empregado quando há mudanças de formatação e estilo do código que não alteram o sistema de nenhuma forma.
- **Exemplo:** Mudar o style-guide, mudar de convenção lint, arrumar indentações, remover espaços em brancos, remover comentários, etc.

### `fix`
- **Descrição:** Utilizado quando há correção de erros que estão gerando bugs no sistema.
- **Exemplo:** Aplicar tratativa para uma função que não está tendo o comportamento esperado e retornando erro.

### `chore`
- **Descrição:** Indica mudanças no projeto que não afetem o sistema ou arquivos de testes. São mudanças de desenvolvimento.
- **Exemplo:** Mudar regras do eslint, adicionar prettier, adicionar mais extensões de arquivos ao .gitignore.

### `docs`
- **Descrição:** Usado quando há mudanças na documentação do projeto.
- **Exemplo:** Adicionar informações na documentação da API, mudar o README, etc.

### `build`
- **Descrição:** Utilizada para indicar mudanças que afetam o processo de build do projeto ou dependências externas.
- **Exemplo:** Gulp, adicionar/remover dependências do npm, etc.

### `perf`
- **Descrição:** Indica uma alteração que melhorou a performance do sistema.
- **Exemplo:** Alterar ForEach por while, melhorar a query ao banco, etc.

### `ci`
- **Descrição:** Utilizada para mudanças nos arquivos de configuração de CI.
- **Exemplo:** Circle, Travis, BrowserStack, etc.

### `revert`
- **Descrição:** Indica a reverão de um commit anterior.
- **Exemplo:** Reverter um commit devido a um erro identificado.

---
