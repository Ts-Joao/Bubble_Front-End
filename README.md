# 🫧 BUBBLE

O Bubble é uma rede social onde você pode se conectar a várias comunidade(bolhas), como o proprio nome já diz uma vez dentro de uma bolha seu feed será somente sobre coisas relacionadas a bolha. Com o foco em Deixar o usuário mais confortavél em suas experiências no Bubble, porém ainda existindo a opção de ter acesso ao feed tradicional com diversas postagens de diversos temas e tópicos. <br><br> Escolhemos criar esta rede social após analizarmos uma breve pesquisa e termos notado que não havia ainda essa funcionalidade nas gigantes plataformas de comunicação via web. Com isso em mente, criamos o Bubble.

## 🛠️ Tech Stack

| Tecnologia | Função no Projeto |
|------------|-------------------|
| <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=38B2AC&labelColor=0D1117&color=0D1117" /> | Estilização dos componentes e criação de layout responsivo |
| <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=61DAFB&labelColor=0D1117&color=0D1117" /> | Construção da interface com componentes reutilizáveis |
| <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=646CFF&labelColor=0D1117&color=0D1117" /> | Ambiente de desenvolvimento rápido e build otimizada |
| <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=F7DF1E&labelColor=0D1117&color=0D1117" /> | Implementação da lógica da aplicação e interações dinâmicas |

## 📦 Depedências Principais
```bash
{
    "dependencies": {
        "@ionic/react": "^8.7.5",
        "@tailwindcss/vite": "^4.1.13",
        "axios": "^1.13.2",
        "ionicons": "^8.0.13",
        "react": "^19.1.1",
        "react-dom": "^19.1.1",
        "react-icons": "^5.5.0",
        "react-router-dom": "^7.9.1",
        "tailwindcss": "^4.1.13"
    }
}
```
## 🛠️ Instalação

```bash
# Na raiz do projeto
npm install
```

## 🏃 Executando

```bash
# Da raiz do projeto
npm run dev
```

## 🔐 Variáveis de Ambiente
Crie um arquivo .env na raiz do projeto:

```env
VITE_API_URL=http://localhost:4000
```

## ⚒️ Features do Site:

- Feed exclusivo das bolhas onde você está vinculado contendo apenas conteúdo da bolha em si, evitando de encontrar algo que possa atrapalhar a experiência do usuário.

- Mêcanica de visualização de movimentação na bolha, caso a bolha começe a ter um grande número de atividade, usuários que estão inserido nelas recebram notificação informando sobre a atividade da bolha, caso ela pare de ter um grande número de atividade o usuário receberam uma notificação informando que a bolha teve a sua atividade reduzida.

- Chat exclusivo, onde você pode enviar mensagens ao seus colegas e amigos.


## 👨‍💻 Colaboradores

- [João Teixeira](https://github.com/ts-joao)
- [Henri Baruki](https://github.com/Baruki-Bytes)
- [Lucas Alves](https://github.com/ktzxs)
- [Felipe Farias](https://github.com/felipinho3105)
- Matheus Barros
