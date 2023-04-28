# IS27 – Full Stack Developer Coding challenge

## Overview

To provide you with an opportunity to demonstrate your proficiency in
software development, this coding challenge asks you to develop a small
web application and related elements. The desired functionality of the
application is discussed in Application Requirements.

Your submission will consist of the code for the web application,
supporting documentation, and a running instance of the web application.
Further details are provided in How to Submit.

In order to progress in the hiring process beyond the coding challenge
to an interview, your coding challenge submission must fulfill the
Application Requirements and satisfactorily meet the criteria in a
minimum of **<u>four</u>** of the Assessment Areas.

If you have questions about the coding challenge, please submit
questions via email to kirsten.clouston@gov.bc.ca. Please ensure you
have read this document in its entirety prior to asking questions. We
will review and respond to questions on Friday, April 28 from
10:30AM-3:00PM PDT and Monday, May 1 from 9:00AM to 3:00PM PDT. We will
do our best to respond promptly, but we encourage you to ask questions
as soon as they occur to you as you may not receive a response
immediately.

If you move on to the interview stage of the competition, you may be
asked to discuss your decisions and thought process related to your
coding challenge submission. You may wish to keep notes for this
purpose.

## How to Submit 

There are 2 parts of your submission to the coding challenge.

The first is the source code for the web application you’ve developed as
well as supporting elements (static assets, CI/CD pipeline definitions,
README file, etc.). You’ll need to store these in the main branch of a
publicly accessible source control repository (e.g. GitHub, GitLab).

The second part is a deployed, working instance of your application at a
publicly accessible URL.

When you have completed your coding challenge, committed your code to
your code repository, and deployed your application, please send an
email to kirsten.clouston@gov.bc.ca including links to both the code
repository and the deployed application. This email must be received
ahead of the submission deadline. Code committed after the submission
deadline will not be considered in the assessment.

## Application Requirements

This section contains background information about the business problem
that your web application must address as well as the specific functions
that it must provide. Your submission must account for the details
described in Background and fulfill all the functionality described in
User Stories. You are also encouraged to consider the Future
Functionality section as you design and build your web application.

### Background

The Director of the software development department in an organization
wants to improve the process of maintaining its staff directory, which
is currently done manually. This will allow for easy updates when new
employees join or when existing employees leave.

The department is a hierarchy that currently has five levels. At the top
there is a Director level, followed by a Senior Manager level, a Manager
level, a Senior Developer level, and finally, a Junior Developer level.
All levels except the Director level may have multiple positions. For
example, multiple Senior Manager positions may exist below the Director,
and multiple Managers positions may exist below each Senior manager, and
so on.

A position may be vacant or occupied by a single employee. If an
employee leaves, a position becomes vacant, but it remains in the
hierarchy.

### User Stories

User Story 1: As a Director, I need to view all of my organization in a
clear format that shows the hierarchy. For each position, the position
title and position number should be shown. For each employee associated
with a position, their first name, last name, and employee number should
be shown. If a position is vacant, this should be indicated.

User Story 2: As a Director, I need to be able to update an employee’s
name and then see an updated organization view, as described in User
Story 1.

User Story 3: As a Director, I need to be able to remove an employee
from a position, leaving a vacant position in the hierarchy. I then need
to see an updated organization view, as described in User Story 1.

User Story 4: As a Director, I need to add a new Manager
position beneath an existing Senior Manager. I then need to see an
updated organization view, as described in User Story 1.

User Story 5: As a Director, I need to associate a new employee
with a vacant position. I then need to see an updated organization view,
as described in User Story 1.

### Future Functionality

The first version of the staff directory web application does not need
to support promoting or moving employees, deleting vacant positions, or
inserting levels in the hierarchy. However, the Director is keen to have
these features in a future version.

## Assessment Areas

In addition to assessing the overall quality of your submission and
whether your web application fulfills the requirements in Application
Requirements, your submission will be assessed based on how well it
meets the criteria across several Assessment Areas. The section
identifies expectations and assessment criteria in each of these areas.

You must receive an “Acceptable” evaluation for a minimum of four of the
Assessment Areas.

### Backend

Your submission \*must\* include a backend component.

The backend of your web application can be built using a programming
language and framework of your choosing. (for example: NodeJS/Express,
Python/flask, Ruby/Rails, C#/ASP.NET core, Java/Spring).

The backend component should expose a RESTful or GraphQL API.

The backend component of your web application may be hosted on a cloud
platform of your choosing (for example: Heroku, Digital Ocean, AWS,
Azure, Google Cloud Platform).

User Authentication/Authorization is not required for this coding
challenge.

Your backend component should be populated with sample data to confirm
that it fulfills the requirements in User Stories.

Use of a database is optional; transient / in-memory storage of data is
acceptable.

User Authentication/Authorization is not required for this coding
challenge.

In addition to the expectations above, the backend component will be
assessed based on the criteria below.

<table>
<colgroup>
<col style="width: 19%" />
<col style="width: 80%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Rating</strong></th>
<th><strong>Looking For</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Acceptable</td>
<td><p>- API operations can be invoked without unexpected errors</p>
<p>- Can use API to list, view, create, update, delete items as required by User Stories</p>
<p>- Codebase is well organized and structured</p>
<p>- Code is well formatted and commented</p>
<p>- Code implements good error handling and logging</p></td>
</tr>
<tr class="even">
<td>Not Acceptable</td>
<td><p>- Backend component not included</p>
<p>- Solution copied from tutorial or elsewhere with few or no changes</p>
<p>- Does not meet the requirements for “Acceptable”</p></td>
</tr>
</tbody>
</table>

### Frontend 

Your submission \*must\* include a frontend component.

The frontend component of your web application can be built using a
front-end framework of your choosing, (for example: React, Vue, or
Svelte).

Your frontend component will consume the API provided by your backend
component and display it to confirm that it fulfills the requirements in
User Stories.

The frontend component of your web application will be hosted on a cloud
platform of your choosing (for example: Heroku, Digital Ocean, AWS,
Azure, Google Cloud Platform).

User Authentication/Authorization is not required for this coding
challenge.

In addition to the expectations above, the frontend component will be
assessed based on the criteria below.

<table>
<colgroup>
<col style="width: 19%" />
<col style="width: 80%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Rating</strong></th>
<th><strong>Looking For</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Acceptable</td>
<td><p>- Application loads and runs without errors in UI or console</p>
<p>- Codebase is well organized and structured</p>
<p>- Implements data binding</p>
<p>- Responsive, mobile friendly interface</p>
<p>- User interface is intuitive and well designed</p>
<p>- Code is well formatted and commented</p>
<p>- Can list, view, create, update, delete items as required by User Stories</p></td>
</tr>
<tr class="even">
<td>Not Acceptable</td>
<td><p>- Frontend component not included</p>
<p>- Solution Copied solution or tutorial with few or no changes</p>
<p>- Inline CSS or JS</p>
<p>- Does not meet the requirements for “Acceptable”</p></td>
</tr>
</tbody>
</table>

### Documentation

Your submission \*must\* include documentation in the form of a README
file in Markdown or similar format stored in the root of your
submission’s code repository.

Additional documentation files may be included if needed, with navigable
links between them.

Your README or other documentation files must include topics referenced
in other assessment areas such as Test automation or CI/CD.

Additionally, your documentation must include the following:

-   Instructions on how to build and run the application locally,
    including any environment set up steps, pre-requisites, or
    dependencies

-   An architecture diagram that shows the structure of your application
    as well as a description of each component

-   Instructions on how to deploy the application to your chosen hosting
    service, including required services/subscriptions or configuration
    that must be done prior to deploying the web application

-   Instructions on using the API of your backend component

-   Instructions on using the frontend component of your web application

You may also wish to include notes on topics such as design decisions,
trade-offs, assumptions, or lessons learned in your documentation.

In addition to the expectations above, your documentation will be
assessed based on the criteria below.

<table>
<colgroup>
<col style="width: 19%" />
<col style="width: 80%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Rating</strong></th>
<th><strong>Looking For</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Acceptable</td>
<td><p>- Documentation is well organized</p>
<p>- Documentation is clear and well written</p>
<p>- Documentation is complete and includes all required topics</p></td>
</tr>
<tr class="even">
<td>Not Acceptable</td>
<td><p>- Documentation is poor quality or incomplete</p>
<p>- Documentation is copied or is framework boilerplate</p>
<p>- Does not meet the requirements for “Acceptable”</p></td>
</tr>
</tbody>
</table>


### Automated testing

Including automated testing in your submission is optional but you must
include either test automation or CI/CD functionality.

If you choose to include automated testing in your submission, you may
use one or more testing frameworks of your choosing and implement one or
more types of testing. (for example: Unit, API, Functional)

Executable tests, dependencies, and test data (if required) must be
included within your codebase.

Your README file or your other linked documentation files will include
your description of the approach to testing that you chose, how to run
the tests, as well as sample test results or reports, or links to these
elsewhere in your code repository.

In addition to the expectations above, automated testing will be assessed
based on the criteria below.

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 81%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Rating</strong></th>
<th><strong>Looking For</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Acceptable</td>
<td><p>- Executable test plans/suites/scripts</p>
<p>- Tests are well organized and structured</p>
<p>- Code is well formatted and commented</p>
<p>- Tests written to ensure application components meet requirements and/or code behaves as expected</p>
<p>- Good test coverage of codebase and/or user stories</p>
<p>- Tests succeed when run</p>
<p>- Uses modern testing framework(s).</p>
<p>- Testing is well documented in README</p></td>
</tr>
<tr class="even">
<td>Not Acceptable</td>
<td><p>- Tests are not executable or do not pass.</p>
<p>- Does not meet the requirements for “Acceptable”</p></td>
</tr>
</tbody>
</table>

### **CI/CD**

Including CI/CD functionality for your submission is optional, but you
must include either test automation or CI/CD functionality.

If you choose to include CI/CD functionality with your submission, you
may use a suitable tool of your choosing (for example: GitHub Actions,
CircleCI, Azure DevOps, Travis, etc.).

You may use more than one tool or service to implement CI/CD
functionality in your submission.

Your README will include a description of the CI/CD functionality, links
to the pipeline definition in your code repository, and a link to your
pipeline deployed within your chosen CI/CD tool’s interface.

In addition to the expectations above, CI/CD will be assessed based on
the criteria below.

<table>
<colgroup>
<col style="width: 19%" />
<col style="width: 80%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Rating</strong></th>
<th><strong>Looking For</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Acceptable</td>
<td><p>- The pipeline checks out code from a public repository</p>
<p>- The pipeline builds and/or packages code, as applicable based on programming</p>
<p>- The pipeline deploys the application to your chosen cloud-hosted environment</p>
<p>- Pipeline definition is well organized, structured, and commented</p>
<p>- CI/CD functionality is well documented in README</p></td>
</tr>
<tr class="even">
<td>Not Acceptable</td>
<td><p>- Automated pipeline does not work or contains unnecessary manual steps</p>
<p>- Relies entirely on bespoke scripts</p>
<p>- Does not meet the requirements for “Acceptable”</p></td>
</tr>
</tbody>
</table>
