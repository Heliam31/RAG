# RAG

## Introduction
ce repo est un RAG en python créant et remplissant une base de données vectorielle ChromaDB de données de documents fournis en entrée, puis répondant à des questions concernant ces documents.

## Structure

* get_embedding_function.py : changer la fonction d'embedding, notament passer d'un modèle local avec ollama, à un modèle en ligne.
* populate_database.py : créer la db si besoin et la remplir avec les données des documents, ou l'update si ajout de nouveaux documents
* query_data.py : poser une question au RAG
* requirements.txt : à pip install
* test_rag.py : teste l'efficacité des données que l'on a

## Lancement

### ollama :  
* Installer ollama  
* ollama pull llama2  
* ollama pull mistral  
* ollama pull nomic-embed-text
* ollama serve  
  
* ollama list  
* go to localhost:11434

  
* Créer un venv
* pip install -r requirements.txt

### Database
* mettre ses documents dans un dossier data à la racine du projet
* lancer le script populate_database.py
  
### RAG
* lancer le script query_rag.py
* poser sa question
  
## TODO



