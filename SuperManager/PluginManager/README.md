# Plugin Manager Module
This folder holds all the files required for the PluginManager Module

## How to add plugins?
Just use the following format:
```json
{
  "id": 1,
  "name": "SuperAuth",
  "platform": "TheProgramSrc",
  "fileName": "{Name}-{Version}.jar"
}
```

\> `id`: The ID number of the product in their Platform<br>
\> `name`: The name of the plugin (Can be found in the plugin.yml file)<br>
\> `platform`: For now it can be either "Spigot" or "Songoda", more marketplaces will be added soon.<br>
\> `fileName`: The name of the file to save in the update folder. Available placeholders: `{Name} - Product Name`, `{Version} - Product Version`
