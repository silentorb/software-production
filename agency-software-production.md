# Agency Software Production

## Roles

![](E:\dev\software-production\images\roles.svg)

| Role           | Responsibility                                             |
| -------------- | ---------------------------------------------------------- |
| What and Why   | Responsible for where you are going                        |
| How            | Responsible for how you get there                          |
| Where and When | Responsible for arriving at the intended place and on time |



### What and Why

* Product determines WHAT the client's goals and needs are
* Product challenges the client's goals
* Product researches the market viability of potential high-level solutions
* While Product and the client can define some high-level solutions, their main responsibility is defining problems, not solutions.

### How

* Designers design solutions based on product needs
* Designers need a firm background in implementation
* Graphic Designers, Developers, and DevOps implement those designs

### Where and When

* Project managers coordinate efforts and track progress
* QA ensures delivered features meet the client's needs

## Steps

### Scoping

* Product meets with the client and gathers a broad, long term list of the client's goals and needs
* Product questions the viability of the client's goals
* Product questions the viability of any presupposed solutions the client has
* Product researches market viability of the client's desired product
  * In particular, this includes becoming knowledgeable of major competitors
* Tech Lead weights features by development cost
* Product prioritizes features based on ideal market priority and feature costs
* 

### Design

### Presentation

* A presentation is prepared for the client
* This preparation can include
  * Text
  * UI Mockups
  * Diagrams / Graphs

### Approval

* The client signs off on the product design

### Requirements

* QA works with Design to create product requirement lists for each feature
* Tech Lead breaks features into tasks based on the product requirements
* Tech Lead defines technical requirements for each task

### Graphics

* UI Screens are created by Graphic Designers

### Development

* Project managers oversee and coordinate development
* Project Manager reports on progress, hours, and efficiency
* Tech leads verify that submitted code meets technical requirements

### Testing

* New features are placed in a staging environment by DevOps
* QA tests the new app to ensure that the new features meet their requirements and no previous features were broken

### Delivery

* The application is deployed to a production environment
* QA verifies that the production application meets all product requirements
* The client is notified of the delivery

## The Problem with Current Agency Role Structures

### Overview

All industry can be divided between design and implementation.

Design is theoretical.  Implementation is pragmatic.  Design practice trains a person to plan ahead and identify patterns.  Implementation practice trains a person with consistent reality checks.  The best designers have a background in implementation, and the best implementers have a background in design.

In most industries, design contains more senior roles and implementation contains more junior roles.  A common career path is for a designer is to start in implementation and work up to design.

In most engineering industries, engineers mainly handle design while other technical roles are responsible for implementation.  In software development, nearly all implementation is performed by engineers.  This results in an industry with practically no entry-level implementation roles.  People only invest in software implementation skills if software engineering is going to be their primary discipline.

Because of this, it is less common for traditional designers of software products to have a background in implementation.  This is especially the case for business products, where people in product design roles tend to have a background in business instead of production.

The end result is application design teams with little pragmatic experience.

On top of that, software development is not some arbitrarily different implementation of a design.  Software systems *model* a product.  They mirror it in very precise and demanding ways.

As an example, one principle of data is many-to-many relationships are more complex and difficult to manage than one-to-many relationships.  That complexity ratio applies just as much to UI/UX as it does to databases.  Database programmers are required to understand the difference between one-to-many and many-to-many relationships, while that concept is hardly ever conceptualized in UI/UX.  It's just that UI/UX designers tend to stumble around the issue and eventually settle on the right solution instead of identifying the distinction at the beginning.

### Application Design and Graphic Design

Sometimes graphic design is referred to as application design, when they are not the same thing.  Within the context of application development, graphic design is primarily the arrangement of elements on a screen and making a UI look aesthetically pleasing.  Graphic design can be considered a subset of application design, though the bulk of an application can be designed before any graphic investment.

### Solution

Software applications should primarily be designed by people who have experience with both design and implementation.  In practice, most of the people who have experience with both are developers.  Most developers are not good designers, but most developers don't need to be.  A single project could have ten developers simply implementing and one lead developer that is designing.