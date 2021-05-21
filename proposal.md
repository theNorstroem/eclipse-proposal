# https://projects.eclipse.org/proposals/eclipse-furo

https://projects.eclipse.org/create/project-proposal

**Project Name**
Eclipse Furo

**Parent Project**
Eclipse Technology

**Background**
 
In a nutshell, the Furo web stack
Is an enterprise grade web stack for creating fast, lightweight web applications
Reduces development efforts for creating modern web applications
Helps developers to focus on implementing business driven use cases


Business web application developers face many recurring requirements. Implementing these should not require a significant amount of time. Instead, developers should be able to concentrate on understanding and implementing business cases.
The Furo web stack provides support in the following areas:

- API first approach
- Continuous type system
- Plugin architecture for the creation of interface formats
    - gRPC
    - REST
-   JSON over HTTP
- Client framework based on the web component standard
    - Custom element
    - Shadow DOM
    - HTML template
    - ES modules
- Out of the box micro frontend support:
    - Run-time integration via iframes
    - Run-time integration with web components
    - Run-time integration with deep linkable micro sites
    - Built-in flow-based programming support
- Fully declarative components compositions
- Fully decoupled, styleable and themable UI elements
- Data binding interface
- Data fetching agents
- Service- and type-based hooks for the creation of UI building blocks (semi-finished products)


**Scope**

> All projects must have a well-defined scope. Describe, concisely, what is in-scope and
(optionally) what is out-of-scope. A project cannot have an open-ended scope.

![Furo Landscape][./eclipse_furo_scope.png]

The Furo Scope contains the following:

- Support in modelling API contracts (types and services)
- A set of components to map the presentation logic
- An interface to bind frontend libraries to the data models
- Enterprise grade web application stack
- Tools to support the development process
- Build chain

*Out of scope*

- Backend framework
- Persistence



**Description**

> Describe the project here. Be concise, but provide enough information that somebody who doesn't already know very much about your project idea or domain has at least a fighting chance of understanding its purpose. Note that the content you provide here will be used as the initial description of the project once it has been created (you will be able to edit the description after the project has been created).

Furo is an enterprise grade web stack for creating fast, lightweight web apps with web components. It strongly relies on open web standards which results in increasing speed, robustness and compatibility for applications based on Furo.
Furo provides components for the presentation logic and for the visual representation of an application.
Furo provides a built in flow based programming language which allows you to build your application fully declarative.

Furo comes with a strong API specification based on the API first approach. This is accompanied by an abstract API specification with template based generators for concrete implementations such as protocol buffers. This functionality is provided by the CLI spectools.
The spectools are designed as an expandable cli tool set. The basic functionality covers the following:


- DSL for fast prototyping of model and service specifications
- Abstract model and service specification format
- Imports from external api specification projects
- Generation of Protocol Buffers
- Generation of gRPC Gateway
- Generation of API Type Classes and Service Interfaces
- Generation of ES Module for client side integration


**Why here**

> What value does this project bring to our community? What value do you expect to obtain from hosting your project at the centre of this community using this forge?

The Eclipse Foundation has proven to be a transparent and reliable home for open source, web technology based projects that target buiness applications in the past. In addition, the clear IP guidelines for Eclipse projects increases the value of the project for usage in heavily related industries.

**Legal Issues**
> Please describe any potential legal issues in this section. Does somebody else own the trademark to the project name? Is there some issue that prevents you from licensing the project under a supported license? Are parts of the code available under a potentially problematic license?
no known legal issues

**Initial Contribution**
>Projects are expected to arrive with existing code. Describe the existing code that will be contributed to the project. Please provide a couple of paragraphs describing the code with modest detail, including important information like code ownership (who holds the copyright?), and some consideration of community that exists around the code. Include a listing of third-party libraries and associated licenses.


Functionality described in this proposal will be provided by the members of the GitHub Organisation theNorstroem (https://github.com/theNorstroem). The Community is asked for input on the existing code base, feature requests for new functionality, and bug requests.



LitElement
BSD 3-Clause (https://github.com/Polymer/lit-element/blob/master/LICENSE)

UI5 Web Components
Apache 2.0 (https://github.com/SAP/ui5-webcomponents/blob/master/LICENSE.txt)


**Project Scheduling**
>Describe, in rough terms, what the basic scheduling of the project will be. You might, for example, include an indication of when an initial contribution should be expected, when your first build will be ready, etc. Exact dates are not required.

- 2021: Furo proposal under eclipse.org
- 2021 Transfer project artefacts to Eclipse according to current guidelines
- 2021 First official Eclipse Furo release

**Future Work**
>What functionality do you expect to add in the next twelve to eighteen months? What sorts of activities do you plan to undertake to grow the community around your project?

- Getting Started Guide

**Interested Parties**
>The following individuals, organisations, companies and projects have expressed interest in this project:

- Adcubum AG, Zürcherstrasse 464, 9015 St.Gallen, Switzerland

The following individuals have expressed interest in this project:[Textflussumbruch]

- Marc Omlin
- Fan Zou, Raiffeisen, Switzerland


**Source Code**
>Specify the type of source code repository the project will use as its primary host. Note that some external hosting providers may be supported; if you do intend to use a supported external hosting service, identify the existing repositories in the "Source Repositories" field.

- GitHub, https://github.com/theNorstroem/FuroBaseComponents
- GitHub, https://github.com/theNorstroem/spectools
- GitHub, https://github.com/theNorstroem/furoBaseSpecs


**Project Leads**
>A proposal must have one or more project leads. The project lead is more of a position of responsibility than one of power. The project lead is immediately responsible for the overall well-being of the project. They own and manage the project's development process, coordinate development, facilitate discussion amongst project committers, ensure that the Eclipse IP policy is being observed by the project and more.

- Veith Zaech; email; nomination criteria: Veith Zaech is the initiator and creator of the original Furo code base. Since 2013, Veith Zäch has been actively working on the codebase (starting with the FBP language).
- Roger Müller; malte.norstroem@gmail.com; nomination criteria: Roger Müller is one of the most active contributors. He also assists Veith Zäch in an advisory capacity. Since April 2019, Roger Müller has been actively working on the codebase.


**Committers**

- Fan Zou; email; Fan Zou list parts where roger has been a major driver for the current Furo framework, some more text since when roger has been working on the code base
Any committers outside Adcubum to be listed? Seems unlikely when looking at the github repos mentioned below.

**Mentor**
>New projects require a mentor from the Architecture Council. The EMO will help you identify a mentor prior to the start of the creation review period. The proposal can be posted before this section is filled in (it's a little easier to find a mentor when the proposal itself is public). Note that the autocomplete does not filter based on Architecture Council membership. We'll add filtering to this feature soon!
