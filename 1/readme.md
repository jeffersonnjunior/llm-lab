## 📌 Classificação de E-mails com LLM

### 🧩 O Problema
A equipe de atendimento precisa classificar a urgência e o sentimento de milhares de e-mails de clientes diariamente.

### 🚧 O Desafio
Construir um script em Python que consuma uma API de LLM.

O script deve:
- Enviar um texto não estruturado simulando uma reclamação de cliente
- Forçar o modelo a retornar **exclusivamente um JSON válido** no seguinte formato:

```json
{
  "sentimento": "positivo/negativo",
  "urgencia": 1-5,
  "resumo_curto": "..."
}
```
