# Sistema de Processamento de Imagens Grayscale

Aplicação web desenvolvida em **React** para processamento digital de imagens em **escala de cinza**, implementando diversas técnicas clássicas da disciplina de **Processamento de Imagens**. O sistema permite carregar uma imagem, aplicar operações em tempo real e baixar o resultado processado.

Projeto acadêmico — **UNIR | Processamento de Imagens — 2025**.

---

## 📸 Funcionalidades

* Upload de imagens diretamente do navegador
* Conversão automática para **grayscale**
* Processamento **client-side** usando **Canvas API**
* Visualização da imagem original e processada
* Ajuste interativo de parâmetros
* Download da imagem resultante

---

## 🧠 Operações Implementadas

### 🔹 Transformações de Intensidade

* Negativo
* Limiarização
* Transformação de Potência (Gamma)
* Transformação Logarítmica
* Alargamento de Contraste

### 🔹 Histograma

* Expansão de Histograma
* Equalização de Histograma
* Contraste Adaptativo

### 🔹 Transformações Geométricas

* Mudança de Escala (Interpolação Bilinear)
* Rotação
* Cisalhamento
* Rebatimento Horizontal e Vertical

### 🔹 Filtragem

* Filtro da Média
* Filtro da Mediana
* Gradiente de Sobel
* Aguçamento de Bordas
* High Boost

### 🔹 Filtros Especiais

* Filtro de Aguçamento parametrizado (c, d)
* Filtro de Relevo
* Filtro de Detecção de Bordas

---

## 🛠️ Tecnologias Utilizadas

* **React** (Hooks)
* **JavaScript (ES6+)**
* **HTML5 Canvas API**
* **Tailwind CSS**
* **Lucide Icons**

Todo o processamento é feito no navegador, sem dependência de backend.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

* Node.js (v18 ou superior recomendado)
* npm ou yarn

### Passos

```bash
# Clone o repositório
git clone git@github.com:sandycampos/ProjetoGrayscale.git

# Acesse a pasta do projeto
cd ProjetoGrayscale

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev
```

Abra o navegador em:

```
http://localhost:5173
```

*(ou a porta indicada no terminal)*

---

## 📚 Contexto Acadêmico

Este projeto foi desenvolvido com fins **didáticos**, visando a aplicação prática dos conceitos de:

* Processamento Digital de Imagens
* Convolução e Filtragem
* Transformações Geométricas
* Realce e Detecção de Bordas
