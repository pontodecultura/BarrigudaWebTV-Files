# Projeto Overlay OBS Studio - Sistema de Legendas e Logos

Este pacote contém o projeto completo, modularizado e pronto para uso como **Overlay no OBS Studio**, acompanhado de um **Painel de Controle (Dashboard)** para gerenciamento em tempo real.

## 📁 Estrutura do Projeto
- `overlay.html` -> Página HTML para ser adicionada como **Fonte de Navegador (Browser Source)** no OBS Studio.
- `painel.html` -> Painel de controle administrativo onde você atualiza legendas, insere URLs de logos e controla a exibição.
- `README.md` -> Instruções de instalação e uso.

---

## 🚀 Como Utilizar no OBS Studio

1. **Extraia** este arquivo ZIP em uma pasta no seu computador.
2. Abra o arquivo **`painel.html`** no seu navegador web (Google Chrome, Edge, etc.).
3. No painel de controle:
   - **Configure as Logomarcas:**
     - Cole a URL da logomarca do seu **canal do YouTube** (posicionada no canto superior esquerdo). Ela é imutável: quando você clica em "Ocultar Overlay", ela **não desaparece**, apenas fica com a transparência ajustável que você definir no cursor deslizante (slider).
     - Insira opcionalmente as URLs da **Logo Esquerda** e **Logo Direita** do programa, se desejar.
     - Clique em **"Salvar Configurações"**.
   - **Gerencie as Legendas/Programas:**
     - Cadastre ou edite títulos, subtítulos e estados (*AO VIVO, RETRANSMISSÃO, GRAVAÇÃO, REPRISE*).
     - Clique em **▶ Usar** para colocar a legenda desejada no ar instantaneamente.
     - Use o botão **"OCULTAR / EXIBIR OVERLAY"** para controlar a barra de legendas na transmissão.
4. **No OBS Studio:**
   - Adicione uma nova fonte do tipo **Navegador (Browser)**.
   - Copie o caminho do arquivo **`overlay.html`** (ou abra-o no navegador e copie o link `file:///.../overlay.html`) e cole no campo URL da fonte do navegador no OBS.
   - Defina a largura para **1920** e altura para **1080**.
   - Pronto! Qualquer alteração feita no painel de controle atualizará o OBS instantaneamente em tempo real.
