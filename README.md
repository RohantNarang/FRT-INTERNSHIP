# Therapeutic - A Healthcare Website

Therapeutic is a comprehensive healthcare website that offers specialized medical services in the fields of Cardiology, Ophthalmology, Neurology, Psychology, and Dermatology. The project's core idea is to provide accessible and patient-centric healthcare solutions, addressing the existing challenges of long waiting times, limited access to expert care, and a lack of personalized treatment options.

# Key Features: 

* User-friendly interface for easy navigation through departments.
* Online appointment booking for timely access to healthcare services.
* Embedded health bot for preliminary health information and guidance.
* Access to highly skilled professionals and advanced medical technology.
* Proactive health education and preventive care resources.


# Azure Services Overview
 
App Service:
* Overview: Azure App Service is a fully managed platform for building, deploying, and scaling web apps. It supports multiple programming languages and frameworks.
Contribution: In this project, App Service is utilized for hosting the main application, providing a scalable and managed environment. It ensures the application is easily deployable and can handle varying levels of traffic.

Static Web App:
* Overview: Azure Static Web Apps is a service that automatically builds and deploys full-stack web apps to Azure from a code repository.
Contribution: Static Web App is used to host static content of the application, such as HTML, CSS, and client-side JavaScript. It enhances reliability by automating the deployment process and enabling quick updates.

 Storage Service:
* Overview: Azure Storage Services include different storage options such as Blob Storage, Table Storage, Queue Storage, and File Storage.
Contribution: Blob Storage, for instance, can be used to store and retrieve large amounts of unstructured data, providing a scalable and durable solution for data storage. This enhances the reliability and scalability of the application by offloading storage responsibilities to a dedicated service.

Q&A Service:
* Overview: Azure QnA Maker is a cognitive service that allows the creation of a question and answer layer over your data.
Contribution: Q&A Service is employed to enhance the application's functionality, providing a natural language interface for users. This service contributes to the scalability by handling user queries effectively and improves the user experience by providing quick and accurate responses.

 Virtual Network:
* Overview: Azure Virtual Network enables the creation of private, isolated networks in the Azure cloud.
Contribution: Virtual Network is crucial for securing the application by isolating resources and controlling inbound and outbound traffic. It enhances security by allowing the definition of network boundaries and controls, preventing unauthorized access. Additionally, it contributes to reliability by providing a dedicated and controlled network environment for the application components.
In summary, the combination of Azure services in this project leverages the strengths of each service to contribute to the scalability, reliability, and security of the overall application. App Service and Static Web App handle application hosting and deployment, Storage Service manages data storage, Q&A Service enriches user interactions, and Virtual Network ensures a secure and controlled network environment.

 By this project we wants to bridge the gap between patients and specialized treatment by allowing users to make educated health decisions. Therapeutic helps to greater well-being and a higher quality of life by providing a seamless experience and competent medical attention.

# To Visit The Website  [Click Here](https://salmon-tree-0a6837c00.3.azurestaticapps.net)

# To Visit Project Demo Video [Click Here](https://vimeo.com/897928731?share=copy)

# Screenshots And Videos

![image](https://github.com/harshavardhan-b20/FRT_Project/assets/113964278/1d214462-1acf-45b1-af67-8fd30cbf2880)

![image](https://github.com/harshavardhan-b20/FRT_Project/assets/113964278/7d3f56ae-7f91-4314-a4aa-e712bc760679)

https://github.com/harshavardhan-b20/FRT_Project/assets/113964278/245c1555-d44c-4897-9d3d-adcaca3c5c82

![image](https://github.com/harshavardhan-b20/FRT_Project/assets/113964278/aa2013b8-c82c-41fc-96bf-bbe16dbb1e8b)

https://github.com/harshavardhan-b20/FRT_Project/assets/113964278/990cbc0c-c6bb-4034-bcdc-6fdbc127d03f

![image](https://github.com/harshavardhan-b20/FRT_Project/assets/113964278/8d2535c7-427d-444e-925d-8816a4ceceed)

# HealthBot Demo Video

https://github.com/harshavardhan-b20/FRT_Project/assets/113964278/4bf31b22-b0de-4417-83ac-498a6747146f

# Technologies Used
- Azure(For Hosting)
- Azure health bot
- Azure health data services
- HTML
- CSS
- Bootstrap
- JavaScript
- jquery

-

## Features

- **Home Page:** Intuitive landing page providing a quick overview of Lifeline Hospital.
- **Services Tab:** Detailed information about the hospital's services and specialities.
- **Contact Tab:** Easy access to contact information and location details.
- **About Tab:** Insights into the hospital's history, mission, and values.
- **Bot Integration:** An intelligent bot powered by Azure Bot Service to answer user queries.

## Technologies Used

- HTML
- CSS
- JavaScript
- Azure Cloud (for deployment)
- Azure Bot Service

## Deployment
Let's discuss how each Azure service mentioned earlier was deployed in the context of this project:

App Service:
* Deployment: The application code, along with its dependencies, is packaged and deployed to Azure App Service. This deployment can be achieved using various methods such as Git-based deployments, continuous integration/continuous deployment (CI/CD) pipelines, or directly through the Azure Portal.

Static Web App:
* Deployment: Azure Static Web Apps simplifies the deployment process. The application code, typically stored in a code repository (e.g., GitHub), is linked to Azure Static Web Apps. Changes to the code trigger an automatic build and deployment process, updating the static content on the Azure infrastructure.

Storage Service:
* Deployment: Azure Storage Services, such as Blob Storage, can be provisioned and configured through the Azure Portal or via Infrastructure as Code (IaC) tools like Azure Resource Manager (ARM) templates or Terraform. The application code is then modified to interact with the specific storage services, and the updated code is deployed to the App Service.

Q&A Service:
* Deployment: The QnA Maker service is configured by creating a knowledge base that contains questions and answers related to the application. This knowledge base can be built and trained through the QnA Maker portal. The QnA Maker endpoint and key are integrated into the application code, allowing the application to interact with the Q&A service.

Virtual Network:
* Deployment: Azure Virtual Network is typically set up and configured using the Azure Portal, Azure CLI, or templates like ARM templates. Resources such as App Service and other components are then connected to this virtual network, ensuring that they communicate securely within the defined network boundaries.
The deployment process for each service may involve a combination of manual configuration through the Azure Portal and automated processes using CI/CD pipelines or IaC tools. The goal is to establish a consistent and repeatable deployment process that ensures the application's components are deployed and configured correctly in the Azure environment.

- Resource group
  ![image](https://github.com/RohantNarang/FRT-INTERNSHIP/assets/89689441/611b6075-31a0-435b-a0c4-742fff9258e8)

- Static web
  ![image](https://github.com/RohantNarang/FRT-INTERNSHIP/assets/89689441/776b53c9-4f07-495c-9093-621b347b0a95)

- Web app deployment
  ![image](https://github.com/RohantNarang/FRT-INTERNSHIP/assets/89689441/bf760954-ac21-4ed2-9ef1-e88c3a4f5855)

- Azure bot
  ![image](https://github.com/RohantNarang/FRT-INTERNSHIP/assets/89689441/b2949cb1-98ef-4d48-b502-44afecffe872)

- Bot Chat
  ![image](https://github.com/RohantNarang/FRT-INTERNSHIP/assets/89689441/5d273752-3154-406a-8f28-c037fce613e2)

- virtual network
  ![image](https://github.com/RohantNarang/FRT-INTERNSHIP/assets/89689441/7cf36052-95a6-4c85-a2a7-74919de1f326)

- firewall
  ![image](https://github.com/RohantNarang/FRT-INTERNSHIP/assets/89689441/f27db5a5-276a-4948-a16f-5158f5c58d0f)




## Future Enhancements

This project is part of the Future Ready Talent internship, and potential future enhancements may involve implementing personalized user profiles, 
expanding the bot's capabilities to cover additional medical topics, and integrating a patient portal for streamlined healthcare management.

## Contribution Guidelines

Contributions are welcome! If you have ideas for improvements or find any issues, please open an issue or submit a pull request.

## Acknowledgments

Thank you for visiting Lifeline Hospital's GitHub repository! We hope this project reflects our commitment to excellence in healthcare.

