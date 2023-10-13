# Software-Deployment-Lab1

Um das Template zu verwenden muss dieses und die .paramemters.json Datei runtergeladen werden.
Anschließend muss man sich dann über den Befehl
```az login```
mit seinem Microsoft Azure Account verbinden.

Falls die Azure CLI nicht installiert wurde, muss diese runtergeladen werden.
Wenn noch keine Ressourcengruppe erstellt wurde, muss diese über den "Erstellen"-Button erstellt werden. Das selbe gilt für einen App-Service Plan.

In der Parameterdatei sollten die Paramenter so geändert werden, wie man sich persönlich haben will. 

Dann kann man über Azure CLI mit dem Befehl 

```az deployment group create --resource-group DEINE_RESOURCE_GROUP --template-file Pfad\zu\deinem\Lab1_azuredeploy.json --parameters Pfad\zu\deiner\Lab1_azuredeploy.parameters.json```

das Template ausführen. 
