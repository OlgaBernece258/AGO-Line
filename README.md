Gestor de Fila 🕑

O Gestor de Fila é uma plataforma que simplifica o gerenciamento de filas em salões de beleza, permitindo que os clientes entrem na fila, recebam notificações no WhatsApp.


Motivação 🚀

A ideia para o Gestor de Fila surgiu de uma experiência pessoal. Em um dia em que precisei organizar o cabelo, cheguei ao salão e me deparei com 10 pessoas já esperando. Anotei meu nome em um caderninho que o salão usava para gerenciar os clientes, mas como a espera seria longa, decidi sair para fazer outras coisas.

No entanto, ir ao salão verificar constantemente quanto tempo faltava para a minha vez se tornou cansativo. Foi então que percebi a necessidade de uma solução mais eficiente. Assim, nasceu o Gestor de Fila, uma maneira de simplificar a espera nos salões de beleza e garantir que os clientes possam aproveitar melhor o seu tempo.

Funcionalidades Principais 📋

Fila de Atendimento: Entre na fila de espera facilmente e acompanhe sua posição.
Notificações WhatsApp: Receba notificações quando for a sua vez e mantenha-se informado.
Agendamento: Faça agendamento para evitar longas esperas.


Backend

O backend do AGO-Line foi desenvolvido com as seguintes tecnologias:

Node.js: Plataforma de desenvolvimento JavaScript baseada em eventos.

Express: Framework web para Node.js.

Zod: Biblioteca para validação de esquemas em TypeScript.

Jsonwebtoken: Para autenticação e geração de tokens JWT.

Prisma ORM: Uma ferramenta de banco de dados com tipos seguros para Node.js e 
TypeScript.

bcryptjs: Para criptografia de senhas.

TypeScript: Linguagem de programação tipada.


Frontend

O frontend do AGO-Line faz uso das seguintes tecnologias:

Vite: Build tool que serve como base para o desenvolvimento web.

React: Biblioteca de JavaScript para a construção da interface do usuário.

Zod: Utilizada para validação de esquemas em TypeScript.

Tailwind CSS: Framework de estilo CSS.

shadcn/ui: Biblioteca de componentes UI.

React Query: Para gerenciamento de estado.

Lucida React: Biblioteca uso de ícones.

React Hook Form: Para gerenciamento de formulários.

Axios: Cliente HTTP para fazer requisições à API.

TypeScript: Linguagem de programação tipada.

Next.js (planejado): Framework React para desenvolvimento web.

Integração com o WhatsApp
Foi criado um microserviço para a integração com o WhatsApp, utilizando as seguintes tecnologias:

TypeScript: Linguagem de programação tipada.

Express: Framework web para Node.js.

