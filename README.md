![Spotify Logo](https://upload.wikimedia.org/wikipedia/commons/1/19/Spotify_logo_without_text.svg)

# Spotify Imersão

O **Spotify Imersão** é uma aplicação web desenvolvida em HTML e CSS durante a Imersão Alura. Permite criar e gerenciar playlists, descobrir novos artistas e acompanhar tendências musicais, tudo com uma interface amigável.

## 📋 Funcionalidades

- **Criar e Gerenciar Playlists:** Adicione e organize suas playlists favoritas.
- **Descobrir Novos Artistas:** Explore novos artistas e músicas.
- **Acompanhar Tendências Musicais:** Veja as músicas mais populares do momento.

## 🛠️ Tecnologias Utilizadas

- **HTML** 
- **CSS**
- **JavaScript**

## ⚙️ Como Executar o Projeto

### Pré-requisitos

Certifique-se de ter o Visual Studio Code e o Node.js instalados. Além disso, será necessário configurar um servidor local utilizando o json-server para levantar as imagens dos artistas que estão em JavaScript.

### 1. **Clone o repositório:**

```bash
git clone https://github.com/pplace11/Spotify-Imersao.git
cd Spotify-Imersao
```

### 2. **Instale a extensão Live Server no Visual Studio Code:**

- Abra o Visual Studio Code.
- Vá até a aba de extensões (ícone de quadrado no lado esquerdo ou use o atalho Ctrl+Shift+X).
- Procure por "Live Server" e clique em "Install" na extensão desenvolvida por Ritwick Dey.

### 3. **Instale as dependências do Node.js:**
```bash
npm install
```

### 4. **Configure e inicie o json-server:**
```bash
npm install -g json-server
```

### 5. **Inicie o json-server:**
```bash
json-server --watch api-artists/artist.json --port 3000
```

## 🗂️ Estrutura do Projeto

```plaintext
📁 Spotify-Imersao/
├── 📂 src/         # Scripts JavaScript e lógica da aplicação
│   ├──📂 assets/         # Recursos estáticos como CSS, JS e imagens
│   ├──📂 styles/         # Contém arquivos CSS que definem os estilos da aplicação
│   │   ├── 📄 sidebar-footer.css      # Estilos da aplicação
│   │   ├── 📄 reset.css               # Reset de estilos para consistência entre navegadores
│   │   ├── 📄 main-content.css        # Define os estilos para a área de conteúdo principal da aplicação
│   │   ├── 📄 vars.css                # Define variáveis de CSS para fontes e cores
│   │   ├── 📄 media-queries.css       # Define estilos responsivos para diferentes tamanhos de tela
├── 📂 api-artists/  # Contém os dados dos artistas
│   ├── 📄 artist.json      # Arquivo JSON com os dados dos artistas
├── 📄 script.js     # Script JavaScript para manipulação dos dados dos artistas
├── 📄 index.html    # Página principal da aplicação
└── 📄 README.md     # Documentação do projeto
```

## 📸 Preview

Aqui está uma visão geral da interface da aplicação:

![Sptify Imersao Preview](src/assets/web/principal.png)
![Sptify Imersao Preview](src/assets/web/segundo.png)