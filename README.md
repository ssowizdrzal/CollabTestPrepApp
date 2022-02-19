

<span>Demonstration project</span>
<h1 style="margin-top: 5px;" > CollabTestPrepApp </h1>
An application that enables group creation of sets of questions in a given field, e.g. for an exam

## Table of Contents
  * [Table of Contents](#table-of-contents)
  * [Users](#users)
  * [Features](#features)
  * [Plans](#plans)
  * [Work progress](#work-progress)
  * [Tags](#tags)
  * [Main Principles](#main-principles)
  * [Technologies](#technologies)
  * [Setup](#setup)


## Users
 - not logged - __{ask him to sign in/sign up}__
 - User - can create/join a space.
    - Manager [ a subrole of a User ] - 'space owner'. Manages questions (version control) and users within the space. He can invite to the space or create an join method.
    - Contributor [ a subrole of a User ] - can ask to join the space or join with a special code/method. He can edit the database of questions depending on the permissions    granted.

## Features
 - As a User, I want to
    - create a space and became Manager of that space
    - join the space
    - ask to join a space
  - As a Manager, I want to
    - manage (add / invite / accept / remove / etc) users in space
    - change user permissions in space
    - control questions (version control/approve/remove/etc)
  - As a Contributor, I want to
    - create/submit new questions
    - test my knowledge (learning using questions in that space)  

## Plans
| Version | Step | Description/Extra info |
| --- | --- | --- |
| 0.1 | DB diagram | simple DB that allows some auditing and version control over questions |
| 0.1 | Init Spring Boot | init Spring Boot with Spring data JPA |
| 0.1 | Create backend structure | Spring structure, by Layer |
| 0.1 | Login method | Build login method |
| 0.1 | Create frontend structure | __TBD__ |
| 0.1 | __TBD__ | __TBD__ |
| 0.1 | SQL script with example data | __TBD__ |
| 0.2 | Custom "nice" Front Look | __TBD__ |
| 0.3 | TESTS | __TBD__ |

## Work progress 
- [ ] TBD
- [ ] TBD
- [ ] TBD

## Tags
- [ ] TBD
- [ ] TBD
- [ ] TBD
- [ ] 
## Main Principles 
  __TBD__
  
## Technologies
- JDK
- Gradle
- Spring Boot
- Spring JPA
- __TBD__ DATABASE
- Lombok
- __FRONT END__
- __TESTS__
- __SWAGGER? __

## Setup
