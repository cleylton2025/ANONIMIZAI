# AnonimizAI

**Desenvolvida por Cleylton Mendes**

AnonimizAI é uma aplicação web local para anonimização de documentos jurídicos, focada inicialmente em arquivos .docx. A ferramenta permite que advogados e departamentos jurídicos removam ou mascarem dados pessoais e sensíveis de documentos antes de utilizá-los em ferramentas de IA, garantindo conformidade com a LGPD e o Código de Ética da OAB.

## Funcionalidades

- Upload de arquivos .docx
- Detecção automática de dados sensíveis (CPF, nome, telefone, e-mail, RG)
- Anonimização configurável (mascaramento, pseudonimização, etc.)
- Processamento 100% local (nenhum dado é enviado para servidores externos)
- Download do .docx anonimizado
- Backup criptografado do original
- Relatório simples de anonimização

## Tecnologias

- **Backend:** Python 3, Flask, python-docx, cryptography
- **Frontend:** React, Material UI

## Como rodar localmente

### Pré-requisitos

- Python 3.8+
- Node.js 16+
- Git

### Passos

1. Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/anonimizai.git
    cd anonimizai
    ```

2. Instale as dependências do backend:
    ```bash
    cd backend
    python -m venv venv
    source venv/bin/activate  # ou venv\Scripts\activate no Windows
    pip install -r requirements.txt
    ```

3. Inicie o backend:
    ```bash
    python app.py
    ```

4. Em outro terminal, instale as dependências do frontend:
    ```bash
    cd frontend
    npm install
    ```

5. Inicie o frontend:
    ```bash
    npm start
    ```

6. Acesse a aplicação em [http://localhost:3000](http://localhost:3000)

## Estrutura do Projeto
