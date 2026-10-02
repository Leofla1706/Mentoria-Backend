# Contrato da API — Tarefas

API simples para gerenciamento de tarefas.

## Criar tarefa

**Método:** POST  
**Rota:** `/tarefas`

### Entrada

```json
{
  "titulo": "Estudar C#",
  "descricao": "Revisar fundamentos"
}