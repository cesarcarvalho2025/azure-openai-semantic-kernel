# Azure OpenAI + Semantic Kernel

## 📌 Objetivo
Este repositório explora o desenvolvimento de aplicações práticas utilizando o **Azure OpenAI**, incluindo **chamadas de API** e **integração com o Semantic Kernel**.

## 🚀 Tecnologias Utilizadas
- Python
- Azure OpenAI API
- Semantic Kernel
- FastAPI (opcional)

## 📖 Estrutura do Projeto
- `src/` → Código-fonte principal
- `docs/` → Documentação e tutoriais
- `tests/` → Testes automatizados

## ⚙️ Instalação
```bash
git clone https://github.com/seu-usuario/azure-openai-semantic-kernel.git
cd azure-openai-semantic-kernel
pip install -r requirements.txt

## 📌 Como Rodar o Projeto
bash
Copiar
Editar
python src/app.py
🤖 Chamadas de API Exemplo
python
Copiar
Editar
import openai

client = openai.AzureOpenAI(
    api_key="SUA_CHAVE",
    azure_endpoint="SEU_ENDPOINT",
    api_version="2024-02-01"
)

response = client.chat.completions.create(
    model="SEU_MODELO",
    messages=[{"role": "user", "content": "Diga uma curiosidade sobre IA"}],
    temperature=0.7
)
print(response)
📌 Contribuição
Fork este repositório
Crie um branch (feature-nova)
Commit suas mudanças (git commit -m 'Nova feature')
Envie um Pull Request 🚀
yaml
Copiar
Editar

---

### 📌 **Subindo o Projeto no GitHub**
Agora, envie o projeto para o GitHub:

```bash
git add .
git commit -m "Inicializando o projeto Azure OpenAI + Semantic Kernel"
git branch -M main
git push origin main
