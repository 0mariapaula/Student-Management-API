## API de Alunos

Uma API RESTful para gerenciamento de alunos, desenvolvida como estudo para certificação em Backend e APIs. Utiliza Python, FastAPI e Pydantic para garantir performance, validação de dados e facilidade de uso.

---

### Tecnologias Utilizadas

- **Python 3.8+**
- **FastAPI** — Framework web moderno e rápido
- **Pydantic** — Validação e tipagem de dados
- **Uvicorn** — Servidor ASGI para execução da API

---

### Instalação das Dependências

1. Clone o repositório e acesse a pasta do projeto:
	```bash
	git clone <url-do-repositorio>
	cd Api-ALUNOS
	```
2. (Opcional) Crie e ative um ambiente virtual:
	```bash
	python -m venv venv
	# Ative no Windows:
	venv\Scripts\activate
	# Ou no Linux/Mac:
	source venv/bin/activate
	```
3. Instale as dependências:
	```bash
	pip install -r requirements.txt
	```

---

### Como Rodar o Servidor

Execute o comando abaixo na raiz do projeto para iniciar a API:

```bash
uvicorn app.main:app --reload
```

Acesse a documentação interativa em: [http://localhost:8000/docs](http://localhost:8000/docs)

---

### Principais Rotas da API

| Método | Endpoint         | Descrição                  |
|--------|------------------|----------------------------|
| GET    | /alunos          | Lista todos os alunos      |
| GET    | /alunos/{id}     | Busca aluno por ID         |
| POST   | /alunos          | Cria um novo aluno         |
| PUT    | /alunos/{id}     | Atualiza dados do aluno    |
| DELETE | /alunos/{id}     | Remove um aluno            |

---

### Observações

- A API segue boas práticas REST.
- Utilize a documentação automática do FastAPI para testar as rotas.

---

> Desenvolvido para fins educacionais e aprimoramento técnico em Backend.