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

## Condition\_(Enable\_Automatic\_Replies)

| Property   | Value                                                                                                                                             |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Name       | Condition\_(Enable\_Automatic\_Replies)                                                                                                           |
| Type       | If                                                                                                                                                |
| Expression | <table><tr><td>and</td><td><table><tr><td>less</td><td>@variables('StartTime')<br/>@variables('EndTime')<br/></td></tr></table></td></tr></table> |

### Inputs

| Property | Value                                                                                               |
| -------- | --------------------------------------------------------------------------------------------------- |
| metadata | <table><tr><td>operationMetadataId</td><td>`3d2deffa-26be-40ac-9372-4e0c0cf8a782`</td></tr></table> |

### Subactions

| Action                                                                                                                                                          |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Configurer\_des\_réponses\_automatiques\_(V2)\_(Schedule\_Automatic\_Replies)](Configurer_des_reponses_automatiques_(V2)_(Schedule_Automatic_Replies)-oooo.md) |

### Elseactions

| Elseactions                                                                                                                                                   |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Configurer\_des\_réponses\_automatiques\_(V2)\_(Disable\_Automatic\_Replies)](Configurer_des_reponses_automatiques_(V2)_(Disable_Automatic_Replies)-oooo.md) |
