# História dos containers ... e Docker

---

## Primeiras experiências

- [IBM VM/370 (1972)](https://en.wikipedia.org/wiki/VM_%28operating_system%29)

- [Linux VServers (2001)](http://www.solucorp.qc.ca/changes.hc?projet=vserver)

- [Solaris Containers (2004)](https://en.wikipedia.org/wiki/Solaris_Containers)

- [FreeBSD jails (1999-2000)](https://www.freebsd.org/cgi/man.cgi?query=jail&sektion=8&manpath=FreeBSD+4.0-RELEASE)

De fato, containers já estão na área por um _longo período_.

(Veja [esse excelente blob do Serge Hallyn](https://s3hh.wordpress.com/2018/03/22/history-of-containers/) para mais detalhes históricos.)

---

class: pic

## A éra VPS (until 2007-2008)

![lightcont](images/containers-as-lightweight-vms.png)

---

## Containers = mais barato que VMs

- Users: hosting providers.

- Audiência extremamente especializada com forte cultura ops..

---

class: pic

## O período PAAS (2008-2013)

![heroku 2007](images/heroku-first-homepage.png)

---

## Containers = mais fácil que VMs

- Eu não posso falar pelo Heroku, mas os containers foram (uma das) armas secretas da dotCloud

- dotCloud estava operando um PaaS, usando um engine próprio de containers.

- Esse engine era baseado no OpenVZ (e depois, LXC) e AUFS.

- Começou como (circa 2008) um simples script Python.

- Em 2012, tinha multiplos (~10) componentes Python.
  <br/>(e outros ~100 microserviços!)

- No final de 2012, dotCloud refatorou esse engine.

- O codinome para esse projeto foi "Docker."

---

## Primeira versão pública do Docker

- Em Março de 2013 na PyCon, Santa Clara:
  <br/>"Docker" é mostrado ao público pela primeira vez.

- Lançado como uma licensa open source.

- Teve reações e feedbacks muito positivos!

- O time dotCloud progressivamente chaveu para o desenvolvimento do Docker.

- No mesmo ano, dotCloud mudou o nome para Docker.

- Em 2014, o PaaS foi vendido.

---

## Docker early days (2013-2016)

---

## Primeiros usuários do docker

- PAAS (Flynn, Dokku, Tsuru, Deis...)

- Usuários de PAAS

- CI platforms

- developers, developers, developers, developers

---

## Docker se torna um padrão da industria

- Docker atinge a versão 1.0 milestone.

- Plataformas existentes como Mesos e Cloud Foundry adicionam suporte ao Docker.

- Padronização na OCI (Open Containers Initiative).

- Outros engines de containers são desenvolvidos.

- Criação da CNCF (Cloud Native Computing Foundation).

---

## Docker se torna uma plataforma

- O engine de container é agora conhecido como "Docker Engine."

- Outras ferramentas foram adicionadas:

  - Docker Compose ("Fig")
  - Docker Machine
  - Docker Swarm
  - Kitematic
  - Docker Cloud ("Tutum")
  - Docker Datacenter
  - etc.

- Docker Inc. lança ofertas comerciais.
