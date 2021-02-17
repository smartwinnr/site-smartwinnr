---
slug: "security-policy"
date: '2017-12-07T15:14:32+08:00'
type: ml_layout
layout: ml_layout
---

<section class="scroll-smooth">
  <div class="padding50 ml-pure-white-background ">
    <div class="row  ">
      <div class="col-lg-3 col-md-12 col-sm-12 col-xs-12 div_sticky_privacy">
        <p><h4><b>Table of Contents</b></h4></p>
        <p><b><a href="#our-approach-to-security" class="content-link"> Our Approach to Security</a></b></p>  
        <p><b><a href="#securing-our-internal-environment"> Securing our internal environment</a></b></p>
        <p><b><a href="#security-in-our-day-to-day-operations">  Security in our day-to-day operations</a></b></p>
        <p><b><a href="#keeping-data-secure"> Keeping data secure</a></b></p>
        <p><b><a href="#how-we-identify-protect-against-and-respond-to-security-threats">How we identify, protect against and respond to security threats</a></b></p> 
        <p><b><a href="#securing-our-ecosystem-and-supply-chain-partners"> Securing our ecosystem and supply chain partners</a></b></p>
        <p><b><a href="#compliance-and-risk-management"> Compliance and risk management</a></b></p>
        <p><b><a href="#further-questions-and-inquiries"> Further questions and inquiries</a></b></p>  
      </div>
      <div class="col-lg-9 col-md-12 col-sm-12 col-xs-12">
        <h2><b>SmartWinnr Security practices</b></h2>
          <section >  
             <div id="">
                <p>
                At SmartWinnr, trust and security is one of the most important aspects of all that we do. We're transparent with our security program so you can feel informed and safe using our products and services.</p>
                <p id="our-approach-to-security">
                  Read more about our approach to security and learn about how customers can play their part.
                </p>   
            </div>    
          </section> 
          <br> 
           <section >  
             <div id="">
             <h3><b>Our Approach to Security</b></h3>
                <p>
                  In this section, we discuss SmartWinnr’s approach to security. It covers the key steps we take and controls we implement across a number of security domains, both in securing our own environments (including our cloud-based platforms), and the processes we have in place to ensure we create products that are secure as possible for our customers and users.
                </p>         
            </div>    
            <div id="">
             <h4><b>Our security philosophy</b></h4>
                <p>
                 Our approach to security is based around a couple of core themes:
                 <ul>
                    <li>Meet all customer requirements for cloud security and exceed requirements for industry security standards</li>
                    <li>Identifying present and future security threats to SmartWinnr and its customers, and limiting the impact and duration of security incidents</li>
                    <li>We want to lead our peers in cloud and product security</li>
                </ul>
                In this section we highlight the range of measures and initiatives we have in place to fulfill this philosophy as covered by these key themes.
                </p>         
            </div>   
             <div id="">
             <h4><b>Our team</b></h4>
                <p>
                At SmartWinnr security is the responsibility of every team member. At the same time, we have specialists focusing on specific aspects of the security lifecycle to ensure the highest level of security. These include:
                 <ul>
                    <li>Security architecture – responsible for defining the security requirements of our products and platforms</li>
                    <li>Product security – responsible for the security of our products and platforms</li>
                    <li>Security intelligence – responsible for detecting and responding to security incidents</li>
                    <li>Corporate security – responsible for our internal security with respect to our corporate network and applications</li>
                    <li>Trust – responsible for tracking and responding to customer expectations and provide transparency into our processes and practices</li>
                    <li>Awareness and training – responsible for ensuring our employees and partners know how to work securely</li>
                </ul>
                In this section we highlight the range of measures and initiatives we have in place to fulfill this philosophy as covered by these key themes.
                </p>         
            </div>   
            <div id="">
             <h4><b>More information</b></h4>
                <p>
                    While this paper will provide a broad overview of our approach to security, more detail regarding our security program is available on our SmartWinnr Trust Center. There’s also a range of dedicated whitepapers on 
                </p>         
                <p><a href="/trust/security-policy" target="_blank" class="ml_custom_link">Our Security Practices </a></p>
                <p><a href="/trust/security-testing" target="_blank" class="ml_custom_link">Our Approach to External Security Testing</a></p>
                <p><a href="/trust/security-incident-management" target="_blank" class="ml_custom_link">Our Approach to Managing Security Incidents</a></p>
                <p><a href="/trust/security-incident-management" target="_blank" class="ml_custom_link">Our Approach to Vulnerability Management </a></p>
                <p><a href="/trust" target="_blank" class="ml_custom_link">Our SmartWinnr Trust Management System </a></p>
                <p><a href="/trust/security-policy" target="_blank" class="ml_custom_link" id="securing-our-internal-environment">Our SmartWinnr Security & Technology Policies </a></p>
            </div> 
            <br><br>
            <div id="">
             <h3><b>Securing our internal environment</b></h3>
                <p>
                   An effective approach to security starts with getting our own house in order – specifically by keeping our own internal environments secure. There are a number of steps we take to achieve this
                </p>     
            </div>  
           <div id="">
             <h4><b>Building security into our network architecture</b></h4>
                <p>
                   SmartWinnr practices a layered approach to security for our networks. We implement controls at each layer of our cloud environments, dividing our infrastructure by zones, environments, and services. We have zone restrictions in place that include limiting office/staff, customer data, CI/CD and DMZ network traffic. We also have environment separation to limit connectivity between production and non-production environments, and production data is not replicated outside of production environments. Access into production networks and services is only possible from within those same networks – e.g. only a production service can access another production service.
                </p>  
                <p>
                Services must be explicitly authorized to communicate with other services through an authentication allowlist. We control access to our sensitive networks through the use of virtual private cloud (VPC) routing, firewall rules, and software defined networking, with all connections into those networks encrypted. We’ve also implemented intrusion detection in our production networks to detect potential compromises.
                </p>   
            </div>  
            <div id="">
             <h4><b>Managing access to our systems and services securely</b></h4>
                <p>
                  SmartWinnr has a well-defined process for provisioning (assigning or revoking) user access for all systems and services. We use role-based access control based on predefined user profiles to ensure staff only have access appropriate to their job role. All user accounts must be approved by management prior to having access to data, applications, infrastructure or network components.
                </p>  
                <p >
                   For accessing business-critical data, users need to authenticate either through a mobile application authenticator provisioned to SmartWinnr employees – we have removed less secure authentication methods such as SMS and phone-based OTPs. SmartWinnr has adopted this approach to ensure our authentication process is highly resistant to phishing-based and man-in-the-middle attacks - any system that sends codes in a text message can be compromised by a skilled attacker.<span id="security-in-our-day-to-day-operations"></span>
                </p>   
            </div> <br> <br>
            <div id="">
             <h3><b>Security in our day-to-day operations</b></h3>
                <p>
                   We strive hard to build security into all aspects of our day-to-day operational processes. We want security to be an inherent part of how we do things so that we minimise the need to ‘retrofit’ or ‘bolton’ security after-the-fact.
                </p>  
                <p>
                   For accessing business-critical data, users need to authenticate either through a mobile application authenticator provisioned to SmartWinnr employees – we have removed less secure authentication methods such as SMS and phone-based OTPs. SmartWinnr has adopted this approach to ensure our authentication process is highly resistant to phishing-based and man-in-the-middle attacks - any system that sends codes in a text message can be compromised by a skilled attacker.
                </p>   
            </div>  
            <div id="">
             <h4><b>Keeping track of our information assets</b></h4>
                <p>
                   Our production systems are located in infrastructure obtained through cloud service providers. These systems are not tracked at a hardware level due to the nature of the service. They are tracked in our internal service management system.
                </p>  
            </div>  
            <div id="">
             <h4><b>Managing changes in our environment</b></h4>
                <p>
                   At SmartWinnr, every change –  be it a code change or an infrastructure change – is reviewed by one or more peers to identify any issues the change may potentially cause. We increase the number of reviewers based on the criticality of the change or the criticality of the systems that the change is going to impact, trusting our engineers to identify issues and then flag them before the change can go through. This process works well to provide a dynamic and adaptable way of managing changes in our environment. All software changes are tracked on our on-premise GitLab server and all infrastructure changes are tracked by AWS Config. Hence in the unlikely event of a change leading to any issues, we can can easily roll it back.
                </p>  
            </div> 
            <div id="">
             <h4><b>Managing configurations in our systems</b></h4>
                <p>
                  We have a limited set of engineers and architects who are allowed to install software in our production environment. Configuration management tools are utilised in our production environments to manage configurations and changes to servers. We rely on standard Amazon Machine Images (AMIs), all changes to either our AMIs or operating systems must be made via our standard change management process, we track and report on exception configurations, and we have implemented resource isolation so issues with services don’t impact other services.
                </p>  
            </div> 
            <div id="">
             <h4><b>Making use of logs</b></h4>
                <p>
                  We aggregate logs from various sources, apply monitoring rules to those aggregated logs, and then flag any suspicious activity. Our internal processes define how these alerts are triaged, investigated further, and escalated appropriately. The SmartWinnr Security Team creates alerts on our security analytics platform and monitors for indicators of compromise. Our SRE teams use this platform to monitor for availability or performance issues. 
                </p>  
            </div> 
          <div id="">
             <h4><b>Business continuity and disaster recovery management</b></h4>
                <p>
                   We care deeply about the resiliency of our products. We appreciate that disruptions can happen. So we are determined to build-in processes to plan for disruptions, and handle disruption with minimal impact to our customers when they do occur. Our business continuity (BC) and disaster recovery (DR) programs capture the various activities done to meet those objectives.
                </p>  
                <p>
                   Leadership involvement in BC and DR planning activities ensures the oversight required to make sure accountability for resiliency reaches all teams. Our BC and DR planning activities strive to achieve the right balance between cost, benefits and risk through an analysis of ‘recovery time objectives’ (RTO) and ‘recovery point objectives’ (RPO) of services. This analysis has led to us establishing a system to help group services based on their respective recovery requirements.
                </p>
                <p>
                Our BC and (DR) programs involve the following activities:
                <ol type="1">
                 <li>building-in redundancy measures to meet resiliency requirements</li>
                <li>testing and verifying those redundancy measures</li>
                <li>learning from tests to continuously keep improving BC and DR measures</li>
                </ol>
                </p>
                <p>
                   We build our products to best utilise redundancy capabilities, such as availability zones and regions, offered by our cloud service providers.
                </p>
                <p>
                   We continuously monitor a wide range of metrics with the aim of detecting potential issues early. Based on those matrices, alerts are configured to notify site reliability engineers (SREs) or the relevant product engineering teams when thresholds are breached so that prompt action can be taken through our incident response process. 
                </p>
                <p>
                    SREs also play a key role in identifying gaps in the DR program, and work with our risk and compliance team to close those gaps. Each of our teams also include a DR champion to oversee and help manage disaster recovery aspects related to that team.
                </p>
                <p>
                   Our DR tests cover process and technology aspects, including relevant process documentation. The frequency of DR tests are done in line with the criticality tier of each service – for example, backup and recovery processes for key customer facing systems are tested quarterly. We conduct manual and ad-hoc failover tests on our systems. These tests range from less complicated tabletop simulation exercises to more complicated availability zone or regional failover tests. Regardless of the complexity of the test, we are diligent in capturing and documenting test results, analysing and identifying possible improvements or gaps.
                </p>
                <p>
                    We conduct annual Business Impact Assessments (BIAs) to assess the risks associated with critical services. The output of these BIAs assist in driving the strategy for DR and BC efforts. As a result, critical services are able to develop effective DR and BC plans.
                </p>
            </div> 
           <div id="">
             <h4><b>Service availability</b></h4>
                <p>
                  In addition to the above measures, we also publish our <a href="https://status.smartwinnr.com/" target="_blank" class="ml_custom_link">service availability status</a> in real-time for our customers. If there are any issues, our customers will know as soon as we do.
                </p>  
            </div> 
            <div id="">
             <h4><b>Backups</b></h4>
                <p>
                  We operate a comprehensive backup program at SmartWinnr. SmartWinnr utilises the snapshot feature of AWS to create automated hourly and daily backups of each database instance.
                </p>  
                <p>
                 Hourly snapshots are retained for 24 hours and daily snapshots are retained for 30 days and are encrypted using AES-256 encryption. Backup data is replicated to multiple data centers within a particular AWS region. We also perform quarterly testing of our backups.
                </p>
            </div> 
           <div id="">
             <h4><b>Physical security</b></h4>
                <p>
                   Physical security controls in our offices are guided by our physical and environmental security policy which ensures robust physical security is implemented across our environments on premises and in the cloud. This policy covers areas such as secure working areas, securing our IT equipment wherever it may be, restricting access to our buildings and offices to appropriate personnel, and monitoring physical ingress and egress points. Our physical security practices include reception attendance during work hours, requirements for visitors to register, badge access to all non-public areas, and we partner with our office building management for after hours access and video recording at ingress and egress points.
                </p>  
                <p>
                  Our partner data centres are SOC-2 compliant, at a minimum. These certifications address a range of security controls including physical and environmental security and protection. Access to the data centres is limited to authorized personnel, and verified by biometric identity verification measures. Physical security measures include on-premises security guards, closed circuit video monitoring, man traps, and additional intrusion protection measures.<span id="keeping-data-secure"></span>
                </p>
            </div> <br><br>
            <div id="">
             <h3><b>Keeping data secure</b></h3>
                <p>
                 We have a number of measures to ensure that we keep customer data secure, available and that customers retain control over it to the fullest extent possible
                </p> 
            </div> 
            <div id="">
             <h4><b>Data centers</b></h4>
                <p>
                  SmartWinnr products and data are hosted with the industry-leading cloud hosting provider Amazon Web Services (AWS). We make use of optimal performance with redundancy and failover options globally. We make use of multiple geographically diverse regions within AWS (US-East and USWest, European Union and the Asia Pacific), and multiple availability zones within each of those regions to ensure that a failure in any single data center does not affect the availability of our products or customer data. 
                </p> 
                <p>
                  Physical access to our data centers, where customer data is hosted, is limited to authorized personnel only, with access being verified using biometric measures. Physical security measures for our data centers include on-premise security guards, closed-circuit video monitoring, man traps, and additional intrusion protection measures.
                </p>
            </div> 
           <div id="">
             <h4><b>Encryption of data</b></h4>
                <p>
                   Any customer data in SmartWinnr cloud products is encrypted in transit over public networks using TLS 1.2+ to protect it from unauthorized disclosure or modification. Our implementation of TLS enforces the use of strong ciphers and key-lengths where supported by the browser
                </p> 
                <p>
                   Data drives on servers holding customer data use full disk, industry-standard AES-256 encryption at rest.
                </p>
            </div> 
           <div id="">
             <h4><b>Key management</b></h4>
                <p>
                SmartWinnr uses the<a href="https://aws.amazon.com/kms/" target="_blank" class="ml_custom_link"> AWS Key Management Service (KMS)</a> for key management. The encryption, decryption, and key management process is inspected and verified internally by AWS on a regular basis as part of their existing internal validation processes. An owner is assigned for each key and is responsible for ensuring the appropriate level of security controls is enforced on keys. 
                </p> 
            </div> 
            <div id="">
             <h4><b>Tenant separation</b></h4>
                <p>
                  While our customers share a common cloud-based IT infrastructure when using SmartWinnr’s products, we have measures in place to ensure they are logically separated so that the actions of one customer cannot compromise the data or service of other customers.
                </p> 
                <p>
                 SmartWinnr use a concept we refer to as the “tenant context” to achieve logical isolation of our customers. This is implemented in the application code so that:
                </p>
                 <ul>
                  <li>Each customer’s data is kept logically segregated from other tenants when at-rest</li>
                  <li>Any requests that are processed have a “tenant specific” view so other tenants are not impacted</li>
                 </ul> 
                <p>
                In broad terms, this works by storing a "context" for individual customer tenants. The context for each tenant is associated with a unique ID stored centrally by the TCS, and includes a range of metadata associated with that tenant (such as which databases the tenant is in, what licenses the tenant has, what features they can access, and a range of other configuration information). When a customer accesses the solution, we use the tenant ID to collate that metadata, which is then linked with any operations the tenant undertakes in the application throughout their session.
                </p>
                <p>
                The context provided effectively acts as a ''lens'' through which any interactions with customer data occur – and this lens is always confined to one specific tenant. This ensures that one customer tenant does not access data of another tenant – nor for one tenant to affect the service of another tenant through their own actions.
                </p>
                <p>
                More information about our cloud architecture is available as part of our cloud support resources.
                </p>
            </div> 
           <div id="">
             <h4><b>Key management</b></h4>
                <p>
                SmartWinnr uses the<a href="https://aws.amazon.com/kms/" target="_blank" class="ml_custom_link"> AWS Key Management Service (KMS)</a> for key management. The encryption, decryption, and key management process is inspected and verified internally by AWS on a regular basis as part of their existing internal validation processes. An owner is assigned for each key and is responsible for ensuring the appropriate level of security controls is enforced on keys. 
                </p> 
            </div> 
           <div id="">
             <h4><b>Sharing the responsibility for managing customer data</b></h4>
                <p>
                  SmartWinnr assumes responsibility for security, availability and performance of the applications we provide, the systems they run on, and the environments within which those systems are hosted. However, security is a joint responsibility between SmartWinnr and our customers with respect to four areas in particular:
                </p> 
                <p>
                <b>Policy and compliance</b><br>
                Ensuring that the system meets customer business needs and is operated in accordance with industry, regulatory and legislative compliance obligations.</p>
                <p>
                  <b>Users</b><br>
                  The creation and management of user accounts.
                </p>
                <p>
                  <b>Information</b><br>
                  The content customers store within SmartWinnr.
                </p>
                <p>
                  <b>Marketplace Apps</b><br>
                    Third party services which integrate with SmartWinnr products.
                </p>
                <p>
                While SmartWinnr takes all necessary steps to protect and secure customer data, the reality is that the decisions our customers make about how they set up our products also have a significant influence on the way security is implemented. Important issues they need to be aware of when using our products include:
                </p>
                <ul>
                <li>Access permissions – Customers do need to exercise caution in the permissions they grant to users within their organization regarding access to data. In some cases they can also grant public access to data – SmartWinnr has no control over this and cannot in these cases prevent such data being copied or further distributed</li>
                <li>Centralized access – Our customers are strongly encouraged to use centralized administration and enhanced security across all SmartWinnr products they use </li>
                </ul>
            </div>
            <div id="">
             <h4><b>Controlling access to customer data</b></h4>
              <p>     
                We treat all customer data as equally sensitive and have implemented stringent controls governing this data. Awareness training is provided to our internal employees and contractors during the on-boarding process which covers the importance of and best practices for handling customer data.
             </p>
             <p>
             Within SmartWinnr, only authorized users have access to customer data stored within our applications. Servers only accept incoming SSH connections from specific IPs mapped to SmartWinnr authorized users or data center locations. All access is restricted to privileged groups unless requested and reviewed, with additional authentication requiring 2FA.
             </p> 
             <p>
             With stringent authentication and authorization controls in place, our global support team facilitates maintenance and support processes. Hosted applications and data are accessed for the purpose of application health monitoring and performing system or application maintenance, or upon customer request via our support system.
             </p>
             <p>
             Unauthorized or inappropriate access to customer data is treated as a security incident and managed through our incident management process. This process includes instructions to notify affected customers if a breach of policy is observed.
             </p>
           </div> 
            <div id="">
               <h4><b>Retention and deletion of data</b></h4>
                 <p>
                     We have provisions in place so that we can respond to user requests to delete personal information, and we also help end users with SmartWinnr accounts delete their personal information. We also have import and export tools so that our customers can access, import and export their data using SmartWinnr’s tools.
                 </p> 
                 <p>
                 Customer sites are deactivated 30 days after the end of a customer’s current subscription period. SmartWinnr retains data for deactivated  accounts for 60 days after the end of the customer’s current subscription period.
                 </p>
            </div> 
            <div id="">
               <h4><b>Retention and deletion of data</b></h4>
                 <p>
                     We have provisions in place so that we can respond to user requests to delete personal information, and we also help end users with SmartWinnr accounts delete their personal information. We also have import and export tools so that our customers can access, import and export their data using SmartWinnr’s tools.
                 </p> 
                 <p>
                 Customer sites are deactivated 30 days after the end of a customer’s current subscription period. SmartWinnr retains data for deactivated  accounts for 60 days after the end of the customer’s current subscription period.
                 </p>
            </div>
            <div id="">
               <h3><b>Securing our people</b></h3>
                 <p>
                   We are intent on making sure all of our staff know how to do their work securely and are empowered to act accordingly. Embedding a security mindset is at the forefront of SmartWinnr’s culture, and contributes towards lifting our overall resiliency against potential cyber attacks.
                 </p> 
            </div> 
            <div id="">
               <h4><b>Security awareness training</b></h4>
                 <p>
                     We make sure all staff undergo security awareness training during the onboarding process and then on an ongoing basis so that security remains ‘front of mind’. We understand that many of the threats faced by our team are the same threats faced by our contractors and other partners we work with, so we extend security awareness training to cover those contractors and partners as well. Topics addressed in our security awareness training program include current threats and scams, secure working practices, potentially risky behaviours that create security risks, and compliance and regulatory issues.
                 </p> 
                 <p>
                 In addition to general information security training, more targeted training is available to our developers on secure coding.
                 </p>
            </div> 
             <div id="">
               <h4><b>Background checks</b></h4>
                 <p>
                    We want to hire people that will go on to positively shape the security embedded culture we have built. Background checks are performed on all new recruits to aid in this process
                 </p> 
            </div> <br>
            <div id="">
               <h3><b>Securing our products</b></h3>
                 <p>
                  SmartWinnr is focused on ensuring that security forms a key part of all phases of our product life cycles. There are a number of methods we utilise to achieve this.
                 </p> 
            </div>
            <div id="">
               <h4><b>Security engineers</b></h4>
                 <p>
                    Our product security team runs a security embedding program providing guidance to product teams and ensuring security processes are integrated into the development lifecycle. Security engineers provide security consulting support, and also help teams monitor, interpret, and promptly action findings that are identified through the scorecard system.
                 </p> 
                 <p>
                 <b>Targeted security assurance</b>
                 </p>
                 <p>
                  The product security team also runs a security review process to provide security assurance across software projects. A risk-based process is used to prioritise where to focus assurance activities, and identify what actions are required to mitigate project risk. Depending on the identified level of risk, assurance activities include a combination of:
                 </p>
                 <ul>
                  <li>Threat modeling</li>
                  <li>Design review</li>
                  <li>Code review (manual and tool assisted)</li>
                  <li>Security testing</li>
                  <li>Independent assurance using expert third party researchers and consultants</li>
                 </ul>
            </div> 
            <div id="">
               <h4><b>Secure design through threat modelling</b></h4>
                 <p>
                   During the planning and design phases for our products, threat modelling to understand better security risks when projects face complex threats or involve development of security critical features. This involves a table-top/ brainstorm session between our engineers, security engineers, architects and product managers to identify and priority relevant threats. This information feeds into the design process and ensures appropriate controls are implemented. It also supports targeted review and testing in later phases of development.
                 </p> 
            </div>
           <div id="">
               <h4><b>Code analysis</b></h4>
                 <p>
                   We have an automated code analysis platform that covers all code repositories at SmartWinnr. This platform runs a variety of static analysis tools (which we are continually adding to and improving) that help to ensure the overall security of our code. <span id="how-we-identify-protect-against-and-respond-to-security-threats"></span>
                 </p> 
            </div>  <br> <br>
            <div id="">
               <h3><b>How we identify, protect against and respond to security threats</b></h3>              
            </div>  
            <div id="">
               <h4><b>Security testing</b></h4>
                 <p>
                   Our security testing approach is built around the concept of ‘continuous assurance’ – including use of targeted, point-in-time penetration tests. More information is available in our separate paper covering our <a href="/trust/security-testing" class="ml_custom_link">approach to external security</a> testing, and a summary of our testing measures is provided below:
                 </p> 
                 <ul>
                 <li>Internal Security Review - As mentioned above, our Product Security team runs a security review program including security testing as a regular activity. Testing consists of code review and application security testing, targeting areas of weakness highlighted by risk assessment</li>
                <li>External Penetration Testing - We use specialist security consulting firms to conduct penetration tests</li>
                <li>SmartWinnr’s Red Team – We have an internal red team whose role is to simulate adversaries attempting to identify and exploit vulnerabilities that exist within our systems, processes, and environments, so that we can ensure they are identified and addressed as promptly as possible</li>
                 </ul>
            </div>
          <div id="">
               <h4><b>Vulnerability management</b></h4>
                 <p>
                    SmartWinnr is constantly striving to reduce the severity and frequency of vulnerabilities in our products, services and infrastructure. To this end, we have a multi-faceted and continually evolving approach to vulnerability management that utilises both automated and manual processes across both our products and infrastructure.
                 </p> 
                 <p>
                    We track vulnerabilities we identify using our internal ticketing systems, and we have created a purpose-built tool that provides a ‘single pane of glass’ view for tracking the current status of vulnerabilities that exist across our products and infrastructure throughout the SmartWinnr environment. This means we have a central point from which we can track every vulnerability that has been identified to ensure that nothing accidentally gets forgotten or overlooked. A summary is provided below, and more information is available in our dedicated paper on <a href="/trust/security-incident-management" class="ml_custom_link">SmartWinnr’s approach to vulnerability management.</a>
                 </p> 
            </div>
             <div id="">
               <h4><b>Infrastructure</b></h4>
                 <p>
                    We use a range of vulnerability detection tools that are run regularly across our infrastructure to automatically scan for and identify vulnerabilities. This includes:
                    <ul>
                      <li>Network scans – to identify active services, open ports and applications running across our environment, as well as any vulnerabilities at the network level</li>
                      <li>Continuous asset discovery – we undertake continuous asset discovery and security analysis across our external network perimeters.</li>
                      <li>AWS Configuration Monitoring – we monitor the configuration of our AWS environments against established configuration baselines</li>
                    </ul>
                 </p> 
                 <p>
                    We are continually reviewing the latest tools available and adding them to the suite we use if we believe they will enhance our vulnerability detection capabilities.
                 </p> 
            </div>
            <div id="">
               <h4><b>Products</b></h4>
                 <p>
                   As part of our development process we use a range of tools to try to identify and prevent as many vulnerabilities and bugs as possible from making their way into our products by the time our customers and users have access to them.
                 </p> 
                 <p>
                    Our products and services rely on numerous open source libraries. We use a combination of open source, and commercial tools to scan for and identify dependencies and compare these to a database of known security vulnerabilities
                 </p> 
                <p>
                  In addition, when a vulnerability is identified by one of our users during standard use of a product, we welcome notifications and respond promptly to any vulnerabilities submitted. We keep the submitter updated as we investigate and respond to the issue.
                </p> 
            </div>
            <div id="">
               <h4><b>Incident response</b></h4>
                 <p>
                   SmartWinnr has a comprehensive approach to handle security incidents. We consider a security incident to be any instance where there is a negative impact to the confidentiality, integrity or availability of customers’ data, SmartWinnr’s data, or SmartWinnr’s services.
                 </p> 
                 <p>
                   We have a clearly defined internal framework that includes documented playbooks for different incident types. The framework covers the steps we need to take at all stages of incident response to ensure our processes are consistent, repeatable and efficient. These include coverage of incident detection and analysis, incident categorization, containment, eradication and recovery. 
                 </p> 
                <p>
                     Comprehensive and centralized logging and monitoring of our products and infrastructure is in place to ensure we quickly detect potential incidents, supported by a team of highly-qualified on-call incident managers who have significant experience in coordinating an effective response. We also have access to a range of external experts to assist us with investigating and responding as effectively as possible.
                </p> 
               <p>
                  We have notification processes in place for our customers if their data is involved in a confirmed incident, as well as a robust post-incident review process so we can take any lessons from an incident to improve our practices to make the job of malicious actors harder in the future. For more information, please see our separate paper our SmartWinnr Trust Center on <a href="/trust/security-incident-management" class="ml_custom_link">Our Approach to Managing Security Incidents.</a><span id="securing-our-ecosystem-and-supply-chain-partners"></span>
               </p> 
            </div><br><br>
            <div id="">
               <h3><b>Securing our ecosystem and supply chain partners</b></h3>
              </div>
                <div id="">
                <h4><b>Supplier risk management</b></h4>
                 <p>
                    Where SmartWinnr engages any third-party suppliers (including contractors and cloud service providers) we are intent on making sure those engagements do not in any way jeopardise our customers or their data. To this end, a review process is undertaken by our legal and procurement teams for any proposed third-party supplier engagements. For any engagements we deem high or critical risk, these are subject to additional reviews by our security and risk and compliance teams. Ongoing due diligence also occurs via subsequent reviews - either upon contract renewal or annually depending on the risk level of the engagement.
                 </p> 
                 <p>
                 SmartWinnr also requires its suppliers to comply with minimum security requirements as part of their engagement with us. These are enforced via inclusion in our supplier contracts. These requirements will vary depending on the risk level of the engagement, and includes the following:
                 </p>
                 <ul>
                  <li>Encryption for data in transit and at rest using non-deprecated algorithms</li>
                  <li>Having sufficient logging mechanisms in place to provide SmartWinnr with relevant information regarding potential security incidents  </li> <span id="compliance-and-risk-management"></span>
                 </ul>
              </div> <br><br>
              <div id="">
                <h3><b>Compliance and risk management</b></h3>
                <h4><b>Our Risk Management Program</b></h4>
                 <p>
                   We undertake on-going risk assessments to our environments and products in order to evaluate the current risks we face and ensure the controls we have in place effectively manage those risks. The nature of how these risk assessments are conducted will vary depending on the environment/ product being assessed – for example, in the case of our products, these will often be technical risk assessments or code reviews. However, we also consider and seek to uncover higher level business risks as well. We perform and undertake an annual risk assessment in support of our Enterprise Risk Management Program and implement projects to mitigate identified risks at least quarterly.
                 </p> 
              </div> 
              <div id="">
                <h4><b>Privacy at SmartWinnr</b></h4>
                 <p>
                   SmartWinnr has a comprehensive privacy program in place to ensure that we not only commit to meeting the highest bar for personal data privacy, but support our customers in meeting their data privacy obligations.
                 </p> 
                <p>
                 We have invested significant resources in maintaining compliance with current privacy requirements in jurisdictions across the world – the Global Data Protection Resolution (GDPR) and the California Consumer Protection Act (CCPA) being two examples. We have ensured SmartWinnr staff that access and process SmartWinnr customer personal data have been trained in handling that data and are bound to maintain the confidentiality and security of that data. We also hold any vendors that we engage that handle personal data to the same data management, security, and privacy practices that we hold ourselves and are subject to.
                 </p> 
                <p>
                Where applicable, we institute appropriate international data transfer mechanisms by executing standard contractual clauses through our updated <a href="https://smartwinnr-resources.s3-eu-west-1.amazonaws.com/SmartWinnr+Trust+Policies+Resources/SmartWinnr+Data+Processing+Addendum.pdf" target="_blank" class="ml_custom_link">data processing addendum.</a> We have made a number of data management and portability tools available to our customers as well, including: 
                </p>
                <ul>
                <li>Profile deletion tool: We help customers respond to user requests to delete personal information, and we also help end users with SmartWinnr accounts delete their personal information</li>
                <li>Import and export tools: Customers may access, import, and export their Customer Data using SmartWinnr’s tools</li>
                </ul>
                <p>
                More information about our privacy program is available on our <a href="/trust" class="ml_custom_link">SmartWinnr Trust Center.</a> You can also view our current <a href="/trust/privacy-policy" class="ml_custom_link">Privacy Policy </a>here.
                </p>
              </div> 
              <div id="">
                <h4><b>Internal and external audit</b></h4>
                    <p id="further-questions-and-inquiries">
                      We perform comprehensive security audits annually. Additional internal audits are performed in areas that are deemed ‘high risk’ and are all fed into a continuous improvement cycle which helps us keep sharpening the overall security program.
                    </p>
              </div>
              <br> 
              <div id="">
                <h3><b>Further questions and inquiries</b></h3>
                    <p>
                      While our security practices have provided a broad overview of our approach to security, naturally given this is a complex area and SmartWinnr is doing a significant amount in this space, we haven’t been able to cover everything in detail here.
                    </p> 
                    <p>
                    If you need more information, visit our <a href="/trust" class="ml_custom_link">SmartWinnr Trust Center.</a>
                    </p>
              </div> 
          </section>  
    
   </div>
    </div>
  </div>
</section>
