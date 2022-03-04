## Sobre o Autor
<img   style="border-radius: 50%"  align="left" width="190" height="190" margin-right="150px"  src="https://lh3.googleusercontent.com/pw/AM-JKLUq-TgjEzhoVY_CtieDZgnZNOoIGyAubOEKisc2FKt7HMCSVv4DGHZjixw4Z2_yomTtgUKr0kxFUyUdmOuTyJnQfhgzXEyOVk6JoajO58wYDtWcrDF-EPRjaE1hj2EsZtM-OYgQsDjHGjdny1yGetxeWw=s250-no?authuser=0"> Oi, meu nome é Pedro Savio, faço engenharia de computação no IFPB, sou desenvolvedor Fullstack e esse é o meu linkedin,  [ir para meu linkdin](https://www.linkedin.com/in/pedro-s-04a300129/).

# CreditCardLedger

Projeto utilizado em um live coding da Digital Innovation One.

Este projeto faz o uso de biblitecas como Cowboy (servidor HTTP) e do Ecto (migrações e conexão
com banco de dados).

## Pré requisitos

Ter Elixir 1.10 ou mais novo instalado ter docker e docker compose instalado.

### Instalação do Elixir

Eu particularmente faço uso de uma ferramenta chamada (asdf)[https://github.com/asdf-vm/asdf], no
qual me permite ter várias versões de várias linguanges instalada em meu computador.

Siga os passos de instalação do readme do asdf.

Instale os plugins do Erlang e do Elixir, pelo commando

```shell
asdf plugin-add erlang
asdf plugin-add elixir
```

Para efetuar a instalação do Erlang recomendo instalar algumas dependencias listadas do (github do
plugin)[https://github.com/asdf-vm/asdf-erlang#before-asdf-install].

Após vamos instalar as linguagens e deixá-las global, usando o commando

```shell
asdf install erlang 22.3
asdf global erlang 22.3
asdf install elixir 1.10.2
asdf global elixir 1.10.2
```

Se fo preciso após a instalação execute o comando

```shell
asdf reshim
```

Para testar sua instalação é só abrir terminal interativo do Elixir.

```shell
iex
```

Para sair use CTRL+C duas vezes.

### Instalação do Docker

Para instalar o docker e docker compose eu recomendo seguir os passos do site do
(Docker)[https://www.docker.com/get-started].


### Comandos 

mix new --sup nome_do_app
