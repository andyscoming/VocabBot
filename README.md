# VocabBot

Bot for vocabulary.com. Runs off GPT-3.5 AI model and selenium. Has a pretty high success rate, when the bot doesn't know what the answer is, it will guess until completion. Can take up to 30 seconds per question however.

You must create a ChatGPT account in order to use the bot.

To use, find your access token for ChatGPT and put them in the config.json

{
"acess_token":"{token}"
}

To find your access token, login to your ChatGPT account on a browser, go to https://chat.openai.com/api/auth/session and copy the the "accessToken" value.

