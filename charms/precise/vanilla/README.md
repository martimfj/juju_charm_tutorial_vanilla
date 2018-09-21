# Overview

Charm para o forum open source Vanilla

# Usage

Instale o banco de dados:
* `juju deploy juju deploy cs:xenial/mysql`

Vá para a pasta do Charm:
* `cd repository_name/charms/precise/vanilla`

Instale a aplicação Vanilla:
* `juju deploy .`

Adicione a relação entre a aplicação e o banco de dados:
* `juju add-relation mysql vanilla`

Libere o acesso a aplicação:
* `juju expose vanilla`

Pegue o IP da máquina onde a aplicação Vanilla está hospedada e o IP da máquina de banco de dados:
* `juju status`

Acesse o IP da aplicação e configure-a. A primeira opção *database host* é o IP da máquina de banco de dados.

Pronto!

## Scale out Usage

None

## Known Limitations and Issues

None

# Configuration

None

# Contact Information

None

## Upstream Project Name

None
