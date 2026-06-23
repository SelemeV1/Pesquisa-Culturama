Culturama - Pesquisa de Opinião

O **Culturama** é um formulário web opinativo desenvolvido estritamente com **HTML5 e CSS3**. O foco principal do projeto foi aplicar validações nativas do navegador e diretrizes essenciais de acessibilidade digital (WCAG/ARIA) para entregar uma experiência leve, inclusiva e de alta performance.

---

## 🚀 Destaques do Projeto

### 🎨 HTML Semântico & UX
* **Organização Lógica:** Divisão estruturada em 5 blocos usando `<fieldset>` e `<legend>` (*Dados Pessoais, Perfil, Hábitos, Satisfação e Confirmações*).
* **Validação 100% Nativa:** Uso de restrições diretas no HTML (como `min`/`max` para idade, `type="email"` e inputs avançados como `type="color"`).
* **Regex no HTML:** Validação do campo de telefone usando o atributo `pattern="[0-9]{11}"`.
* **Datalist:** Sugestões inteligentes para *Estilo Musical* e *Cor Favorita* sem travar a digitação livre.

### ♿ Acessibilidade (WCAG & ARIA)
* **Suporte a Leitores de Tela:** Uso de `aria-describedby` para associar instruções de ajuda aos campos de *Telefone* e *Upload*.
* **Ações Claras:** Botões de enviar e limpar enriquecidos com `aria-label`.
* **Navegação por Teclado:** Ordem de tabulação natural e foco visual bem definidos.

### 📊 Qualidade e SEO Técnico
* **Auditorias Completas:** Otimizado com base nos critérios do **Google Lighthouse** e **WAVE** para garantir contraste ideal e zero erros de acessibilidade.
* **Performance Máxima:** Carregamento ultra rápido e ótima indexação (SEO) por não utilizar JavaScript pesado, contando com conexões prévias (`preconnect`) para fontes.

---

## 🛠️ Tecnologias
* **HTML5** (Semântica, validações e atributos ARIA)
* **CSS3** (Estilização responsiva e estados visuais)

---
