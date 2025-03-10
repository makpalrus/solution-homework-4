# Singleton and Adapter in Java

## Description
This project demonstrates the use of two design patterns: **Singleton** and **Adapter**.

### Part 1: Singleton (ConfigurationManager)
**ConfigurationManager** is a global configuration manager that ensures that there is only one instance of it in the entire program. 

**Functions:**
- Stores predefined configuration parameters (maxPlayers, DefaultLanguage, gamedifficiency).
- Provides a method for getting configuration by key.
- Allows you to display all settings in the console.

### Part 2: Adapter (ChatServiceAdapter)
The adapter allows you to integrate an outdated chat system with a new interface.

**Functions:**
-**LegacyChatService** is an outdated service using `sendLegacyMessage()'.
- **ChatService** - new interface with `SendMessage()'.
- **ChatServiceAdapter** is an adapter that translates calls from `SendMessage()` to `sendLegacyMessage()'.


## Expected output
```
maxPlayers: 100
maxPlayers → 100
defaultLanguage → en
gameDifficulty → medium
Legacy Chat: Hello world!
```
