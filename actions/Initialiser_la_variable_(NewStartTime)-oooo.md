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

## Initialiser\_la\_variable\_(NewStartTime)

| Property | Value                                     |
| -------- | ----------------------------------------- |
| Name     | Initialiser\_la\_variable\_(NewStartTime) |
| Type     | InitializeVariable                        |

### Inputs

| Property  | Value                                                                                                                                                                                 |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| variables | <table><tr><td>name</td><td>`NewStartTime`</td></tr><tr><td>type</td><td>`string`</td></tr><tr><td>value</td><td>`@addHours(addDays(variables('StartTime'),-1),16)`</td></tr></table> |

### Next Action(s) Conditions

| Next Action                                                                                           |
| ----------------------------------------------------------------------------------------------------- |
| [Initialiser\_la\_variable\_(NewEndTime) \[Succeeded\]](Initialiser_la_variable_(NewEndTime)-oooo.md) |
