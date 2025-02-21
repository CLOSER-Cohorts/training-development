
# Basic Training Overview


``` mermaid

flowchart TD

  Basic --> WID[What is Data]
  Basic --> WIM[What is Metadata]
  Basic --> WIF[What is FAIR]
  Basic --> WP[Provenance]
  Basic --> MC[Metadata Components]
  Basic --> MS[Metadata Standards]
  Basic --> MR[Metadata Relationships]
  WID --> WIDD[Definition]
  WIDD --> CMD[Concept, Measure,Data]
  WIM --> WIMD[Definition]
  WIMD --> Components
  Components--> Roles
  Roles --> Users
  WIF --> WIFD[Definitions]
  WIFD --> WIFDR[Roles]
  WIFDR --> WIFDU[Users] 
  WIFDU --> WIFDI[Implementing]
  WIFDI --> Responsibilities
  WP --> Concepts
  MC --> MCCatalogue[Catalogues]
  MCCatalogue --> MCClass[Classifications]
  MCClass --> CV[Controlled Vocabularies]
  CV --> MCDatasets[Datasets]
  MCDatasets --> MCQuestionnaires[Data Collection instruments]
  MS --> MSCatalogue[Catalogues]
  MSCatalogue --> MSClass[Classifications]
  MSClass --> MSCV[Controlled Vocabularies]
  MSCV --> MSDatasets[Datasets]
  MSDatasets --> MSQuestionnaires[Data Collection instruments]
  MR --> RD[Research Data Lifecycle]
  
    style Basic color:#FFFFFF, stroke:#00C853, fill:#00C853
    style WID color:#FFFFOO, stroke:#00C853, fill:#90ee90
    style WIDD color:#FFFFOO, stroke:#00C853, fill:#90ee90
    style CMD color:#FFFFOO, stroke:#00C853, fill:#90ee90
    style WIM color:#FFFFFF, stroke:#00C853, fill:#87A96B
    style WIMD color:#FFFFFF, stroke:#00C853, fill:#87A96B
    style Components color:#FFFFFF, stroke:#00C853, fill:#87A96B
    style Roles color:#FFFFFF, stroke:#00C853, fill:#87A96B
    style Users color:#FFFFFF, stroke:#00C853, fill:#87A96B
    style WIF color:#FFFFOO, stroke:#00C853, fill:#ACE1AF
    style WIFD color:#FFFFOO, stroke:#00C853, fill:#ACE1AF    
    style WIFDI color:#FFFFOO, stroke:#00C853, fill:#ACE1AF    
    style WIFDU color:#FFFFOO, stroke:#00C853, fill:#ACE1AF    
    style WIFDR color:#FFFFOO, stroke:#00C853, fill:#ACE1AF    
    style Responsibilities color:#FFFFOO, stroke:#00C853, fill:#ACE1AF  
    style WP color:#FFFFOO, stroke:#00C853, fill:#8FBC8B
    style Concepts color:#FFFFOO, stroke:#00C853, fill:#8FBC8B
    style MC color:#FFFFFF, stroke:#00C853, fill:#50C878
    style MCCatalogue color:#FFFFFF, stroke:#00C853, fill:#50C878   
    style MCClass color:#FFFFFF, stroke:#00C853, fill:#50C878   
    style MCDatasets color:#FFFFFF, stroke:#00C853, fill:#50C878   
    style CV color:#FFFFFF, stroke:#00C853, fill:#50C878   
    style MCQuestionnaires color:#FFFFFF, stroke:#00C853, fill:#50C878   
    style MS color:#FFFFFF, stroke:#00C853, fill:#6B8E23
    style MSCatalogue color:#FFFFFF, stroke:#00C853, fill:#6B8E23   
    style MSClass color:#FFFFFF, stroke:#00C853, fill:#6B8E23   
    style MSDatasets color:#FFFFFF, stroke:#00C853, fill:#6B8E23   
    style MSCV color:#FFFFFF, stroke:#00C853, fill:#6B8E23   
    style MSQuestionnaires color:#FFFFFF, stroke:#00C853, fill:#6B8E23  
    style MR color:#FFFFFF, stroke:#00C853, fill:#71BC78
    style RD color:#FFFFFF, stroke:#00C853, fill:#71BC78
    
