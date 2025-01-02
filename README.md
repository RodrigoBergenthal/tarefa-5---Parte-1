# Lista de Tarefas (To-Do List)

Este projeto é uma aplicação de lista de tarefas construída com React, Redux e TypeScript. A aplicação permite adicionar, remover e visualizar tarefas.

## Tecnologias Utilizadas

- **React**: Biblioteca JavaScript para construção de interfaces de usuário.
- **Redux**: Biblioteca para gerenciamento de estado.
- **TypeScript**: Superset do JavaScript que adiciona tipagem estática.
- **Styled-components**: Biblioteca para estilização de componentes.
- **React Router**: Biblioteca para roteamento em aplicações React.
- **ESLint**: Ferramenta de linting para identificar e corrigir problemas no código.
- **Prettier**: Ferramenta de formatação de código.

## Estrutura do Projeto

- **src**
  - **components**: Componentes reutilizáveis da aplicação.
  - **containers**: Componentes que estão conectados ao Redux.
  - **models**: Definições de tipos e interfaces.
  - **pages**: Páginas da aplicação.
  - **store**: Configuração do Redux e reducers.
  - **styles**: Estilos globais e componentes estilizados.
  - **utils**: Utilitários e funções auxiliares.

## Funcionalidades

- **Adicionar Tarefa**: Permite adicionar uma nova tarefa à lista.
- **Remover Tarefa**: Permite remover uma tarefa existente da lista.
- **Visualizar Tarefas**: Exibe a lista de tarefas com detalhes como título, descrição, prioridade e status.

## Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
   cd NOME_DO_REPOSITORIO

Instale as dependências:
   npm install

 Execute a aplicação:
   npm start

   A aplicação estará disponível em http://localhost:3000.

   src/
  components/
    Tarefa/
      index.tsx
      styles.ts
  containers/
    ListaDeTarefas/
      index.tsx
    BarraLateral/
      index.tsx
  models/
    Tarefa.ts
  pages/
    Home/
      index.tsx
  store/
    reducers/
      tarefas.ts
    index.ts
  styles/
    index.ts
  utils/
    enums/
      tarefa.ts

      Contribuição
Se você quiser contribuir com este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.


### Adicionar o `README.md` ao Projeto

1. Crie um arquivo chamado `README.md` na raiz do seu projeto.
2. Copie e cole o conteúdo acima no arquivo `README.md`.
3. Adicione o arquivo ao Git, faça o commit e envie para o repositório remoto:

```bash
git add README.md
git commit -m "Add README.md"
git push origin main
