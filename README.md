# Temove Guri — MVP

## O que está pronto
- `public/index.html`: cópia do arquivo de landing page enviado, preservada como referência visual.
- `/app`: área do aluno.
- Anamnese com objetivo, nível, distância atual, dias, prazo, rotina e observações.
- Geração de proposta via endpoint `/api/ai/generate-workout`.
- Integração opcional com OpenRouter usando modelo gratuito.
- Status obrigatório de revisão: `Treino gerado — aguardando aprovação do treinador`.
- Área do treinador com regeneração e aprovação.
- Estrutura para evolução do aluno.

## Rodar
1. `npm install`
2. copie `.env.example` para `.env`
3. sem chave, o sistema funciona em modo demo local;
4. com chave gratuita do OpenRouter, preencha `OPENROUTER_API_KEY`;
5. `npm start`
6. abra `/` para a landing e `/app` para a aplicação.

A chave fica somente no servidor. O treino gerado pela IA é uma proposta e deve ser revisado pelo professor antes da liberação.
