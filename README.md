## What is Cloud-native

"Cloud native technologies empower organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. Containers, service meshes, microservices, immutable infrastructure, and declarative          APIs exemplify this approach."

[CNCF Cloud Native Definition v1.0](https://github.com/cncf/toc/blob/master/DEFINITION.md)

## Two scenarios, two approaches

Lets assume there are 2 companies, Abc and Xyz, both have ambitious business plans and both are aiming to get the best out from new technologies. Both are planning highly scalable, resilient new products, with rapid development and fast delivery, frequent release to customers.

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
          <li>Take full control from infrastructure, operating, and application. There are great internal resources and experties availble.</li>
          <li>Lift and shift some existing services at the initial phases to reduce impacts to business.</li>
        </ul>
      </td>
        <td>
        <ul>
          <li>As a startup, develop a brand-new B2C cloud-based service. Fast business growth is as expected.</li>
          <li>Competition is hot, faster to market is on top of the priorities. </li>
          <li>Stay focus on product development. Ideally everything is operating in the cloud without worrying about infrasctructure and scaling.</li>
          <li>Build and strengthen the partnership with the current cloud provider to achieve long-term Win-Win. </li>
          <li>The leadership heard about "serverless", "auto-scale", "pay for consumption", and they are keen to embrace it.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

Both have made key decisions, and chosen core technologies to use.
<table style="width:100%">
  <tbody>
    <tr>
      <th style="width:50%">Company Abc</th>
      <th style="width:50%">Company Xyz</th>
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

Both Abc and Xyz are planning to build a small, simple app as a Proof-of-Concept to start with. The app is called, easyPlanner, which will provide a simple weekly planning tool for everyone who *"living your values, planning for goals, and designing your week"*.

They come up with different architecture design. (Assume Xyz is using Azure as their pubic platform. Similar design can be achieved on other cloud platforms.) 
<table style="width:100%">
  <tbody>
    <tr>
      <th style="width:50%">Company Abc</th>
      <th style="width:50%">Company Xyz</th>
    </tr>
    <tr>
    <tr>
      <td>
         <img alt="Overall architecture" src="images\Easy-Planner-Microservices-Architecture.png">
      </td>
        <td>
         <img alt="Overall architecture" src="images\easy-planner-serverless-on-azure-architecture.png">
      </td>
    </tr>
  </tbody>
</table>