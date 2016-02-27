# Ludobox Borgia

These are clean files for the Borgia game. It can be used as a sample to distribute your games using the [Ludobox](https://github.com/ludobox/ludobox) .


Each of your game should be made of :

* a folder named with the name of your game - ex : ```borgia```
* a JSON file containing information about your game - ex. ```/borgia/game-info.json```
* any files attached to the game - ex. ```/borgia/borgia-files.zip```

### Data model

Model of a JSON game description

    {
        "timestamp": "10/10/2015 14:52:35",
        "title": "Borgia, le jeu malsain",
        "description": "Ouais",
        "fab_time": "2+ h",
        "requirements": "IMPRIMANTE",
        "players": 4,
        "duration": "60+",
        "audience": "Adultes",
        "authors": "Michel",
        "illustrators": "Jean-Claude",
        "source": "Le vin",
        "license": "CC 1.0",
        "languages": "Français",
        "themes": "Médiéval, Salopard",
        "type": 0
    }
