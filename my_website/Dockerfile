FROM python:3.12.1
WORKDIR /app

# Gerekli bağımlılıkları kopyala ve yükle
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8000
# Uygulamayı çalıştır
CMD ["python", "views.py"]





