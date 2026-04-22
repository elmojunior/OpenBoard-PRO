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

O OpenBoard-PRO é totalmente *client-side*. Escolha a forma que melhor se adapta à sua necessidade:

### 1\. Uso Online (Recomendado)

Para garantir que todas as funcionalidades (como embeds e carregamento de fontes) funcionem perfeitamente sem configurações técnicas, utilize a versão online.
👉 **Clique aqui para abrir o OpenBoard-PRO: [https://elmojunior.github.io/OpenBoard-PRO/openboardpro.html](https://elmojunior.github.io/OpenBoard-PRO/openboardpro.html)**

> **Dica:** Para a melhor experiência de performance e compatibilidade, utilize o **Google Chrome** ou **Chromium**.

### 2\. Uso Local (Offline)

Você pode rodar o aplicativo diretamente do seu computador:

1.  Faça o download do arquivo `openboardpro.html` presente neste repositório.
2.  Abra o arquivo em seu navegador de preferência.

-----

> **⚠️ Nota sobre embeds e segurança:** Devido a políticas de segurança dos navegadores (CORS), recursos de *Embed* (como vídeos do YouTube ou sites externos) podem ser bloqueados se você abrir o arquivo localmente usando o protocolo `file://`. Se precisar dessas funções rodando localmente, é necessário configurar um **servidor local** em sua máquina. Caso contrário, utilize a **versão online** indicada acima.

## ⌨️ Atalhos de Teclado Principais

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

## 📂 Estrutura do Repositório

  * `openboardpro.html`: O aplicativo completo em um único arquivo.
  * `README.md`: Documentação do projeto.
  * `LICENSE`: Termos da licença de uso.

## 📄 Licença

Este projeto é distribuído sob a licença **GPL-3.0**. Veja o arquivo `LICENSE` para mais detalhes.
