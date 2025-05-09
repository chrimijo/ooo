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

## Configurer\_des\_réponses\_automatiques\_(V2)\_(Disable\_Automatic\_Replies)

| Property   | Value                                                                        |
| ---------- | ---------------------------------------------------------------------------- |
| Name       | Configurer\_des\_réponses\_automatiques\_(V2)\_(Disable\_Automatic\_Replies) |
| Type       | OpenApiConnection                                                            |
| Connection | [Office 365 Outlook](https://docs.microsoft.com/connectors/office365)        |

### Inputs

| Property       | Value                                                                                                                                                                                                                                 |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| metadata       | <table><tr><td>operationMetadataId</td><td>`ad183cd9-93c8-4eca-8cda-3201ecf13807`</td></tr></table>                                                                                                                                   |
| parameters     | <table><tr><td>body/automaticRepliesSetting/status</td><td>`disabled`</td></tr><tr><td>body/automaticRepliesSetting/externalAudience</td><td>`None`</td></tr></table>                                                                 |
| host           | <table><tr><td>apiId</td><td>`/providers/Microsoft.PowerApps/apis/shared_office365`</td></tr><tr><td>connectionName</td><td>`shared_office365`</td></tr><tr><td>operationId</td><td>`SetAutomaticRepliesSetting_V2`</td></tr></table> |
| authentication | @parameters('$authentication')                                                                                                                                                                                                        |
