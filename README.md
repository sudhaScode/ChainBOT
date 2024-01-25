# chainBOT
./requirements.txt for the packages use in this application
load the api key by the load_dotenv("path/to/.env")

Working flow:
Load and read the pdf available in documents folder
splite the text into chuncks
Use OpenAIEmbeddings to load chuncks into Vector database pinecone-client
