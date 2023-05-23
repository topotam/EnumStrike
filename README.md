# EnumStrike
``` 
___________                        _________ __         .__ __           
\_   _____/ ____  __ __  _____    /   _____//  |________|__|  | __ ____  
 |    __)_ /    \|  |  \/     \   \_____  \\   __\_  __ \  |  |/ // __ \ 
 |        \   |  \  |  /  Y Y  \  /        \|  |  |  | \/  |    <\  ___/ 
/_______  /___|  /____/|__|_|  / /_______  /|__|  |__|  |__|__|_ \\___  >
        \/     \/            \/          \/                     \/    \/ 
```
Cobalt Strike Aggressor script to automate host and domain enumeration.

Content:

Host Discovery :

        - Seatbelt :
                -> -group=user
                -> -group=system
                -> -group=remote
                -> -group=misc

        - Credentials dump :
                -> LSA secret
                -> Logonpassword
                -> SAM dump
                -> Ticket list
                -> Wifi password
                -> Password in registery (HKLM)
                -> Password in registery (HKCU)
                -> SharpWeb

        - Privilege Esclation :
                -> SharpUp
                -> PrivescCheck

Domain Discovery :

        - Domain information
        - Domain controller
        - Trust information
        - User list
        - Computer list
        - Group list
        - GPO list
        - GPO local group
        - OU list
        - MSSQL instance
        - Kerberoastable user
        - Asreproastable user
        - Logged on
        - Net session
        - RDP session
        - DFS share
        - Share finder
        - Search deleguation (user)
        - Search deleguation (computer)
        - DNS record
        - Run sharphound

Import module :

        - PowerView
        - PowerUpSQL
        - Powermad
        - PrivescCheck
        - Inveigh
        - Clear

Credit :

    https://github.com/PowerShellMafia/PowerSploit
    https://github.com/NetSPI/PowerUpSQL
    https://github.com/r3motecontrol/Ghostpack-CompiledBinaries
    https://github.com/BloodHoundAD/BloodHound
    https://github.com/akenofu/Sharp-Wifi-Password-Dump
    https://github.com/djhohnstein/SharpWeb
    https://github.com/Kevin-Robertson/Powermad
    https://github.com/Kevin-Robertson/Inveigh
