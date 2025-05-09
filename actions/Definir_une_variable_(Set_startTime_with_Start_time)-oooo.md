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

## Définir\_une\_variable\_(Set\_startTime\_with\_Start\_time)

| Property | Value                                                       |
| -------- | ----------------------------------------------------------- |
| Name     | Définir\_une\_variable\_(Set\_startTime\_with\_Start\_time) |
| Type     | SetVariable                                                 |

### Inputs

| Property | Value                                                                                               |
| -------- | --------------------------------------------------------------------------------------------------- |
| metadata | <table><tr><td>operationMetadataId</td><td>`3788a80a-aba3-42ab-a6e3-8d3cf29aae09`</td></tr></table> |
| name     | StartTime                                                                                           |
| value    | @items('Appliquer_à_chacun')?['start']                                                              |
