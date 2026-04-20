# OpenBoard-PRO 🎨

Um aplicativo de quadro digital interativo, leve e executável diretamente no navegador. Construído inteiramente em HTML, CSS e JavaScript (Vanilla), sem dependências externas pesadas ou frameworks complexos.

## 🤖 Desenvolvido com IA e Vibe Coding

Este projeto é um experimento prático e funcional de **Vibe Coding** — uma abordagem onde o software é construído não pela digitação manual de código, mas através da orquestração de Inteligências Artificiais usando linguagem natural.

As IAs **Gemini** (Google) e **Claude** (Anthropic) atuaram como co-desenvolvedoras deste projeto. Todo o código, a lógica de canvas, o sistema de DOM sobreposto e a interface de usuário foram gerados iterativamente a partir de prompts, correções de bugs guiadas e refinamentos de arquitetura conversacionais. 

## ✨ Funcionalidades

* **Ferramentas de Desenho:** Caneta livre com ajuste de espessura e cor.
* **Laser Pointer:** Ferramenta efêmera ideal para apresentações e compartilhamento de tela.
* **Formas e Notas:** Notas adesivas, textos ricos (com formatação), retângulos, círculos, losangos e triângulos.
* **Conexões Inteligentes:** Setas e linhas (retas, curvadas ou em degraus) que se conectam magneticamente aos elementos e os acompanham ao serem movidos.
* **Mídia e Embeds:** Suporte para arrastar e soltar (drag-and-drop) imagens, e integração de iframes (YouTube, PDFs, sites).
* **Alinhamento Magnético (Snapping):** Guias inteligentes que ajudam a alinhar elementos perfeitamente no quadro.
* **Navegação Infinita:** Canvas com zoom ajustável, ferramenta panorâmica (pan) e um minimapa dinâmico.
* **Personalização:** Suporte a fontes do Google Fonts, modo claro/escuro e personalização completa de cores, bordas e opacidade.
* **Importação/Exportação:** Salve o estado completo do quadro e baixe como um arquivo SVG (que pode ser reaberto no app).

## 🚀 Como usar

Como o projeto é totalmente *client-side*, não há necessidade de instalação de pacotes via npm ou configuração de bancos de dados.

1. Clone o repositório:
   ```bash
   git clone [https://github.com/SEU-USUARIO/nome-do-repositorio.git](https://github.com/SEU-USUARIO/nome-do-repositorio.git)
   ```
2. Abra a pasta do projeto.
3. Dê um duplo clique no arquivo `.html` (ex: `index.html`) para abri-lo no seu navegador padrão.

> **⚠️ Nota sobre embeds locais:** Devido a políticas de segurança dos navegadores (CORS), recursos de *Embed* (como iframes de outros sites) podem ser bloqueados se você abrir o arquivo usando o protocolo `file://`. Para testar todas as funcionalidades de rede, recomenda-se servir o arquivo através de um servidor local simples (ex: usando a extensão *Live Server* do VSCode ou executando `python -m http.server` no terminal).

## ⌨️ Atalhos de Teclado Principais

O aplicativo é focado em produtividade. Aqui estão alguns atalhos úteis:

* `V`: Selecionar / Mover
* `N`: Nota Adesiva
* `T`: Texto Livre
* `X`: Seta / Linha de conexão
* `TAB`: Duplica o elemento atual e cria uma conexão automática para a cópia.
* `Shift + Arrastar`: Trava o eixo ao mover um elemento.
* `Ctrl + Scroll`: Zoom in/out.
* `Botão do meio do mouse (Scroll)`: Navegar pela tela (Pan).

## 🛠️ Tecnologias Utilizadas

* HTML5 (Canvas API)
* CSS3
* Vanilla JavaScript (ES6+)

## 📄 Licença

Este projeto é distribuído sob a licença **GPL-3.0**.

Você é livre para usar, estudar, modificar e distribuir este software. No entanto, qualquer versão modificada que seja distribuída também deve adotar a mesma licença GPL-3.0 e ter seu código-fonte aberto. Veja o arquivo `LICENSE` para mais detalhes.
