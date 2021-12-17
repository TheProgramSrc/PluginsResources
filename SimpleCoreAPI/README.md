# repositories.json

### What's this?
This contains all the repositories containing SimpleCoreAPI Modules, used to download them at runtime if required.

### Format
```json
[
  { 
    "url": "my-repo-url",
    "repo": "simplecoreapi-modules"
  },
  { 
    "url": "another-repo-url",
    "repo": "maven-public"
  }
]
```

### How the download system works
First the system will download the latest version available of the `repositories.json` file, 
then it will go through every repository looking for an artifact with the exact same name as the one provided in the 
module.properties file
