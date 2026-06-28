# Docker Templates

This is a respository with Docker compose templates.

## How to add new template

1. Create a new folder with with a Docker compose file.
2. Add template to `templates.json` file.
```
    {
      "type": 3,
      "title": "<Title>",
      "description": "<Desription>",
      "logo": "<Logo>,
      "categories": ["<Category>"],
      "repository": {
        "url": "https://github.com/Pathfinder9021/Docker-Templates",
        "stackfile": "<Folder>/compose.yaml"
      }
    },
```
__Note__: An icon for application can be found on [dashboardicons.com](https://dashboardicons.com/).