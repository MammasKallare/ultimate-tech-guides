# Snabb guide till hemsidan

### Hemsidan är nere
Om hemsidan är nere så kan det bero på att servern hade problem att starta om. Detta kan bero på att servern inte hade släppt porten innan den försökte starta om.

För att fixa detta logga in på servern (Referera till login info)
Och kör följande kommandon:

Kolla om servern är nere:
```
sudo service nginx status
```
Starta servern:
```
sudo service nginx start
```
