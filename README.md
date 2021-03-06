[![Build Status](https://travis-ci.org/capitalone/Hygieia.svg?branch=master)](https://travis-ci.org/capitalone/Hygieia)
[![Codacy Badge](https://api.codacy.com/project/badge/grade/de1a2a557f8e458e9a959be8c2e7fcba)](https://www.codacy.com/app/amit-mawkin/Hygieia)
[![Maven Central](https://img.shields.io/maven-central/v/com.capitalone.dashboard/Hygieia.svg)](http://search.maven.org/#search%7Cga%7C1%7Ccapitalone)
[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Join the chat at https://gitter.im/capitalone/Hygieia](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/capitalone/Hygieia?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)  

<img width="650" src="/images/hygieia_b.png"> <a href="https://www.blackducksoftware.com/2015-open-source-rookies" > <img src="/images/Rookies_Award_Badge.png" width="100" align="right" alt="Hygieia℠ is now BlackDuck 2015 OpenSource Rookie of the Year"></a>

**Pronunciation: _hi-gee-ya_ (Origin: Greek)**

# Contents

- [About Hygieia](#about-hygieia)
- [Objectives](#objectives)
- [Features](#features)
- [Hygieia Architecture](#hygieia-architecture)
- [Setup Instructions](#setup-instructions)
- [Hygieia Dashboard - A Snapshot](#hygieia-dashboard---a-snapshot)
- [Contribute](#contribute)
- [Links](#links)

## About Hygieia

Hygieia is a single, configurable, easy-to-use dashboard to visualize near real-time status of the entire delivery pipeline. In addition, it provides a continuous feedback loop for any DevOps organization.

The health of the continuous delivery pipeline, from code commit to production deployment, with all the necessary information around health and quality of the software, is essential for any DevOps Organization. Hygieia dashboards assist in achieving process transparency and therefore help establish feedback loops, to implement the underlying concepts of lean and DevOps. The dashboard contains interactive elements that enable drilling-down and linking to the connected DevOps tools.

Hygieia dashboards are customizable; you can select your story tracking, code repository, build, quality, and deployment tools. In addition, Plugins  are available to enable customizations.

Watch this video to see Hygieia in action:
<img width="650" src="/images/video-shot.png" alt="Hygieia℠ Is AWESOME"> <a href="https://www.youtube.com/watch?v=SoNTA78j0tc"></a>

## Objectives
* Automate Development Environment Setup
* Continuous Performance Measurement and Visualization
* Unified DevOps Dashboard

## Features
- **Visual Delivery Pipeline** - Use the pipeline view to visualize the status of the entire delivery pipeline and the components’ lifecycle progression.
- **Team Dashboard** - Monitor work items, code repo, builds, quality items (unit tests, security coverage), and deployments in a single dashboard.
- **Real-time Status** - Monitor quality, productivity, and work in process on a real-time basis within the dashboard.
- **Configurable View** - Configure the dashboard to display the widgets that matter most to your project, which helps amplify and shorten to feedback loop.
- **Open Source** - Hygieia is open source and free for everyone to use. We also encourage external users to contribute to the project. Refer to the [Contribute](#contribute) section to begin contributing to the project.

## Hygieia Architecture

<img width="650" src="/images/architecture.png" alt="Architecture Overview">

## Setup Instructions

**1. Configure the Components** - The following components are required to run Hygieia:

   - **Database Configuration** - Hygieia uses MongoDB as the database for storage and retrieval of data. To configure the database for each of the supported paltforms, refer to the [Database Setup Instructions](http://www.capitalone.io/Hygieia/database.html).
  
   - **API Configuration** - Hygieia API contains all the common REST API services that work with the source system data (collected by service tasks). The Hygieia API layer is an abstraction of the local and source system data layer. To configure the API layer, refer the [API Configuration](https://github.com/capitalone/Hygieia/blob/gh-pages/pages/hygieia/API/api.md).
	
   - **UI Configuration** - 
	
   - **Tool Collectors** - The Tool Collecters fetch data from the your DevOps tools and reflect this data on your Hygieia Dashboard. You can choose to install the collectors applicable to your DevOps tool set from the [Hygieia Collectors Inventory](https://github.com/capitalone/Hygieia/blob/master/collectors/README.md).

   - **Plugins/WebHook Configuration** -  The Hygieia-Jenkins plugin is used to publish data from Jenkins to Hygieia. To configure, refer to the [Hygieia-Jenkins Plugin](https://github.com/capitalone/Hygieia/tree/master/hygieia-jenkins-plugin) document.
   - **Proxy Configuration** - Hygieia supports proxy authentication for working behind corporate firewalls. To configure, refer to the Proxy Configuration section in [Setup Instructions](Setup.md).
  
**2. Build Hygieia** - 

**3. Test the Installation**

## Hygieia Dashboard - A Snapshot
A view is a primary mechanism for displaying data. The Hygieia dashboard offers a comprehensive overview through two view methods:
- **Widget View** - Widget view showcases detailed information, which include features in the current sprint, code contribution activities, continuous integration activities, code analysis, security analysis, unit and functional test results, and deployment and environment status.
- **Pipeline View** - The pipeline view pulls back to show each component’s lifecycle progression through the development, testing, and deployment stages.
- **Product View** - 
- **Cloud View** - 

### Widget View
<img width="650" src="/images/hygiea-screenshot.jpg" alt="Widget View">

### Pipeline View
<img width="650" src="/images/pipeline_view.png" alt="Pipeline View">

### Product View

### Cloud View

## Contribute

We welcome Your interest in Capital One’s Open Source Projects (the “Project”). Any Contributor to the Project must accept and sign an Agreement indicating agreement to the license terms below. Except for the license granted in this Agreement to Capital One and to recipients of software distributed by Capital One, You reserve all right, title, and interest in and to Your Contributions; this Agreement does not impact Your rights to use Your own Contributions for any other purpose.

- [**Individual Agreement**](https://docs.google.com/forms/d/19LpBBjykHPox18vrZvBbZUcK6gQTj7qv1O5hCduAZFU/viewform)
- [**Corporate Agreement**](https://docs.google.com/forms/d/e/1FAIpQLSeAbobIPLCVZD_ccgtMWBDAcN68oqbAJBQyDTSAQ1AkYuCp_g/viewform?usp=send_form)

This project adheres to the [Open Code of Conduct][code-of-conduct]. By participating, you are expected to honor this code.

[code-of-conduct]: http://www.capitalone.io/codeofconduct/

## Links
- [Documentation](http://www.capitalone.io/Hygieia/getting_started.html)
- [Underlying Frameworks and Technologies](/images/4.png)
