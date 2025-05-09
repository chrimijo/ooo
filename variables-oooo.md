# Flow Documentation \- oooo

| Flow Name                  | oooo                                     |
| -------------------------- | ---------------------------------------- |
| Flow Name                  | oooo                                     |
| Flow ID                    | 0499a189\-3e07\-426b\-88cc\-9058e23a8f5f |
| Documentation generated at | vendredi, 9 mai 2025 09:33               |
| Number of Variables        | 4                                        |
| Number of Actions          | 20                                       |

- [Overview](index-oooo.md)
- [Connection References](connections-oooo.md)
- [Variables](variables-oooo.md)
- [Triggers & Actions](triggersactions-oooo.md)

## Variables

### NewEndTime

| Property | Value      |
| -------- | ---------- |
| Name     | NewEndTime |
| Type     | string     |

| Variable Property                                                                         | Initial Value |
| ----------------------------------------------------------------------------------------- | ------------- |
| @convertTimeZone(variables('EndTime'),'UTC','W. Europe Standard Time','dddd d MMMM yyyy') |               |

| Variable Used In                                                                                                                                                        |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Configurer\_des\_réponses\_automatiques\_(V2)\_(Schedule\_Automatic\_Replies)](actions/Configurer_des_reponses_automatiques_(V2)_(Schedule_Automatic_Replies)-oooo.md) |
| [Définir\_une\_variable](actions/Definir_une_variable-oooo.md)                                                                                                          |
| [Définir\_une\_variable\_(NewEndTime)](actions/Definir_une_variable_(NewEndTime)-oooo.md)                                                                               |
| [Initialiser\_la\_variable\_(NewEndTime)](actions/Initialiser_la_variable_(NewEndTime)-oooo.md)                                                                         |

### NewStartTime

| Property | Value        |
| -------- | ------------ |
| Name     | NewStartTime |
| Type     | string       |

| Variable Property                                 | Initial Value |
| ------------------------------------------------- | ------------- |
| @addHours(addDays(variables('StartTime'),\-1),16) |               |

| Variable Used In                                                                                                                                                        |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Configurer\_des\_réponses\_automatiques\_(V2)\_(Schedule\_Automatic\_Replies)](actions/Configurer_des_reponses_automatiques_(V2)_(Schedule_Automatic_Replies)-oooo.md) |
| [Initialiser\_la\_variable\_(NewStartTime)](actions/Initialiser_la_variable_(NewStartTime)-oooo.md)                                                                     |

### EndTime

| Property | Value   |
| -------- | ------- |
| Name     | EndTime |
| Type     | string  |

| Variable Property       | Initial Value |
| ----------------------- | ------------- |
| @getPastTime(1, 'year') |               |

| Variable Used In                                                                                                            |
| --------------------------------------------------------------------------------------------------------------------------- |
| [Condition\_(Enable\_Automatic\_Replies)](actions/Condition_(Enable_Automatic_Replies)-oooo.md)                             |
| [Condition\_(Maximize\_endTime)](actions/Condition_(Maximize_endTime)-oooo.md)                                              |
| [Définir\_une\_variable\_(NewEndTime)](actions/Definir_une_variable_(NewEndTime)-oooo.md)                                   |
| [Définir\_une\_variable\_(Set\_endTime\_with\_End\_time)](actions/Definir_une_variable_(Set_endTime_with_End_time)-oooo.md) |
| [Initialiser\_la\_variable\_EndTime](actions/Initialiser_la_variable_EndTime-oooo.md)                                       |

### StartTime

| Property | Value     |
| -------- | --------- |
| Name     | StartTime |
| Type     | string    |

| Variable Property        | Initial Value |
| ------------------------ | ------------- |
| @getFutureTime(1,'year') |               |

| Variable Used In                                                                                                                    |
| ----------------------------------------------------------------------------------------------------------------------------------- |
| [Condition\_(Enable\_Automatic\_Replies)](actions/Condition_(Enable_Automatic_Replies)-oooo.md)                                     |
| [Condition\_(Minimize\_startTime)](actions/Condition_(Minimize_startTime)-oooo.md)                                                  |
| [Définir\_une\_variable\_(Set\_startTime\_with\_Start\_time)](actions/Definir_une_variable_(Set_startTime_with_Start_time)-oooo.md) |
| [Initialiser\_la\_variable\_StartTime](actions/Initialiser_la_variable_StartTime-oooo.md)                                           |
