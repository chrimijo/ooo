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

## Initialiser\_la\_variable\_EndTime

| Property | Value                              |
| -------- | ---------------------------------- |
| Name     | Initialiser\_la\_variable\_EndTime |
| Type     | InitializeVariable                 |

### Inputs

| Property  | Value                                                                                                                                                   |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| metadata  | <table><tr><td>operationMetadataId</td><td>`575f6c5a-f966-48f5-b64a-66fffb97d753`</td></tr></table>                                                     |
| variables | <table><tr><td>name</td><td>`EndTime`</td></tr><tr><td>type</td><td>`string`</td></tr><tr><td>value</td><td>`@getPastTime(1, 'year')`</td></tr></table> |

### Next Action(s) Conditions

| Next Action                                                                                                                  |
| ---------------------------------------------------------------------------------------------------------------------------- |
| [Obtenir\_une\_vue\_Calendrier\_des\_événements\_(V3) \[Succeeded\]](Obtenir_une_vue_Calendrier_des_evenements_(V3)-oooo.md) |
