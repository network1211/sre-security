# Getting Started

## Summary
In a organization who has enough maturity in terms of both cybersecurity and modern app architecture, enterprises runs two different cyber security teams to operate the more advanced security policies for the company. NetSecOps and DevSecOps are two different cyebrsecurity teams in a organization and they have different security requirements. NetSecOps normally wants to have a ‘Standardize Application Security’ and they want to block commonly used attack types with high-confidence, meaning that ‘low-false positive rate’, at the network level. And OWASP Top 10 threats could be a good example here.
But for DevSecOps, they need to have the application-specific security policies which meet the requirements from different types of applications in OpenShift. 
Since DevSecOps understands how their applications work, they want to apply different security policies for their backend applications. 

## Use Case Scenario
This use case demonstrates how organizations position F5 AWAF and NAP(NGINX App Protect) to provide the advanced application security policies for NetSecOps and DevSecOps in a OpenShift environment. In this demo, we suppose that NetSecOps wants to block OWASP Top 10 threats while DevSecOps wants to have different 'file accessing' policy for each backend applications. Below is the table for each team's requirements. 
![](images/sre_usecase01-1.png)


## Configuration Steps

### Prerequisites
- Running OpenShift Cluster (3.11 used in this demo) 
- BIG-IP AWAF already installed

### Demo diagram
![](images/sre_usecase01-2.png)

### Install NAP(NGINX App Protect) 

### Configuring AWAF 

### Simulating the Attack
