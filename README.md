# 🥗 Landing Page · Nutrição Clínica e Esportiva

Uma landing page de alta conversão para nutricionista, construída do zero com
foco em **captar clientes**, **ranquear no Google** e **funcionar perfeitamente
no celular**.

> Do primeiro clique ao agendamento no WhatsApp — sem dietas radicais de código.

<img width="600px" src="/imgs/landing-page.png" alt="Preview da seção hero da landing page de nutrição">

**🔗 Acesse a página:** [gabrielneox3.github.io/Landing-Page-Cirilia-Camejo](https://gabrielneox3.github.io/Landing-Page-Cirilia-Camejo/)

---

## 🎯 O problema que o projeto resolve

Uma profissional de nutrição precisa de presença digital que **transforme
visitante em paciente**. A maioria das páginas falha em três pontos: não tem
chamada para ação clara, não aparece no Google e não funciona bem no celular —
de onde vem a maior parte do tráfego.

Esta página resolve os três com escolhas técnicas deliberadas.

---

## 💡 Decisões que fazem a página converter

### Chamada para ação pensada para o negócio
- **Botão de WhatsApp repetido em 3 pontos** (início, meio e fechamento), com
  **mensagem pré-preenchida** para o cliente iniciar a conversa sem esforço.
- **Hierarquia de CTA**: um primário ("Agendar minha consulta") e um secundário
  ("Conhecer os serviços") para atender quem já decidiu e quem ainda avalia.

### SEO que faz o Google entender o negócio
- **Dados estruturados JSON-LD (LocalBusiness)**: o Google identifica nome,
  profissão e localização — essencial para busca local.
- Metatags de `title` e `description` otimizadas, estrutura semântica e
  `alt text` descritivo em todas as imagens.

### Acessibilidade como padrão, não como extra
- Contraste de cor conforme diretrizes WCAG.
- Foco visível por teclado (`focus-visible`) e área de toque mínima de `44px`.
- Atributos `aria` para leitores de tela.

---

## 🛠️ Stack e conhecimentos aplicados

**HTML semântico** — uso de `<header>`, `<main>`, `<section>` e `<footer>` para
contextos específicos, melhorando acessibilidade, organização e SEO.

**CSS externo (`style.css`)** — estrutura separada da apresentação, com:

- **Variáveis CSS (`:root`)** — cores, espaçamentos e sombras centralizados:
  trocar a identidade visual é alterar uma linha, não cinquenta.
- **Tipografia fluida com `clamp()`** — o texto escala com a tela sem quebrar
  no mobile.
- **Grid responsivo com `auto-fit` e `minmax()`** — os cards se reorganizam
  sozinhos em qualquer largura de tela.
- **Media queries** — menu hambúrguer e empilhamento do hero no mobile.

**JavaScript** — menu mobile funcional com controle de estado (`aria-expanded`).

---

## 📁 Estrutura do projeto

```text
Landing-Page-Cirilia-Camejo/
├── index.html
├── style.css
└── img/
    ├── nutri-hero.jpg
    └── nutri-about.jpg
