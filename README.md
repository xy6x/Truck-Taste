![image](https://github.com/xy6x/Truck-Taste/assets/121990181/9c158659-accc-4ba0-ab7b-2bfa84335744)



Introduction
we delighted to present Truck Taste, an innovative solution revolutionizing the way individuals and companies experience culinary delights at their events. Our platform is dedicated to connecting you with a curated selection of top-notch food trucks, offering a seamless and delightful experience for any occasion


Table of Contents
The Problem
The Solution
Dependencies
Tools Used
Endpoints
The Problem
Delay in finding food trucks
Lack of knowledge about the rating and quality of this food truck
Lack of knowledge about the services it provides
The Solution
Simplify the Ordering Process:

Ensure that your program's user interface is user-friendly and intuitive.
Make the ordering process seamless and quick to encourage more companies to place orders.
Enhance Customer Service:

Provide robust customer support to address any issues that may arise.
Use a ticketing system or chat service to improve communication with customers.
Improve Search and Filtering:

Make searching for trucks and food items easy and effective.
Offer filtering options to help companies quickly find suitable food trucks for their events.
Offers and Promotions:

Introduce special offers or promotions to incentivize companies to order through your program.
Utilize promotional campaigns to raise awareness about your program and attract more companies.
Technology Enhancement:

Improve your system to facilitate tracking of food trucks and real-time updates.
Embrace modern technologies such as mobile applications to make ordering and tracking more efficient.
Enhance Communication with Companies:

Provide effective communication channels for companies to inquire and meet their needs.
Consider conducting meetings or informational sessions to explain your program's services to local companies.

Dependencies
Lombok
Validation
Spring Web
Spring Security
Spring Data JPA
MySQL Driver
JUnit tests
Tools Used
Figma
Postman
XAMPP
MySQL
PowerPoint
DataGrip
Endpoints
Engineer	Endpoint	Description

Abdulaziz	/api/v1/review/getAllReviewsForEngineer	Get All Reviews For Engineer.
Abdulaziz	/api/v1/review/getAllCustomerReviews	Get All Customer Reviews.
Abdulaziz	/api/v1/review/getRatingsBetween/{rate1}/{rate2}	Get Ratings Between reate 1 and rate 2.
Abdulaziz	/api/v1/review/getRatingByContent/{content}	Get Rating By Content.
Abdulaziz	/api/v1/request/acceptRequest/{request_id}`	Accept Request.
Abdulaziz	/api/v1/request/rejectRequest/{request_id}	Reject Request.
Abdulaziz	/api/v1/request/getRequestForEngineer	Get Request For Engineer.
Abdulaziz	/api/v1/request/getRequestByStatus/{status}	Get Request By Status.
Abdulaziz	/api/v1/place/getPlaceForCustomer 	Get Place For Customer.
Abdulaziz	/api/v1/place/getPlaceById/{id} 	Get Place By Id.
Abdulaziz	/api/v1/place/getPlaceByType/{type} 	Get Place By Type.
Abdulaziz	/api/v1/message/getMessagesForCustomer	Get Messages For Customer.
Abdulaziz	/api/v1/message/getMessagesContain/{content} 	Get Messages Contain.
Abdulaziz	/api/v1/certification/getCertificationById/{id}	Get Certification By Id.
Abdulaziz	/api/v1/certification/getCertificationForEngineer	Get Certification For Engineer.
Abdulaziz	/api/v1/certification/getCertificationForCustomer	Get Certification For Customer.
Abdulaziz	/api/v1/certification/getByVisitorDate/{date} 	Get By Visitor Date.
Abdulaziz	/api/v1/certification/getByFinishDate/{date}	Find Review By Id.
Faisal	/api/v1/customer/getById/{customerId}	Endpoint to get customer by ID.
Faisal	/api/v1/customer/getByUsername/{username}	Endpoint to get customer by username.
Faisal	/api/v1/customer/count	Endpoint to get customer count.
Faisal	/api/v1/customer/updateEmail/{newEmail}	Endpoint to update customer email.
Faisal	/api/v1/customer/getByCR/{cr}	Endpoint to get customer by CR.
Faisal	/api/v1/engineer/ordered-by-experienceDESC	Ordered By Experience DESC.
Faisal	/api/v1/engineer/ordered-by-experienceASC	Ordered by experience ASC.
Faisal	/api/v1/engineer/getEngineersBetweenRate/{rate1}/{rate2}	Get Engineers Between Rate1 and reate2 .
Faisal	/api/v1/report/getReportsByCustomer	Get Reports By Customer.
Faisal	/api/faisal/getReportsByEngineer	Get Reports By Engineer.
Faisal	/api/faisal/getReportById/{id}	Get Report By Id.
Faisal	/api/v1/auth/users/role/{role}	Get users by role.
Faisal	/api/v1/auth/user/check-username/{username}	Check if username is available.
Faisal	/api/v1/auth/user/check-email/{email}	Check if email is available.
Faisal	/api/v1/auth/user/lock/{id}	Lock user account.
Faisal	/api/v1/auth/user/unlock/{id}	Unlock user account.
