# API de Chamados de Suporte

## 1. Estudante
Rubens Paulo Rodrigues Parente

## 2. Objetivo do Projeto
Criar a estrutura inicial da API de chamados de suporte, reproduzindo o desenvolvimento apresentado na videoaula “Criando a primeira API com Flask”.

## 3. Como Instalar as Dependências
Com o `uv` instalado no ambiente, sincronize e instale as dependências a partir do `uv.lock` executando:

```bash
uv sync --locked
```

## 4. Como Executar a Aplicação
Para iniciar a aplicação Flask (incluindo no GitHub Codespaces), execute:

```bash
uv run flask --app app run --host=0.0.0.0 --port=5000
```

## 5. Como Acessar a Rota Inicial e Resposta Esperada
Com o servidor rodando, acesse a rota inicial `GET /` pelo navegador em `http://localhost:5000/` ou pelo terminal com:

```bash
curl -i http://localhost:5000/
```

Resposta esperada:
- **Código HTTP:** `200 OK`
- **Cabeçalho `Content-Type`:** `application/json`
- **Corpo da resposta (JSON):**

```json
{
  "mensagem": "API de chamados em funcionamento"
}
```