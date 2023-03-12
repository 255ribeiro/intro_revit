# Tipos de parâmetros no Revit

---------

## Parâmetros do Modelo

### Bulit-in

   * Existem no projeto e nas famílias desde o começo da modelagem.
   * Não podem ser apagados ou ter os tipos de dados alterados.
   * Exemplos
     * Mark
     * Comments
     * Type Mark
     * Description
     * Type Comments
  
### Parâmetros de Projeto

   * São criados pelo usuário em um projeto do Revit
   * Podem ser adicionados à maioria das categorias do Revit.
   * Podem aparecer em planilhas.
   * Não aparecem em tags(identificadores).
  
### Parâmetros globais.
   
   * São criados pelos usuários para controlar globalmente propriedades das instâncias dos elementos.
   * Não aparecem e planilhas, mas os parâmetros associados à eles podem aparecer.

### Parâmetros de família
   
   * Existem dentro das famílias do Revit para controlar elementos geométricos destas, bem como outras características.
   * Não aparecem em planilhas ou tags(identificadores).

----------

### Parâmetros compartilhados
   
   * São armazenados em um arquivo de texto externo.
   * Possuem um identificador único (ID).
   * Podem ser aplicados à parâmetros de projeto ou de família.
   * Podem aparecer em planilhas e tag(identificadores).

-------


### Tabela resumo

| Tipo de parâmetro                           | Onde é usado?     | Identificadores (Tags) | Planilhas (Shedules) |
|---------------------------------------------|-------------------|------------------------|----------------------|
| Built-in                                    | Famílias Projetos | x                      | x                    |
| Parâmetros de Projeto                       | Projetos          | -                      | x                    |
| Parâmetros de Família Family parameters     | Famílias          | -                      | -                    |
| Parâmetros compartilhados Shared parameters | Famílias Projetos | x                      | x                    |
| Parâmetros globais Global parameters        | Projetos          | -                      | -                    |