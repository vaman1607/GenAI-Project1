Our goal is to create a Reader Digest of the internet.
We shall pass a web url to openai and get the summarization of the contents

Steps:
1. Scrape the url and parse it using BeautifulSoup.
2. Connect to openai using openai key
3. Create messages with system and user prompts to provide instructions to the model
4. Bring together messages and openai to produce required output.

Prerequisites:
Create and OpenAI apikey from https://platform.openai.com/
store the apikey under .env
create ba python virtual environment
