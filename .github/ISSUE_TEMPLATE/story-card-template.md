---
name: Story card template
about: Track the progress of a story card
title: ''
labels: Storycard
assignees: ''

---
# Story Card Request

**Project:**    
**Card Title:**        
**Card Document:** (link here)        

## Milestones

### Setup
- [ ] Create Card Document from [this template](https://docs.google.com/document/d/1aNBU5m5vc7coXbHzItJB9sUMAGufMVYEJZqXUkY40Gc/edit#) and link above     

### Type of data processing / analysis this story card uses 
- [x] descriptive - simple data (re)-representation, doing summary statistics belongs to this category, we do this for all data sets      
- [ ] explanatory - testing hypotheses and / or comparing data points     
- [ ] predictive - any regression, model fitting, classification or clustering tasks      
- [ ] prescriptive - when you want to recommend any action to be taken (we do this rarely, if at all)      

### Data documentation and proposed analysis
- [ ] Document [metadata](https://forms.gle/7aL8U3Y9ANNz9oda7)       
- [ ] Decide whether to load to database or S3 with proper metadata documentation       
- [ ] Review metadata and proposed data analysis      

### Set up data processing development environment   
- [ ] Clone repo from [template] (https://github.com/karenng-civicsoftware/HackORDataScienceTemplate)       
- [ ] Set up access to GitHub repo for all team members
- [ ] Set up a container from a suitable version of the [Dockerfile template](https://github.com/karenng-civicsoftware/HackORDataScienceTemplate/blob/master/build/Dockerfile)       
- [ ] Prototyping and testing analysis proposals       
- [ ] Review additional proposed data analysis identified through prototyping       
- [ ] Write code for reproducible data processing steps with proper version control & data lineage    
- [ ] Data science results produced and documented      
- [ ] Data science peer reviewed        

### Build APIs
- [ ] Database deployed to CIVIC Cloud      
- [ ] Initial backend API repo created via [cookiecutter](https://github.com/hackoregon/2019-backend-cookiecutter-django), using templatized names  
- [ ] API developer confers with Data Visualization/Frontend teams regarding story card MVP
- [ ] API developer confers with Data Scientists regarding all needed calculations, filters and queries, validation
- perhaps using OpenAPI as a contract/organization first, can help understand the needs/requirements [link to OpenAPI](https://swagger.io/docs/specification/about/) and 
[Why use OpenAPI](https://apievangelist.com/2018/04/03/openapi-is-the-contract-for-your-microservice/)

- [ ] Basic API in container       
- [ ] Basic API deployed to CIVIC Cloud       
- [ ] TBD process for API design - standardization?        
- [ ] API endpoint with all needed calculations, filters and queries        

### Data visualization:
- [ ] Concept clearly articulated through card title, visualization title/subtitle, card question(s)/action(s), and card context
- [ ] Titles and context use consistent language (e.g., census tract v. neighborhood) and match grain of data used in the visualization 
- [ ] Visualization and component choices inline with [data visualization best practices](https://docs.google.com/document/d/1t-9bQXNJDPHbsdiikel_GnRnIjRR_eG6J0m650QUidI/edit?pli=1#heading=h.twg0yldcvbia)        
- [ ] All components needed available in [Storybook](https://hackoregon.github.io/civic/)       
- [ ] Components available in [Storybook](https://hackoregon.github.io/civic/) demonstrate all needed features      
- [ ] Follows data visualization and interface guidelines available in [Storybook](https://hackoregon.github.io/civic/)       

### Design
- [ ] TBD Wireframes?     
- [ ] TBD Design review?     

### Written content / additional links
- [ ] Write content     
- [ ] Review content      
