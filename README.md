# 🎧 Spotify Clone - Interface Web


Este projeto é um **clone da interface do Spotify**, desenvolvido exclusivamente como **atividade acadêmica**, sem qualquer finalidade comercial.

A interface implementa funcionalidades visuais semelhantes às do Spotify, incluindo:

- Um menu lateral esquerdo (**aside**) que pode ser **compactado ou expandido** através de um botão.
- Dois ícones de menu **hambúrguer**:
  - Um localizado na **navegação superior** (`<nav>`).
  - Outro no próprio **menu lateral esquerdo** (`<aside>`).
- Incorporação de playlists reais do Spotify por meio de **iframes**.
- Uma seção com:
  - Botão **Playlists**;
  - Ícone de **pesquisa**;
  - Título **"Recentes"** alinhado à direita junto ao menu hambúrguer;
  - Um **dropdown** com opções de ordenação.
- Exibição de playlists com:
  - **Imagem da playlist**;
  - **Nome da playlist**;
  - **Nome do criador**;
  - Esses elementos **desaparecem quando o aside está compactado**.

> ⚠️ Este projeto tem fins puramente educacionais.
## 🖼️ Visão Geral

A aplicação web é composta por:

- **Cabeçalho (`header`)** com navegação (voltar/avançar, home, busca, notificações, perfil).
- **Menu lateral esquerdo (`aside`)** com biblioteca do usuário, playlists, opções de ordenação e um dropdown interativo.
- **Conteúdo principal (`main`)** com destaques, filtros (músicas, podcasts, tudo) e cartões de músicas/álbuns com botões de "play".
- **Menu lateral direito (`aside`)** com a fila de reprodução atual e próximas músicas.
- **Rodapé (`footer`)** com player simplificado da música em execução.

## 📁 Estrutura de Pastas
```
📁 projeto/

├── index.html

├── img/

│ └── (ícones, capas de playlists e músicas)

├── styles/

│ ├── navigation_left.css

│ ├── menu.css

│ ├── navigation_center.css

│ ├── navigation_right.css

│ ├── aside_left.css

│ ├── main.css

│ ├── aside_right.css

│ ├── footer_left.css

│ ├── footer_center.css

│ └── footer_right.css
```

> Cada arquivo CSS representa um módulo visual específico da interface, promovendo **organização e manutenibilidade**.

## 🧩 Funcionalidades

- ✅ Interface 100% HTML e CSS modularizada
- ✅ Reprodutor real via `iframe` do Spotify
- ✅ Menu dropdown funcional com `checkbox toggle`
- ✅ Layout responsivo
- ✅ Ícones e imagens estilizados para imersão
- ✅ Exibição de playlists e músicas recentes

## 🔧 Tecnologias Utilizadas

- **HTML5**  
- **CSS3**  
- **Google Fonts (Montserrat)**  
- **Spotify Embed API (via iframe)**  

## 📸 Capturas de Tela

(Adicione aqui capturas da interface: biblioteca expandida, conteúdo principal, fila da direita...)

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/spotify-clone.git