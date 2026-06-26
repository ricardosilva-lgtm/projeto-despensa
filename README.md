# Gerenciador de Despensa Doméstica

Sistema desenvolvido em **Pascal** para auxiliar no gerenciamento da despensa doméstica, permitindo o controle de estoque e da lista de compras por meio de uma aplicação em linha de comando (CLI).

O projeto foi desenvolvido em equipe como atividade acadêmica do curso de **Análise e Desenvolvimento de Sistemas**, com foco na aplicação de conceitos fundamentais de programação e estruturas de dados.

---

# Objetivo

Criar uma solução simples para auxiliar famílias na organização da despensa, permitindo o cadastro, controle e atualização de produtos, além do gerenciamento automático da lista de compras.

---

# Funcionalidades

- Cadastro de produtos
- Controle de estoque
- Gerenciamento da lista de compras
- Alteração de nome e categoria dos produtos
- Atualização da quantidade em estoque
- Exclusão de produtos
- Busca de produtos por ID
- Geração automática de IDs únicos
- Transferência automática de produtos entre estoque e lista de compras conforme a quantidade disponível
- Interface baseada em menus interativos

---

# Tecnologias Utilizadas

- Pascal

---

# Conceitos Aplicados

- Lógica de Programação
- Estruturas de Dados
- Vetores (Arrays)
- Registros (Records)
- Functions
- Procedures
- Modularização
- CRUD
- Busca Linear
- Manipulação de vetores
- Organização de menus

---

# Funcionamento do Sistema

Quando um produto é cadastrado:

- Quantidade maior que zero → Produto é enviado para o estoque.
- Quantidade igual a zero → Produto é enviado automaticamente para a lista de compras.

Durante a atualização:

- Caso a quantidade do produto seja reduzida para zero, ele é removido do estoque e adicionado automaticamente à lista de compras.
- Quando um produto da lista de compras é adquirido, ele retorna ao estoque com a quantidade informada pelo usuário.

Esse fluxo automatiza o gerenciamento dos produtos e reduz a necessidade de movimentações manuais.

---

# Principais Características

- Sistema totalmente desenvolvido em Pascal.
- Organização do código em funções e procedimentos.
- Utilização de IDs únicos para identificação dos produtos.
- Controle automático entre estoque e lista de compras.
- Estrutura baseada em registros e vetores.
- Interface em linha de comando (CLI).

---

# Demonstração

*Em breve serão adicionadas capturas de tela da aplicação em funcionamento.*

---

# Como executar

1. Abra o projeto em um compilador Pascal compatível.
2. Compile o arquivo principal.
3. Execute o programa.
4. Utilize o menu para acessar as funcionalidades disponíveis.

---

# Desenvolvimento

Projeto desenvolvido em equipe como atividade acadêmica e durante o planejamento da aplicação, a equipe utilizou um quadro colaborativo (Whiteboard) para organizar a lógica do sistema, discutir as funcionalidades e estruturar os módulos antes da consolidação do código em Pascal.

---

# Status

Concluído

**Versão:** v1.0.0

---

# Licença

Projeto desenvolvido exclusivamente para fins acadêmicos.
