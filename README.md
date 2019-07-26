# Streamlabs-Chatbot-Scripts-Help
Here you are going to find valuable information for programming Streamlabs Chatbot scripts. (It's not finished yet)

## Pre-built Classes and its members

Variable type is indicated in the parenthesis after the variable.
- `Parent`
  - `.IsChatMessage()`
  - `.SendStreamMessage(message`(str)`)`
  - `.AddCooldown(ScriptName`(str)`, command_to_cooldown`(str)`, seconds_to_cooldown`(int)`)`
  - `.AddUserCooldown(ScriptName`(str)`, command_to_cooldown`(str)`, user_to_cooldown`(data.User)`, seconds_to_cooldown`(int)`)`
  - `.IsOnCooldown(ScriptName`(str)`, command_on_cooldown`(str)`)`
  - `.IsOnUserCooldown(ScriptNane`(str)`, command_on_cooldown`(str)`, user_on_cooldown`(data.User)`)`
  - `.GetCooldownDuration(ScriptName`(str)`, command_on_cooldown`(str)`)`
  - `.GetUserCooldownDuration(ScriptName`(str)`, command_on_cooldown`(str)`, user_on_cooldown`(data.User)`)`
  - `.AddPoints(whom_to_add_points`(str)`, points_amount`(int)`)`
  - `.GetPoints(whom_to_get_points`(data.User)`)`
  - `.RemovePoints(user_name`(str)`, points_amount`(int)`)`
  
- data
