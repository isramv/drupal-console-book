# node:access:rebuild
Permissões de acesso ao node reconstruídas. A reconstrução irá remover todos os privilégios do conteúdo e substituí-los com permissões baseadas nos módulos e configurações atuais.

**Uso:**
```
$ drupal node:access:rebuild [options]
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--batch | Processo em modo de lotes.

## Exemplos
* Reconstruir permissões de acesso a nodes
```
$ drupal node:access:rebuild --batch
```
