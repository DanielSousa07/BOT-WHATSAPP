# BOT-INGLES-WHATSAPP

Bot para correção de inglês via WhatsApp usando Flask, OpenAI e gTTS.

## Como usar

1. Crie um arquivo `.env` com as variáveis do `.env.example`.
2. Instale as dependências:
3. Rode o servidor:
4. Configure seu webhook no Twilio para apontar para `http://seu_servidor:5001/webhook`

## Variáveis de ambiente

- `OPENAI_API_KEY`: Sua chave da API OpenAI.
- `TWILIO_ACCOUNT_SID`, `TWILIO_AUTH_TOKEN`, `TWILIO_PHONE_NUMBER`: Credenciais do Twilio.
- `NUMEROS_AUTORIZADOS`: Lista separada por vírgula dos números permitidos.
- `LIMITE_MENSAGENS`: Número máximo de mensagens por dia por usuário.

---

## Logs

Erros são registrados em `app.log`.# BOT-WHATSAPP
A bot'whatsapp for english class 
