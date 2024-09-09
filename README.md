# django_nginx_websockets
This has a nginx which serves websockets
# Django environment settings
DEBUG=True
SECRET_KEY=your-secret-key
DJANGO_SUPERUSER_USERNAME=omkar
DJANGO_SUPERUSER_PASSWORD=yourpwd
DJANGO_SUPERUSER_EMAIL=yourmail


# Database settings
POSTGRES_DB=mydb
POSTGRES_USER=myuser
POSTGRES_PASSWORD=mypassword
POSTGRES_HOST=db
POSTGRES_PORT=5432

# Allowed hosts
ALLOWED_HOSTS=127.0.0.1,localhost,

# Redis Configuration
REDIS_URL=redis://redis:6379