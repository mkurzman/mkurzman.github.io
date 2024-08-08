# mkurzman.github.io

This is a first trial to use github pages based on https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
as preparation to test https://github.com/jgraph/drawio - integration

First test picture created with drawio:
![drawiotest](test.drawio.png "a dummy")

Mermaid Test (as copied from https://mermaid.js.org/syntax/classDiagram.html) 
```mermaid
classDiagram
      Blueprint <|-- ORT-Server
      Blueprint <|-- Fossology
      Blueprint <|-- ScanCodeIO
      Blueprint : +array UseCase
      Blueprint : +String abc
      Blueprint: +isStructure()
      Blueprint: +bac()
      class ORT-Server{
          +String abc
          +orchestrate()
          +analyze()
      }
      class Fossology{
          -String abc
          -orchestrate()
      }
      class ScanCodeIO{
          +bool is_Cool
          +orchestrate()
      }
```
