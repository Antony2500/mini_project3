# Mini Project 3 GOITEENS

### Description:

This project created for new mini project with current functionality:
- Async API (FastAPI) with Uvicorn - **For buying and selling used items**
- Websocket integration **(Chat)**
- Include Database - Sqlite: **CRUD, Session Manager, Filtering**
- Pydantic - **For validation and serialization/deserialization **


### Project Structure 

```bash 
├───app
│   ├───api
│   │   ├───dependencies
│   │   └───routes
│   ├───models
│   ├───schemas
│   ├───services
│   └───utils

```

### How to run 

1. Clone repo -> ```git clone https://github.com/Antony2500/mini_project3.git```
2. Chose right dir -> ```cd miniproject```
3. Create venv -> ```bash python -m venv my_env```
4. Activate venv -> ```.\my_env\Scripts\activate```
5. Install requirements -> ```pip install -r requirements.txt```
6. Run server -> ```uvicorn app:main --port 8010```