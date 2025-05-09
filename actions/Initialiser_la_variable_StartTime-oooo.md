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

## Initialiser\_la\_variable\_StartTime

| Property | Value                                |
| -------- | ------------------------------------ |
| Name     | Initialiser\_la\_variable\_StartTime |
| Type     | InitializeVariable                   |

### Inputs

| Property  | Value                                                                                                                                                      |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| metadata  | <table><tr><td>operationMetadataId</td><td>`cb295e06-c2e4-4ed2-a6cc-82f21cab5672`</td></tr></table>                                                        |
| variables | <table><tr><td>name</td><td>`StartTime`</td></tr><tr><td>type</td><td>`string`</td></tr><tr><td>value</td><td>`@getFutureTime(1,'year')`</td></tr></table> |

### Next Action(s) Conditions

| Next Action                                                                                 |
| ------------------------------------------------------------------------------------------- |
| [Initialiser\_la\_variable\_EndTime \[Succeeded\]](Initialiser_la_variable_EndTime-oooo.md) |
