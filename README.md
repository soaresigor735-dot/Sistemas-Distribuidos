# Sistemas-Distribuidos

Um Sistema Distribuído é um conjunto de computadores independentes que se comunicam via rede e se apresentam ao usuário final como um sistema único e coeso.

Objetivo Principal: Compartilhar recursos e processamento com alta disponibilidade, tolerância a falhas e escalabilidade.

Transparência: O usuário não precisa saber em qual máquina um dado está armazenado ou onde um processo é executado; para ele, tudo funciona em um só local.

Comunicação: Ocorre por meio de troca de mensagens em rede (usando Sockets, RPC/RMI, Web Services ou MOM/Filas), já que não há memória compartilhada entre os nós.

Desafios Principais:

Sincronização: Ausência de um relógio físico global único para ordenar eventos.

Tolerância a Falhas: Capacidade de continuar funcionando mesmo se uma parte dos nós cair.

Consistência: Manter as informações atualizadas e idênticas em todas as réplicas de dados.
