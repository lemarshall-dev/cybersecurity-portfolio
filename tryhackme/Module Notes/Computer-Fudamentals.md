# Computer Fundamental Notes

## Client-Server Model

<img width="1263" height="836" alt="image" src="https://github.com/user-attachments/assets/8400c489-d21c-4708-8ce3-fc6dbfa4dd14" />

### HTTP(S)
- Stands for Hypertext Transfer Protocol (Secure)
- It's a stateless client-server protocol used for WWW (World Wide Web)
- Processes each request independantly without storing information
- Session Identifiers are required to store information for the next time the request is made, these are stored in cookies or tokens
- There are 9 core methods to HTTP:
  - GET
  - POST
  - PUT
  - DELETE
  - PATCH
  - HEAD
  - OPTIONS
  - CONNECT
  - TRACE

### GET

<img width="780" height="525" alt="image" src="https://github.com/user-attachments/assets/ece310e3-7ee6-4b4f-8085-c7739bffbb4e" />

The GET method is used to retrieve files from a web server, see above example. 
You can explore the GET method via the inspect tool on most browsers. You will see things like:


## Cloud Computing Fundamentals

### Cloud Evolution

![alt text](image.png)

### Cloud Computing
- There are three types of Cloud computing
  - Public (Every use case, no infastructure managment required)
  - Private (Perfect for banks, healthcare etc, greater compliance for sensitive data)
  - Hybrid (Perfect for companies in e-commerce who need to keep sensitive data but also scale publicly)

### Hypervisors
A hypervisor is a software that you can use to run multiple virtual machines on a single physical machine. Every virtual machine has its own operating system and applications.

Benefits of Hypervisors:
  - Hardware Independence - you aren't restricted by hardware. i.e, running MacOS on a windows machine
  - Efficiency - Hypervisors can be configured to immediately create your virtual computer, no time consuming hardware setup. 
  - Scalability - Organisations use hypervisors to maximise resources on physical machines, allowing them to create multiple VMs on a single machine rather than individual machines for singular workloads. 
  - Portability - They can have additional resources allocated to them on the fly and IT teams can allocate resources across multiple servers

### Cloud Service Models
- Infrastructure as a Service (IaaS): You rent basic computing resources such as virtual servers, storage, and networking. You are responsible for managing the operating system and your application, while the provider manages the physical hardware.
  - This is the equivalent of renting an empty flat

- Platform as a Service (PaaS): The cloud provider manages the infrastructure and the operating system. You focus on building, deploying, and running your application without worrying about servers.
  - This is the equivalent of renting a semi-furnished flat

- Software as a Service (SaaS): You use a complete application over the internet. The provider manages everything, and you access the software through a browser or app, for example, Gmail or Zoom
  - This is the equivalent of getting a hotel

### Some important market leading vendors include:
  - AWS (Amazon Web Services)
  - Microsoft Azure
  - GCP (Google Cloud Platform)

### How Companies Are Using the Cloud

- Netflix runs its entire platform on AWS so it can scale globally, stay online during peak demand, and stream content reliably to millions of users at once.
- Spotify uses the cloud to handle millions of songs and users, scaling quickly when new music or features are released.
- Instagram relies on the cloud to store massive amounts of photos and videos and deliver them fast to users around the world.
- Online stores use the cloud to handle traffic spikes during black friday without buying permanent infrastructure.


