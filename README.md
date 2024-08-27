# rolodexpal

## 📦 | Install instructions (Mac Only)
* Control click to install application
  *   ![Screenshot 2024-08-21 at 3 41 12 PM](https://github.com/user-attachments/assets/42869083-2806-414f-a92c-bb3d98d22518)
  *   If you are running the latest version of the MacOS, you will have to open settings -> Privacy & Security -> Open Anyway!
  *   This is an interim step during the testing phase, we plan to release the app in the app store!
* Make sure you have homebrew installed on your machine
* Reached out to make sure your gmail ID is added to list of testers!
* While installation you will be asked for this permission
  * ![Screenshot 2024-08-15 at 11 10 34 AM](https://github.com/user-attachments/assets/029fa5f4-5d43-473e-8bab-3d94a3ef1749)
  * Why: we don't have a server so everything runs on your machine, this pemission is to install that software!
  * This is an interim step during the testing phase, we plan to release the app in the app store!
* The installation will take sometime! 

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
- [ ] Names: Only supporting givenName & familyName for now, need to add support middleName, phonetic, Prefix & Suffix
- [ ] Location: Geographical or location-based data.
- [ ] URLs: URLs like profiles, etc
- [ ] Streaming: The service processes requests sequentially and does not support streaming output.
