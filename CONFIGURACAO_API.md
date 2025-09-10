# 🔑 Configuração da API OpenAI - PROCESS MIND

## 📋 Pré-requisitos

1. **Conta OpenAI**: Crie uma conta em [platform.openai.com](https://platform.openai.com)
2. **Chave da API**: Gere uma chave em [API Keys](https://platform.openai.com/api-keys)
3. **Créditos**: Adicione créditos à sua conta OpenAI

## ⚙️ Configuração Local

### Método 1: Variável de Ambiente (Recomendado)

```bash
# Linux/Mac
export OPENAI_API_KEY="sk-sua_chave_aqui"
streamlit run process_mind_melhorado.py

# Windows
set OPENAI_API_KEY=sk-sua_chave_aqui
streamlit run process_mind_melhorado.py
```

### Método 2: Arquivo .env

```bash
# 1. Copie o arquivo de exemplo
cp .env.example .env

# 2. Edite o arquivo .env
nano .env

# 3. Adicione sua chave:
OPENAI_API_KEY=sk-sua_chave_aqui

# 4. Execute com as variáveis
source .env && streamlit run process_mind_melhorado.py
```

## 🔒 Segurança

### ✅ **FAÇA:**
- Use variáveis de ambiente
- Mantenha o arquivo `.env` no `.gitignore`
- Nunca commite chaves no código
- Use chaves com permissões limitadas

### ❌ **NÃO FAÇA:**
- Hardcode chaves no código
- Commite arquivos `.env`
- Compartilhe chaves publicamente
- Use chaves de produção em desenvolvimento

## 🚀 Verificação

Quando configurado corretamente, você verá:
- ✅ **Sidebar**: "ChatGPT configurado e funcionando!"
- 🤖 **Chat**: Respostas com badge "ChatGPT + Dados Reais"

## 🔧 Troubleshooting

### Erro: "ChatGPT não configurado"
- Verifique se a variável `OPENAI_API_KEY` está definida
- Confirme se a chave está correta (começa com `sk-`)
- Instale a biblioteca: `pip install openai`

### Erro: "Quota exceeded"
- Adicione créditos à sua conta OpenAI
- Verifique limites de uso em [Usage](https://platform.openai.com/usage)

### Erro: "Invalid API key"
- Gere uma nova chave em [API Keys](https://platform.openai.com/api-keys)
- Verifique se copiou a chave completa

## 💡 Fallback Inteligente

Se a API não estiver configurada, o sistema usa:
- ✅ **Respostas locais** baseadas nos dados reais
- ✅ **Análise de PDFs** funcionando
- ✅ **Todas as funcionalidades** mantidas

O ChatGPT é um **enhancement**, não um requisito!

