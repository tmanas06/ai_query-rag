# ai_query-rag
This is a repository for a chatbot that uses rag + openai's ai and postgresql to answer questions about the data in the postgresql database.

when we run the application in the website we get the option of uploading a csv, when we upload a csv the file directly gets uploaded in the postgresql database and the schema of the table is also stored in the TABLE_SCHEMA table.

then we can ask questions about the data in the postgresql database and the chatbot will answer the questions using rag + openai's ai.


# Architecture

![Architecture](architecture.png)

# Usage

1. Run the server
2. Run the ui
3. Upload a csv file
4. Ask a question about the data

# Steps

## Clone the repository

```bash 
   git clone https://github.com/tmanas06/ai_query-rag
```

## Server

```bash
   cd server
   npm install
   npm run dev
```

## UI

```bash
   cd ui
   npm install
   npm run dev
```
