# json-tech-talk-public

Teknisk Format:
Man starter en JSON fil ved enten at have et array[ ] eller et objekt { } og bruger komma som separator mellem statements. Et objekt er et såkaldt ‘key value pair’, med andre ord har den en key som er en string og dens value kan være alle datatyper.

DataTyper:
[] : arrays
“” : strings
1 : numbers
true : boolean
{} : objects

Eksempel på en json fil ligger i bunden.

C#
https://docs.microsoft.com/en-us/dotnet/standard/serialization/system-text-json-how-to

I C# kan man tilgå namespacene System.Text.Json. og System.Text.Json.Serialization for at arbejde med json filer. Vi anbefaler at læse den officielle microsoft dokumentation igennem (Det overstående link). 

Teori
Vi anbefaler at se codingtrain’s 4 første videoer på playlisten i linket som handler om json og data på web.
https://www.youtube.com/watch?v=rJaXOFfwGVw&list=PLRqwX-V7Uu6a-SQiI4RtIwuOrLJGnel0r

At ‘deserialize’ betyder at man tager noget rå tekst som er et hvis format, og konvertere det til objekter i et givent programmeringssprog. 

At ‘serialize’ er det modsatte. Man tager et objekt i et givent programmeringssprog og konvertere det til rå tekst.


Opgave:
Du skal lave en opgave som kan læse fra en json fil og skrive til en json fil. 
Den læste json fil skal kunne konverteres til et c# objekt. 
Samt skal du kunne lave et nyt c# objekt og skrive det til en json fil.

Json filen skal indeholde: et number, string, boolean, string array, og et objekt array.
Se det nedenstående eksempel på en json fil.
Man kan med fordel bruge linket til microsoft’s dokumentation af hvordan man læser og skriver til en json fil.
Hvis dokumentationen og stackoverflow ikke er tilstrækkeligt kan man spørge Json master gruppen.

```json
{
  "name": "Oliver",
  "age": 21,
  "isMale": true,
  "hobbies": [
    "coding",
    "gaming"
  ],
  "computers": [
    {
      "id": "macbook",
      "model": "m12"
    },
    {
      "id”: "pc",
      "model": "custom"
    }
  ]
}
```
