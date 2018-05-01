
# collect requirements
- **what is it ?**
- **is it important ?**
- **tools ?**

# wireframe
- **what is it ?**
- **tools ?**

# I select top down development
- **what is it ?**

# LAYERS

## UI
### REACTJS

## API
### OPEN API

## SERVICE
### SPRING BOOT

## DATA
### SPRING DATA JPA



# CREATE PROJECT
As a user I want to select **FROM** country and **TO** country so that I can see Financial Exchange line chart

## TASKS
### 1. UI
1. create react project
2. implement fx dashboard panel
3. implement country select
4. implement fx rate chart
5. combine fx dashboard ui elements

### 2. BACKEND
#### 1. API
1. implement country list endpoint
2. implement fx rate endpoint

#### 2. SERVICE
1. implement country list service
2. implement fx rate service

#### 3. REPOSITORY
1. implement country list repository
2. implement fx rate repository

#### 4. COMBINE ALL
1. combine fx dashboard ui, api, service and repository implementations



## EXAMINE DOMAIN

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
  - Spring Boot
  - H2 Database In Memory
- Software Project Management
  - Maven

### UI
- Draw Wireframe
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
