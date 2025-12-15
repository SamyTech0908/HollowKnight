# Hollow Knight — Projeto Web

Descrição
--------

Pequena página/mini-projeto inspirado na estética de Hollow Knight. Contém arquivos estáticos (HTML, CSS, JavaScript) e pastas de recursos (imagens e sons).

Estrutura do repositório
------------------------

- index.html — página principal
- style.css — estilos
- script.js — scripts JavaScript
- IMAGENS/ — imagens usadas pelo projeto
- Sons/ — arquivos de áudio

Pré-requisitos
--------------

- Navegador moderno (Chrome, Edge, Firefox)
- (Opcional) Python 3 para servir localmente
- (Opcional) Node.js/npm para usar `http-server`
- (Opcional) Extensão Live Server no VS Code

Como executar (opções)
----------------------

1) Abrir com Live Server (VS Code)

- Instale a extensão "Live Server".
- Abra a pasta do projeto no VS Code e clique em "Go Live".
- O projeto abrirá no navegador automaticamente.

2) Servir com Python 3 (PowerShell)

```powershell
# a partir da raiz do projeto
python -m http.server 5500
# abra http://localhost:5500 no navegador
```

3) Usar npx http-server (Node.js)

```powershell
# se não tiver http-server instalado globalmente
npx http-server -p 5500
# ou (com instalação global): http-server -p 5500
# abra http://localhost:5500 no navegador
```
