# Sistema de Controle de Estoque em Python

## Sobre o Projeto

Este projeto foi desenvolvido como atividade da disciplina de **Programação de Computadores** do curso de **Análise e Desenvolvimento de Sistemas**.

O sistema tem como objetivo auxiliar no gerenciamento de estoque, permitindo cadastrar produtos, consultar informações, controlar entradas e saídas de mercadorias e calcular o valor total armazenado.

Todo o sistema foi desenvolvido em **Python** utilizando conceitos fundamentais de programação, como funções, listas, dicionários, estruturas condicionais, laços de repetição e tratamento de exceções.

---

## Funcionalidades

* Cadastro de produtos
* Listagem de produtos cadastrados
* Busca de produtos por nome
* Edição de produtos
* Remoção de produtos
* Entrada de estoque
* Saída de estoque
* Cálculo do valor total do estoque
* Alerta para produtos com estoque baixo
* Tratamento de erros para entradas inválidas

---

## Tecnologias Utilizadas

* Python 3

---

## Estrutura dos Dados

Cada produto é armazenado em um dicionário com as seguintes informações:

```python
{
    "nome": "Arroz",
    "preco": 25.90,
    "estoque": 10
}
```

Todos os produtos são armazenados em uma lista chamada `produtos`.

---

## Como Executar

1. Instale o Python 3 em seu computador.
2. Faça o download ou clone este repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

3. Acesse a pasta do projeto:

```bash
cd seu-repositorio
```

4. Execute o programa:

```bash
python estoque.py
```

---

## Menu do Sistema

```text
1 - Cadastrar Produto
2 - Listar Produtos
3 - Remover Produto
4 - Editar Produto
5 - Buscar Produto
6 - Adicionar Estoque
7 - Remover Estoque
8 - Valor Total do Estoque
9 - Estoque Baixo
0 - Sair
```

---

## Conceitos Aplicados

Durante o desenvolvimento deste projeto foram utilizados:

* Variáveis e tipos de dados
* Listas
* Dicionários
* Funções
* Estruturas condicionais (`if`, `elif`, `else`)
* Estruturas de repetição (`for` e `while`)
* Tratamento de exceções (`try` / `except`)
* Organização e modularização de código

---

## Objetivo Acadêmico

Este projeto foi desenvolvido para aplicar os conhecimentos adquiridos na disciplina de Programação de Computadores, demonstrando a utilização prática dos principais conceitos da linguagem Python.

---

## Autor

**Eduardo Guedes Lopes Mota**

**RGM:** 40511871

**Curso:** Análise e Desenvolvimento de Sistemas
