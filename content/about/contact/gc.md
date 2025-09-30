# Simple, scalable and agile VTL execution

## Package management
- Nice because | makes | VTL execution | simple and practical | in the SDMX context
- For production use cases | need a way | package | distribute VTL
- For this | Transformation Schemes | FMR
- Transformation Scheme | artefact | Information Model
- FMR | Free | Open source | SDMX *object* repository

## Scalability
- Packaging VTL | as Transformation Schemes | & using FMR as a VTL repo | means that business logic | can be decoupled from | data processing mechanics
- And it's this separation of concerns | that makes | data ops more scalable...
- Business rules & data structures | reused across multiple processes  
- Reduces duplication | & importantly promotes modular, composable pipelines
- Also benefits for | external data collection
- Using this model | all reporters | have instant access | collector's VTL business rules
- That means | use vtlengine & pysdmx | programmatically check data | before submission | which guarantees integrity | & eliminates propagation of bad data 

## Agility
- And there's more
- Because business logic | separated from | data processing mechanics | two can evolve independently
- Business users | take control of | their business logic & quality rules | which can iterate rapidly | without pipeline changes | which relieves burden on IT specialists & data engineers 
- Moreover | data reporters | automatically use latest rules | with zero effort
- Making data ops | more agile

## Conclusion
- vtlengine | democratises VTL execution
- pysdmx |  helps VTL work nicely | in the SDMX context
- FMR | productionises whole thing
- Together | these combine to make | VTL execution simple | scalable | & agile

