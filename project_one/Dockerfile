# Usa uma imagem base de Python
FROM python:3.10

# Define o diretório de tabalho dentro do container
WORKDIR /app

# Copie o arquivo de requisitos
COPY requirements.txt .

# Instale as dependências
RUN pip install -r requirements.txt

# Copie todo o código de aplicação para o container
COPY . .

# Defina a porta exposta
EXPOSE 5000

# Comando para rodar a aplicação
CMD ["python", "app/main.py"]