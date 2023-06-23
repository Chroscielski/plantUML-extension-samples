# plantUML-extension-samples

```
@startuml
!include 
Person(personAlias, "Label", "Optional Description")
Container(containerAlias, "Label", "Technology", "Optional Description")
System(systemAlias, "Label", "Optional Description")


System_Ext(extSystemAlias, "Label", "Optional Description")


Rel(personAlias, containerAlias, "Label", "Optional Technology")


Rel_U(systemAlias, extSystemAlias, "Label", "Optional Technology")
@enduml
```
