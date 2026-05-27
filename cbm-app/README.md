# 📱 CBM Estudos — App Android

Guia completo de estudos para **CBM PE** e **CBM AL** com:
- Rastreamento de horas por tópico
- Timer Pomodoro integrado
- Notas por tópico
- Progresso visual com barras
- Funciona offline
- Instalável no Android como app nativo

---

## 🚀 Como instalar no Android (2 métodos)

### Método 1 — GitHub Pages (gratuito, 3 minutos)

1. Crie uma conta gratuita em [github.com](https://github.com)
2. Crie um repositório chamado `cbm-estudos` (público)
3. Faça upload de todos estes arquivos
4. Vá em **Settings → Pages → Source: main / root**
5. Acesse `https://SEU_USUARIO.github.io/cbm-estudos` no Chrome do Android
6. Chrome mostrará automaticamente **"Adicionar à tela inicial"** → toque e instale!

### Método 2 — APK via PWABuilder (sem código, gratuito)

1. Hospede os arquivos (método acima)
2. Acesse [pwabuilder.com](https://pwabuilder.com)
3. Cole a URL do seu GitHub Pages
4. Clique em **"Build My PWA"** → **Android** → **Download**
5. Instale o APK no seu Android (habilite "fontes desconhecidas" nas configurações)

---

## 📲 Recursos do App

| Recurso | Descrição |
|---------|-----------|
| 🏠 Início | Dashboard com progresso geral + streak |
| 📊 Progresso | Rastreamento de horas por tópico com barras verdes |
| ⏱ Timer | Pomodoro 25/50/15 min com log de sessões |
| 📝 Notas | Anotações por tópico + exportação |
| 🔔 Notificações | Lembretes de estudo (após instalar) |
| 📴 Offline | 100% funcional sem internet |

---

## 📁 Arquivos incluídos

```
cbm-app/
├── index.html     ← App principal (toda a lógica)
├── manifest.json  ← Configuração PWA (ícones, nome, shortcuts)
├── sw.js          ← Service Worker (offline + cache)
├── icon-48.png    ← Ícone do app
├── icon-96.png
├── icon-192.png   ← Ícone principal Android
├── icon-512.png   ← Ícone splash screen
├── icon-180.png   ← Ícone Apple (iOS)
└── favicon.png    ← Favicon do navegador
```

---

## ⚙️ Atalhos de tela (Widgets)

Após instalar, **pressione longamente** o ícone do app para ver:
- 📊 **Meu Progresso** — acesso direto à aba de progresso
- ⏱ **Timer Pomodoro** — inicia direto no timer
- 📝 **Minhas Notas** — abre as anotações

---

## 📊 Conteúdo dos Editais

### CBM PE (Praça/Soldado — AOCP 2023)
- 9 disciplinas · 60 questões · ~162h de estudo
- Blocos: Linguagens | Lógico-Matemático | Ciências | Conhecimentos Gerais

### CBM AL (Soldado — AOCP 2026)
- 8 disciplinas · ~110h de estudo  
- Disciplinas: LP, Inglês, Informática, Matemática, RL, Legislação, Cidadania, Atualidades

---

## 💾 Dados salvos localmente

Todo o progresso, notas e sessões ficam salvos no **localStorage** do navegador/app.
Para fazer backup manual, use o botão **"Exportar notas"** na aba Notas.

---

*Desenvolvido com HTML5 PWA — Compatível com Android 8.0+, iOS 14+ e qualquer navegador moderno*
