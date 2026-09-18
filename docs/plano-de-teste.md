# Plano de Teste — OrangeHRM Login

## 1. Identificação

**Projeto:** Testes da funcionalidade de Login — OrangeHRM  
**Tipo de teste:** Teste funcional manual  
**Aplicação:** OrangeHRM Demo  
**Módulo:** Login  
**Responsável pelos testes:** Karoliny Carvalho

---

## 2. Objetivo

Validar o comportamento da funcionalidade de login da aplicação OrangeHRM, verificando se o sistema permite o acesso de usuários com credenciais válidas e apresenta o comportamento esperado para diferentes combinações de dados inválidos ou ausentes.

---

## 3. Escopo

### Dentro do escopo

Os testes contemplam:

- Login com usuário e senha válidos;
- Login com senha inválida;
- Login com usuário inválido;
- Login com usuário e senha inválidos;
- Tentativa de login com os dois campos vazios;
- Tentativa de login com o campo de usuário vazio;
- Tentativa de login com o campo de senha vazio;
- Validação das mensagens apresentadas ao usuário;
- Validação do comportamento da interface durante as tentativas de login.

### Fora do escopo

Não fazem parte deste ciclo de testes:

- Funcionalidades internas após o login;
- Testes de performance;
- Testes de carga;
- Testes de API;
- Testes automatizados;
- Testes de banco de dados.

---

## 4. Estratégia de Teste

Os testes foram realizados manualmente, utilizando cenários positivos e negativos.

Foram utilizadas técnicas de teste baseadas em:

- Particionamento de Equivalência;
- Análise de valores e entradas válidas e inválidas;
- Testes positivos;
- Testes negativos;
- Validação de mensagens e comportamento da interface.

---

## 5. Cenários de Teste

Foram definidos os seguintes cenários:

| ID | Cenário |
|---|---|
| CT-LOGIN-01 | Login com senha inválida |
| CT-LOGIN-02 | Login com usuário inválido |
| CT-LOGIN-03 | Login com usuário e senha inválidos |
| CT-LOGIN-04 | Login com usuário e senha válidos |
| CT-LOGIN-05 | Login com os campos vazios |
| CT-LOGIN-06 | Login com usuário vazio |
| CT-LOGIN-07 | Login com senha vazia |

Os casos de teste detalhados estão disponíveis na pasta [`test-cases-manual`](../test-cases-manual/).

---

## 6. Dados de Teste

Foram utilizadas combinações de:

- Credenciais válidas;
- Credenciais inválidas;
- Usuário inválido;
- Senha inválida;
- Campos sem preenchimento.

Os dados utilizados têm finalidade exclusivamente acadêmica e de demonstração.

---

## 7. Evidências

As execuções dos testes foram registradas por meio de vídeos, disponíveis na pasta [`evidences/videos`](../evidences/videos/).

As evidências demonstram diferentes comportamentos da funcionalidade de login, incluindo:

- Login realizado com sucesso;
- Tentativa de login com credenciais inválidas;
- Tentativas de login com campos não preenchidos.

---

## 8. Critérios de Entrada

O ciclo de testes foi iniciado considerando:

- Aplicação disponível para acesso;
- Página de login acessível;
- Ambiente adequado para execução dos cenários;
- Dados necessários para realização dos testes disponíveis.

---

## 9. Critérios de Saída

O ciclo de testes é considerado concluído após:

- Execução dos cenários planejados;
- Registro dos resultados obtidos;
- Registro das evidências;
- Identificação e documentação de possíveis comportamentos inesperados.

---

## 10. Resultado

Foram elaborados e executados 7 casos de teste relacionados à funcionalidade de login.

Os resultados e evidências das execuções estão organizados no repositório para facilitar a análise do processo de teste.

---

## 11. Observações

Este projeto foi desenvolvido como prática de QA Manual, com o objetivo de aplicar conceitos de planejamento, elaboração de casos de teste, execução, registro de evidências e identificação de possíveis defeitos em uma aplicação web.
