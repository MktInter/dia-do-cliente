# Assets do e-mail

Extraídos do export do Claude Design (`Email_Semana_do_Cliente_-_Inter_Risk.html`),
que embute as imagens em base64 no bundle.

| Arquivo | Dimensão | Exibição | Peso | Uso |
|---|---|---|---|---|
| `hero-1200x520.jpg` | 1200 × 520 | 600 × 260 | 84 KB | Hero — Inter Experience |
| `faixa-garantia-1200x400.jpg` | 1200 × 400 | 600 × 200 | 21 KB | Faixa entre os blocos 01 e 02/03 |
| `interrisk-logo-branco.png` | 230 × 110 | 115 × 55 (header) e 96 × 46 (rodapé) | 5 KB | Logo branco, fundo transparente |

As duas fotos vieram do bundle como PNG (1,2 MB somados) e foram convertidas para
JPEG progressivo (q82) — o canal alfa era totalmente opaco, então a conversão não
perdeu transparência. O logo continua PNG, porque usa transparência de verdade.
Total do disparo: 133 KB.

## Antes de disparar

Clientes de e-mail exigem URLs absolutas: troque `img/...` pela URL pública do
CDN/ESP. E preencha:

- `https://SEU-DOMINIO.com.br/contato` — destino do CTA
- `[RAZÃO SOCIAL COMPLETA]`, CNPJ e endereço no rodapé
- `%%unsubscribe_link%%` e `%%webversion_link%%` — merge tags do ESP

---

## v3 (Semana do Cliente — diagramação nova)

| Arquivo | Dimensão | Exibição | Peso | Uso |
|---|---|---|---|---|
| `foto-inter-experience-1200x400.jpg` | 1200 × 400 | 600 × 200 | 114 KB | Foto full-bleed no fim |
| `interrisk-logo-branco.png` | 230 × 110 | 96 × 46 | 5 KB | Logo dentro do painel navy |

A v3 usa só duas imagens. O hero de 1200×520 saiu, e a foto do Inter Experience
passou a ser a versão **colorida** — não é a mesma faixa da v2, que era duotone.
Veio do bundle como PNG de 1,1 MB e foi convertida para JPEG progressivo q82.

O logo da v3 é byte a byte igual ao da v2.
