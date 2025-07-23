<div align="center">
    <img src="src/Assets/logo_discipline.png" alt="Logo do Discipline">
</div>

# ✏️ Discipline

> Um app web para execução de provas online.

**Matéria completa:** [https://phgodoycosta.com.br/projeto/discipline](https://phgodoycosta.com.br/projeto/discipline)

![Node.js](https://img.shields.io/badge/Node.js-18+-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-4.9+-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-18.2+-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## 🎥 Funcionamento do projeto

Um vídeo demonstrando o uso e realização de uma prova com o Discipline.

<div align="center">
    <video src="src/Assets/Fazendo_prova_design_novo.mp4" controls></video>
</div>

## 📦 Instalação

Para o código funcionar corretamente, é necessário iniciar tambem o [**Discipline Server**](https://github.com/PHGodoyCosta/discipline-server) na sua maquina local.

```bash
# Clonar o repositório
git clone https://github.com/PHGodoyCosta/discipline-web
cd discipline-web

# Instalar dependências
npm install
# ou usando pnpm
pnpm install

# Configurar variáveis de ambiente
cp .env.example .env

# Iniciar o servidor
npm run start
```

## ⚙️ Configuração

Configure as seguintes variáveis no arquivo `.env`:

```env
# Adicionar a URL em que você está rodando o Discipline Server.
REACT_APP_API_URL=http://localhost:3001
```