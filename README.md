# Enpoint Guard

Enpoint Guard é uma aplicação simples de monitoramento de saúde de endpoints (health checker). Ela consiste em:

* API Backend: Exposição de endpoints REST para gerenciamento e consulta dos serviços monitorados.
* Frontend: Uma interface web simples para visualização do status dos serviços.
* Scheduler: Processo interno que realiza verificações periódicas nos endpoints configurados.
* Notifier: Sistema para envio de notificações externas (ex.: Slack, e-mail, etc. - futuras integrações).

A aplicação é escrita em Go (Golang), com suporte inicial ao banco de dados PostgreSQL.
