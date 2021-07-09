# OnlineModeFix
A Bukkit, hMod and Vanilla plugin to fix online-mode for old Minecraft servers.

## Bukkit
1. Move the jar into your server's plugin folder.
2. Set online-mode to true in the server.properties file.

## hMod
1. Move the jar into your server's plugin folder.
2. Add the plugin to the plugins list in server.properties (ex. plugins=OnlineModeFix).
3. Set online-mode to true in the server.properties file.

## Vanilla (or any other modded servers)
1. Move the jar next to your server jar.
2. Launch the server using this command:

`java -Djava.protocol.handler.pkgs=gg.codie.mineonline.protocol -cp minecraft_server.jar;OnlineModeFix.jar net.minecraft.server.MinecraftServer`
