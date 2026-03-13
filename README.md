# Vídeo Link 🎬

Sistema inteligente para adicionar vídeos da galeria (MP4) e gerar automaticamente links URL válidos HTTPS no formato **m3u8 (HLS)**.

## 🚀 Funcionalidades
- **Interface Inteligente:** Design moderno com degradê personalizado (Roxo, Laranja, Vermelho).
- **Processamento de Grande Escala:** Preparado para lidar com vídeos de qualquer tamanho, incluindo filmes completos.
- **Geração Automática:** Transcodificação de MP4 para M3U8 de forma automática via API.
- **Foco na Ação:** Interface minimalista sem barras de busca, com botão de ação sempre visível.

## 🎨 Identidade Visual
O aplicativo utiliza um tema vibrante em degradê:
- `Roxo (#800080)`
- `Laranja (#FF4500)`
- `Vermelho (#FF0000)`

## 🛠️ Tecnologias
- **Frontend:** HTML5, CSS3 (Glassmorphism), JavaScript (Fetch API).
- **Backend Recomendo:** Node.js com FFmpeg para processamento de filmes longos.

## ⚙️ Como Funciona
1. O usuário seleciona um arquivo `.mp4`.
2. O sistema envia o arquivo para um servidor de processamento.
3. O servidor utiliza **FFmpeg** para fragmentar o vídeo em segmentos `.ts` e criar a playlist `.m3u8`.
4. O link final HTTPS é retornado para o usuário pronto para ser usado em qualquer player.

## 📦 Como Instalar
1. Clone o repositório:
   ```bash
   git clone [https://github.com/SEU-USUARIO/video-link.git](https://github.com/SEU-USUARIO/video-link.git)
