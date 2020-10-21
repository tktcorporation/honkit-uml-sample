# Introduction

- plantuml

```uml
@startuml

/'
  Comment
'/

    Class Stage
    Class Timeout {
        +constructor:function(cfg)
        +timeout:function(ctx)
        +overdue:function(ctx)
        +stage: Stage
    }
    Stage <|-- Timeout

@enduml
```

