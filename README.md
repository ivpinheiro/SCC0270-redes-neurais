# SCC0270-redes-neurais

Repositório com os projetos da disciplina **SCC0270 - Redes Neurais e Aprendizado Profundo**, oferecida pelo ICMC - USP São Carlos, 2025.

## Configurando o projeto

Este projeto utiliza o gerenciador de ambientes e dependências [`uv`](https://github.com/astral-sh/uv).  
Para configurar o ambiente corretamente, siga os passos abaixo:

### 1. Instale o `uv`

Se ainda não tiver o `uv` instalado, execute:

```bash
curl -Ls https://astral.sh/uv/install.sh | bash
```

### 2. Crie e sincronize o ambiente virtual

Para criar um ambiente virtual e instalar todas as dependências listadas no `pyproject.toml`, execute:

```bash
uv sync
```

Este comando cria automaticamente o ambiente virtual e instala as bibliotecas necessárias.

---

## Projetos

### Projeto 01

- **Prazo:** 26/06/2025

O objetivo do Projeto 01 é construir um classificador binário capaz de classificar as imagens como `CT` (Tomografia Computadorizada) ou `MR` (Ressonância Magnética).  
Como modelo baseline, serão utilizados descritores de textura e imagem clássicos para a construção do classificador.

Na etapa seguinte, será realizado o *fine-tuning* de um modelo pré-treinado de visão computacional para melhorar o desempenho da classificação.

---

### Projeto 02

- **Prazo:** 07/07/2025

(Descrição será adicionada em breve.)

---

### Projeto 03

- **Prazo:** 11/06/2025

(Descrição será adicionada em breve.)
