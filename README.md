# Robin Morton - Senior Software Development Engineer

## Contact

+44 (0)7428156441

hello@robinmorton.dev

## About

Experienced Senior Software Engineer with specialisms in backend engineering, automation engineering, and DevOps.

I have built tools and services which allow Prime Video to be continually released to hundreds of millions of customers, with confidence in product quality on a daily basis.

Currently working as a Senior Software Development Engineer owning an application-critical backend service handling many tens of thousands of transactions per seconds. My service ensures that Prime Video customers are able to browse, discover, and enjoy all the content on the Prime Video platform.

---

## Experience

<table style="width:100%">
    <td>
        <h3> Senior Software Engineer </h3>
        <h4> Amazon, Prime Video <h4>
        </h4> July 2013 - Present </h4>
    </td>
    <td>
        <img src="./img/Amazon_Prime_Video_logo.svg" width="300" style="float:right" />
    </td>
</table>

#### Key Projects

- Lead engineer on the Edge Service team which handles all API requests from the Prime Video application. This service currently handles 27,000 transactions per second during peak time and many times this number during Prime Video-wide stress testing events.

  - I joined a greenfield team within Prime Video to create an vanilla AWS service from scratch to handle all API and data request from the Prime Video application
  - The service operates across three main regions but is designed and architected to be rolled out across all regions that AWS operates in.
  - I pushed for all infrastructure to be defined in code using AWS CDK; this includes all load balancers, EC2 instance types, other compute definitions, alarms, monitors, dashboards, etc. the main goal was to have easily auditable and maintainable infrastructure to allow for rapid regional expansion.
  - I have written multiple design documents for the Edge Service which cover an array of topics including; caching strategy to reduce traffic spikes at the end of live events, infrastructure experimentation to easily change the type of compute used under given circumstances to improve customer experience, reduce service latency, increase availability, and reduce overall operational costs

- The Remote Executor (TREx) - Design, task breakdown, and implementation of set of libraries and services to allow for the remote execution of commands within any JavaScript application context.

  - I was the lead engineer on this multi-year project from idea inception, system design, task breakdown, overseeing implementation, and also ensuring adoption across a wide-range of Prime Video teams
  - TREx is used as the backbone command execution model for end-to-end, on-device testing for 15+ teams within Prime Video and IMDbTV; including frontend application teams, native rendering framework teams, video quality analysis teams, and also teams responsible for fuzzy and chaos testing of the Prime Video application.
  - TREx is actively used in software pipelines which are responsible for releasing to customers and is the primary enabler for Continuous Integration/ Continuos Deployment of the Prime Video application to hundreds of millions of customers.
  - As an example TREx handled nearly one million execution instructions in February 2022.

- Ported and launched the Prime Video application to React from a previous proprietary technology stack.

  - Spearheaded development and laying the foundations for rolling out the Prime Video React application to thousands of devices types.
  - Designed and implemented the release strategy for the newly ported application, including implementation of the release pipeline allowing for zero-touch deployments. All infrastructure was written using the AWS CDK.
  - Led the design and implementation of the automation testing strategy using TREx to ensure that the application which was deployed to production was thoroughly tested. Initially these tests were executed on a low-powered Roku streaming stick.
  - Expanded the testing framework to allow for testing across roughly 15 set references devices before the Prime Video application was released to customers.
  - My implementation reduced the release cycle from roughly 14-days, which often resulted in rollbacks, to 11-times in one day. This was primarily done by removing all need for manual testing of devices by implementing automation through the quality assurance phase.

  - Device Access Bus (DAB) - Initial Specification Design with YouTube, Google, and Netflix.
    An open source protocol to allow engineers to remotely interact with and control living room devices, e.g. start and stop applications, send key press commands. More info at [getdab.org](https://getdab.org/).

  - Founding member of cross-company standards group whose sole purpose was to write a protocol to iron out many of the pain-points with on-device automation testing
  - I was part of a small collaboration team of 8 engineers from Amazon, Netflix, and YouTube to implement the protocol which was then demonstrated to a large TV manufacturer.
  - The above demonstration was then used to prove the concept and get adoption from other TV manufacturers to enable a higher-level of automation testing for 2021+ devices.

---

## Programming Languages

<table>
    <td>
        <ul> 
            <li> TypeScript </li>
            <li> JavaScript </li>
        </ul>
    </td>
    <td>
        <ul> 
            <li> Java </li>
            <li> Kotlin </li>
        </ul>
    </td>
    <td>
        <ul> 
            <li> Go </li>
        </ul>
    </td>
</table>

## Familiar Technologies and Concepts

<table>
    <td>
        <ul> 
            <li> Node.js </li>
            <li> Git </li>
            <li> NPM </li>
            <li> IaaS </li>
        </ul>
    </td>
    <td>
        <ul> 
            <li> AWS </li>
            <li> AWS CDK </li>
            <li> Bash </li>
            <li> Automation Testing </li>
        </ul>
    </td>
    <td>
        <ul> 
            <li> Highly scalable services </li>
            <li> REST API design </li>
            <li> Microservice Architecture </li>
            <li> Continuos Integration/ Continuos Delivery </li>
        </ul>
    </td>
</table>

## Qualifications

<table style="width:100%; text-align: center">
    <thead/>
    <tr>
        <td>
            <a href="https://www.credly.com/badges/aa9f21ef-9ac0-472c-a5d2-afcc1c2fe8ef">
                <img src="https://images.credly.com/size/340x340/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png"/> 
            </a>
        </td>
        <td>
            <a href="https://www.credly.com/badges/9b63b7c5-6023-4d20-92e4-aa58a842c190">
                <img src="https://images.credly.com/size/340x340/images/b9feab85-1a43-4f6c-99a5-631b88d5461b/image.png"/>
            </a>
        </td>
        <td>
            <a href="https://www.credly.com/badges/c1d8921d-7a0e-4349-9c3b-dea7ebabf0ad"> 
                <img src="https://images.credly.com/size/340x340/images/00634f82-b07f-4bbd-a6bb-53de397fc3a6/image.png"/>
            </a>
        </td>
    </tr>
    <tr>
        <td> AWS Certified Solutions Architect - Associate (SAA) </td>
        <td> AWS Certified Developer - Associate (DVA) </td>
        <td> AWS Certified Cloud Practitioner (CLF) </td>
    </tr>
</table>

### In progress

- AWS Certified Solutions Architect - Professional
- AWS Certified Database - Specialty

---

## Education

<table style="width:100%">
    <td>
        <h3> University of Aberdeen </h3>
        <h4> Bachelor of Science (BSc) Hons., Artificial Intelligence </h4>
        <h4> 2009 - 2013 </h4>
        <h4> Grade: 2.1 </h4>
    </td>
    <td>
        <img src="./img/UoA_Primary_Logo_RGB_2018.svg#gh-light-mode-only" width="300" style="float:right" />
    </td>
</table>

---

## Hobbies and Interests

General Aviation; I am a qualified private pilot with ratings which allow me to fly at night and also in cloud. I enjoy cross-country trips and I'm looking forward to flying to France for breakfast / lunch in the Summer months with my family.

Cycling; I am a keen cyclist and enjoy both commuting by bike and also leisure rides. I am a member of a cycling club and take part in group rides. My greatest achievements in cycling are; completing the Ride London 100-mile route because of the distance, and completing Tour de Yorkshire because of the hills!

Cooking; I really enjoy cooking! I'm currently obsessed with Italian food and make my own pasta. I'm also trying to perfect making different pasta sauces which is proving more challenging than initially expected.

Gardening; I enjoy being in the garden during the nice weather. I also try to grow my own vegetables which ranges from tomatoes and wonky carrots to a massive overproduction of kale - the worms were happy with that one.
