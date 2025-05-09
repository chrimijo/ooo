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

## Obtenir\_une\_vue\_Calendrier\_des\_événements\_(V3)

| Property   | Value                                                                 |
| ---------- | --------------------------------------------------------------------- |
| Name       | Obtenir\_une\_vue\_Calendrier\_des\_événements\_(V3)                  |
| Type       | OpenApiConnection                                                     |
| Connection | [Office 365 Outlook](https://docs.microsoft.com/connectors/office365) |

### Inputs

| Property       | Value                                                                                                                                                                                                                                                                                                                                                                                               |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| metadata       | <table><tr><td>operationMetadataId</td><td>`30091a1a-f4c8-4363-834b-00b7b3c3b666`</td></tr></table>                                                                                                                                                                                                                                                                                                 |
| parameters     | <table><tr><td>calendarId</td><td>`AAMkADhmYzdkY2FiLWZmMzktNDczMy05NWYyLTg1M2E2M2Y2NDBiMwBGAAAAAAD-aY4pAm3CS5YYqeAMHY6mBwA95EEmQe4-RZZdCzzeu9ymAAAAAAEGAAA95EEmQe4-RZZdCzzeu9ymAAAAAHygAAA=`</td></tr><tr><td>startDateTimeUtc</td><td>`@body('Heure_actuelle')`</td></tr><tr><td>endDateTimeUtc</td><td>`@body('Obtenir_l''heure_future')`</td></tr><tr><td>search</td><td>`ooo`</td></tr></table> |
| host           | <table><tr><td>apiId</td><td>`/providers/Microsoft.PowerApps/apis/shared_office365`</td></tr><tr><td>connectionName</td><td>`shared_office365`</td></tr><tr><td>operationId</td><td>`GetEventsCalendarViewV3`</td></tr></table>                                                                                                                                                                     |
| authentication | @parameters('$authentication')                                                                                                                                                                                                                                                                                                                                                                      |

### Next Action(s) Conditions

| Next Action                                                      |
| ---------------------------------------------------------------- |
| [Appliquer\_à\_chacun \[Succeeded\]](Appliquer_a_chacun-oooo.md) |
