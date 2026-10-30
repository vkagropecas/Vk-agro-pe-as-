# VK Agro Peças — protótipo Android

Projeto inicial para Redmi Note 13 Pro 4G. Reconhecimento de fala **acionado por botão** e resposta por voz (voz feminina depende das vozes instaladas no Android).

Comandos de teste:
- "VK, ligar para João" abre o discador; não efetua chamada sem confirmação.
- "VK, WhatsApp para João dizendo bom dia" prepara uma mensagem; é necessário conferir e enviar manualmente.
- "VK, abrir WhatsApp" abre o aplicativo.

**Não implementado:** ativação por palavra-chave contínua, funcionamento com tela apagada, atendimento/desligamento de chamadas WhatsApp, gravação/envio automático de áudio e integração com IA. Essas funções requerem desenvolvimento adicional e podem ser limitadas por Android/WhatsApp.

## Como gerar APK no GitHub
Envie **o conteúdo extraído do ZIP** para a raiz do repositório, mantendo as pastas `app` e `.github`. No GitHub, entre em **Actions** > **Gerar APK Android** > **Run workflow** (ou aguarde o push). Depois de executar com sucesso, abra o resultado da execução e baixe o artefato **VK-Agropecas-APK**. Extraia o ZIP do artefato e instale `app-debug.apk`. O projeto ainda não foi compilado nem testado neste ambiente.

O aplicativo pede permissões de microfone e contatos. Não compartilhe informações de contatos em repositório público.
