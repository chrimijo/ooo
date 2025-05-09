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

## Condition\_(Maximize\_endTime)

| Property   | Value                                                                                                                                                             |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Name       | Condition\_(Maximize\_endTime)                                                                                                                                    |
| Type       | If                                                                                                                                                                |
| Expression | <table><tr><td>and</td><td><table><tr><td>greater</td><td>@items('Appliquer_à_chacun')?['end']<br/>@variables('EndTime')<br/></td></tr></table></td></tr></table> |

### Inputs

| Property | Value                                                                                               |
| -------- | --------------------------------------------------------------------------------------------------- |
| metadata | <table><tr><td>operationMetadataId</td><td>`9f4c9c24-8752-4407-92e0-81e5bf43a0ac`</td></tr></table> |

### Subactions

| Action                                                                                                              |
| ------------------------------------------------------------------------------------------------------------------- |
| [Définir\_une\_variable\_(Set\_endTime\_with\_End\_time)](Definir_une_variable_(Set_endTime_with_End_time)-oooo.md) |
