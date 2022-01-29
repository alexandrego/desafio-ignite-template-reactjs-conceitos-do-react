# Passos para execução do desafio.
Você deve criar as funcionalidades para as três funções presentes nesse arquivo, que são:</br>

- **handleCreateNewTask**: Deve ser possível adicionar uma nova task no estado de `tasks`, com os campos `id` que deve ser gerado de forma aleatória, `title` que deve ser um texto e `isComplete` que deve iniciar como false.</br>
- **handleToggleTaskCompletion:** Deve alterar o status de `isComplete` para uma task com um ID específico que é recebido por parâmetro.</br>
- **handleRemoveTask:** Deve receber um ID por parâmetro e remover a task que contém esse ID do estado.</br></br>
  
1. Começamos rodando o ```sudo yarn``` para instalar as dependências do projeto.</br>
2. Vamos instalar a seguinte biblioteca para podermos gerar novos "Id's" a cada chamada da função.</br>
   ```sudo npm i uuidv4```</br>
3. Apliquei um degradê ao fundo com cor azul.</br>
4. Troquei o titulo "Minhas tasks" por "Minhas tarefas".</br>
5. Havia trocado o placeholder "Adicionar novo todo" para "Adicionar nova tarefa", só que ao rodar os testes dava erro, então voltei ao estado original.</br>
6. Ao digitar a tarefa no input e apertar "Enter" percebi que nada acontencia, então adicionei a funcionalidade de também adicionar tarefa ao apertar o "Enter".</br>