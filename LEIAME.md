# LoadUp PWA — Guia de Instalação

## 📁 Arquivos do projeto
```
loadup-pwa/
├── index.html      ← App completo
├── manifest.json   ← Configuração PWA
├── sw.js           ← Service Worker (offline)
└── LEIAME.md       ← Este arquivo
```

---

## 🚀 Como hospedar (obrigatório para instalar no celular)

O PWA precisa estar num servidor HTTPS. Opções **gratuitas**:

### Opção A — Netlify (mais fácil)
1. Acesse https://netlify.com e crie conta gratuita
2. Arraste a pasta `loadup-pwa` para a área de deploy
3. Seu app estará em https://seuapp.netlify.app

### Opção B — GitHub Pages
1. Crie repositório no GitHub
2. Suba os 3 arquivos
3. Vá em Settings → Pages → Deploy from branch
4. URL: https://seuusuario.github.io/loadup

### Opção C — Vercel
1. Acesse https://vercel.com
2. Importe o repositório ou arraste a pasta
3. Deploy automático com HTTPS

---

## 📱 Instalar no iPhone (iOS Safari)

1. Abra o link do app no **Safari** (obrigatório — não funciona no Chrome iOS)
2. Toque no ícone de **Compartilhar** (quadrado com seta ↑) na barra inferior
3. Role para baixo e toque em **"Adicionar à Tela de Início"**
4. Confirme o nome "LoadUp" e toque em **Adicionar**
5. O ícone aparece na sua tela inicial ✅

> ⚠️ **Importante:** No iPhone, use sempre o Safari para instalar PWAs.

---

## 🤖 Instalar no Android (Chrome)

1. Abra o link do app no **Chrome**
2. O banner "Instalar LoadUp" aparece automaticamente na tela
3. Toque em **Instalar**
4. O app é adicionado à tela inicial como um app normal ✅

> Alternativa: toque nos 3 pontos (⋮) → "Adicionar à tela inicial"

---

## ✅ Funcionalidades do app

- Criar e renomear rotinas de treino (A, B, C...)
- Registrar exercícios, séries, repetições e peso
- Volume total calculado automaticamente por exercício e por treino
- Sistema de PRs (recordes pessoais) automático
- 8 medalhas desbloqueáveis por conquistas
- Histórico de todos os treinos
- Perfil com nome e estatísticas
- **Funciona offline** após a primeira abertura
- Dados salvos localmente no dispositivo

---

## 🎨 Identidade Visual
- Paleta: Preto + Dourado
- Estilo: Dark / Academia pesada
- Fontes: Oswald (títulos) + Barlow (texto)
