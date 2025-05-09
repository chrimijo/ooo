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

## Définir\_une\_variable\_(Set\_endTime\_with\_End\_time)

| Property | Value                                                   |
| -------- | ------------------------------------------------------- |
| Name     | Définir\_une\_variable\_(Set\_endTime\_with\_End\_time) |
| Type     | SetVariable                                             |

### Inputs

| Property | Value                                                                                               |
| -------- | --------------------------------------------------------------------------------------------------- |
| metadata | <table><tr><td>operationMetadataId</td><td>`6056a535-e783-4c2e-b40f-72b147d892b3`</td></tr></table> |
| name     | EndTime                                                                                             |
| value    | @items('Appliquer_à_chacun')?['end']                                                                |
