# Bancos do trem — 3º1 e 3º2

Professor Natanael · EETI Bilíngue Profª. Jacimar Da Silva Gama · atividade remota de 15/10/2026.

- `index.html`: atividade dos alunos, na ordem A → B → C.
- `professor.html`: painel protegido, usando a mesma conta confirmada do professor da atividade anterior.
- `entregas.html`: consulta pública de recebimento, sem respostas ou notas.

As entregas só ficam confirmadas após resposta positiva do servidor. Rascunhos e comprovantes ficam no navegador; reenvios idênticos não duplicam a entrega.
O painel apresenta primeiras respostas e tentativas posteriores. O Supabase existente é compartilhado, mas os dados desta atividade ficam nas tabelas `bancos1510_alunos` e `bancos1510_entregas`, acessadas pela função `atividade-bancos1510`.
As tabelas e a função de permutação não foram alteradas. `config.js` contém apenas configuração pública; nunca publique chaves secretas.

GitHub Pages: branch `main`, pasta `/`.
