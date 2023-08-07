# Web Fundamentals - [Assignment 1](https://apps.pesto.tech/developer/classroom/2ed0d3dc-1027-41e4-8cd9-58e247dde075/topic/61ca4575-5b4b-4cba-9e24-91be6cb4912e/assignments/frontend/2)

> This doc contains solutions to the week-1, assignment-1

- ### What is a protocol stack, and how is it used in web development?
  * The protocol stack is a way for us to  define a high level abstraction of how internet devices can communicate with each other. The protocol stack defines seperation of responsibilites by roughly dividing the sets of __rules__ (protocols) into different __layers.__
  
    #### The Link Layer
    > This layer defines the protocols which enables devices to physically send/receive data over a wired or a wireless connection. Link layer handles the transmission of signals as bits. eg: _Ethernet, Wireless LAN (WIFI)_

    #### Network Layer
    > Network layer is responsible to __define a virtual addressing protocol for 2 or more devices in a network__ that are connected via some link layer protocols. Virtual addressing protocols are required as we want to uniquely identify each device while transmiting or receiving data. eg: _IPv4 and IPv6_

    #### Transport Layer
    > Transport layer defines the protocols on how to transport the data over the internet. Data on the internet is divided into small packets for efficient transmission. The Transport Layer manages the reliable and orderly delivery of these packets. eg: TCP (Transmission Control Protocol) and UDP (User Datagram Protocol)

    #### Application Layer
    > The Top layer caters the needs of different services and applications of the internet. eg: HTTP, DNS, TLS.

- ### What are the different types of web servers, and how do they differ in terms of functionality and performance?
  * Servers are machines in the network that can cater a type of _service_ over the internet. There are different kinds of servers avaliable which provide different _services._ Web servers are one of them. it is a server that hosts a web application over the internet using HTTP/HTTPS application protocol. Other kinds of servers are, DNS server, Database Server, Email Server, FTP Server etc

    There are mainly 2 kinds of web servers, dynamic web servers and static web servers.

    #### Dynamic vs. static web servers

    Static refers to the content being shown as is, while dynamic content can be updated and changed. A static web server will consist would mainly consist of a single multiple edge nodes that are used to host and serve static, on demand files.

    Dynamic servers would typically consist of an HTTP server, database server, email server and other such applications that enable the serving of dynamic content. this kind of web server can generate content when on request.

- ### What is web hosting, and what are the different types of hosting services available for websites?
  * hosting refers to the service of storing and making websites accessible on the internet. There are various types of hosting available, each catering to different needs and requirements. Let's explore each type and understand where and when to use them:
  
  #### Shared Hosting:

    This type of hosting refers to hosting multiple webapps on a single __machine.__ This kind of hosting refers to sharing the same server resources such as memory and processing power. this is preferred when we have a small, less resource intensive website and do not expect much network traffic.

  #### VPS Hosting (Virtual Private Server):

    VPS hosting is a type of hosting service that uses a virtual machine to share resources on a physical server. It’s best for websites whose traffic exceeds the limits of shared hosting but don’t need the resources of a dedicated server.

    Note: 
    - Difference between shared vs VPS is that in shared hosting, different websites are not containerized and therefore there is no control on resource allocation. 

  #### Dedicated Hosting:

    Dedicated hosting is a type of web hosting where an entire server is devoted to a single client or website. This is opposed to shared hosting, where multiple websites are hosted on the same shared server together.

  #### Cloud Hosting:

    Cloud hosting refers to the use of multiple servers referred to as __cloud.__ This type of hosting enables a finer contol over resource allocation and also allow the user to do server upgrades with 0 downtime.


- ### What is scaling, and why is it important for web applications? How does scaling differ for vertical and horizontal scaling?
  * Scaling refers to increasing the capacity of a website to handle more traffic. As the traffic on a website grows, it may experience increased load, leading to slower response times and potential crashes. Scaling helps ensure that the website remains accessible to users during increased loads.
  There are 2 types of scaling: 
    - Vertical Scaling
    - Horizontal Scaling

  * #### The differences
  > Vertical scaling refers to upgrading the resources of the current server, such as, increasing RAM, SSD, Processor etc to enable the server's to handle more loads. In vertical scaling, overall infrastructure remains unchanged.
  > Horizontal scaling refers to upgrading the overall infrastructure by adding more servers to handle a sudden increase in load.

- ### What is SEO (Search Engine Optimization), and how can web developers optimize their websites for better search engine rankings?
  * Search Engines play a critical role in gaining traction on a website. A search engine is a powerful tool that indexes and catalogs websites, allowing users to search for specific topics, products, or services. A search engine works by crawling, indexing and ranking different results.
  A web developer can optimize their webapps for search engine by understanding how the search engine __crawls, indexes and ranks__ websites.

  Steps to follow:

  __Keyword Research:__ Use keyword research tools to find relevant and popular keywords related to the blog's content.

  __Optimize Content:__ Incorporate the selected keywords naturally into the blog posts' titles, headings, and content. Ensure the blog's content is informative, engaging, and valuable to readers.

  __Meta Tags and Descriptions:__ Create compelling meta tags and descriptions for each blog post, as these elements appear in search engine results and can influence click-through rates.

  __Submit Sitemap:__ Submit the blog's sitemap to Google and Bing Webmaster Tools to ensure search engines can crawl and index the pages efficiently.

  __Measure and Analyze:__ Use Google Webmaster Tools and Bing Webmaster Tools to monitor the blog's performance, track search queries, and identify any issues that need attention.