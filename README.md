# 📋 Lista de Tarefas com Prioridade

Projeto de uma aplicação web interativa de **To-Do List** desenvolvida utilizando **HTML5, CSS3 e JavaScript puro**, com foco em usabilidade, design responsivo e persistência de dados no navegador.

---

## 🚀 Demonstração

🔗 Em breve (adicione aqui o link do GitHub Pages, se publicar)

---

## 🎯 Objetivo

Desenvolver uma aplicação web funcional que permita ao usuário gerenciar tarefas de forma simples e eficiente, implementando conceitos fundamentais de desenvolvimento front-end sem o uso de frameworks.

---

## ✅ Funcionalidades

- ➕ Adicionar novas tarefas com descrição
- 🔥 Definir prioridade (Alta, Média, Baixa)
- ✔️ Marcar tarefas como concluídas (com efeito visual)
- 🗑️ Excluir tarefas individualmente
- 💾 Persistência de dados com `localStorage`
- 📱 Design responsivo (mobile e desktop)
- 📊 Contador de tarefas
- 💤 Estado vazio amigável
- ⚡ Feedback visual ao adicionar tarefas

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** → Estrutura da aplicação  
- **CSS3** → Estilização e responsividade  
- **JavaScript (Vanilla)** → Lógica e interatividade  
- **Google Fonts (Inter)** → Tipografia  

> ❌ Nenhum framework ou biblioteca externa foi utilizado

---

## 📂 Estrutura do Projeto

```

📁 projeto-todo-list
│
├── index.html
├── style.css
├── script.js
└── README.md

````

---

## 🧠 Como Funciona

1. O usuário digita uma tarefa e seleciona a prioridade  
2. A tarefa é adicionada à lista  
3. Os dados são salvos no navegador (`localStorage`)  
4. A interface é atualizada automaticamente  
5. O usuário pode concluir ou excluir tarefas a qualquer momento  

---

## 💻 Principais Trechos de Código

### ➕ Adicionar tarefa
```javascript
tasks.unshift({
    id: Date.now(),
    text: text,
    priority: prioritySelect.value,
    done: false
});
````

### ✔️ Marcar como concluída

```javascript
tasks[index].done = !tasks[index].done;
```

### 💾 Persistência de dados

```javascript
localStorage.setItem('collegeTodoTasks', JSON.stringify(tasks));
```

---

## ⚠️ Desafios Enfrentados

* Manipulação dinâmica do DOM
* Atualização da interface (re-renderização)
* Controle de índices após exclusão
* Responsividade para diferentes dispositivos
* Feedback visual ao usuário

---

## 📚 Aprendizados

* Manipulação de eventos em JavaScript
* Uso prático de `localStorage`
* Organização e estruturação de código
* Importância da UX/UI
* Boas práticas de validação

---

## 🔮 Melhorias Futuras

* 📅 Adicionar data de criação das tarefas
* 📊 Ordenação automática por prioridade
* 🧹 Limpar tarefas concluídas
* 🌙 Modo escuro

---

## 👨‍🎓 Autor

**João Bugary Teles Sobrinho**

* Projeto acadêmico – Desenvolvimento Web
* Abril de 2026

---

## 📄 Licença

Este projeto é apenas para fins educacionais.

```

---

Se quiser, posso também:
- deixar com **badges do GitHub (deploy, linguagem, etc.)**
- adicionar **GIF demonstrando o app**
- ou adaptar para um nível mais profissional (portfólio)
```
