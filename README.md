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

  
* [ ] Names: Only supporting givenName & familyName for now, need to add support middleName, phonetic, Prefix & Suffix
- [ ] Location: Geographical or location-based data.
- [ ] URLs: URLs like profiles, etc
- [ ] Streaming: The service processes requests sequentially and does not support streaming output.


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

## 🔜 Coming soon

## Known issues
- [ ]  Podman installs fails sometimes https://github.com/containers/podman/issues/23784#issuecomment-2315351722
