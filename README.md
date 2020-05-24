## What is Cloud-native

*"Cloud native technologies empower organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. Containers, service meshes, microservices, immutable infrastructure, and declarative          APIs exemplify this approach."*

[CNCF Cloud Native Definition v1.0](https://github.com/cncf/toc/blob/master/DEFINITION.md)

## Two scenarios, two approaches

Let's assume there are two companies, **Abc** and **Xyz**. Both have ambitious business plans and both are aiming to get the best out from new technologies such as cloud computing, microservices, DevOps, etc. Both are planning new highly scalable, resilient products, ideally with rapid development and fast delivery, frequent release to customers.

However, they are different in many ways.

<table style="width:100%">
  <tbody>
    <tr>
      <th style="width:50%">Company Abc</th>
      <th style="width:50%">Company Xyz</th>
    </tr>
    <tr>
      <td>
        <ul>
          <li>Empower their enterprise customers to choose where to host and run the product: on-prem or in the cloud (if so, whatever cloud platform customers prefer to). </li>
          <li>Continue their successful strategy to leverage open source technologies.</li>
          <li>Take full control from infrastructure, operating, and application. There are great internal resources and expertise available.</li>
          <li>Lift and shift some existing services at the initial phases to reduce impacts to business.</li>
        </ul>
      </td>
        <td>
        <ul>
          <li>As a start-up, develop a brand-new B2C cloud-based service. Fast business growth is as expected.</li>
          <li>Competition is hot, faster to market is on top of the priorities. </li>
          <li>Stay focus on product development. Ideally everything is operating in the cloud without worrying about infrastructure and scaling.</li>
          <li>Build and strengthen the partnership with the current cloud provider to achieve long-term Win-Win. </li>
          <li>The leadership heard about "serverless", "auto-scale", "pay for consumption", and they are keen to embrace it.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
<br>

Both have made key decisions and chosen core technologies to use.
<table style="width:100%">
  <tbody>
    <tr>
      <th style="width:50%">Abc</th>
      <th style="width:50%">Xyz</th>
    </tr>
    <tr>
      <td>
        <ul>
          <li>Based on Containers/Docker and Orchestration/Kubernetes</li>
          <li>100% Open Source</li>
          <li>Targeting both On-prem and Multi-Cloud</li>
        </ul>
      </td>
        <td>
        <ul>
          <li>100% Serverless</li>
          <li>Leverage serverless technologies with the current cloud provider </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
         <img alt="Docker, Kubernetes, Terraform..." src="images\open-source.png">
      </td>
        <td>
         <img alt="Serverless..." src="images\serverless.png">
      </td>
    </tr>
  </tbody>
</table>

*Note: not all possible cloud providers are listed above.*

Both Abc and Xyz are planning to build a small, simple app as a Proof-of-Concept to start with. The app is called, **easyPlanner**, which will provide a simple weekly planning tool for everyone who *"living your values, planning for goals, and designing your week"*. 

The current goal is to demontrate all essential architecture elements and how they can be used to achieve business goals. The features of the app can be minimised at this stage.

They come up with different architecture proposals. Abc has a design as below.

![Easy Planner Architecture](/images/easy-planner-architecture.png)

Xyz has a differnt one. As an example we assume Xyz is using Azure as their cloud platform. However, similar design can be achieved on other cloud platforms.

![Easy Planner Serverless on Azure Architecture](/images/easy-planner-serverless-on-azure-architecture.png)

Both have started PoC projects. They are publishing their documents on project sites. Please visit them for more information. 
<table style="width:100%">
  <tbody>
    <tr>
      <th style="width:50%">Abc</th>
      <th style="width:50%">Xyz</th>
    </tr>
    <tr>
      <td>
        <a href="http://www.buildcloud-nativeapp.co.uk/easyPlanner/">easyPlanner (on containers)</a>
      </td>
        <td>
        <a href="http://www.buildcloud-nativeapp.co.uk/easyPlannerServerlessOnAzure/">easyPlanner Serverless on Azure</a>
      </td>
    </tr>
  </tbody>
</table>
<br>
<a href="#top">Back to top</a>
