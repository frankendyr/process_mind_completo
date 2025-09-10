# 🏛️ PROCESS MIND - Sistema Integrado de Gestão Municipal

Sistema completo de gestão municipal com dados reais e ChatGPT integrado.

## 🚀 Instalação e Execução

### 1. Dependências
```bash
pip install streamlit pandas plotly PyPDF2 requests folium streamlit-folium openai
```

### 2. Configurar ChatGPT (Opcional)
```bash
# Método 1: Variável de ambiente
export OPENAI_API_KEY="sk-sua_chave_aqui"

# Método 2: Arquivo .env
cp .env.example .env
# Editar .env com sua chave
source .env
```

### 3. Executar
```bash
streamlit run process_mind_melhorado.py
```

## 🔑 Credenciais de Teste

- **Guaraciaba do Norte - CE**: admin@guaraciaba.ce.gov.br / admin123
- **Nísia Floresta - RN**: admin@nisiafloresta.rn.gov.br / admin123  
- **Santa Quitéria - MA**: admin@santaquiteria.ma.gov.br / admin123
- **São Bernardo - MA**: admin@saobernardo.ma.gov.br / admin123

## 📊 Módulos Disponíveis

- **🏥 Saúde**: Estabelecimentos reais do CNES + dados simulados
- **🎓 Educação**: Escolas e indicadores educacionais
- **🚔 Segurança**: Unidades de segurança e criminalidade
- **👥 Demografia**: Dados populacionais baseados no IBGE
- **🤖 ChatBot**: Assistente inteligente com análise de PDF

## 🎯 Características

- ✅ **Dados híbridos**: Reais (CNES, IBGE) + Simulados (claramente identificados)
- ✅ **Multi-município**: Sistema escalável para múltiplas cidades
- ✅ **ChatGPT integrado**: Com fallback inteligente
- ✅ **Mapas interativos**: Folium para visualizações geográficas
- ✅ **Gráficos profissionais**: Plotly para dashboards
- ✅ **Seguro para GitHub**: Variáveis de ambiente e .gitignore

## 📁 Arquivos

- `process_mind_melhorado.py` - Aplicação principal
- `.env.example` - Template de configuração
- `.gitignore` - Arquivos ignorados pelo Git
- `CONFIGURACAO_API.md` - Guia detalhado da API
- `README.md` - Este arquivo

**Sistema pronto para produção e GitHub!** 🏛️✨

