# Peru a Dois

Mini app para o casal planejar a viagem ao Peru (set/2027), a partir do documento "Peru 2027 — roteiros de 10 dias e orçamento".

- **Cards**: ~100 passeios, trilhas, cidades, bairros, hotéis, restaurantes, pratos, lojas e feiras. Nota de 0 a 10 ou arrastar (direita = quero, esquerda = pode cortar).
- **Duelos**: 24 comparações diretas (roteiro A × B, Humantay × Vinicunca, trens, hotéis, ritmo, orçamento, datas).
- **Match**: os dois amam, divergências, os dois topam, podem cortar.
- **Roteiros**: os roteiros A, B e C do plano ajustados pelas notas (dia livre, trem, hotel especial, encaixes), com custo estimado, dia a dia e o que fica de fora.
- **Chat**: conversa entre os dois, com o Claude respondendo e propondo ajustes aplicáveis.

É um único `index.html`, publicado como Artifact no claude.ai (usa as capacidades `db`, `user`, `sample` e `assets`). Aberto fora do claude.ai, funciona em modo local (sem sincronizar).
Preços são estimativas para o casal em R$ de 2026; as capas são ilustrações geradas por código.
