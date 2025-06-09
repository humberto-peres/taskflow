# 📘 Casos de Uso

## 🎭 Atores

1. **Usuário**: Pessoa logada no sistema, responsável por interações diretas.
2. **Sistema**: Executa automaticamente validações e regras de negócio (implícito nos casos estendidos).

---

## ✅ Casos de Uso

### 1. Criar conta
- **Ator Principal**: Usuário  
- **Descrição**: Permite que o usuário registre uma nova conta no sistema.

---

### 2. Realizar login
- **Ator Principal**: Usuário  
- **Descrição**: Permite que o usuário acesse sua conta existente.

---

### 3. Editar informações pessoais
- **Ator Principal**: Usuário  
- **Descrição**: Permite que o usuário atualize seus dados pessoais, como nome, e-mail e senha.

---

### 4. Criar, editar e excluir tarefas
- **Ator Principal**: Usuário  
- **Descrição**: Permite o gerenciamento completo das tarefas.  
- **Estende**: `Definir responsáveis e prazos`

---

### 5. Definir responsáveis e prazos
- **Ator Principal**: Sistema  
- **Descrição**: Funcionalidade adicional ativada durante a criação ou edição de tarefas, permitindo definir responsáveis e prazos.

---

### 6. Criar quadros de tarefas
- **Ator Principal**: Usuário  
- **Descrição**: Permite a criação de quadros de tarefas para organização visual (ex: Kanban ou Scrum).

---

### 7. Gerenciar sprints
- **Ator Principal**: Usuário  
- **Descrição**: Permite o gerenciamento de sprints vinculados aos quadros Scrum.

---

### 8. Acessar workspace
- **Ator Principal**: Usuário  
- **Descrição**: Permite que o usuário acesse ambientes de trabalho (workspaces) dos quais faz parte.  
- **Estende**: `Visualizar dados da atividade`

---

### 9. Visualizar dados da atividade
- **Ator Principal**: Usuário  
- **Descrição**: Permite a visualização de informações detalhadas das tarefas ou atividades em andamento.

---

## 📈 Diagrama UML

![Diagrama de Casos de Uso](assets/use-case/uml.png)
