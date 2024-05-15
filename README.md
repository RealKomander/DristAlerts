Maven dependency setup:

<repositories>
    <repository>
        <id>DristAlerts</id>
        <url>https://raw.githubusercontent.com/RealKomander/DristAlerts/main/</url>
    </repository>
</repositories>

<dependencies>
    <dependency>
        <groupId>dristmine</groupId>
        <artifactId>DristAlerts</artifactId>
        <version>1.20.4</version>
    </dependency>
</dependencies>

Currently supports 1.20.4 only.

Usage:
DristAlerts.sendGlobalMessage(String message, String permission, Sound sound) - sends a global message to every player with the specified permission. Can also play a sound.
DristAlerts.sendPrivateMessage(String message, String permission, Sound sound, Player player) - sends a local message to every player with the specified permission. Can also play a sound.
