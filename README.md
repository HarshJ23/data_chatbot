
# custom-data_chatbot
A chatbot where you can chat with your own custom data just like ChatGPT.


## Environment Variables

To run this project, you will need to add the following environment variables to your .env.local file in root directory

`OPENAI_API_KEY`

`PINECONE_API_KEY`

`PINECONE_ENVIRONMENT`



You can setup OpenAI API and pinecone by referring the below mentioned links

[OpenAI API key setup](https://platform.openai.com/docs/api-reference)

[Pinecone](https://app.pinecone.io/)


## Add the project on your device

Clone the project with this command

```bash
  git clone https://github.com/HarshJ23/data_chatbot
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```




## Add custom data
In ./documents folder in root directory, create a .txt file having your own custom data. make sure to convert pdf/docx etc. type of files to .txt and add it.
## Run the app
Start the server

```bash
  npm run dev
```
Now you should be able to ask questions and get desired response from the bot from your own custom data.
