
[comment]: # (Total : 84 hours, 10.5 day)
# HOW TO START
[comment]: # (2 hours)
## collect requirements
- **what is it ?**
- **is it important ?**
- **tools and techniques ?**
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
