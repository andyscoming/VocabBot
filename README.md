# VocabBot

Bot for vocabulary.com. Runs off GPT-3.5 AI model and selenium. Has a pretty high success rate, when the bot doesn't know what the answer is, it will guess until completion. Can take up to 30 seconds per question however.

You must create a ChatGPT account in order to use the bot.

To use, find your session token or username and password for ChatGPT and put them in the config.json

If you registered with Google, you must use session token.

{
"email":"{email}"
"password":"{password}"
}

or

{
"session_token":"{session_token}"
}

You can find your session token by going to ChatGPT, inspect -> application -> cookies -> https://chat.openai.com/ -> __Secure-next-auth.session-token