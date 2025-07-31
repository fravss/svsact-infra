# svsact-infra


---

## 🐳 Rodando com Docker Compose

Antes de tudo, certifique-se de ter:

- [Docker](https://www.docker.com/get-started)  instalado.

### 🔧 1. Geração do `.jar`

>  Eexecute manualmente no projeto backend:
```bash
cd ../backend
mvn clean package

````
### Suba os containers:
```bash
docker-compose up --build

````
