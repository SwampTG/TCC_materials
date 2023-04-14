# Securing microservices and microservice architectures: A systematic mapping study


## Objectives


- Main threats. Studies that identify threats and propose solutions;
- Ontology.


## Intro


- Competition. Tech advance. Constant changes.
- Maintainability, reusability, modularity;
- Use of architectures;
- Fine grained Components;
- MSA -> lightweight services. Business function.
- INDEPENDENT.
- HETEROGENEOUS.
- Novel hype -> flaws -> Security -> communication overflow && entry-points;
- Software security -> only after computer network spreading;
- Adopters: Netflix &&  Amazon


## MSA


- Fine-grained; Loosely coupled;
- Can be only one function of the business;
- HTTP APIs or brokers;
- Containers
- Quality: Reusability; Interoperability; Scalability; Maintainability;


## Methodology


- RQs: 
  - Most addressed risks -> classification.
  - Approaches and techniques for security;
  - Levels of applicability - Domains;
  - Platform dependent or independent.


## Mapping


- Threats
  - Insiders
  - External: Most addressed
  - Classification: From target:
    - User-based: Direct or indirect;
    - Data: Replay, Sniffing, Exposure, MiTM;
    - Infrastructure;
    - Software: Injection, compromise service...

- Tools and mechanisms:
  - **General security;**
  - **Framework modules;**
  - **Techniques (other domains);**
  - Tools;
  - Protocols;
  - Analysis (compare, discuss);

- Solutions
  - Authentication x Authorization
  - Auditing: Discover gaps and initiate measures (automatically) or only report;
  - Mitigation: Attacks happen in a limited environment;
  - Prevention: New systems;

- MSA Layers
  - Microservice
  - Composition
  - API
  - Communication
  - Deployment -> Containers -> Configs and untrusted images


## Discussion


- Most attacks are internal - Minimum works about this;
- External: Easier to be handled;
- Insiders can have dangerous privileges and access to data exposure;
- Software, user based, data attacks > infra
- Suggestion: investigate all OWASP identified vulnerabilities with effects;
- Low mitigation research;
- Every study should do performance analysis;
  

