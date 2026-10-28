# Controle Financeiro Revenda Mel

App da Mentoria Elite Apícola (Escola de Apicultura) para quem revende mel. O app reproduz as fórmulas da planilha "Controle Financeiro de Quem Revende Mel".

- **Site:** publicado pelo GitHub Pages a partir da branch `main`. É um arquivo só: `index.html`.
- **Login:** conta Google, pelo Firebase Authentication.
- **Dados:** Firestore, no caminho `users/{uid}/dados/`. São um documento `config` e um documento `lanc-AAAA-MM` por mês. Cada mentorado só lê e grava os próprios dados (veja `firestore.rules`).
- **Manutenção:** feita pelo Claude, que edita o `index.html` e publica com um commit na `main`. O GitHub Pages atualiza o site em cerca de 1 minuto.
