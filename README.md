# Funil Frequência 33 (Frequência 33Hz Jesus)

Funil completo de alta conversão clonado e limpo, pronto para deploy instantâneo na **Vercel** conectado com o repositório GitHub [frequencia33hzjesus](https://github.com/Guima-MktDgtGM/frequencia33hzjesus).

---

## 📂 Estrutura de Páginas do Funil

| Rota | Descrição |
| :--- | :--- |
| `/` (`index.html`) | **Página Principal de VSL** (Black VSL com placeholder de vídeo centralizado) |
| `/manuscrito` | **Upsell 1** (Manuscrito Café com Seu Anjo + Grimório de São Bento) |
| `/livros` | **Upsell 2 / Downsell 1** (Combo 5 Livros Físicos Sagrados com Widget 1-Click Hotmart) |
| `/obrigado` | **Página de Obrigado** (Onboarding VIP direto no WhatsApp) |

---

## 🎬 Como Plugar seu Vídeo (VSL)

No arquivo `index.html`, localize a linha com `<!-- [ÁREA DO VÍDEO / VSL] -->`:
- **VTurb**: Descomente o bloco do VTurb e insira o seu ID de vídeo.
- **Panda Video**: Cole seu iframe do Panda Video.
- **YouTube**: Cole seu iframe do YouTube com proporção 9:16 ou 16:9.
- Em seguida, apague ou comente a `<div class="video-placeholder-box" id="video-placeholder">`.

---

## 🎯 Pixels e Rastreamento

Todos os rastreadores de terceiros antigos foram removidos.
No `<head>` de `index.html`:
- **Facebook Pixel**: Descomente o script e substitua `SEU_NOVO_PIXEL_ID`.
- **UTMify**: Descomente a chamada do script oficial do seu UTMify.
