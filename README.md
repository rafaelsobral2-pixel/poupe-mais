# Poupe+ — Tela de Criar Conta

Projeto acadêmico de Fintech. Tela de **cadastro de novo usuário** do app **Poupe+**, uma plataforma de gestão de finanças pessoais.

![Tecnologia](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![Tecnologia](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![Tecnologia](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)

---

## 🚀 Como executar

Basta abrir o arquivo `index.html` no navegador. Não precisa de servidor nem de conexão com a internet — todos os arquivos são locais.

```
1. Baixe ou clone este repositório
2. Dê duplo clique em index.html
3. Pronto, a tela abrirá no navegador
```

---

## 📁 Estrutura de arquivos

```
poupe-mais/
├── index.html       → Estrutura da tela (HTML)
├── styles.css       → CSS personalizado (identidade visual)
├── tailwind.css     → Tailwind CSS pré-compilado (funciona offline)
└── README.md        → Este arquivo
```

> **Por que o Tailwind está pré-compilado?**
> Para garantir que o projeto abra corretamente na máquina do professor, mesmo sem conexão com a internet, todo o CSS do Tailwind já vem gerado em `tailwind.css`. Não é necessário rodar nenhum build.

---

## 🎨 Identidade visual

| Elemento | Valor |
|---|---|
| Cor primária (verde escuro) | `#1a5d36` |
| Cor secundária (verde profundo) | `#0f3d22` |
| Cor de destaque (verde claro) | `#3fce7a` |
| Cor de erro (vermelho) | `#dc2626` |
| Fonte principal | Inter (Google Fonts) |
| Bordas arredondadas | `0.5rem` (forms) / `0.625rem` (cards) |

---

## ✅ Atendimento aos critérios de avaliação

| # | Critério | Peso | Como foi atendido |
|---|---|---|---|
| 1 | **Estrutura e Contexto da Tela** | 20% | Tela de cadastro coerente com a proposta do app de finanças Poupe+. Layout em dois painéis: branding à esquerda (logo + benefícios) e formulário à direita (campos organizados, estados de foco e erro). |
| 2 | **Funcionamento e Organização do Projeto** | 20% | Tailwind pré-compilado localmente — abre direto pelo `index.html` sem internet. Sem dependências externas que possam falhar. Código organizado e comentado. |
| 3 | **Responsividade** | 10% | Layout adapta-se a mobile (< 1024px o painel verde vai para o topo; < 640px os campos lado a lado empilham). Usa `flex-col`/`lg:flex-row` e `grid-cols-1`/`sm:grid-cols-2` do Tailwind. |
| 4 | **Separação correta entre HTML e CSS** | 10% | HTML em `index.html`, CSS em `styles.css` (personalizado) e `tailwind.css` (framework). Nenhum estilo inline. |
| 5 | **Uso de Framework Web (Tailwind CSS)** | 10% | Tailwind CSS 3.4 usado em todo o layout (flexbox, grid, espaçamentos, tipografia, cores, breakpoints). Cores da marca configuradas via `tailwind.config.js`. |
| 6 | **GitHub e Versionamento** | 30% | Repositório público com todos os arquivos necessários para execução. |

---

## 🖥️ Funcionalidades da tela

- Campo de **Nome** com estado de foco (borda verde)
- Campo de **Sobrenome** com placeholder
- Campo de **E-mail** com placeholder
- Campos de **Senha** e **Confirmar senha**
- **Estado de erro visual** demonstrado (senhas não coincidem)
- Checkbox de aceite dos Termos de Uso e Política de Privacidade
- Botão de submissão "Criar conta"
- Link para "Fazer login" para quem já tem conta
- Painel lateral com benefícios da plataforma:
  - Controle de gastos mensais
  - Metas financeiras
  - Dados seguros e criptografados

---

## 📱 Responsividade

| Tela | Comportamento |
|---|---|
| **Desktop** (≥ 1024px) | Dois painéis lado a lado (50/50) |
| **Tablet** (640px – 1023px) | Painéis empilhados verticalmente, campos NOME/SOBRENOME e SENHA/CONFIRMAR ainda lado a lado |
| **Mobile** (< 640px) | Tudo empilhado em coluna única, painel verde compactado |

---

## 👤 Autor

Projeto desenvolvido como atividade da disciplina de Fintech.
