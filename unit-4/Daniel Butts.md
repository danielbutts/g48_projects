**Chosen Project:** Part Analysis Tool
**Project Github:** 
- https://github.com/danielbutts/portfolio-analysis-api
- https://github.com/danielbutts/portfolio-analysis-client
**Deployed URL:** TBD

### First Project Proposal Idea

#### Part Analysis Tool

A web application allowing companies to perform a high-level evaluation of the practicality of 3D printing parts to reduce cost or improve efficiency in their supply chain.

**What problem does your project solve?**

The project was proposed by 3Discovered a startup developing a platform for 3D printing. The current platform allows companies to upload digitized 3D models, analyze them for printing, select a service bureau, and request a quote. However, the current application does not provide a tool for estimating the cost to 3D print a given model.

Because digitizing, test printing, and certifying a part requires time, expense, and expertise, it would be valuable to companies to narrow their parts inventory to a subset that might be well suited to digitization given cost, quantity, and turnaround requirements.

**How will your project solve this problem?**

This project will provide an interface for a user to bulk upload a parts inventory and analyze it for parts with the highest potential for digitization and speed the process/reduce the cost of moving to a digital supply chain.

Information on uploaded parts and their score (potential) will be displayed tabularly and in a graphical format.

Application will automatically match parts with compatible printers based on dimensions and material.

Application will calculate least cost service bureaus to fullfill minimum order size/turnaround time and graph those results to show a user the quantities at which digitization is most likely to be cost effective.

User will be able to manually add or edit parts.

#### Stretch Goals:
- Admin will be able to add/edit/delete service bureaus and printers

- User will be able to upload an STL file and the file will be analyzed for dimensions, volume, and bounding box (using node-stl package)

#### User Stories

- https://www.pivotaltracker.com/n/projects/2071049

#### Wireframes

- https://github.com/danielbutts/portfolio-analysis-client/tree/master/wireframes

**What web APIs will it use?**

- manufacturethis.build - cost estimator for 3D printing based on material, printer, dimensions, etc.

- senvol.com - The Senvol Database is the first and most comprehensive database for industrial additive manufacturing machines and materials.

- goshippo.com - Shipping cost API

- *(possible)* 3discovered.com - Connect to the 3Discovered database to get information on services bureaus and their available printers/turnaround times.


**What technologies will it use?**

#### API
- Java
- Spring
- Spring Data JPA
- Postgres
- JWT (to secure API endpoints)

#### Web Client
- Node/Express/AngularJS
- Postgres
- Knex
- HMTL/CSS

#### Stretch
- Deploy to AWS in Docker containers

### Second Project Proposal Idea

# Nope!