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

## Condition\_\_(Show\_as\_Out\_of\_Office)

| Property   | Value                                                                                                |
| ---------- | ---------------------------------------------------------------------------------------------------- |
| Name       | Condition\_\_(Show\_as\_Out\_of\_Office)                                                             |
| Type       | If                                                                                                   |
| Expression | <table><tr><td>equals</td><td>@items('Appliquer_à_chacun')?['showAs']<br/>oof<br/></td></tr></table> |

### Inputs

| Property | Value                                                                                               |
| -------- | --------------------------------------------------------------------------------------------------- |
| metadata | <table><tr><td>operationMetadataId</td><td>`bb752976-391c-4d3d-bc31-41c852fc9a36`</td></tr></table> |

### Subactions

| Action                                                                     |
| -------------------------------------------------------------------------- |
| [Condition\_(Maximize\_endTime)](Condition_(Maximize_endTime)-oooo.md)     |
| [Condition\_(Minimize\_startTime)](Condition_(Minimize_startTime)-oooo.md) |
