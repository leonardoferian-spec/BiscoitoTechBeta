# 🎄 Biscoito Alegre de Natal

Um mini-aplicativo web interativo e festivo onde os usuários podem "quebrar" um biscoito de Natal virtual para revelar mensagens e desejos de boas festas. Originalmente tematizado para o clima natalino do SENAI, o projeto conta com animações ricas, efeitos sonoros gerados proceduralmente e sistemas de partículas.

## ✨ Funcionalidades

*   **Interatividade Tátil:** Clique no biscoito 3 vezes para quebrá-lo. A cada clique, o biscoito treme, racha e solta faíscas mágicas.
*   **Mensagens Procedurais:** Um gerador inteligente cria dezenas de combinações de mensagens natalinas únicas para cada usuário.
*   **Efeitos Visuais Avançados:** 
    *   Sistema de partículas em Canvas para neve caindo continuamente ao fundo.
    *   Explosões de partículas (sparkles) sincronizadas com os cliques do usuário.
    *   Iluminação com luzes pisca-pisca de Natal animadas via CSS puro.
*   **Áudio Procedural:** Nada de arquivos `.mp3` pesados! Todos os efeitos sonoros (rachaduras do biscoito, sinos de Natal e sons de transição) são sintetizados em tempo real usando a **Web Audio API**.
*   **Compartilhamento de Imagem:** Integração com a biblioteca `html2canvas` para capturar a tela e permitir que o usuário baixe ou compartilhe sua mensagem diretamente pelo celular (Web Share API).
*   **Design Responsivo:** Construído com Tailwind CSS para se adaptar perfeitamente a celulares, tablets e desktops.
