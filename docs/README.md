# Objects

## Property

A Property object that explain property information 

### Parameters

-   `name` **[string](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String)** 
-   `address` **[string](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String)** 

## Job

A Job object

### Parameters

-   `title` **[string](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String)** 
-   `type` **[string](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String)** 
-   `date` **[date](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Date)** 
-   `status` **[string](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String)** 


Approach: 
1.	Defining the audience types for documentation
1.	End application users
2.	Tennent administrators/superusers
3.	BH teach team
4.	External developers trying to integrate with Application
5.	Customer support representatives

2.	Defining type of documentation catering to key audience type and classifying them as private / public?
1.	Technical 
1.	Technical/Code documentation [for new comer and debugger] - Private
2.	Open API documentation - Public
3.	Developer guide - Public
2.	Functional
1.	product documentation (offerings)- Public
2.	Knowledge base (how to?) – Public
3.	Knowledge base [customer support] - Private

 
3.	Defining document content structure for non-linear discovery
Proposed structure
1.	Code / Technical documentation [for new comer and debugger]
-	Introduction
-	Application version
-	Current Version 
-	Application architecture
-	Front end
-	Technical overview
-	Components
-	Design system
-	Back end
-	Technical overview
-	APIs
-	Models
-	Database (Dynamo)
-	Security
-	Technical overview
-	Authentication
-	Authorization
-	Supporting libraries and frameworks
-	Release Notes
-	Archived


2.	Open API documentation 
-	Overview
-	Introduction
-	Quick start
-	How to authenticate and authorize
-	Sample API calls
-	API version
-	APIs
-	Deprecated
-	FAQs
-	Contact support
3.	Developer guide -WIP
4.	product documentation (offerings) -WIP
5.	Knowledge base (how to?) -WIP
6.	Knowledge base [customer support] -WIP


4.	Identifying documentation that can automatically be generated from code 
-	Code documentation
-	API documentation

5.	Identifying hosting options for private and public documentation 
Private documentation – requires VPC (AWS) / Content hosting providers (Netlify)
Public documentation – opensource hosting - GitHub pages / Netlify

Note: google sites can’t host custom sites

