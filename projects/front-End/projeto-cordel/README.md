---
tags: [projeto, front-end, estudo]
status: parado
stack: [HTML, CSS]
created: 2026-02-02
updated: 2026-02-02
---
# 🚀 Projeto – Projeto Cordel

## 🎯 Objetivo do Projeto

> O projeto utiliza-se como conteúdo um cordel, exigindo a aplicação de background-attachment para efeito parallax simples, além de conceitos semânticos e de estilização em CSS

---

## 🧠 Conceitos Aplicados
- HTML semântico
- Organização de layout por seções
- Tipografia com Google Fonts
- Parallax simples com `background-attachment`
- Variáveis CSS (`:root`)
- Responsividade básica (sem media queries)

---

## 🛠 Stack Tecnológica

- [x] HTML5
- [x] CSS3
- [ ] JavaScript

---

## 📐 Estrutura do Projeto

```
📦 projeto-cordel
 ┣ 📂 assets
 ┃ ┣ 📂 images
 ┃ ┗ 📂 style
 ┃   ┗📜 style.css
 ┣ 📜 index.html
 ┗ 📜 README.md
```

---

## 📋 Checklist de Desenvolvimento (MVP)

### Estrutura
- [x] HTML base
- [x] Tags semânticas
- [x] SEO básico

### Estilo
- [x] Reset CSS
- [x] Variáveis globais
- [ ] Layout responsivo
- [ ] Estados de interação

---

## 🐛 Bugs & Soluções (Diário de Bordo)

### 31/01/2026
- **Erro:** Estrofes separadas por parágrafos não exibiam corretamente
- **Causa:** Utilização de `position: absolute;` no elemento p fazendo com que todos os parágrafos fossem sobrepostos um pelo outro
- **Solução:** remoção de `position: absolute;`

### 02/02/2026
- **Erro:** Algumas estrofes não eram exibidas causando ausências
- **Causa:** Utilização de `position: absolute;` nos id das imagens que recebem o efeito parallax, causando sobreposição dos parágrafos
- **Solução:** remoção de `position: absolute;`

### 03/02/2026
- **Erro:** Rolagem lateral devido imagens estarem maior que o body
- **Causa:** Uso de `width: 100%` o que fazia as imagens saírem um pouco pra fora da main
- **Solução:** remoção de `width: 100%`

---

## 🧪 Testes Realizados

- [x] Desktop
- [ ] Mobile
- [x] Chrome
- [x] Edge

---

## 💡 Melhorias Futuras (V2.0)

- [ ] Menu mobile
- [ ] Animações CSS
- [ ] JavaScript básico
- [ ] Acessibilidade

---

## 📚 Aprendizados (Feynman)

>  O uso de `position: absolute` retira o elemento do fluxo normal do layout, o que pode causar sobreposição de conteúdos e desaparecimento visual de elementos subsequentes. Isso exige cuidado extremo e geralmente deve ser evitado para blocos de texto.
>  
>  O uso de `width: 100%` ou valores relacionados ao viewport pode gerar rolagem lateral quando combinado com `padding`, `margin` ou containers com largura limitada, sendo uma boa prática preferir `max-width` e centralização com margin automática.

---

## 🧭 Próximo Passo

➡️ Analisar diferenças do projeto do curso para a minha criação pessoal

