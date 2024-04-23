# desafio-banco-versao-3-full

O sistema bancário desenvolvido é uma aplicação de terminal que simula operações básicas de um banco, como criar usuários, criar contas, depositar, sacar e exibir extratos. Ele foi criado como parte de um desafio proposto pela Digital Innovation One (DIO), no contexto do Bootcamp Python Back End.

1. **Funcionalidades Principais**:
   - **Depósito**: Permite ao usuário realizar depósitos em uma conta.
   - **Saque**: Permite ao usuário realizar saques de uma conta, desde que dentro do limite de saldo e número máximo de saques permitidos.
   - **Extrato**: Exibe o extrato de uma conta, mostrando as transações realizadas e o saldo atual.
   - **Nova Conta**: Permite criar uma nova conta associada a um usuário existente ou criar um novo usuário e uma nova conta para ele.
   - **Listar Contas**: Lista todas as contas cadastradas no sistema.

2. **Segurança**:
   - O sistema utiliza CPF como identificador único para cada usuário, garantindo a unicidade das contas.
   - Limites de saldo e número máximo de saques são aplicados para cada conta, proporcionando segurança e controle sobre as transações.

3. **Facilidade de Uso**:
   - A interface de linha de comando torna a interação intuitiva e de fácil compreensão.
   - O menu principal oferece opções claras e descritivas para cada funcionalidade.

4. **Flexibilidade**:
   - O sistema permite criar novos usuários e contas de forma dinâmica, adaptando-se às necessidades dos clientes.

5. **Organização e Manutenção**:
   - O código foi estruturado de forma modular, facilitando a manutenção e extensão do sistema.
   - As funções estão claramente definidas e separadas por responsabilidades, facilitando a identificação e correção de possíveis erros.

Este sistema representa não apenas um desafio técnico, mas também uma oportunidade de aprendizado e prática para os participantes do Bootcamp Python Back End da DIO, oferecendo uma experiência prática na implementação de conceitos fundamentais de programação e manipulação de dados em Python.
