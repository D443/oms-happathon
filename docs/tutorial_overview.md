# Overview: Open Mustard Seed (OMS)

## Developers: Getting Started

### Assumed knowledge:
*Assumed knowledge should link to external resources on that topic*
* Linux command line
* Virtual machines (at least conceptually)
* Python
* Others? (we can link to the appropriate sites here)
* SSH


### Tutorials
*note: each section of learnings under each tutorial should link to that section of the tutorial*
* Setting up your dev environment (with callouts where hackathon participant instructions differ)
  * From this tutorial, you should feel comfortable with:
  * [virtualenv](#)
* Restarting your existing dev environment
  * From this tutorial, you should feel comfortable with:
  * [choosing an existing virtualenv](#)
* Editing your dev environment's files in Windows
  * From this tutorial, you should feel comfortable with:
  * [Starting an SSH session to your vm](#)
  * [Establishing password-free access with SSH keys](#)
  * [Editing your vm's files with vim](#)
  * [Editing your vm's files locally with Sublimetext](#)
* Editing your dev environment's files on Mac


## Developers: OMS Basics

### Assumed knowledge:
* All the knowledge in "Getting Started", plus...
* ??? What else are we assuming to accomplish the below tutorials?

### Tutorials
* [Developing a django app in OMS](#)
  * From this tutorial, you should feel comfortable with:
  * [Installing Django in your virtualenv](#)
  * [MVC Architecture](#)
  * [Django](#)
  * [REST APIs](#)
  * [Locations of your database, instance, models, views, urls, etc.](#)
  * [What directories to make changes in](#)
  * [How to get Django running in debug mode](#)
  * [The directory structure of a django app](#)
  * [How to create models, routes, views, etc.](#)
  * [More as I finish going through the process](#)



## Developers: Intermediate OMS

### Assumed knowledge:
* All the knowledge in "OMS Basics", plus...
* ??? What else are we assuming to accomplish the below tutorials?

### Tutorials
* [Converting a standard Django app to OMS](#)
  * From this tutorial, you should feel comfortable with:
  * [How OMS app differs from regular django](#)
  * [One simple app directory structure](#)
  * [How to create simple OMS queries (FACT?)](#)
* [Creating a Django app from scratch in OMS](#)
  * From this tutorial, you should feel comfortable with:
  * [Creating a Rest API in OMS](#)
  * [Creating a simple manifest](#)
  * [One simple way to manage users](#)
  * [What a coreID is](#)
  * [Setting up a coreID](#)
  * [Simple Authentication](#)
  * [Creating a simple login](#)
  * [One simple persona](#)
  * [One simple way to make a login screen](#)
  * [The difference between, including locations of, python modules, django modules, oms modules, and anything else called modules](#)
  * [The difference between, including locations of, Django Templates, Manifest templates, and any other things called templates](#)
  * [The difference between an OMS TAB and a browser tab](#)
  * [The difference between, anything else where we're using the same name as somethign else that's common](#)
  * **NOTE: When using terms like modules, please always use the correct prefix, such as OMS modules, django modules, python modules., etc.  Using 'modules' by itself is confusing.**
* Converting a node.js app to OMS (TBD)
* Creating a node.js app from scratch in OMS (TBD)
* Converting a Ruby/Rails app to OMS (TBD)
* Creating a Ruby/Rails app from scratch in OMS from scratch (TBD)

## Knowledge at the end of this section (Things the tutorials need to cover)
* Basic OMS architecture - What's the minimum I need to know to get an OMS app running?
* Know how to create an OMS app from scratch



## Developers: Advanced OMS
**Note: Follows the same format as the above sections.**

### Assumed knowledge:
* All the knowledge in "Intermediate OMS"

### Tutorials (Things the tutorials need to cover)
** Note: The learnings under "Exploring & Modifying Perguntus" need to be split up and moved under appropriate tutorials.  I'm sure that there are many more. Need help fleshing out all OMS' possibilities. **
* Exploring & Modifying Perguntus
  * From this tutorial, you should feel comfortable with:
  * Advanced OMS architecture - Tell me everything I could want to know from a developer's standpoint.
  * Advanced OMS architecture (with rationale for each part)
  * Where Django stops and OMS starts 
  * Know alternate directory structures for OMS apps - which should I choose?
  * Know alternate persistence methods for OMS apps - which should I choose?
  * Know alternate deployment methods for OMS apps - which should I choose?
  * Know how to create an OMS app *without* Django
  * How Querying OMS TCCs differs from querying other data stores
  * How to query OMS
  * Whatever other topics illustrate OMS' power and flexibility
  * Understand how static and template files work
  * Personas
  * Scopes
  * Private registries
  * Portal registries
* Creating an OMS app without Django
  * From this tutorial, you should feel comfortable with:
* Alternate deployment options
  * From this tutorial, you should feel comfortable with:
* Alternate directory structures
  * From this tutorial, you should feel comfortable with:
* Alternate persistence methods
  * From this tutorial, you should feel comfortable with:
* Advanced queries
  * From this tutorial, you should feel comfortable with:
* Really advanced Queries
  * From this tutorial, you should feel comfortable with:
* Personas
  * From this tutorial, you should feel comfortable with:
* Scopes
  * From this tutorial, you should feel comfortable with:
* Manifests
  * From this tutorial, you should feel comfortable with:




## Sysadmins: OMS Basics

### Assumed knowledge
* Python
* Virtualenv
* Git
* Linux command line
* Virtual machines
* VMware
* What else?

### Tutorials
* How to think in OMS
  * From this tutorial, you should feel comfortable with:
  * The difference between a portal admin and a sysadmin
* How to set up a private portal
  * From this tutorial, you should feel comfortable with:
  * The difference between a private and public portal
  * The purpose of a private portal
* How to set up a public portal
  * From this tutorial, you should feel comfortable with:
  * The difference between a private and public portal
  * The purpose of a public portal
* Administering a single TAB
  * From this tutorial, you should feel comfortable with:
* Administering multiple TABS
  * From this tutorial, you should feel comfortable with:
  * Logging
  * Data
  * Security
  * Deployment options - which should I choose?
  * Salt
  * Celery
  * What else?
