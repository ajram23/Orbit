# Orbit

## 📦 | Install instructions (Mac Only)
* Double Click and install :) Notarized by apple :) 

## Post Install
* You will be asked for permissions
  * ![Screenshot 2024-08-15 at 11 10 16 AM](https://github.com/user-attachments/assets/eb336dee-9a66-4846-a010-f30c8360eae8)
  * This is for Google Sign.
* Downloading & parsing the contacts will take sometime, we have to understand all of your contacts 🤩

## 💬 List of Use Cases

# 🙋 Questions
* What do you know about [🧍]?
* When did I meet [🧍]?
* What common interests do I have with [🧍] and [👩🏼‍🤝‍👨🏽]?
* I am in the mood for Sichuan in NYC. Who should I ask?
* What events are coming up in the next week? (including Checkins)?
* Who do I know really well from Goldman Sachs?
* Do I know any product managers at Google?

# 📝 Edits
* I'd like to check in with [🧍] 2 days, can you update it?
* I met with [🧍] this past Sunday, can you please update it?
* I connected with [🧍] today, please record it!
* [🧍], unfortunately passed away on April 6th this year, please make note of it!
* Can you change [🧍]'s familiarity to someone I am friendly with 
* Can you update [🧍] interests to include swimming
* [🧍] works at [🏢] as a VP of Product in the Cloud Division. Can you make an update?

- Location: Geographical or location-based data.
- URLs: URLs like profiles, etc
- Streaming: The service processes requests sequentially and does not support streaming output.

# Updates
- Whenever you launch the app, its shows you
  - the upcoming celebrations (Birthday's/Anniversaries)
  - Scheduled Checkins
  - Reminders for followups
    
## ❌ Not Supported
### We take a very conservative approach to deleting data, so for now its not supported
- [ ] Can’t add new labels - for instance you can’t say “add assistant’s email“ unless its predefined in your data.
- [ ] Can't add or remove groups
- [ ] Add the ability to remove
- [ ] Add the ability to delete

## ⊯ Limitations
- Labels for fields like emails, phones, relationships will default to Other
- We only create columns for fields that have data, because we need to train our system with the data, Adding data later doesnt retrain or work at the moment.

  
### 📝 Updates
- [ ] Adding a new contact (need to change update to create/edits)
- [ ] Multiple updates for one contact
- [ ] Addition new relationships (Doesn’t need to find a match!)

## Added support for MCP server
Open Claude Desktop
Goto Settings
Click on Developer
Click Edit Config
Open claude_desktop_config.json
Make sure it has orbit-mcp, here are the details
{
  "mcpServers": {
    "orbit-mcp": {
      "command": "npx",
      "args": [
        "@orbitapp/orbit-mcp@latest"
      ]
    }
  }
}
Close the app & reopen Claude
You should see an hammer icon with the number 3 (if you only have orbit-mcp), clicking on it will show you available MCP tools
Now open a new conversation. You now have can send texts, draft emails and put your contacts to work!

