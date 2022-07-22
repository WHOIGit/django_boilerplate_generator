FROM python
WORKDIR /app
RUN apt-get update && apt-get install --no-install-recommends -y \
  # dependencies for building Python packages
  build-essential \
  # psycopg2 dependencies
  libpq-dev \
  python3-pip

RUN pip install "cookiecutter>=1.7.0"