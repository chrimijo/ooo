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

## Obtenir\_l'heure\_future

| Property | Value                    |
| -------- | ------------------------ |
| Name     | Obtenir\_l'heure\_future |
| Type     | Expression               |

### Inputs

| Property | Value                                                                                               |
| -------- | --------------------------------------------------------------------------------------------------- |
| metadata | <table><tr><td>operationMetadataId</td><td>`fc52e49d-5d6a-4f0a-8fa6-5caa010f6a93`</td></tr></table> |
| kind     | GetFutureTime                                                                                       |
| interval | 24                                                                                                  |
| timeUnit | Hour                                                                                                |

### Next Action(s) Conditions

| Next Action                                                                                     |
| ----------------------------------------------------------------------------------------------- |
| [Initialiser\_la\_variable\_StartTime \[Succeeded\]](Initialiser_la_variable_StartTime-oooo.md) |
