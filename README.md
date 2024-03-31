# Palestras de Lógicas Brasileiras

Esse github repo, parte da organizacao Logicas Brasileiras,  e' usado para descrever uma colecao de palestras/falas de logicas brasileiras.

<br>

Esse repo produz a pagina em https://logicasbrasileiras.github.io/Palestras/


## Contributing

To contribute a talk to the repo, go to the [data.json](https://github.com/WomeninLogic/RecordedTalks/blob/main/data.json) file and add an entry with the following details:

```
{"title": "Title of the talk",
"talk_link": "Link to the Youtube video",
"author": "speaker’s name",
"date": "Date of recording the talk",
"author_image": "Name of image as you have named it in the img/ folder",
"author_link": "Link to speaker’s website",
"description": "Short description of the talk."}
```

Add author’s image to the `img/` folder and make sure to link to the image under the `author_image` key of the database with the the exact name as you have given in the `img/` folder. Try to follow the convention for the name of the speaker photo `firstname-lastname.png'. Please don't use numbers only for the date, as conventions are different in the US and the rest of the world. The description of the talk should be very brief to fit in the allotted space.

Also, make sure that each of the entries you add are separated by a comma in the appropriate JSON format. You can ensure the data you have entered is in the correct format by validating the JSON file by copy pasting it in one of the JSON services like [JSONLint](https://jsonlint.com)
