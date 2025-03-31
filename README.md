# Gerenciador de Tarefas - Kanban Simplificado


Kanban é uma metodologia de gestão de projetos que usa quadros visuais para organizar o fluxo de trabalho. O objetivo é melhorar a eficiência e produtividade da equipe. 


## 📌 Contextualização
Uma indústria do ramo alimentício gerencia tarefas de seus setores utilizando o modelo Kanban de forma simplificada, semelhante a um **to-do list**. As tarefas são categorizadas nos seguintes status:
- **A fazer**
- **Fazendo**
- **Pronto**

O uso do Kanban permite compartilhar informações visualmente, aumentando a transparência e permitindo que toda a equipe do setor fique ciente das atividades em andamento. No entanto, a empresa busca **aumentar a visibilidade das tarefas e integrar informações entre todos os setores**.

## 🎯 Desafio
Desenvolver uma aplicação para gerenciamento de tarefas no formato **to-do list**, permitindo que as tarefas sejam criadas, gerenciadas e organizadas de forma eficiente.

### 🏗 Requisitos do Projeto
1. **Gerenciamento de Usuários**
   - Armazenar os seguintes dados:
     - ID do usuário
     - Nome
     - E-mail
2. **Gerenciamento de Tarefas**
   - Armazenar os seguintes dados:
     - ID da tarefa
     - ID do usuário
     - Descrição da tarefa
     - Nome do setor
     - Prioridade (**baixa, média ou alta**)
     - Data de cadastro
     - Status (**a fazer, fazendo ou pronto** - padrão: "a fazer")
   - Um usuário pode cadastrar uma ou mais tarefas, mas uma tarefa pertence a um único usuário.
   - O usuário pode gerenciar a tarefa alterando seu **status** e/ou **prioridade**.
3. **Apresentação das Tarefas**
   - Exibição das tarefas em uma tabela com **três colunas**, representando cada status (**A fazer, Fazendo, Pronto**).
4. **Regras de Validação**
   - Todos os campos de cadastro são obrigatórios.
   - Não será implementado controle de acesso (login, sessão, níveis de usuário).

## 🛠 Tecnologias Utilizadas
- Linguagens aprendidas durante o curso (exemplo: Python, JavaScript, etc.)
- Frameworks e bibliotecas conforme necessidade do projeto
- Banco de dados para armazenar as informações dos usuários e tarefas

## 🚀 Como Executar o Projeto
1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Acesse o diretório do projeto:
   ```sh
   cd nome-do-projeto
   ```
3. Instale as dependências necessárias (caso haja um arquivo `requirements.txt` ou `package.json`).
4. Execute a aplicação e aproveite!

## 📌 Contribuição
Sinta-se à vontade para contribuir com melhorias no projeto! Para isso:
1. Faça um **fork** do repositório
2. Crie uma **branch** para sua funcionalidade (`git checkout -b minha-feature`)
3. Faça o **commit** das suas alterações (`git commit -m 'Adiciona nova funcionalidade'`)
4. Faça um **push** para a branch (`git push origin minha-feature`)
5. Abra um **Pull Request**

---
📢 **Agradecemos seu interesse no projeto!** Se tiver dúvidas ou sugestões, fique à vontade para entrar em contato. 🚀

