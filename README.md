# Censos

# 🗺️ Atividade Censos — Visualização Geográfica de Dados do Censo 2022

Este projeto fullstack tem como objetivo visualizar dados do Censo Demográfico 2022 de cidades do estado de São Paulo, utilizando mapas interativos para análise territorial por setor censitário. Desenvolvido com **React**, **TypeScript**, **Leaflet**, **Node.js**, **Express** e **PostgreSQL/PostGIS**.

---

## 📁 Estrutura do Projeto

```
AtividadeCensos/
├── backend/       # Servidor Node.js com Express, manipulação de dados GeoJSON e rotas de API
├── frontend/      # Aplicação React com visualização de mapa interativo e seleção de cidades
├── data/          # Arquivos GeoJSON e SQL de cidades do estado de SP
```

---

## 🚀 Funcionalidades

- Seleção de cidades com base em dados do censo (Campinas, Jacareí, Sorocaba, etc.)
- Mapa interativo com setores censitários carregados via Leaflet
- Cores e informações exibidas dinamicamente por setor
- Consumo de dados armazenados em **PostGIS**
- Sistema modular de componentes React + Context API

---

## 🧰 Tecnologias

**Frontend**
- React + Vite
- TypeScript
- React Leaflet
- Context API
- Styled Components

**Backend**
- Node.js
- Express
- TypeScript
- PostgreSQL + PostGIS
- Leitura de arquivos `.geojson` e inserção no banco via scripts

---

## 🗃️ Banco de Dados

Utiliza arquivos `.geojson` do censo e um script `comandos.sql` para importação no PostgreSQL com extensão PostGIS.

---

## ▶️ Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/AtividadeCensos.git
cd AtividadeCensos
```

### 2. Configure o backend

```bash
cd backend
npm install
# Crie um arquivo .env com as credenciais do PostgreSQL
npm run dev
```

### 3. Configure o frontend

```bash
cd ../frontend
npm install
npm run dev
```

### 4. Acesse

Abra [http://localhost:5173](http://localhost:5173) no navegador para usar o sistema.

---

## 🧠 Créditos

Atividade desenvolvida como parte da disciplina de Desenvolvimento Web II (Fatec Jacareí), com foco em integração entre frontend, backend e dados espaciais.
