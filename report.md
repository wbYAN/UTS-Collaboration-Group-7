# **Information System Development Methodologies 31257**

# **Tutorial 11: Friday 1.30 PM**

# **Tutor: Ghassan**

# **Group 7**

| **Student Name** | **Student ID** |
| --- | --- |
| Yan Wei Bing | 13396813 |
| Sean Christian | 13341767 |
| Peifeng Xing | 13314594 |
| Zhibo Zhao | 13593571 |

**Table of Contents**

**[Executive Summary](#_2dv39k7rogo) 2**

**[Introduction](#_vrgdzcedw1om) 3**

**[Objectives](#_vnz4ka6xd3j2) 3**

**[Problem definition](#_du8yrkpjzzqw) 4**

**[Stakeholders](#_vd8yhbbgn4nh) 4**

**[Empathy Map](#_cpy9qyp7id63) 5**

**[Reflection](#_xf6zqcxlgtt8) 7**

**[User stories](#_ljwod5usx4vd) 9**

**[Use Case Diagrams](#_1u7spb3jvyte) 10**

**[Activity Diagram](#_40munpyz744v) 12**

**[Class Diagram](#_hd3ajky9ortx) 13**

**[Collaborative diagram](#_c44bboridgfm) 14**

**[Advantages](#_z9co7hayptws) 14**

**[Possible Risks](#_viknf1ec3oht) 15**

**[Scrum](#_ki3yju795hm3) 15**

# Executive Summary

The purpose of this proposal report is to help the major travel company to develop and implement an information system to enhance the operation of their call management centre. The report will show how the information system will be implemented using the design thinking system and the scrum method. Moreover, it also addresses the competitive advantage and potential risk of the project.

# Introduction

A travel company is upgrading a CMC system to improve customer service.The main idea of the system is to score the customer and the RM separately, and then make a reasonable match.This will make telemarketing more efficient and make the customers more satisfied.The system builds an RM profile that includes age, gender, culture, language, and experience.A customer profile is also created, with basic information and purchase history.And then the system will make the appropriate match based on that. During peak hours, users&#39; calls are transferred to IVR and they are asked for the service they need.Then, the user may wait a while before being served, which may make the customer hang up.This is an issue that needs to be solved.

# Objectives

· Improve the operations of inbound and outbound calls

· Implement and use third party supporting tools, Profiler Tool, to help matching a right customer to a right relationship manager based on their profile created.

· The Call Management Centre automated system will respond to the customer automatically. Then collect and search the customer profile before directing the call to a relationship manager.

· Enable customers to book a call to prevent them from suffering a long wait time.

· The ability to check the cost of calls, answering time and handle time of call monthly for the company to analyse.

· Allow the relationship manager to perform more sales when matching to the right customer.

· Allow the relationship manager to provide better service to the customer by reading the detailed customer profile

· All customers will be fairly treated.

· Create a target list of potential buyers for each RM to make outbound calls. Using the script as a guide to meet the customer needs.

# Problem definition

The current in-house call management centre operation is not efficient because customers are segments according to their postcodes and surnames. As a result, customers with a preferable postcode are served first, whereas customers with a lower postcode must wait a longer time than those customers. Hence, it can be seen that the current system is not fair for all customers.

On top of that, the current matching system only utilizes the customer postcodes to match the customer to a relationship manager, where it does not pose any useful information to guide the relationship manager. This causes relationship managers to not understand the customer&#39;s needs, and the customer is feeling a lack of interest, which makes the whole duration of call lead to a waste of time.

Also, during peak hour, customers who suffer a long wait time for a relationship manager to answer decide to hang up the call. This will cause travel company loss of the potential and current customer.

# Stakeholders

Customer – Person who makes calls to the relationship manager to receive information about the holiday packages or purchase holiday packages. The proposed solution helps them to reduce wait time for calling the travel company relationship manager and receive better service.

Relationship Manager – Employee who works for the travel company that answers calls from customers to solve their queries about holiday packages and perform sales of holiday packages. The proposed solution could help the relation manager to manage inbound and outbound calls efficiently and effectively.

Profiler Tool – Third party supporting tool that will be implemented into the call centre system to build customer and relationship manager profiles. Then, find the best matches of both entities.

Telecommunication service provider – Provide services to the customer and the travel company to make calls.

# Empathy Map

![](RackMultipart20200602-4-5k8xe7_html_fc84cccd94bcbeda.png)

![](RackMultipart20200602-4-5k8xe7_html_facb2fb487ff05a8.png)

# Reflection

Relationship managers promote holiday packages to customers through calls. During outbound calls when relationship managers call potential customers to promote deals, customers tend to have a lack of motivation to purchase it because of irrelevant deals. In addition, some customers are concerned that the outbound calls may be scams or they do not trust the relationship manager with their information which causes them to hang up on relationship managers. This could cause relationship managers and customers to waste time when unable to make a purchase. Furthermore, an issue that might arise is that without sufficient information about the customers, the relationship manager and the customer may not speak the same language. From these assumptions, the relationship managers will require a tool or system to help identify what the customer wants such as a profiler tool where relationship managers will be able to input customer data to match it with the most suitable holiday deals. When inbound calls happen, customers are concerned when they do not know their score because it will determine the time for when they will be served by the relationship managers which leads to customers to hang up when it takes too long to be served.

| POV | HMW |
| --- | --- |
| Customers who are from different backgrounds would purchase holiday packages from the travel company to have a trip that is organized and planned. However, some of the holiday packages might not attract them | How might we offer the right travel package to the customer?HMW know what customers like?HMW makes the customer feel satisfied with the travel packages? |
| Customers who want to purchase the holiday package introduced will call the RM to receive additional information and details about the packages. However, a long wait time to approach a RM causes the customer to hang up the call. | HMW reduces the wait time of the customer?HMW make the customer not hang up the call? |
| Customers who want to know more about the holiday packages by calling the RM to receive more information about the holiday packages. Unfortunately, the RM did not have sufficient knowledge which makes the customer turned down the call | HMW ensures that the RMs are knowledgeable and proficient in their work?HMW train the RMs?HMW guarantees that the customer understands the holiday packages? |
| RM of the travel company will call potential customers to sell their holiday packages, but most of the calls are rejected. | HMW reduces the number of rejected calls made by RMs?HMW makes the RMs successfully promote a plan to a customer through calls? |
| RM of the travel company will call potential customers to sell their holiday packages, but the customer might not speak the same languages. | HMW eliminate the problem of language barriers?HMW prevent the RMs misunderstanding with the customer? |
| RM need to make sales to make profits, but he met the wrong customer | HMW match the right customer to the right RM? |
| Customers who want to buy holiday packages need to call the RM. However, due to the feeling of less satisfaction, the customer did not purchase any deals. | HMW make the customer feel satisfied? |

# User stories

1. As a relationship manager, I want more information about the customer so that I can give the right advice and promote the right deal to them.

2. As a customer, I want my call to be answered as soon as possible so that I will not hang up the call.

3. As a customer, I want a knowledgeable relationship manager to answer my call so that I can get a right and value deals.

4. As a customer, I want to book a call so that I will not waste my time waiting for the relationship manager to be available.

5. As a RM, I want to promote the best travel package to my customer so that I can make a sale.

6. As a customer, I want a higher customer score so that I can get service faster.

7. As a RM, I want to answer the calls from customers as soon as possible so that I will not lose any potential customers.

8. As a RM, I want my customer to respect me so that I can serve them better

9. As a customer, I want RM, who contacted me to have the same background as me so that misunderstanding can be avoided.

10. As a RM, I want to have more colleagues so that all calls from customers will be answered.

11. As a RM, I want to learn more about other cultures so that I could understand customers with different backgrounds.

12. As a RM, I want to make sure that I will only give accurate and real information to customers so that they will not receive false information.

13. As a Rm, I want to make sure that the customer understands what the travel package contains so that they will not complain afterward.

# Use Case Diagrams

![](RackMultipart20200602-4-5k8xe7_html_1a572abc2e60db77.png)

![](RackMultipart20200602-4-5k8xe7_html_5d8db2c53c5816a5.png)

# Activity Diagram

![](RackMultipart20200602-4-5k8xe7_html_60fe061e7267923b.png)

# Class Diagram

![](RackMultipart20200602-4-5k8xe7_html_cf69794ecc1a164c.png)

# Collaborative diagram

![](RackMultipart20200602-4-5k8xe7_html_55e268daa7f9d389.png)

#


# Advantages

The new system will improve the in-house call operation so that inbound and outbound calls are processed effectively and efficiently.

By implementing the new system, it would allow the travel company to gain competitive advantage by:

- Automated system of matching customers to a relationship manager with better skill matcher using Profiler Tool.
- Help customers to manage their time better to prevent wasting time by allowing them to book a call with a relationship manager.
- Save costs by making effective outbound calls using a target list generated from the system where guides are shown to the relationship manager of which holiday packages suit the customer well.
- Allowing better management and job quality by analysing the call log.
- During the call, RM can recommend the package according to the destination and time that the customer has filled in in advance, instead of communicating about the repeated information.
- More personalized service will increase the chance of customers to purchase again, besides, will get a good reputation and therefore attract new customers.
- During the busy time, the customer can be led to an Interactive Voice Response unit prompting them for options, and can be asked about call reason then redirect to an router. This can effectively reduce congestion during peak hours.

Additionally, the new system would help the company to serve more customers since the call operations are improved and efficient.

# Possible Risks

- If the profiler tool went down, the whole call operations will not run due to being unable to match a customer to a relationship manager.
- Customer and relationship manager profiles might be stolen or leaked to unauthorized people.
- If the system does not update the customer information in time, it may cause an inappropriate match.
- Customers are too lazy to create their profile.
- Relationship manager may create a false profile to gain more customers.

# Scrum

Scrum is an agile methodology that we used to carry out the project. Firstly, we define the purpose and objectives of the project so that we are clear of what we should achieve in the project. Then, building product backlog by writing user stories. Prioritise the user stories according to their importance. Then, create a sprint backlog during the sprint planning meeting. Each sprint lasts for a week and the whole project is set to be completed within 4 weeks. During the progress, we use issues in GitHub to raise questions and requests for help by opening an issue and closing the issue after being solved.Use a commitment timeline to view members commitment and lastly use the project to track what work has been completed, who did what and what work remains.

A sprint review meeting is conducted every friday to show what we have done and further discussion of the project.

Presentation

[https://www.youtube.com/watch?v=0BJ4NsFxwH0&amp;feature=emb\_title](https://www.youtube.com/watch?v=0BJ4NsFxwH0&amp;feature=emb_title)
