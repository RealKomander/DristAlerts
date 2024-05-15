Maven dependency setup:

```
<repositories>
    <repository>
        <id>DristAlerts</id>
        <url>https://raw.githubusercontent.com/RealKomander/DristAlerts/main/</url>
    </repository>
</repositories>
```
```
<dependencies>
    <dependency>
        <groupId>dristmine</groupId>
        <artifactId>DristAlerts</artifactId>
        <version>1.20.4</version>
    </dependency>
</dependencies>
```
Currently supports 1.20.4 only.

Usage:

sendGlobalMessage(message, permission, sound) - sends a global message to every player with the specified permission. Can also play a sound.

sendPrivateMessage(message, permission, sound, player) - sends a local message to the player if they have the permission. Can also play a sound.
