FROM python:3.13.0a4
WORKDIR /app

# Gerekli bağımlılıkları kopyala ve yükle
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8000
# Uygulamayı çalıştır
CMD ["python", "views.py"]





