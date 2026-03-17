# CheckList Centauro - AppSheet

Este repositório contém a documentação técnica e o histórico de regras de negócio do aplicativo de CheckList da Centauro.

## 🔗 Documentação Completa
A documentação detalhada de processos, fluxos e manuais de usuário está centralizada no Confluence:
* [Link para Documentação no Confluence](https://grupo-sbf.atlassian.net/wiki/spaces/~712020440dc84834d941aa97738dc33b5e53cd/folder/771031041?atlOrigin=eyJpIjoiZmFjNTUyZmM2ZGJkNDEzZWFlYmQyNmE1YWY0ODgyNzIiLCJwIjoiYyJ9)

## 📊 Estrutura de Dados
O app consome dados das seguintes fontes:
* **Google Sheets:** [CheckList Centauro Dados]
* **Tabelas Principais:** Lojas, Admins, KPIs_loja, Perguntas_Fixas, Configuracao_Perguntas, Checklist_Gerado, Historico_Respostas. (LISTA_COLUNAS): usada para navegar no BigQuery.

## ⚙️ Regras de Negócio Importantes (Backup Manual)
> Como o plano AppSheet Core não permite integração nativa, as fórmulas críticas são registradas aqui:

* **Automação de E-mail:** Disparada quando a coluna `[Status]` muda para "Finalizado".

## 🛠️ Versões
O histórico de versões nativo pode ser consultado no editor do AppSheet em: 
`Manage > Author > Versions`.
