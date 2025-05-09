# Desafio Técnico – Desenvolvedor(a) Mobile React Native (Pleno)


Seja bem-vindo(a) ao nosso desafio técnico!  

Nosso objetivo com este desafio é avaliar suas habilidades práticas em desenvolvimento mobile com **React Native**, boas práticas de desenvolvimento, gerenciamento de estados, integração com APIs, componentização, navegação, experiência do usuário e uso de bibliotecas modernas.


## 📌 Contexto

A Prefeitura do Rio de Janeiro deseja lançar um **Aplicativo de Qualidade do Ar**, com o objetivo de que qualquer pessoa possa visualizar dados atualizados sobre a qualidade do ar em diferentes bairros da cidade. A ideia é permitir que os moradores consultem as medições mais recentes, entendam a situação em sua região e possam planejar suas atividades ao ar livre com mais segurança.

Seu desafio é criar um aplicativo mobile funcional, com boa usabilidade e adaptada para iOS e Android, com UI consistente entre plataformas e capaz de consumir e exibir dados fictícios da qualidade do ar em cada bairro.


## ✨ Requisitos Funcionais do Desafio

### 🔹Tela Inicial
- Exibir um **mapa interativo** com os bairros do Rio de Janeiro.
- Adicione uma busca por bairro no mapa. Ao selecionar o bairro de interesse, transicionar com zoom e "fly to" até este bairro. Além disso, ainda na tela inicial, mostre um resumo das informações relativas a este bairro. Adicione um botão para a **Tela de Detalhes do Bairro**. **Seja criativo(a)!**

### 🔹Tela de tabela ou lista com as medições recentes de qualidade do ar.
- Exibir uma lista ou tabela responsiva com as medições mais recentes da qualidade do ar em diferentes bairros do Rio de Janeiro.
- Cada item da lista deve conter:
    - Nome do bairro;
    - Data e hora da medição;
    - Classificação da qualidade (`bom`, `moderado`, `ruim`, `péssimo`);
    - Indicador visual (ex: cor, ícone ou tag) para facilitar a identificação rápida do nível de qualidade.
- Permitir ordenar ou filtrar a lista por data ou nível de qualidade do ar.
    - Ao tocar em um item da lista, navegar para a **Tela de Detalhes do Bairro** correspondente.
    - A tabela deve conter paginação.

### 🔹Tela de Detalhes do Bairro
- Exibir **dados detalhados** e **gráficos de variação** da qualidade do ar no bairro selecionado.
- Implementar **pull-to-refresh** para atualizar os dados manualmente.

### 🔹Navegação
- O usuário deve ser capaz de navegar intuitivamente entre as telas.


## 🛠️ Requisitos Técnicos

### Obrigatórios
- Projeto desenvolvido com **React Native** (Expo ou CLI, fica a sua escolha).
- Uso de Typescript.
- Compatível com **Android e iOS**.
- Uso de **Redux**, **Zustand** ou afins para gerenciamento de estado.
- Utilizar **React Hook Form** para formular interações, filtros ou inputs.
- **Zod** para validação de schemas de dados da API / formulários.
- Consumo de API REST mockada para obter os dados.
- Simular **notificações push** para alertas de mudança brusca na qualidade do ar.
- Boa organização do código e boas práticas de desenvolvimento.
- Uso de **Git + GitHub** para versionamento.
- README explicativo com:
  - Como rodar o projeto;
  - Quais bibliotecas foram usadas e por quê;
  - Quais decisões arquiteturais foram tomadas.

### Desejáveis / Diferenciais
- Suporte a **modo escuro** e **modo claro**.
- Utilização de bibliotecas modernas de UI como **Gluestack**, **UI Kitten** ou similares.
- Animações e transições com **Reanimated** ou similares.
- Implementação de **testes automatizados** (unitários com Jest ou de integração com Testing Library).
- Criação de um **APK/IPA de demonstração** para facilitar testes.


## 🏗️ Como Submeter o Desafio
1. Faça um fork ou clone este repositório.
2. Implemente a solução seguindo os requisitos descritos.
3. Inclua um pequeno documento (ou atualize este README) explicando suas decisões técnicas, estrutura do código e instruções para rodar o projeto.
4. Envie o link do repositório para nós!

## 📖 O que será avaliado?

- Código bem estruturado e reutilizável.
- Boas práticas de UI/UX.
- Organização e clareza na implementação.
- Corretude do código.
- Documentação clara do projeto.

## ❓ Dúvidas?

Se tiver qualquer dúvida, fique à vontade para perguntar!

Boa sorte! 🚀
