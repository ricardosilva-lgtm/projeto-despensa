# Gerenciador de Despensa Doméstica

Sistema desenvolvido em **Pascal** para auxiliar no gerenciamento da despensa doméstica, permitindo o controle de estoque e da lista de compras por meio de uma aplicação em linha de comando (CLI).

O projeto foi desenvolvido em equipe como atividade acadêmica do curso de **Análise e Desenvolvimento de Sistemas**, com foco na aplicação de conceitos fundamentais de programação e estruturas de dados.

---

# Objetivo

Desenvolver uma solução simples para gerenciamento de produtos domésticos, permitindo:

- Cadastro de produtos
- Controle de estoque
- Gerenciamento de lista de compras
- Atualização automática de quantidades
- Organização e busca de itens

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

# Regras de Negócio

- Se a quantidade do produto for maior que zero, ele permanece no estoque
  
- Se a quantidade for igual a zero, o produto é movido automaticamente para a lista de compras

- Alterações na quantidade podem realocar automaticamente o produto entre as listas

- Produtos são identificados por ID único

---

# Arquitetura do Sistema

## Escopo do sistema
- Foco em funcionalidades essenciais (MVP)
- Exclusão de recursos complexos como login ou banco de dados

## Requisitos analisados
- Requisitos funcionais (RF)
- Regras de negócio (RN)
- Validação de entradas (RV)

---

# Implementação 

## Linguagem: Pascal

## Estruturas de Dados:
- Vetores (arrays)
- Records (modelagem de produtos)

## Lógica de Programação:
- Modularização com procedures e functions
- Passagem de parâmetros
- Busca linear
- Manipulação e reorganização de vetores
- Controle de loops estruturados

---

# Arquitetura de Código 

- Separação lógica por funções e procedimentos
- Menu principal baseado em repetição (loop)

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

# Estratégia de Desenvolvimento

Devido à limitação de edição simultânea em Pascal, a equipe utilizou um quadro colaborativo (whiteboard) para:

- Planejamento da arquitetura do sistema
- Definição dos módulos
- Organização do fluxo de dados
- Alinhamento das funcionalidades antes da implementação

Isso reduziu conflitos de código e melhorou a clareza do desenvolvimento em equipe.

---

# Fluxo do Sistema

O sistema inicia e exibe o menu principal

O usuário escolhe uma opção:
- Cadastrar produto
- Listar estoque
- Listar lista de compras
- Buscar produto
- Atualizar ou remover produto

O sistema executa a ação correspondente

O menu é exibido novamente até a opção de saída

---

# Demonstração
## Menu Principal

<img width="422" height="154" alt="pascal 1" src="https://github.com/user-attachments/assets/533ba3d5-4eaa-400a-95bb-4236530566e4" />

---

## Cadastro de Produtos

<img width="418" height="254" alt="pascal 2" src="https://github.com/user-attachments/assets/27ed78ca-c7fd-45cd-9c4c-2ede9924284e" />

---

## Estoque

<img width="379" height="292" alt="pascal 3" src="https://github.com/user-attachments/assets/b919e30a-b0e5-4318-ba8f-5bc7cde89e1c" />

---

## Lista de Compras

<img width="425" height="299" alt="pascal 4" src="https://github.com/user-attachments/assets/67bea3d7-6f8e-4493-a510-b5fc5573fe42" />

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
