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

## Condition\_(Minimize\_startTime)

| Property   | Value                                                                                                                                                              |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Name       | Condition\_(Minimize\_startTime)                                                                                                                                   |
| Type       | If                                                                                                                                                                 |
| Expression | <table><tr><td>and</td><td><table><tr><td>less</td><td>@items('Appliquer_à_chacun')?['start']<br/>@variables('StartTime')<br/></td></tr></table></td></tr></table> |

### Inputs

| Property | Value                                                                                               |
| -------- | --------------------------------------------------------------------------------------------------- |
| metadata | <table><tr><td>operationMetadataId</td><td>`a4ba4ad8-55dc-426e-b6dd-a7d2f5a4efc7`</td></tr></table> |

### Subactions

| Action                                                                                                                      |
| --------------------------------------------------------------------------------------------------------------------------- |
| [Définir\_une\_variable\_(Set\_startTime\_with\_Start\_time)](Definir_une_variable_(Set_startTime_with_Start_time)-oooo.md) |

### Next Action(s) Conditions

| Next Action                                                                          |
| ------------------------------------------------------------------------------------ |
| [Condition\_(Maximize\_endTime) \[Succeeded\]](Condition_(Maximize_endTime)-oooo.md) |
