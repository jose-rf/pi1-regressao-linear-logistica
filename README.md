# Como Rodar o Projeto

Este projeto contém dois modelos de **Aprendizado de Máquina Supervisionado**:
- **Regressão Linear**: Previsão de preço de imóveis
- **Regressão Logística**: Detecção de churn de clientes

Você pode executar o código de duas formas: **no Google Colab (online)** ou **na sua máquina local**.

---

## Opção 1: Google Colab (Recomendado para Iniciantes)

### Vantagens
- Sem instalação
- Todas as bibliotecas já inclusas
- Ideal para compartilhar e entregar o PI1

### Passo a Passo

1. Acesse: [https://colab.research.google.com](https://colab.research.google.com)
2. Clique em **"Novo notebook"**
3. Crie duas células de código:
   - **Célula 1**: Cole o código da **Regressão Linear**
   - **Célula 2**: Cole o código da **Regressão Logística**
4. Execute com `Shift + Enter` ou vá em **"Ambiente de execução" → "Executar tudo"**
5. Salve:
   - `Arquivo` → `Salvar uma cópia no Drive`
   - Renomeie para: `PI1_Aprendizado_Supervisionado.ipynb`
6. Compartilhe:
   - Clique em **"Compartilhar"** → Gere um link com permissão de visualização

---

## Opção 2: Máquina Local (PC ou Notebook)

### Requisitos
- Python 3.8 ou superior
- Editor: VS Code, PyCharm, Jupyter ou Thonny

### Passo a Passo

```bash
# 1. Crie a pasta do projeto
mkdir PI1_ML_Supervisionado
cd PI1_ML_Supervisionado

# 2. Crie e ative um ambiente virtual
python -m venv venv

# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate

# 3. Instale as dependências
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
