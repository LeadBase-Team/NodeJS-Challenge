# Desafio NodeJS

Nosso objetivo com este desafio será observar habilidades como análise de requisitos e características básicas de programação.

Procuramos desenvolvedores(as) versáteis, motivados(as) a resolver os mais diversos problemas, capazes de propor novas soluções.


### Perfil esperado 
- Proativo, sabe trabalhar em equipe, bom raciocínio lógico, tem responsabilidade e comprometimento;
- Fácil adaptação em projetos experimentais e complexos;
- Aprendizado rápido no uso de tecnologias de desenvolvimento de software;
- Experiência em desenvolvimento de software para web;
- Experiência com testes automatizados.


### Desafio
> Montar uma API REST de uma loja fictícia em NodeJS, capaz de realizar Autenticação e Autorização de usuários. 

1 - Um usuário poderá enviar seu email e uma senha para um endpoint API e realizar login na plataforma, recebendo assim um token de acesso contendo seus dados pessoais, e suas permissões, caso suas credenciais estejam válidas.

2 - Um usuário do que tenha permissão de `listUsers` poderá acessar a rota `GET /users` para que possa listar todos os usuários do sistema. 

3 - Um usuário do que tenha permissão de `listOrders` poderá acessar a rota `GET /orders` para que possa listar todas as vendas sistema.

4 - Um usuário autenticado ou não poderá acessar a rota `GET /comments` para que possa listar todos os comentários do sistema.

5 - Caso o usuário não tenha as permissões adequadas para acessar as rotas dos itens 2 e 3, deverá receber uma mensagem de erro adequada.


### Constraints
- O desenvolvimento da API deve ser em NodeJS;
- Não é necessário submeter uma aplicação que cumpra cada um dos requisitos descritos, mas o que for submetido deve funcionar e ter um código limpo;
- Informar em um arquivo `INSTRUCOES.md` o passo a passo necessário para rodar o projeto, juntamente com o descritivo das funcionalidades que foram implementadas.


### Pontos importantes
- Limpeza do código;
- Resultado funcional;
- Uso consistente do `git`;
- Se necessário explicar as escolhas (Ex.: bibliotecas, ferrramentas, o uso de design patterns, etc);
- Tratamento de erros;
- Testes automatizados;


### Como enviar o resultado
- Faça um fork deste repositório e crie um branch com o seu nome (exemplo: `nome-sobrenome`).
- Ao finalizar o desafio, faça um pull request com o código de sua autoria.

---
Em caso de dúvidas, envie um email para [filipe@leadbase.com.br](mailto:filipe@leadbase.com.br).

