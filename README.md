
---

# 🏗️ **MICROSERVIÇOS**

---

## 📚 **A) O que é uma Arquitetura Monolítica?**

Uma arquitetura monolítica é uma abordagem onde todas as funcionalidades de um aplicativo são desenvolvidas e implantadas como uma única unidade. Isso pode levar a desafios em termos de escalabilidade, manutenção e atualização.

---

## 🔄 **B) O que Significa SPOF?**

SPOF significa **Single Point of Failure** (Ponto Único de Falha). É uma falha no sistema que pode causar a interrupção total do serviço, pois não há redundância ou backup para essa parte do sistema.

---

## ⚙️ **C) Por Que Entender/Aplicar o Conceito de Stateful x Stateless é Importante Antes de Escalar uma Aplicação?**

Entender se uma aplicação é **Stateful** (com estado) ou **Stateless** (sem estado) é crucial para escalabilidade. **Stateful** requer que o estado seja mantido entre requisições, o que pode complicar o escalonamento, enquanto **Stateless** permite que cada requisição seja independente, facilitando a escalabilidade.

---

## ↔️ **D) O Que é Escalabilidade Horizontal?**

Escalabilidade horizontal refere-se à adição de mais máquinas ou instâncias para distribuir a carga de trabalho. Isso permite que o sistema lide com mais tráfego e dados sem modificar o hardware existente.

---

## ⬆️ **E) O Que é Escalabilidade Vertical?**

Escalabilidade vertical envolve a adição de mais recursos (CPU, RAM, etc.) a uma única máquina para aumentar seu desempenho. Isso pode melhorar o desempenho, mas tem limites físicos e pode levar a um ponto de estrangulamento.

---

## 📚 **F) Quais São os 4 Grandes Grupos de Integração de Alto Nível Propostos no Livro Enterprise Integration Patterns?**

Os quatro grandes grupos são:

1. **Message Routing (Roteamento de Mensagens)**
2. **Message Transformation (Transformação de Mensagens)**
3. **Message Endpoints (Pontos de Fim de Mensagens)**
4. **Messaging Channels (Canais de Mensagens)**

---

## 🔗 **G) O Que é Alta Coesão?**

Alta coesão refere-se a um design onde os componentes de um módulo ou serviço são fortemente relacionados e focados em uma única tarefa ou responsabilidade. Isso facilita a manutenção e a compreensão do sistema.

---

## 🔗 **H) O Que é Baixo Acoplamento?**

Baixo acoplamento é uma prática onde os componentes de um sistema são independentes e interagem entre si através de interfaces bem definidas. Isso reduz a dependência entre módulos, facilitando mudanças e manutenção.

---

## 💡 **I) Um Benefício dos Microserviços é que Podemos Utilizar Ferramentas Distintas para Resolver Problemas Específicos sem Ter que Mudar Todo Nosso Produto. Esta Afirmação é:**

Ex: Para resolver um problema matemático de cálculo complexo, eu poderia criar um serviço em uma linguagem de programação que tenha boa performance para cálculos e adicionar ao meu produto/sistema.

- **Opções de múltipla escolha:** 1. Verdadeira

---

## 💡 **J) Utilizando Arquitetura de Microserviços Eu Posso Resolver Problemas Encontrados no Meu Produto Corrigindo Somente a Parte Específica do Produto que Está Contida no Microserviço Criado para Tal. Esta Afirmação é:**

- **Opções de múltipla escolha:** 1. Verdadeira

---

