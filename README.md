# Source Engine Configuration server files

For pure_whitelist... files, is supposed to used as .txt files. And sv_pure needs to be 1

# Wiki and guide for configuration

pure_server_full.txt and pure_server_whitelist.txt will work together
pure_server_full it's the root file that defines what  could be blocked, allowed folder/files from customization.
custom server files will be configured here.

pure_server_whitelist could be use for allowing client files modifications at all, after first rules that have been set in the pure_server_full.

These pure configurations are about to 90% complete. Some folders are probably missing, but could be ignored.

Last warning, maps that have custom resource, texture, models etc, paked into their .bsp, will replace any custom file of client if has, so no need to add those to the pure files.

You could find more concise and official information at:
https://developer.valvesoftware.com/wiki/Pure_Servers
