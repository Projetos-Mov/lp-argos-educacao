# LP ARGOS Educação — Método VQM

Landing page de captação de matrículas para escolas, faculdades e cursos preparatórios.
HTML único, sem build: `index.html` + `assets/`.

**No ar:** https://projetos-mov.github.io/lp-argos-educacao/

## Estrutura

- `index.html` — página inteira (CSS e JS inline)
- `assets/` — fotos em WebP + JPG de fallback e a marca
- `serve.py` — servidor local em `http://127.0.0.1:4327` para desenvolvimento

## Antes de rodar tráfego

1. `ENDPOINT` (no fim do `index.html`): URL do webhook que recebe o formulário.
   Vazio = fallback que abre o WhatsApp com o briefing preenchido.
2. `WHATS`: número que recebe esse fallback — hoje está com o placeholder `5500000000000`.

## Método VQM

Volume → Qualificação → Matrículas. O gradiente azul→verde é a representação do método
e deve aparecer sempre da mesma forma (componente `.vqm`).
