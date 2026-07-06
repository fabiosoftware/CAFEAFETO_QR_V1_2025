# ☕ Café Afeto - Cardápio Digital QR Code 📱

Este repositório documenta a jornada de desenvolvimento do **Café Afeto**, um aplicativo Mobile desenvolvido em **Flutter** para modernizar a experiência de atendimento em cafeterias através de um cardápio interativo acessado via QR Code.

---

## 🗺️ A Jornada de Desenvolvimento: Do Protótipo à Refatoração

Nesta seção, apresento as principais fases de transição do projeto, ilustrando não apenas o resultado final, mas o meu processo de aprendizado, a identificação de problemas e a aplicação de melhorias técnicas e visuais.

### Fase 1: Primeiros Passos e Estrutura Básica (Início de Junho/2026)

O início do projeto focou na criação das telas fundamentais. A estética era simples e os componentes ainda estavam sendo testados.

| <img src="Captura de tela 2026-06-01 233004.png" width="250"> | <img src="Captura de tela 2026-06-15 190602.png" width="250"> |
|:---:|:---:|
| **Primeira Tela de Boas-Vindas:** Foco na estrutura básica de layout. | **Primeiro Cardápio:** Listagem simples de itens, com componentes ainda em estado bruto. |

---

### Fase 2: Introdução da Identidade Visual e Funcionalidades (Meados de Junho/2026)

Nesta etapa, comecei a definir uma paleta de cores inspirada no café e introduzi a primeira grande funcionalidade: a seleção de múltiplos idiomas para o cardápio.

| <img src="Captura de tela 2026-06-17 181017.png" width="250"> | <img src="Captura de tela 2026-06-21 235343.png" width="250"> |
|:---:|:---:|
| **Seleção Multilíngue V1:** Implementação da lógica de troca de idioma com bandeiras e botões simples. | **Cardápio com UI Consolidada:** O layout começa a ganhar forma, com cartões de itens mais organizados e melhores espaçamentos. |

---

### Fase 3: Refatoração Visual e Polimento de UI (Fim de Junho/2026)

Após análise, identifiquei que a primeira interface de idiomas estava muito simples. Iniciei uma **refatoração completa da UI**, adotando um visual mais moderno, limpo e profissional.

| <img src="Captura de tela 2026-06-27 233353.png" width="250"> | <img src="Captura de tela 2026-07-02 180402.png" width="250"> |
|:---:|:---:|
| **Nova UI de Idiomas:** O visual evolui para uma abordagem mais imersiva, com ícones mais claros e componentes Material Design polidos. | **Aperfeiçoamento do Cardápio:** Layout mais limpo e focado na legibilidade, com uso estratégico de sombras e bordas arredondadas. |

---

### Fase 4: O Estado Atual e Próximos Passos (Julho/2026)

Esta é a fase mais recente do projeto, onde a identidade visual está totalmente consolidada e as funcionalidades core (como o carrinho de compras) estão prontas para a integração final.

| <img src="Captura de tela 2026-07-05 010307.png" width="250"> | <img src="Captura de tela 2026-07-04 182119.png" width="250"> |
|:---:|:---:|
| **UI Consolidada e Identidade Visual (Atuais):** Tela inicial refinada, com logo claro e fluxo de navegação otimizado. | **Ajustes de UX no Carrinho de Compras:** O layout do carrinho está organizado e aprimorado visivelmente para o usuário. |

---

## 🛣️ Roadmap de Evolução e Próximos Passos

Apesar da grande evolução visual, o projeto continua em desenvolvimento ativo. Este é o meu roadmap para as próximas sprints:

### ✅ Concluído (Foco em UI/UX)
* [x] Definição e aplicação da Identidade Visual.
* [x] Refatoração completa da UI de seleção de idiomas.
* [x] Organização visual do cardápio e componentes de itens.
* [x] Polimento do layout do carrinho de compras.

### 🚧 Em Andamento (Foco Técnico e Integração)
* [ ] **Ajuste Técnico no Carrinho:** Atualmente, os botões de adicionar e remover itens no carrinho funcionam visualmente, mas ainda precisam de correção na gerência de estado para atualizar o subtotal e o total geral corretamente.
* [ ] **Leitura do QR Code:** Implementar a lógica real para que o app leia um QR Code e direcione para a mesa correta.

---

## 🛠️ Tecnologias e Arquitetura

*   **Framework:** Flutter (Android/iOS/Web)
*   **Linguagem:** Dart
*   **Gerência de Estado:** `setState` / `ChangeNotifier`
*   **Principais Pacotes:**
    *   `qr_code_scanner` / `qr_flutter` (Manipulação e leitura de QR Codes)
    *   `flutter_localizations` (Suporte ao sistema multilíngue de idiomas)

---

**Autor:** Fabio (fabiosoftware) - Desenvolvedor Flutter em Evolução
