# API de Orçamento
Crie um API que permita criar, visualizar e editar orçamentos para serviços de computação em nuvem.

# Requisitos

Sua API deverá conter 3 entidades básicas:

  - Customer
  - Projeto
  - Orçamento
  - Grupo

**Customer:** Pode ter varios projetos associados.

**Projeto:** Possui um orçamento e deve conter informaçoes como: `id`, `nome`, `centro de custo` e `customer`

**Orçamento:** É composto por 12 meses. Cada mês possui um valor alocado. Esse valor pode ser em reais ou dólar.

**Grupo:** Contem vários projetos e possui informações como: `id` e `nome`.

**A API deve ser capaz de criar, ediar e exibir `projetos`, `orçamentos` e `grupos`**

**A API deve possuir autenticação utilizando JWT.**


# Avaliação

- Qualidade do código, legibilidade e simplicidade.

- Fique a vontade para tomar as decisões técnicas e arquiteturais que você quiser para o projeto, mas esteja preparado para justificar suas decisões.

- Testes automatizados.

- Manutenção e evolução da solução



# Dicas
- Documente sua solução explicando a estrutura e passos para executar localmente.
- Pense em escalabilidade e performance mas sem _overengineering_
- Gostamos de Docker. :)
- Use boas práticas de programação.
- Utilizar o inglês como padrão para funções, classes, commits e documentação é algo que nos deixa feliz.


# Perguntas frequentes

## Quais linguagens posso utilizar?

    - Go
    - Python
    - Javascript


## Posso utilizar frameworks/bibliotecas?

    Você pode usar frameworks e/ou bibliotecas desde que isso nao influencie no modo em que você deve arquitetar sua soluçao.

## Quanto tempo eu tenho disponível para desenvolver?

    Você tem o prazo de 1 semana

## Qual banco de dados posso usar ?

    Preferimos que seja utilizado algum banco de dados relacional. Utilizamos PostgreSQL

## Posso usar bibliotecas de ORM ?
    Gostarímos de poder avaliar os seus conhecimentos em SQL, portanto seria mais interessante escrever queries `raw`


## Boa sorte!!