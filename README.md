# profeta-instagram-midia

Repositório de mídia pública (imagens) do pipeline
[profeta-instagram](https://github.com/rafaelnicolaevsky/profeta-instagram) —
hospeda os slides gerados como URLs consumíveis via
`raw.githubusercontent.com` pela Instagram Graph API (que exige
`image_url` público, não aceita upload de arquivo local).

As imagens ficam em `posts/<identificador_execucao>/slide-N.png`, uma
pasta por execução — ver `scripts/utils/hospedagem_midia.py` no repo
principal.
