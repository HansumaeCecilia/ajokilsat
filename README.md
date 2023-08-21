# Ajokilsat

Tämä on Expolla toteutettu sovellus ajokilometrien keräämiseen.
Projektin tarkoitus on harjoitella kännykkäsovellusten ohjelmointia.
Expolla toteutettuna sovellus toimii Androidilla ja iOS:llä, mutta 
tähän mennessä sitä on testattu vain Androidilla.

## Tietomallit



### Trip (Matka)

- `vehicle(*)` - ajoneuvo, jolla matka tehtiin
- `description(*)` - matkan kuvaus
- `odometerAtBegin` - matkamittarin lukema matkan alussa
- `odometerAtEnd` - matkamittarin lukema matkan lopussa
- `timestampAtBegin(*)` - aikaleima matkan alussa
- `timestampAtEnd(*)` - aikaleima matkan lopussa
- `track` - "jälki", johon tallennetaan matkan kulku  
- `routeDescription` - reitin kuvaus (esim: "Turku-Raisio-Turku")
    * Lista GPS-koordinaateista ja aikaleimoista

### Vehicle (Ajoneuvo)

- `name(*)` - nimi
- `registrationNumber` - rekisterinumero
