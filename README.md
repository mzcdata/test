# mtc-azure-openai-back

### App Spec

- Python 3.10
- FastAPI
- Azure App Service

### App Start

```bash
# Started App
python -m venv venv
source venv/Script/activate
pip install -r requirements.txt
# pip install fastapi uvicorn azure-search-documents azure-storage-blob faiss-cpu python-dotenv langchain openai python-multipart tiktoken

# Library 추가시
# pip freeze > requirements.txt

# FaskAPI 시작
uvicorn main:app
# 새로고침
uvicorn main:app --reload
```

### Swagger Doc

- http://localhost:8000/docs
