# internship
Allows user to upload PDF documents and ask questions regarding the content of these documents.


if you face error like: ModuleNotFoundError: No module named 'models'

>> cd app
>> set PYTHONPATH=file-path\Project\pdf-question-app-backend
python main.py


to start server you should be under app

uvicorn app.main:app --reload
