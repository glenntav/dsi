# Simple, scalable and agile VTL execution

## Package management
- Nice because | makes | VTL execution | simple and practical | in the SDMX context
- For production use cases | need a way | package | distribute VTL
- For this | Transformation Schemes | FMR
- Transformation Scheme | artefact | Information Model
- FMR | Free | Open source | SDMX *object* repository

## Scalability
- Packaging VTL as Transformation Schemes | & using FMR as a VTL repo | means | business logic | can be decoupled from | data processing mechanics
- This separation of concerns | makes | data ops more scalable
- Business rules & data structures | reused across multiple processes
- This reduces duplication | & promotes modular, composable pipelines
- Also benefits for | external data collection
- Using this model | all reporters | have instant access | collector's VTL business rules
- That means | use vtlengine & pysdmx | programmatically check data | before submission | guaranteeing integrity | eliminating propagation of bad data 

## Agility
- Moreover
- Because | business logic | separated from | data processing mechanics | two can evolve independently
- Business users | take control | of their | business logic & quality rules | which can iterate rapidly | without code changes
- Not only | relieve the burden on IT specialists | & data engineers
- All data reporters | automatically use latest rules | with zero effort
- Making data ops | more agile

## Conclusion
- vtlengine | democratises VTL execution
- pysdmx |  helps VTL work nicely | in the SDMX context
- FMR | productionises whole thing
- Together | these combine to make | VTL execution simple | scalable | & agile
