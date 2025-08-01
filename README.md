# svsact-infra


---

## 🐳 Rodando com Docker Compose

Antes de tudo, certifique-se de ter:

- [Docker](https://www.docker.com/get-started)  instalado.

  e

- [Maven](https://maven.apache.org/install.html) (para gerar o arquivo `.jar`)

  **Importante:**  
Certifique-se de que o Maven esteja instalado e que o comando `mvn` esteja disponível no seu PATH. Caso contrário, o comando para gerar o `.jar` não funcionará. 


### 🔧 1. Geração do `.jar`

>  Eexecute manualmente no projeto backend:
```bash
cd backend
mvn clean package -DskipTests

````
### Suba os containers:
```bash
docker-compose up --build

````
