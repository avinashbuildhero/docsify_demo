# BH Documentation approach

## Approach: 

   ### 1. Defining the audience types for documentation
        1.	End application users
        2.	Tennent administrators/superusers
        3.	BH teach team
        4.	External developers trying to integrate with Application
        5.	Customer support representatives

### 2. Defining type of documentation catering to key audience type and classifying them as private / public?
   ### Technical 
        1.	Technical/Code documentation [for new comer and debugger] - Private
        2.	Open API documentation - Public
        3.	Developer guide - Public
  ### Functional
        1.	product documentation (offerings)- Public
        2.	Knowledge base (how to?) – Public
        3.	Knowledge base [customer support] - Private

 
### 3. Defining document content structure for non-linear discovery
   ### Proposed content organization structure
__*1.	Code / Technical documentation [for new comer and debugger]*__
    
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


__*2.	Open API documentation*__
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

__*3.	Developer guide -*__ __**WIP**__

__*4.	product documentation (offerings) -*__ __**WIP**__

__*5.	Knowledge base (how to?) -WIP -*__ __**WIP**__

__*6.	Knowledge base [customer support] -*__ __**WIP**__



### 4.	Identifying documentation that can automatically be generated from code 
    -	Code documentation
    -	API documentation

### 5.	Identifying hosting options for private and public documentation 
    Private documentation – requires VPC (AWS) / Content hosting providers (Netlify)
    Public documentation – opensource hosting - GitHub pages / Netlify

   __**Note: google sites can’t host custom sites**__

