FROM python:3.12.3
WORKDIR /smart_home
EXPOSE 8000
COPY . .
RUN pip install --no-cache-dir -r requirements.txt
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
