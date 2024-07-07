# plantuml-experiment
Experiment with PlantUML


## Example with live generated image
Using the plantUML server that links to a file in this repo. No need for secrets, keys, accounts, pipelines, just a link.

![Alice-Bob](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/amkuipers/plantuml-experiment/master/alice-bob.iuml)


Copied example with file structure examples.

![filestruct](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/amkuipers/plantuml-experiment/master/filestruct.iuml)



## Example with embedded (to do)

Code block with PlantUML. Adding a GitHub Action to generate the image; this is not needed using mermaid.js or on gitlab.

```plantUML
@startuml
Alice -> Bob: test
@enduml
```
