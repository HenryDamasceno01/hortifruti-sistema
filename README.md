# Sistema de Hortifruti 🍎🥦

Este projeto tem como objetivo desenvolver um sistema para gestão de um hortifrúti,
permitindo controle de estoque, vendas, clientes e relatórios de faturamento.

## 📌 Backlog do Produto

| Épico | História de Usuário                                                                 | Status |
|-------|-------------------------------------------------------------------------------------|--------|
| Gestão de Produtos e Estoque | Como administrador, quero cadastrar produtos com nome, categoria, preço e validade. | ⬜ A Fazer |
| Gestão de Produtos e Estoque | Como administrador, quero editar e excluir produtos.         | ⬜ A Fazer |
| Gestão de Produtos e Estoque | Como administrador, quero registrar entrada e saída de produtos. | ⬜ A Fazer |
| Gestão de Produtos e Estoque | Como administrador, quero receber alertas de produtos próximos ao vencimento. | ⬜ A Fazer |
| Vendas e Caixa | Como atendente, quero registrar vendas rapidamente.                        | ⬜ A Fazer |
| Vendas e Caixa | Como atendente, quero emitir nota ou cupom para o cliente.                | ⬜ A Fazer |
| Vendas e Caixa | Como administrador, quero gerar relatórios diários de vendas.             | ⬜ A Fazer |
| Gestão de Clientes | Como atendente, quero cadastrar clientes para promoções.              | ⬜ A Fazer |
| Gestão de Clientes | Como administrador, quero acompanhar os clientes mais frequentes.      | ⬜ A Fazer |
| Relatórios e Administração | Como administrador, quero ver relatório mensal de faturamento. | ⬜ A Fazer |
| Relatórios e Administração | Como administrador, quero acompanhar quantidade de clientes por dia. | ⬜ A Fazer |
| Segurança e Acesso | Como administrador, quero controlar permissões de acesso dos usuários. | ⬜ A Fazer |

## 📅 Planejamento de Sprints

| Sprint | Duração   | Foco Principal                                | Entregas Planejadas |
|--------|-----------|-----------------------------------------------|----------------------|
| Sprint 1 | 3 semanas | Configuração inicial + Produtos              | Estrutura do projeto, cadastro/edição de produtos, registro de estoque |
| Sprint 2 | 1 semana | Vendas e relatórios básicos                  | Registro de vendas, emissão de cupom, relatório diário |
| Sprint 3 | 5 dias | Clientes e relatórios avançados              | Cadastro de clientes, relatório de clientes frequentes, relatório mensal |
| Sprint 4 | 4 semanas | Segurança e finalização                      | Permissões de usuários, alertas de validade, testes e ajustes finais |


## 🚀 Funcionalidades
- Cadastro de produtos
- Controle de estoque
- Registro de vendas e emissão de comprovantes
- Relatórios de faturamento e clientes
- Gestão de usuários com permissões

## 📂 Estrutura do Projeto
- `src/` → Código-fonte da aplicação
- `docs/` → Diagramas, backlog e documentação
- `tests/` → Testes automatizados
- `.gitignore` → Arquivos ignorados pelo Git

## 🛠️ Tecnologias utilizadas
- Linguagem C
- Git e GitHub para versionamento
- Markdown para documentação

## 📌 Estratégia de Branch
- `main` → versão estável
- `feature/*` → novas funcionalidades
- `bugfix/*` → correções de bugs
- `hotfix/*` → correções urgentes

## 📖 Padrão de commits
Usarei o [Conventional Commits](https://www.conventionalcommits.org/):

- `feat`: nova funcionalidade
- `fix`: correção de bug
- `docs`: mudanças na documentação
- `style`: formatação de código (sem impacto lógico)
- `refactor`: refatoração de código
- `test`: inclusão/modificação de testes
- `chore`: tarefas menores

**Exemplo:**  
```
feat (API-101): implementação do cadastro de produtos
fix (API-202): correção no cálculo do estoque
docs: inclusão de diagrama de caso de uso
```

## ✅ Boas práticas
- Nunca realizar commits direto na `main`
- Fazer pequenos commits com mensagens claras
- Revisar Pull Requests antes do merge
- Utilizar `.gitignore` para logs, binários e senhas
