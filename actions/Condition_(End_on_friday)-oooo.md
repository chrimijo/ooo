# Flow Documentation \- oooo

| Flow Name                  | oooo                                     |
| -------------------------- | ---------------------------------------- |
| Flow Name                  | oooo                                     |
| Flow ID                    | 0499a189\-3e07\-426b\-88cc\-9058e23a8f5f |
| Documentation generated at | vendredi, 9 mai 2025 09:33               |
| Number of Variables        | 4                                        |
| Number of Actions          | 20                                       |

- [Overview](../index-oooo.md)
- [Connection References](../connections-oooo.md)
- [Variables](../variables-oooo.md)
- [Triggers & Actions](../triggersactions-oooo.md)

## Condition\_(End\_on\_friday)

| Property   | Value                                                                                                                                                                                                      |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Name       | Condition\_(End\_on\_friday)                                                                                                                                                                               |
| Type       | If                                                                                                                                                                                                         |
| Expression | <table><tr><td>and</td><td><table><tr><td>contains</td><td>@convertTimeZone(variables('EndTime'),'UTC','W. Europe Standard Time','dddd d MMMM yyyy')<br/>Saturday<br/></td></tr></table></td></tr></table> |

### Subactions

| Action                                                 |
| ------------------------------------------------------ |
| [Définir\_une\_variable](Definir_une_variable-oooo.md) |

### Elseactions

| Elseactions                                                                       |
| --------------------------------------------------------------------------------- |
| [Définir\_une\_variable\_(NewEndTime)](Definir_une_variable_(NewEndTime)-oooo.md) |
