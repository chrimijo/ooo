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

## For\_each

| Property | Value     |
| -------- | --------- |
| Name     | For\_each |
| Type     | Foreach   |

### Inputs

| Property | Value                                                                     |
| -------- | ------------------------------------------------------------------------- |
| foreach  | @outputs('Obtenir_une_vue_Calendrier_des_événements_(V3)')?['body/value'] |

### Subactions

| Action                                                            |
| ----------------------------------------------------------------- |
| [Condition\_(End\_on\_friday)](Condition_(End_on_friday)-oooo.md) |

### Next Action(s) Conditions

| Next Action                                                                                           |
| ----------------------------------------------------------------------------------------------------- |
| [Condition\_(Enable\_Automatic\_Replies) \[Succeeded\]](Condition_(Enable_Automatic_Replies)-oooo.md) |
