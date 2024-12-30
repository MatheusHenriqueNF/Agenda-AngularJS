# 📒 **Agenda de Contatos**  

Aplicação desenvolvida em **Angular** para gerenciar e exibir uma lista de contatos a partir de um arquivo JSON. A aplicação apresenta os nomes e números de telefone de forma dinâmica, permitindo uma interface simples e intuitiva.  

---

## 📖 **Sobre o Projeto**  

A **Agenda de Contatos** é um projeto que demonstra o uso de **Angular** para consumir dados de um arquivo JSON e renderizar informações em tela. Ele foi criado com o objetivo de praticar conceitos como:  
- Estrutura de um projeto Angular.  
- Consumo de dados estáticos em JSON.  
- Interpolação de dados e uso de diretivas Angular para renderização de listas.  
- Organização de componentes e estilos.  

---

## 🛠️ **Tecnologias Utilizadas**  

- **Angular**: Framework principal para o desenvolvimento da aplicação.  
- **TypeScript**: Linguagem utilizada para desenvolvimento no Angular.  
- **HTML** e **CSS**: Para a estrutura e estilização da aplicação.  
- **JSON**: Arquivo de dados estáticos que simula uma API.  

---

## 📂 **Estrutura do Projeto**  

- **/src/app**: Contém os componentes principais da aplicação.  
  - **contact-list**: Componente que exibe a lista de contatos.  
  - **services**: Serviço Angular responsável por consumir o arquivo JSON.  
- **/assets/data/contacts.json**: Arquivo contendo a lista de contatos no formato JSON.  

Exemplo do arquivo `contacts.json`:  
```json
[
  { "name": "João Silva", "phone": "(11) 99999-9999" },
  { "name": "Maria Oliveira", "phone": "(21) 88888-8888" },
  { "name": "Carlos Pereira", "phone": "(31) 77777-7777" }
]

