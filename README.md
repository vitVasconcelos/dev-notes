# Notes App 📝

Aplicação de **bloco de notas** desenvolvida com **HTML, CSS e JavaScript**, que permite criar, editar, fixar, duplicar, excluir, pesquisar e exportar anotações de forma simples e dinâmica.

## 🚀 Funcionalidades

* Criar novas notas
* Editar notas em tempo real
* Fixar notas importantes no topo
* Excluir notas
* Duplicar notas rapidamente
* Pesquisar notas por conteúdo
* Salvar automaticamente no navegador com **LocalStorage**
* Exportar notas em arquivo **CSV**
* Interface prática e intuitiva


## 📸 Preview

## Tela Inicial 

**Tela sem nenhuma nota cadastrada, é possível cadastrar uma nova nota digitando o conteúdo e apertando o botão de adicionar, ou a tecla Enter no teclado**

<img width="1365" height="639" alt="1" src="https://github.com/user-attachments/assets/82363484-6134-4223-9de0-1c1bc454fbfc" />

## Adicionando nota

**A nota é adionada possui o conteúdo que foi cadastrado, e botões para fixar, excluir ou copiar a nota. Para editar o conteúdo, basta clicar e adicionar o novo texto. As notas cadastradas são salvas na LocalStorage**

<img width="1359" height="645" alt="2" src="https://github.com/user-attachments/assets/c197fb0b-8176-4ebb-ba1c-f0fcb0447722" />

## Fixando uma nota

**As notas fixadas são listadas antes das notas não fixas**

<img width="1363" height="641" alt="3-2" src="https://github.com/user-attachments/assets/64f5dabd-723b-4389-9f19-22e2d3b73c04" />

## Pesquisando nota

**A funcionalidade de pesquisa de nota exibe as notas que possuem o conteúdo digitado, independentemente se ele foi digitado com letras maiúsculas ou minúsculas**

<img width="1363" height="639" alt="4" src="https://github.com/user-attachments/assets/590cb59a-3387-434f-8851-95048f1e402d" />

## Botão para exportação de arquivo CSV

**O botão de exportar para CSV converte o conteúdo salvo na LocalStorage em um arquivo CSV**

<img width="1365" height="637" alt="5" src="https://github.com/user-attachments/assets/66d111df-918e-4e48-a9b0-f6463766cfc8" />

## Responsividade

**O projeto foi adaptado para telas menores**

<img width="309" height="555" alt="6" src="https://github.com/user-attachments/assets/cd8da48a-f33b-4b63-89a1-9bf255e44962" />






## 🛠️ Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript
* LocalStorage API
* Bootstrap Icons

## 📚 Conceitos Aplicados

Neste projeto foram praticados diversos conceitos essenciais de JavaScript:

* Manipulação do DOM
* Criação dinâmica de elementos
* Eventos (`click`, `keyup`, `keydown`)
* Arrays (`map`, `filter`, `sort`)
* Objetos
* Funções reutilizáveis
* LocalStorage
* Exportação de dados em CSV
* Atualização em tempo real
* Organização de código

## 📂 Estrutura do Projeto

```bash id="yloc5h"
📁 notes-app
 ┣ 📄 index.html
 ┣ 📄 style.css
 ┗ 📄 script.js
```

## ▶️ Como Executar

1. Clone este repositório:

```bash id="0syk9l"
git clone https://github.com/seu-usuario/notes-app.git
```

2. Acesse a pasta do projeto:

```bash id="5b7lfd"
cd notes-app
```

3. Abra o arquivo `index.html` no navegador.

## 💡 Como Usar

### ➕ Adicionar Nota

Digite o conteúdo no campo principal e pressione **Enter** ou clique no botão de adicionar.

### ✏️ Editar Nota

Clique dentro da nota e altere o texto normalmente.

### 📌 Fixar Nota

Clique no ícone de alfinete para manter a nota no topo.

### 📄 Duplicar Nota

Clique no ícone de duplicar para criar uma cópia da nota.

### ❌ Excluir Nota

Clique no ícone de fechar para remover a nota.

### 🔍 Pesquisar

Use o campo de busca para encontrar notas pelo conteúdo.

### 📤 Exportar

Clique no botão de exportação para baixar suas notas em formato `.csv`.

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido para praticar lógica de programação, manipulação de dados, armazenamento local e criação de interfaces interativas com JavaScript puro.

## 📌 Melhorias Futuras

* Tema Dark/Light
* Categorias de notas
* Drag and Drop
* Sincronização em nuvem
* Alterar cores das notas
* Backup em JSON
* Ordenação personalizada
