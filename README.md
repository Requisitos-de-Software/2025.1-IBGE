## Guia para Executar o MKDocs Localmente

Este manual detalha os passos para configurar e executar o MKDocs localmente, permitindo que você visualize e trabalhe na documentação do projeto antes de enviar suas contribuições.

### 1. Clonando o Repositório

Primeiro, você precisa clonar o repositório do projeto para sua máquina local. Utilize o seguinte comando no seu terminal:

```bash
git clone https://github.com/Requisitos-de-Software/2025.1-Grupo05.git
```

Este comando criará uma cópia do repositório na sua máquina, permitindo que você acesse e modifique os arquivos.

### 2. Instalando as Dependências

Para garantir que o MKDocs funcione corretamente, você precisa instalar as dependências necessárias. Recomenda-se criar um ambiente virtual para isolar as dependências do projeto do seu ambiente global do Python.

#### Criando um Ambiente Virtual (venv)

Execute o seguinte comando para criar um ambiente virtual chamado `venv`:

```bash
python3 -m venv venv
```

#### Ativando o Ambiente Virtual

* **No Linux:**

    ```bash
    source venv/bin/activate
    ```

* **No Windows:**

    ```bash
    venv\Scripts\activate
    ```

Após a ativação, o nome do ambiente virtual (`venv`) deve aparecer no seu terminal, indicando que o ambiente está ativo.

#### Instalando as Dependências do Python

Com o ambiente virtual ativado, instale as dependências listadas no arquivo `requirements.txt` usando o pip:

```bash
pip install -r requirements.txt
```

#### Instalando Dependências do Node

É necessário instalar as dependências do node, para isso, execute o comando:

```bash
npm install
```

### 3. Executando o MKDocs Localmente

Finalmente, para visualizar a documentação do projeto no seu navegador, execute o seguinte comando:

```bash
mkdocs serve
```
