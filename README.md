# 🎬 CineBRM- 

Bem-vindo ao **CineBRM-**, um aplicativo de streaming leve e automatizado que roda diretamente no navegador.

## 🚀 Link do Aplicativo
👉 **[CLIQUE AQUI PARA ASSISTIR](https://cinebrmofficial-afk.github.io/CineBRM-/)**

---

## 🛠️ Como o projeto funciona?
Este projeto utiliza uma integração entre Python (Google Colab) e uma interface Web (GitHub Pages):

1.  **Banco de Dados:** Os filmes são gerenciados em um arquivo `filmes.db` (SQLite).
2.  **Sincronização:** Um script Python no Colab transforma os dados em `filmes.json`.
3.  **Interface:** O `index.html` lê esse JSON e monta a vitrine de filmes automaticamente.

## 📂 Arquivos Principais
* `index.html`: O "corpo" do aplicativo (Design e Player).
* `filmes.json`: A lista atualizada de filmes e links.
* `filmes.db`: Backup do banco de dados completo.

## 🔄 Como atualizar o catálogo
Para adicionar novos filmes, basta rodar o seu **Notebook no Google Colab** que envia as atualizações via API do GitHub.

---
*Mantido por [cinebrmofficial-afk](https://github.com/cinebrmofficial-afk)*
