# Relatório Final - Página Colaborativa de Receitas

## Integrantes do Grupo
- Nome do projeto:
- Integrantes:
   - Rui Cruz nº 2025139
   - Marcos Santos nº 2024293  
   - Emerson Baldé nº 2025160
   - Rafael Pina nº 2025014
   - Paulo Marçal nº2025487
- Repositório: https://github.com/Rafa-el-Pina/ProjectoFinal_DAS

## Branches Criadas
Para garantir o isolamento do desenvolvimento e seguir as boas práticas descritas em `CONTRIBUTING.md`, cada funcionalidade ou ajuste foi trabalhado numa branch própria:
- `feature/pao-de-queijo`: Criação e adição do ficheiro com a receita tradicional de pão de queijo mineiro.
- `feature/bolo-cenoura` / `BoloCenoura`: Criação da estrutura base e receita de bolo de cenoura.
- `feature/receita-feijoada`: Adição da receita tradicional de feijoada.
- `fix/cobertura-bolo-cenoura`: Atualização da receita existente do bolo de cenoura, adicionando os ingredientes e modo de preparo da cobertura de chocolate.
- `finished/relatorio-final`

**Realização dos Merges:**
Todos os merges para a branch principal (`main`) foram realizados obrigatoriamente através de `Pull Requests`, exigindo a revisão e aprovação de pelo menos um colaborador do grupo.

---

## Histórico de Commits
Seguimos o padrão de mensagens de commit informativas e prefixadas (ex: `feat:` e `fix:`), como foi indicado no guia de contribuição.

**Exemplos de boas mensagens de commit:**
- `feat: adicionar receita de pao de queijo mineiro`
- `feat: adicionar cobertura de chocolate na receita de bolo de cenoura`
- `fix: reordenar ficheiros de receitas para a pasta src`

**Gráfico de Contribuições:**
 O histórico completo de commits e participação individual pode ser consultado no repositório em:  
 `https://github.com/Rafa-el-Pina/ProjectoFinal_DAS/graphs/contributors`

---

## Issues Criadas
As issues foram utilizadas para gerir o trabalho e atribuir tarefas a cada membro do grupo:
- **Issue #1 - ✍️ Criar receita de pão de queijo:** Responsável: Rui Cruz (`Ezakiy`).
- **Issue #2 - Criar receita de bolo de cenoura:** Responsável: Rafael Pina (`Rafa-el-Pina`).
- **Issue #3 - Criar receita de feijoada:** Responsável: Membro do grupo encarregue da feijoada.
- **Issue #4 - Adicionar cobertura de chocolate na receita de Bolo de Cenoura:** Responsável: Rui Cruz (`Ezakiy`).

---

## Pull Requests
O fluxo de trabalho via Pull Request decorreu da seguinte forma:
1. Criação da branch temática a partir da `main`.
2. Implementação das alterações e commit local.
3. *Push* da branch para o repositório remoto no GitHub.
4. Abertura do Pull Request com a inclusão de palavras-chave na descrição (ex: `Closes #1` ou `Closes #4`) para fechar a issue associada automaticamente após o merge.
5. Atribuição de revisores (*Reviewers*) e do responsável (*Assignee*).
6. Revisão dos ficheiros por parte dos colegas através do Pull Request.
7. Realização do *Merge Pull Request* para a branch `main` e eliminação da branch secundária para não ficarf poluido.

---

## Conflitos e Resoluções
- Não Houve

---

## Dificuldades Enfrentadas
1. **Sincronização de dependências de trabalho:** Necessidade de esperar que a receita base de uma componente (ex: bolo de cenoura) fosse aceite na `main` antes de iniciar a adição da cobertura.
2. **Adoção rigorosa do fluxo do GitHub:** Garantir que nenhum elemento do grupo fazia commits diretamente na `main` sem passar por Pull Request e revisão de pares.

---

## Principais Comandos Git Utilizados

- `git clone <url>`
- `git checkout -b <nome-da-branch>`
- `git status`
- `git add .`
- `git commit -m "mensagem"`
- `git pull origin main`
- `git push -u origin <branch>`

---

## Conclusão
A realização deste projeto permitiu ao grupo fortalecer na prática os conceitos fundamentais do controlo de versões distribuído com Git e GitHub. Compreendemos a importância de um fluxo de trabalho organizado no desenvolvimento colaborativo de software. A atividade reforçou o trabalho em equipa e a comunicação contínua de forma ágil e estruturada.
