<h1 align="center">reply-bot</h1>
<p align="center">
  <img alt="Java" src="https://img.shields.io/badge/Java-11+-ED8B00?logo=openjdk&logoColor=white">
  <img alt="Telegram Bot API" src="https://img.shields.io/badge/Telegram%20Bot%20API-2CA5E0?logo=telegram&logoColor=white">
  <img alt="Gson" src="https://img.shields.io/badge/Gson-2CA5E0?logo=google&logoColor=white">
  <img alt="Status" src="https://img.shields.io/badge/status-stable-green">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-blue">
</p>

<br>

**reply-bot** is a lightweight Telegram support bot. Enables seamless communication between users and moderators with message routing and access control.

## features

- user-to-moderator message forwarding
- moderator replies via `/reply <user_id> <message>` command
- moderator whitelist validation
- async message processing
- simple JSON-based configuration

## installation

### prerequisites:

- Java 11+
- Maven 3.6+
- Telegram Bot token

### from source:

```bash
git clone https://github.com/yourusername/vpn-support-bot.git
cd vpn-support-bot
mvn clean package
java -jar target/vpn-support-bot.jar
