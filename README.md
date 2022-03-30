# **fineasy**

Aplicativo para realizar o gerenciamento e controle de finanças pessoais, garantindo uma maior visibilidade para o usuário final, dessa forma o usuário poderá visualizar toda a sua saúde financeira.

</br>

## **Objetivo**
</br>

- Garantir uma melhor saúde financeira para os usuários;
- Controlar o fluxo de entrada e saída de dinheiro;
- Facilitar a visualização de dados financeiros do usuário;

</br>

## **Arquitetura**
</br>

![](/docs/architecture.drawio.png)

### **Componentes**

- Frontend:

    - Aplicação mobile multiplataforma;
    - Desenvolvido em Flutter;

- Backend:

    - Microsserviços desenvolvidos em Python;
    - Kong sendo o API Gateway para expor os endpoints de comunicação;

- Database:

    - Utilizando MongoDB para uma melhor performance;