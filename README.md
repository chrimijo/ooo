This Power Automate flow activates automatic out-of-office replies with the following settings:
- Recurs every 2 hours.
- Initiates at 18:00 on the evening before the first full-day out-of-office status with the subject "ooo."
- Deactivates at midnight following the last full-day out-of-office status with the subject "ooo."
- If the last "ooo" day falls on a Friday, the replies extend until midnight the following Monday.
- Configures distinct reply messages for both internal and external recipients, specifying the return-to-office date.

[Documentation](index-oooo.md), made with https://github.com/modery/PowerDocu

[Realease](/release/)

Highly inspired from the follwing archived repository https://github.com/toaomatis/AutoffOffice initialy made by [Toaomatis](https://github.com/toaomatis)




