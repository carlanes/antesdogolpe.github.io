# Operação Brasil 31 de Março
## Arquivo histórico digital — Guia de publicação no GitHub Pages

---

## Estrutura de arquivos

```
golpe1964/
├── index.html          ← Página inicial
├── css/
│   └── style.css       ← Todo o CSS do site
└── pages/
    ├── cronologia.html
    ├── telegramas.html
    ├── analises.html
    ├── personagens.html
    ├── documentos.html
    └── sobre.html
```

---

## Passo a passo: publicar no GitHub Pages

### 1. Criar conta no GitHub
- Acesse https://github.com
- Clique em "Sign up"
- Escolha um nome de usuário (ex: `golpe1964brasil`)
- Confirme o e-mail

### 2. Criar o repositório
- Clique no "+" no topo direito → "New repository"
- **Nome do repositório:** `golpe1964` (ou qualquer nome)
- Deixe como **Public**
- Clique em "Create repository"

### 3. Fazer upload dos arquivos
- Na página do repositório, clique em "uploading an existing file"
- Arraste TODOS os arquivos e pastas de uma vez
  (index.html + pasta css/ + pasta pages/)
- Clique em "Commit changes"

### 4. Ativar o GitHub Pages
- Vá em **Settings** (aba no topo do repositório)
- No menu lateral, clique em **Pages**
- Em "Branch", selecione **main**
- Clique em **Save**

### 5. Acessar o site
- Aguarde 1–2 minutos
- Seu site estará em:
  `https://SEU-USUARIO.github.io/golpe1964/`

---

## Como adicionar novos conteúdos

### Adicionar um novo telegrama
1. Abra o arquivo `pages/telegramas.html`
2. Copie um bloco `<div class="telegrama-doc">...</div>` existente
3. Cole abaixo do último telegrama
4. Edite os dados: número de referência, data, remetente, texto, análise
5. Faça upload do arquivo atualizado no GitHub

### Adicionar um evento à cronologia
1. Abra `pages/cronologia.html`
2. Copie um bloco `<div class="cronologia-entry">...</div>`
3. Cole na posição cronológica correta
4. Edite a data e o conteúdo

### Adicionar fotos
1. Crie uma pasta `imagens/` no repositório
2. Faça upload das fotos lá
3. Substitua os placeholders `<div class="hero-img">` por:
   `<img src="../imagens/nome-da-foto.jpg" alt="Descrição" style="width:100%;height:200px;object-fit:cover;">`

---

## Domínio personalizado (opcional, gratuito)
Se você comprar um domínio (ex: `golpe1964.com.br`):
1. No registro do domínio, crie um registro CNAME apontando para `SEU-USUARIO.github.io`
2. No GitHub Pages (Settings → Pages), adicione o domínio em "Custom domain"
3. O site ficará disponível no seu domínio em até 24h

---

## Busca no site (opcional)
Para ativar busca real, instale o Pagefind:
- Documentação: https://pagefind.app
- Gratuito e funciona 100% no GitHub Pages

---

Conteúdo de domínio público. Fontes: Arquivo Nacional, NARA, CPDOC/FGV.
