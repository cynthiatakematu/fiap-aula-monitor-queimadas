# Monitor de Queimadas: versão inicial (arquivado)

> **Este repositório está arquivado.** A versão completa do projeto, com a Azure Function de coleta, o modelo de dados e o CI/CD, está em **[fiap-aula-queimadas-inpe](https://github.com/cynthiatakematu/fiap-aula-queimadas-inpe)**.

Primeira etapa ("Dia 1") do projeto Monitor de Queimadas, desenvolvida em aula na FIAP:

- `bootstrap.sh`: cria o backend remoto do Terraform e o service principal.
- `infra/`: Terraform com o Resource Group aplicado. Os recursos de MySQL e Function App (`*.tf.disabled`) foram adiados e concluídos no repositório final.
