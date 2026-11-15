# TODO — Document Review & Audit (`core-lib`)

Este documento define o plano de tarefas para a revisão exaustiva, auditoria e atualização de toda a documentação, *docstrings*, guias e referências do repositório `core-lib`.

## 1. Auditoria de Docstrings e Type Safety (`src/core_lib/`)
* [ ] **`core_lib.logger`**
  * [ ] Verificar se todas as funções e métodos possuem *type annotations* completas e rigorosas.
  * [ ] Atualizar docstrings com descrições detalhadas de parâmetros e valores de retorno.
* [ ] **`core_lib.file_utils`**
  * [ ] Documentar o comportamento de exceções e o tratamento robusto de erros na leitura/escrita de ficheiros.
* [ ] **`core_lib.gdrive`**
  * [ ] Rever a documentação dos métodos de autenticação OAuth2, verificação de pastas e sincronização de backups.
  * [ ] Adicionar notas explicativas sobre os requisitos de credenciais e permissões.
* [ ] **`core_lib.discord`**
  * [ ] Documentar a classe `DiscordNotifier` e o método `send_message`.
  * [ ] Incluir orientações claras sobre a configuração obrigatória do webhook (`CORE_LIB_DISCORD_WEBHOOK`).

## 2. Documentação do Repositório (`README.md`)
* [ ] Atualizar o README principal com o novo submódulo `core_lib.discord` e respetivos exemplos de utilização rápida.
* [ ] Garantir a consistência dos emblemas (*badges*) de qualidade (Ruff, Mypy, Pytest, Python).
* [ ] Adicionar um guia rápido de instalação e configuração para novos projetos dependentes.

## 3. Automações e CI/CD (`.github/workflows/`)
* [ ] Documentar o fluxo de funcionamento do bot de monitorização (`gdrive_bot.yml`), incluindo o papel da branch órfã `bot-state`.
* [ ] Criar secção de instruções no README sobre como testar e depurar os workflows localmente utilizando o `act`.

## 4. Validação de Qualidade
* [ ] Executar validação estática de docstrings e formatação através do Ruff.
* [ ] Garantir que o Mypy valida 100% da base de código sem erros de tipagem pendentes.