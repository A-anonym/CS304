# <center>Milestone2 Team Report</center>

## <center>Junfeng Li   Haolin Huang   Peilin Wu    Weixian Zhou    Chenlang Yi</center>



## Requirements Modeling & Degin

### 1. Use Case Diagram(UCD)

Our team provides 3 use case diagrams to describe the functionalities that our community management system provide to end-users. 

The first UCD(Figure 1) is about the students' functionalities.



![Figure1: Students UCD](https://github.com/11910713/cs304/blob/main/%E5%AD%A6%E7%94%9F.jpg?raw=true)

<center><p>Figure 1: Students UCD</p></center>

The secend UCD(Figure 2) is about the association manager's functionalities.

![社团社长.jpg](https://github.com/11910713/cs304/blob/main/%E7%A4%BE%E5%9B%A2%E7%A4%BE%E9%95%BF.jpg?raw=true)

<center><p>Figure 2: Association manager UCD</p></center>

The third UCD(Figure 3) is about the school manager's functionalities.

![管理员.jpg](https://github.com/11910713/cs304/blob/main/%E7%AE%A1%E7%90%86%E5%91%98.jpg?raw=true)

<center><p>Figure 3: School manager UCD</p></center>



### 2. Swimlane Diagram(for activity application process) 

Our team designed a swimline diagram for the detailed process of activity application(Figure 4).

![SL_diagram.png](https://github.com/11910713/cs304/blob/main/SL_diagram.png?raw=true)

<center><p>Figure 4: Swimlane Diagram</p></center>

### 3. Natural Language Description(for membership application)

Our team designed a  natural language description for the detailed process of membership application following the tenplate introduced in lectures and labs.

```
Use case Name: Apply to join a club online

Participants: students, society management system, president

Objective: Students hope that they can easily and quickly complete the application process of joining the club, and at the same time get to know the club name, activity content, contact information and other information; The community management system hopes that students can see the new recruitment information of the community in time and fill in the application quickly. The application request should not be too high within the unit time, so as not to cause greater pressure on the system. The president hopes to see the application materials of students in time and make a quick and convenient decision whether to agree to join.

Prerequisites: The current user has a campus card and the campus card is available.

Trigger condition: Readers log on to the website and choose to apply for membership.

Main scenario: Students complete the application process to join the club in one go

1. Students conduct website login verification.
2. After successful login, students can view the club information.
3. The system displays community information.
4. Students click on the application, fill in the information and submit.
5. Community Management system processes online applications.
6. The system displays that the application is successful.
Other scenarios:
1. The login fails
1) Readers should verify website login.
2) The system displays a login failure.
2. Students failed to submit their application and tried again successfully
1) The system displays a message indicating that the application fails and asks you to try again.
2) Students choose to try again.
3) After the system displays the club, continue to execute according to the main scene, and finally the application is successful.
3. Readers choose to give up after students fail to apply
1) The system displays the payment failure and prompts you to try again.
2) Students choose to give up.
Exception scenario: Waiting for confirmation from the community management system times out
1) Students wait for confirmation from the club management system.
2) The system prompts students to call the club manager.
```

### 4. Diagrams for Logical view

Our team desgined one class diagram to describe the components, relations, and structure of the system, to provide a logical view of the system(Figure 5).

![class diagram.jpg](https://github.com/11910713/cs304/blob/main/class%20diagram.jpg?raw=true)

<center><p>Figure 5:Class Diagram</p></center>

### 5. Data Design
### 6. UI Design
![登录页.png](https://github.com/sustech-cs304/team-project-1146/blob/main/milestone2/6.UI%20Design/%E7%99%BB%E5%BD%95%E9%A1%B5.png)

<center><p>Figure 4: Swimlane Diagram</p></center>
## Collaborations
## Deliverables