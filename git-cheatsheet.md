# 📘 Git Cheatsheet -- Projetos de Análise de Dados

## 🔀 Configuração inicial da branch

Quando o Git cria `master` em vez de `main`, rodar:

``` bash
git branch -M main
```

------------------------------------------------------------------------

## 🔎 Verificar status

Ver os arquivos modificados, novos ou deletados:

``` bash
git status
```

------------------------------------------------------------------------

## ➕ Adicionar arquivos

-   Todos os arquivos:

    ``` bash
    git add .
    ```

-   Pasta específica:

    ``` bash
    git add Biblioteca_Pandas/
    ```

-   Arquivo específico:

    ``` bash
    git add analise_dados_SEEG.ipynb
    ```

------------------------------------------------------------------------

## 📝 Criar commit

Usar mensagens claras e objetivas.\
Alguns exemplos para os projetos de análises de dados:

-   **Novo notebook**

    ``` bash
    git commit -m "Adiciona notebook de análise de emissões por estado"
    ```

-   **Atualização de análises**

    ``` bash
    git commit -m "Atualiza gráficos de emissões por setor"
    ```

-   **Correção**

    ``` bash
    git commit -m "Corrige cálculo de médias em notebook"
    ```

-   **Organização**

    ``` bash
    git commit -m "Reorganiza pastas de exercícios"
    ```

------------------------------------------------------------------------

## 🚀 Enviar para o GitHub

``` bash
git push origin main
```

------------------------------------------------------------------------

## ✅ Fluxo rápido (passo a passo)

Sempre que eu modificar o projeto:

``` bash
git branch -M main       # Garante branch correta
git status               # Verifica alterações
git add .                # Adiciona todos os arquivos
git commit -m "Mensagem" # Cria commit
git push origin main     # Envia para o GitHub
```
