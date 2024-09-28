# Doação de orgãos

# Introdução

O Projeto de Extensão de Doação de Órgãos tem como objetivo conscientizar a comunidade sobre a importância da doação de órgãos e facilitar o processo de cadastro de doadores e receptores. Este documento apresenta o levantamento de requisitos funcionais e não funcionais do sistema que será desenvolvido pelos alunos do 6º período de Engenharia de Software, assim como as telas iniciais do projeto.



# Requisitos

## Admin

- [ ] Deve ser possível um admin fazer qualquer coisa no sistema;

## Requisitos Funcionais

tela de "Login, cadastro de doador, cadastro de receptor, tela dashboard" no sistema.

- [ ] Deve ser possível se cadastrar como Doador;
- [ ] Deve ser possível um Doador realizar login;

- [ ] Deve ser possível se cadastrar como Receptor;
- [ ] Deve ser possível um Receptor realizar login;

## Requisitos Não Funcionais

- [ ] O Sistema deve utilizar Docker;
- [ ] O sistema deve ser persistido em um banco de dados PostgreSQL;
- [ ] O sistema deve ter um Front-End Web;
- [ ] O Front-End Web deve ser feito em React.Js ou Next.Js;
- [ ] O Front-End deve seguir boas práticas de acessibilidade e SEO;
- [ ] O sistema deve ter um Back-End em Node.js;
- [ ] O Back-End deve ser feito em Nest.js;

- [ ] As senhas devem ser armazenadas de forma segura utilizando criptografia;
- [ ] O sistema deve ser responsivo e adaptar-se a diferentes dispositivos (desktop, tablet, celular);
- [ ] O tempo de carregamento das páginas deve ser minimizado;
- [ ] A arquitetura do sistema deve permitir fácil adição de novas funcionalidades no futuro;
- [ ] O código deve ser bem documentado para facilitar a manutenção e futuras atualizações;
- [ ] O código deve seguir o padrão de codificação;
- [ ] O código deve possuir testes automatizados;
- [ ] Deve ser possível visualizar informações sobre o projeto Doação de Orgãos;
- [ ] Toda listagem deve ter paginação;

## Ideias Futuras

Ideia futura desenvolver uma newsletter, dai a pessoa nessa landing page preneche as informações para receber no "email" toda vez que tiver alguma noticia relacionada ao assunto (doação de orgãos e divulgação da AEDO).

Ideia futura, poder receber noticia de alguem perto de voce que precisa ou que recebeu um orgao, incrementando a idea de newsletter.



# Design de Telas

## Tela de Login
Formulário simples para login de doadores, receptores e administradores

## Tela de Cadastro de Doador
Formulário para que novos doadores possam se cadastrar no sistema, inserindo suas informações pessoais.

## Tela de Cadastro de Receptor
Formulário semelhante ao de doadores, mas para receptores

## Tela de Dashboard
Após o login, doadores e receptores terão acesso a uma página de dashboard com suas informações e o status de suas solicitações



# Tecnologias Utilizadas

## Front-End 
React.js ou Next.js, utilizando Tailwind CSS para estilização e Typescript como linguagem principal.

Optamos por utilizar React.js ou Next.js no front-end devido à sua popularidade, comunidade ativa, e capacidade de criar interfaces dinâmicas e performáticas. O React.js oferece flexibilidade e componentização, ideal para a construção de interfaces reutilizáveis. Já o Next.js complementa isso com funcionalidades avançadas, como renderização no servidor (SSR) e otimização para SEO, essenciais para melhorar a experiência do usuário e garantir uma boa indexação em buscadores.

## Back-End
Node.js com Nest.js, garantindo segurança e escalabilidade para as APIs.

Para o back-end, escolhemos Node.js com Nest.js, pois essas tecnologias proporcionam alta performance e uma estrutura modular robusta. O Node.js é conhecido por sua escalabilidade e suporte a operações assíncronas, o que torna o sistema mais eficiente. O Nest.js, por sua vez, oferece uma arquitetura sólida e suporte nativo ao TypeScript, facilitando a manutenção, segurança e criação de novas funcionalidades com base em padrões de projeto modernos.

## Banco de Dados
PostgreSQL para a versão final, com SQLite durante o desenvolvimento inicial.

O banco de dados escolhido para produção é o PostgreSQL devido à sua robustez, segurança e capacidade de lidar com grandes volumes de dados. É uma solução open-source confiável, adequada para um sistema que exige integridade e controle transacional, como o cadastro de doadores e receptores. Durante o desenvolvimento, utilizaremos o SQLite, que oferece simplicidade e agilidade, permitindo o desenvolvimento local sem a complexidade de configurar um servidor de banco de dados completo.