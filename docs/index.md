# Waar staat de afkorting FTP voor?
#File Transfer Protocol
![Alt-tekst](ftp.jpg)


##
[pagina-1](index.md)
##
[pagina-2](extra.md)
##

[Naar veiligheid](#veiligheid-veiligheid)
##
# Definitie
1. FTP staat voor File Transfer Protocol, een standaard netwerkprotocol waarmee bestanden van de ene host naar de andere kunnen worden overgebracht via het internet. Het wordt gebruikt voor het uploaden, downloaden en beheren van bestanden op een server.

# Leg het concept uit in je eigen woorden
1. Een manier om een document via de ene pc naar de andere verkrijgen via een netwerk zoals het internet

# Hoe draagt FTP bij aan de functionaliteit van het internet?
FTP draagt bij aan de functionaliteit van het internet door een manier te bieden om bestanden over te brengen tussen verschillende computers via een netwerk, waardoor het gemakkelijk wordt om informatie te delen en bestanden te beheren. Het zorgt ervoor dat men bestanden kan uploaden of downloaden van een server.

### Veiligheid {#Veiligheid}
Het biedt beperkte beveiliging omdat de gegevens tijdens de overdracht niet versleuteld zijn, wat betekent dat ze kwetsbaar zijn voor afluisteren door kwaadwillende partijen. Het wordt daarom niet aanbevolen om FTP te gebruiken voor het overdragen van gevoelige/belangerijke informatie, tenzij er maatregelen worden genomen om de beveiliging te verbeteren, zoals het gebruik van Secure FTP (SFTP) of het instellen van beveiliging op serverniveau. In het algemeen wordt FTP als onveilig beschouwd.

# Welke rol speelt FTP bij het waarborgen van de beveiliging van online communicatie?
Ze speelen een beperkte rol in dit sinds ze maar beperkte beveileging hebben bv. tijdens het overdracht van documenten zijn ze niet versleuteld en kunnen ze dus afgeluisterd worden door andere partijen/mensen.




|                | FTP                          | SFTP                                 |
|----------------|------------------------------|--------------------------------------|
| Beveiliging    | Verzendt gegevens in platte tekst  | Versleutelt gegevens met SSH   |
| Authenticatie  | Gebruikersnaam en wachtwoord   | Gebruikt openbare sleutelauthenticatie        |
| Poort         | Gebruikt poort 21            | Gebruikt poort 22                     |
| Firewall       | Vereist extra geopende poorten  | Gebruikt meestal een enkele poort |
| Bestandsintegriteit | Geen ingebouwde integriteitscontroles | Ondersteunt bestandsintegriteitscontroles |
| Protocol       | FTP-protocol                 | SSH-protocol                        |
| Bestandsoverdrachten | Hervat niet onderbroken overdrachten | Ondersteunt hervatten en parallelle overdrachten |
[Lees meer](https://kinsta.com/nl/kennisbank/wat-is-ftp/)