# Analise DeepRacer

Esse repositório é dedicado aos alunos de INF2070 para se abtuarem com o deepracer-utils, uma biblioteca Python que facilita a analise de modelos do AWS DeepRacer.


## Setup

Não é necessário usar o **uv** mas é recomendado. Se quiser instalar use:

**Windows:**
```powersheel
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

**Linux/MacOS:**
```bash
curl -sSL https://astral.sh/uv/install.sh | bash
```

### Usando UV

**Instale as dependências do projeto:**
```bash
uv sync
```
**Execurtando o projeto**
```bash
uv run --with jupyter jupter lab
```

### Sem usar UV
**Crie um ambiente virtual:**
```bash
python -m venv venv
```
**Ative o ambiente virtual:**
- Windows:
```powershell
.\venv\Scripts\activate
```
- Linux/MacOS:
```bash
source venv/bin/activate
```
**Instale as dependências do projeto:**
```bash
pip install -r requirements.txt
```
**Inicie o Jupyter Lab:**
```bash
jupyter lab
```
