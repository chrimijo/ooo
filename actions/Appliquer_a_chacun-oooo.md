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

## Appliquer\_à\_chacun

| Property | Value                |
| -------- | -------------------- |
| Name     | Appliquer\_à\_chacun |
| Type     | Foreach              |

### Inputs

| Property | Value                                                                                               |
| -------- | --------------------------------------------------------------------------------------------------- |
| foreach  | @outputs('Obtenir_une_vue_Calendrier_des_événements_(V3)')?['body/value']                           |
| metadata | <table><tr><td>operationMetadataId</td><td>`7a8a76d0-bd75-4d00-85fa-52fa1006a958`</td></tr></table> |

### Subactions

| Action                                                                                 |
| -------------------------------------------------------------------------------------- |
| [Condition\_\_(Show\_as\_Out\_of\_Office)](Condition__(Show_as_Out_of_Office)-oooo.md) |

### Next Action(s) Conditions

| Next Action                                                                                               |
| --------------------------------------------------------------------------------------------------------- |
| [Initialiser\_la\_variable\_(NewStartTime) \[Succeeded\]](Initialiser_la_variable_(NewStartTime)-oooo.md) |
