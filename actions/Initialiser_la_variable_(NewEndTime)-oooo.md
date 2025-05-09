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

## Initialiser\_la\_variable\_(NewEndTime)

| Property | Value                                   |
| -------- | --------------------------------------- |
| Name     | Initialiser\_la\_variable\_(NewEndTime) |
| Type     | InitializeVariable                      |

### Inputs

| Property  | Value                                                                                                                                                                                                                        |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| variables | <table><tr><td>name</td><td>`NewEndTime`</td></tr><tr><td>type</td><td>`string`</td></tr><tr><td>value</td><td>`@convertTimeZone(variables('EndTime'),'UTC','W. Europe Standard Time','dddd d MMMM yyyy')`</td></tr></table> |

### Next Action(s) Conditions

| Next Action                                 |
| ------------------------------------------- |
| [For\_each \[Succeeded\]](For_each-oooo.md) |
