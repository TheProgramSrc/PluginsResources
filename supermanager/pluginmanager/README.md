# Plugin Manager Module Files

Those files are for the PluginManager Module, if you want to manually add one you need to download the file and place it 
inside the plugin folder, usually the name of the plugin is the folder name, i.e. for PlaceholderAPI the folder location is
`server_root/plugins/PlaceholderAPI/` and the file should be placed like `server_root/plugins/PlaceholderAPI/SuperManager.json`

The format to store the files here is `PluginName.json`, but if you download the file make sure to rename it to `SuperManager.json`

The json format is this:
```json
{
  "id": 6245,
  "name": "PlaceholderAPI",
  "songoda": false
}
```
- `ID`: The id is the identifier of the product, in songoda and spigotmc the url format is `.../productname.id/...` the id is always a number greater than 0. 
- `NAME`: The name comes from the plugin.yml file inside the plugin jar, usually it's the same name as the product name, but if you're not sure, you can try 
to [decompile the plugin](http://java-decompiler.github.io/#jd-gui-overview), and if is not allowed by the terms of service of the product, ask to the creator. We are not asking you to decompile it, the best 
solution would be asking to the creator of the product.
- `SONGODA`: Only set to true if the product is from songoda.com, if is not, set it to false. If the product comes from Songoda and Spigot, we recommend you to use
to use songoda because their API is easy to use than the one from spiget.
