
[comment]: # (Total : 84 hours, 10.5 day)
# HOW TO START

[comment]: # (2 hours)
## COLLECT REQUIREMENTS
- **what is it ?** to understand what CUSTOMER NEEDS, not what they WANTS

- **what do i need to ?**
  - ask questions
  - define scopes
  - use **S.M.A.R.T.**
    - **S**pecific
    - **M**easurable
    - **A**greed upon
    - **R**ealistic
    - **T**ime based
  - use **MoSCoW** principle
    - Must have
    - Should have
    - Could have
    - Won't have (this time)
  - confirm that what did you understand
  - change is an inevitable so, be ready to negotiate with using time and money advantages


- **is it important ?** no doubt, yes :)

- **tools and techniques ?**

  - techniques
    - `mind maps :` to capture ideas, requirements and help organize a conversation with many tangents  
    - `context diagram :` birds view
    - `textual analysis :` collect customer needs and extract key terms
    - `user stories :`  analyse function of a system
    - `use case diagram :` detail function interaction between x and y
    - `functional decomposing :` extract functions
    - `sequence diagram :` detail interactions
    - `swim lane process model :` understand business processes

  - tools
    - visual paradigm
    - plantuml
    - enterprise architect


>**Use Case versus Functional Decomposition**
Use cases stand for functions, functional decomposing stand for details of functions

**links**
- https://en.wikipedia.org/wiki/Requirements_analysis
- https://scs.ewi.utwente.nl/files/teaching/guidelines_v211.pdf
- https://www.pmexamsmartnotes.com/collect-requirements-process-tools-and-techniques-part-1-of-2/
- https://www.pmexamsmartnotes.com/collect-requirements-process-tools-and-techniques-part-2-of-2/
- https://en.wikipedia.org/wiki/Functional_decomposition#Software_architecture
- https://stackoverflow.com/questions/38418346/functional-decomposition-vs-use-case
- https://www.projectsmart.co.uk/requirements-gathering.php
- https://en.wikipedia.org/wiki/MoSCoW_method
- https://wikimatze.de/smart-principle/
- https://en.wikipedia.org/wiki/SMART_criteria

[comment]: # (2 hours)
## prototype
- **what is it ?**
- **tools and techniques ?**

[comment]: # (4 hours)
## I select top down development
- **what is it ?**

# CREATE PROJECT
As a user I want to select **FROM** country and **TO** country so that I can see Financial Exchange line chart

## TASKS

[comment]: # (20 hours)
### 1. UI
1. create react project
2. implement fx dashboard panel
3. implement country select
4. implement fx rate chart
5. combine fx dashboard ui elements

### 2. BACKEND

[comment]: # (16 hours)
#### 1. API
1. implement country list endpoint
2. implement fx rate endpoint

[comment]: # (16 hours)
#### 2. SERVICE
1. implement country list service
2. implement fx rate service

[comment]: # (8 hours)
#### 3. REPOSITORY
1. implement country list repository
2. implement fx rate repository

[comment]: # (8 hours)
#### 4. COMBINE ALL
1. combine fx dashboard ui, api, service and repository implementations

## EXAMINE DOMAIN

[comment]: # (8 hours)
### TECHNOLOGIES

- Frontend
  - React JS
    - Material UI
  - Test
    - Jest
    - Chai
    - Enzyme

- Backend
  - API
    - Rest
      - Open API
      - Spring Rest
  - SERVICE
    - Spring
  - REPOSITORY
    - Spring Data
    - H2 Database In Memory
  - Test
    - Spring Test

- Software Project Management
  - Maven

### UI
- Draw Prototype
  - FX Dashboard Panel
  - Country List Select for **FROM**
  - Country List Select for **TO**
  - FX Rate Chart
  - Animate Story
- Extract Components
  - Panel
  - Select
  - Chart

### BACKEND

#### API
  - Country
    - List Endpoint
  - FX
    - Rate Endpoint

#### SERVICE
  - Country Service
    - List Country
  - FX Service
    - Rate

#### REPOSITORY
  - Country Repository
    - List
  - FX Repository
    - Rate
