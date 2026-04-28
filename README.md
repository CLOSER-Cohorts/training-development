# Training Development

This repositpory is for work in progress and archived materials from training courses

Latest versions of 

- Introduction and
- Foundation

are now at https://github.com/CLOSER-Cohorts/understanding-metadata


## Training Plan Overview

``` mermaid

flowchart TD

  Introduction --> WID[What is Research Data]
  WID --> WIM[What is Research Data Management ]
  WIM --> WIF[What is FAIR]
  WIF --> WP[What is Metadata]
  WP --> MC[Metadata in the Research Data Lifecycle]
  MC --> MS[Using Metadata]
  MS --> MR[Metadata standards]

  Foundational --> FDC[Who should create metadata]
  FDC --> FMR[Why metadata matters]
  FMR --> FAIR[Metadata components]
  FAIR --> FID[Metadata relationships]
  FID --> FMC[What metadata to create]
  FMC --> FMS[Considerations for what metadata to create]
  FMS --> HTC[How to create metadata]

  Advanced --> DDICU[Metadata reuse]
  DDICU --> DDICI[Identification]
  DDICI --> DDILU[Versioning]
  DDILU --> DDILI[Schemas]
  DDILI --> MI[Interoprability]
  MI --> FAIRI[FAIR Infrastructures]
  FAIRI --> DSMW[Designing sustainable workflows]


  SpecialisedXYZ --> RM[ e.g. Repeated Measures]
 RM --> RMU[What are repeated measures]
 RMU --> DDIL[DDI Lifecycle]
 DDIL --> VC[Variable cascade]

 SpecialisedABC --> ML[ e.g. Machine Learning]
 ML --> MLTD[Metadata for training datasets]
 MLTD --> MLP[Provenance]
 MLP --> BP[Best practice]

    
    style Introduction color:#FFFFFF, stroke:#00C853, fill:#00C853
    style WID color:#FFFFOO, stroke:#00C853, fill:#90ee90
    style WIM color:#FFFFOO, stroke:#00C853, fill:#90ee90
    style WIF color:#FFFFOO, stroke:#00C853, fill:#90ee90
    style WP color:#FFFFOO, stroke:#00C853, fill:#90ee90
    style MC color:#FFFFOO, stroke:#00C853, fill:#90ee90
    style MS color:#FFFFOO, stroke:#00C853, fill:#90ee90
    style MR color:#FFFFOO, stroke:#00C853, fill:#90ee90
    style Foundational color:#FFFFFF, stroke:#2962FF, fill:#2962FF
    style FDC color:#FFFFFF, stroke:#00C853, fill:#318CE7
    style FAIR color:#FFFFFF, stroke:#00C853, fill:#318CE7
    style FMC color:#FFFFFF, stroke:#00C853, fill:#318CE7
    style FID color:#FFFFFF, stroke:#00C853, fill:#318CE7
    style FMS color:#FFFFFF, stroke:#00C853, fill:#318CE7
    style HTC color:#FFFFFF, stroke:#00C853, fill:#318CE7
    style FMR color:#FFFFFF, stroke:#00C853, fill:#318CE7
    style Advanced color:#FFFFFF, fill:#AA0000, stroke:#AA00FF
    style DDICU color:#FFFFFF, stroke:#00C853, fill:#E62020
    style MI color:#FFFFFF, stroke:#00C853, fill:#E62020
    style FAIRI color:#FFFFFF, stroke:#00C853, fill:#E62020
    style DSMW color:#FFFFFF, stroke:#00C853, fill:#E62020
    style DDICI color:#FFFFFF, stroke:#00C853, fill:#E62020
    style DDILU color:#FFFFFF, stroke:#00C853, fill:#E62020
    style DDILI color:#FFFFFF, stroke:#00C853, fill:#E62020
style SpecialisedXYZ color:#FFFFFF, fill:#AA00FF, stroke:#AA00FF
style SpecialisedABC color:#FFFFFF, fill:#AA00FF, stroke:#AA00FF 

style RM color:#FFFFFF, fill: #D580FF, stroke:#AA00FF
style RMU color:#FFFFFF, fill: #D580FF, stroke:#AA00FF
style DDIL color:#FFFFFF, fill: #D580FF, stroke:#AA00FF
style ML color:#FFFFFF, fill: #D580FF, stroke:#AA00FF
style MLTD color:#FFFFFF, fill: #D580FF, stroke:#AA00FF
style MLP color:#FFFFFF, fill: #D580FF, stroke:#AA00FF
style BP color:#FFFFFF, fill: #D580FF, stroke:#AA00FF
style VC color:#FFFFFF, fill: #D580FF, stroke:#AA00FF

 
