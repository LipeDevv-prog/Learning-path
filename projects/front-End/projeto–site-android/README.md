---
tags:
  - projeto
  - front-end
  - estudo
status: concluido
stack:
  - HTML
  - CSS
created: 2026-01-02
updated: 2026-01-02
---
# 🚀 Projeto – Site Android

## 🎯 Objetivo do Projeto

> Construir um site responsivo e semântico, aplicando os conceitos dos Módulos 1 e 2 de HTML5 e CSS3.

---

## 🧠 Conceitos Aplicados

- HTML Semântico
- Hierarquia de títulos
- Responsividade
- Variáveis CSS (`:root`)
- Flexbox / Grid
- Pseudo-classes e pseudo-elementos

---

## 🛠 Stack Tecnológica

- [x] HTML5
- [x] CSS3
- [ ] JavaScript

---

## 📐 Estrutura do Projeto

```
📦 Projeto - Site Android
 ┣ 📂 assets
 ┃ ┣ 📂 fonts
 ┃ ┗ 📂 images
 ┃ ┗ 📂 style
 ┃    ┗ 📜 style.css
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
- [x] Layout responsivo
- [x] Estados de interação

---

## 🐛 Bugs & Soluções (Diário de Bordo)

### 02/01/2026
- **Erro:** Tive problemas de responsividade ao incorporar um vídeo no site, onde o vídeo não se adaptava a tela do usuário
- **Causa:** Falta de um container adaptável através de CSS
- **Solução:** Adicionei o iframe responsável por incorporar o vídeo no site dentro de uma div, assim definindo os parâmetros para responsividade utilizando CSS3 Moderno

- **Erro:** Cabeçalho de site misturado com o Menu
- **Causa:** Menu estava dentro do `header`
- **Solução:** Separei o `nav` para facilitar o controle visual e organizacional
  
- **Erro:** Id desnecessário no header
- **Causa:** Atribuição de id cabeçalho no elemento h1 do header
- **Solução:** Remoção do id, já que não é necessário e melhora a estrutura do CSS

- **Erro:** Falta de definição das versões adocicadas do android
- **Causa:** Ausência da tag abbr
- **Solução:** Adição da tag abbr com as definições dos nomes

- **Erro:** Limitação na responsividade
- **Causa:** min-width definido em 360px, sem muito suporte a celulares antigos
- **Solução:** alteração do valor de 360px em min-width para 320px adicionando maior suporte de responsividade

- **Erro:** line-height  estava padrão em todos os elementos, além de margin:auto estar definido enquanto removia todas as margins
- **Causa:** line-height estava definido na configuração global
- **Solução:** Remoção do line-height e margin:auto da configuração global

- **Erro:** Responsividade de imagem quebrada demorava para adaptar-se a tela
- **Causa:** Ausência de width
- **Solução:** Adição de width com valores de 100% para img normal e width 50% para img com class=pequena além de margin:auto e display:block já que nossa imagem não é tratada como um bloco por padrão.

---

## 🧪 Testes Realizados

- [x] Desktop
- [x] Mobile
- [x] Chrome
- [x] Edge

---

## 💡 Melhorias Futuras (V2.0)

- [x] Otimização de CSS3 Moderno
- [ ] Menu mobile
- [ ] Animações CSS
- [ ] JavaScript básico
- [ ] Acessibilidade


---

## 📚 Aprendizados (Feynman)

>Esse projeto consolidou meu entendimento sobre HTML semântico, containers e estilização com CSS moderno. Consegui aplicar pseudo-classes, pseudo-elementos e responsividade, resultando em uma landing page simples, porém funcional e adaptável a diferentes telas.

---

## 🧭 Próximo Passo

➡️ Revisar código e acompanhar aulas passo a passo sobre o projeto, a fim de pegar insights e verificar lugares onde errei e melhorias
