# Um exemplo de cliente/servidor – AngularJS 1.x / Spring 4

👉 Curso relacionado:
[Um exemplo de cliente/servidor - AngularJS 1.x / Spring 4](https://stahe.github.io/br-spring-angular1.x-juillet-2014/)

---

## 📌 Introdução

Este documento oferece uma introdução conjunta a duas importantes estruturas (frameworks), com base na implementação de uma aplicação **cliente/servidor**:

* **AngularJS 1.x** para o lado do cliente (front-end)
* **Spring 4** para o lado do servidor (back-end)

Para simplificar, os termos **Angular** e **Spring** serão utilizados no restante deste documento.

O objetivo é ilustrar de forma concreta a comunicação entre um cliente web e um servidor Java, com base em tecnologias amplamente utilizadas no desenvolvimento de aplicativos web modernos. 

---

## 🎯 Objetivos

* Compreender a arquitetura cliente/servidor
* Implementar o AngularJS 1.x para desenvolvimento front-end
* Utilizar o Spring 4 para disponibilizar serviços back-end
* Ilustrar a comunicação HTTP entre cliente e servidor
* Gerenciar um banco de dados via JPA

---

## ⚙️ Pré-requisitos

Para compreender este documento, são necessários os seguintes conhecimentos:

* Nível intermediário em **Java EE**
* Domínio do **JPA (Java Persistence API)**
* Conhecimento de uma versão anterior do **Spring**
* Uso do **Maven** para gerenciamento de projetos
* Compreensão da comunicação **HTTP**
* Conhecimento básico de:

  * **HTML**
  * **JavaScript**

Conceitos adicionais serão introduzidos gradualmente ao longo do estudo de caso. 

---

## ⚠️ Observação importante

Este documento:

* **não é um curso completo**
* é deliberadamente **incompleto**
* tem como foco principal uma **abordagem prática com base em exemplos**

---

## 📚 Fontes recomendadas

Para aprofundar ainda mais os conceitos abordados:

### AngularJS

* *Pro AngularJS* – Adam Freeman (Apress)
* Documentação oficial: [https://docs.angularjs.org/guide](https://docs.angularjs.org/guide)

### Spring

* *Spring Data* – O’Reilly
* *Pro Spring 3* – Apress (conceitos aplicáveis ao Spring 4)
* Documentação oficial do Spring:
  [https://docs.spring.io/spring/docs/current/spring-framework-reference/](https://docs.spring.io/spring/docs/current/spring-framework-reference/)

### Recursos adicionais

* [https://stackoverflow.com/](https://stackoverflow.com/) (útil para depuração e exemplos práticos)

---

## 🧩 Abordagem pedagógica

Este documento baseia-se em:

* um **estudo de caso concreto**
* **exemplos práticos**
* uma estrutura voltada para a **resolução de problemas**

---

## 🚀 Conclusão

Este material serve de base para:

* compreender a integração do AngularJS e do Spring
* experimentar uma arquitetura web moderna
* preparar-se para desenvolvimentos mais avançados
