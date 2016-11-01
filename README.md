# OOAD-WEEK08

## Use Case Diagram (ภาษาไทย)

การบ้านเรื่อง use case diagram 
 ภาพที่1 Costomer side
 code
 
 ```
@startuml
Costomer--(View Product)
Costomer--(Add Product To Cart)
Costomer--(Remove Product\nFrom Cart)
Costomer--(Fill customer detail)
Costomer--(Confirm Order)
@enduml
..........................
```
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuNBEBox9pqqjqjNL2CjCBLS8ACfFAKqkqKIMS4n9WOahXEGhE0EreiW7fURcbwN2bCJakHNbvsAgSilCoL58BeNm5L9IIn8pSr0KEEVdfMKMvIhu5wMa5cboSJcavgM0d0W0)



ภาพที่ 2 ATM system
code
```
..................................
@startuml
Operator -- (system\nstartup)
Operator--(System\nShutdown)
Customer -- (Session)
(Session).>(Transaction):include
Transaction<.(Invalid\nPin):extend
bank--(Transaction)
Transaction<|--(withdrawal)
Transaction<|--(Deposit)
Transaction<|--(Transfer)
Transaction<|--(Inquiry)
@enduml
................................
```
![](http://www.plantuml.com/plantuml/img/PP313e8m44Jl_GgESAWVO8mXqGidJV38fT8rD9OjThSYYHzl4KCmt7RcxMGdcnChpw6rujI1L-ny8cMIqa0CROKJxRAPIfcMFrOsWRNhCHE7GEnQcA8b41aNtNdQxDEBLqYgvb5k3TOsQ10BSxT92tmgQtI5PnDtuCM0MbmLtkF9PVmlzewmDznehtfbr-m8dIF3Q_3LD_1hKk0Z63zaGkInmVYP3m00)


ภาพที่ 3 messaging user
code
```
......................
@startuml
MessagingUser -- (Interacively dialog)
(Interacively dialog)..>(indentify oneself):Include
(Interacively dialog)<..(Show a schema):Extend
Moderator--(Bar a group)
(Bar a group)<--(Bar a user)
(Bar a group)..>(indentify oneself):Include
@enduml
...................................
```
![](http://www.plantuml.com/plantuml/img/XKzB2i8m5Dpd55acY-G0fKWHN7JHbVG0Z-Gr3QGlae_Qsnit8b9mEJzcPiW5KgbRO1Fc3CwJcpCchXGN8nLCOFmTmywjXn2TP8UirYVXoI8Ll-my4cOCY-n6Cg5QFCxqMelh6XySU3OhRY2xoxCWMJP5szmb9gN46L8pk1JhhNL_e_wZrZRuH_mpQ6Wrxyyl)

ภาพที่ 4 admin website
code
..............
```
@startuml
WebsiteAdministrator--(Manage\nUser Groups)
WebsiteAdministrator--(Manage Users)
HelpDesk--(Manage Users)
WebsiteAdministrator--(Manage\nUser Sessions)
WebsiteAdministrator--(Manage Logs)

@enduml

...............................
```
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuGfFJIhEB4brJCdDpCiiBYbABCalqjNLy4tCIqnFZSaBBKujKd0loYyjADR4hrO1f1Ieo2Crfy0bjJWRGu8Ocu9JYuipy_C8skMJdmvKm-MGcfS2yWG0)

ภาพที่ 5 library information system
code
```
..................
@startuml
Member--(User login)
(User login)<..(Answer security\nquestion):extend
@enduml
........................
```
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuV9DpKrABTBLrGWjJYrIoCbFpypJv4BcsEZfQJZc5PS31OfJaqkBCaigO_8AIrEBIpBpypIjKYjAKlDIkBWSW2J8F000)


* บรรยายเรื่อง UML โดย อ.ปานใจ  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/0eq2FGEQul8/0.jpg)](http://www.youtube.com/watch?v=0eq2FGEQul8 "บรรยายเรื่อง UML โดย อ.ปานใจ  " target="_blank") 

* เรียนการออกแบบโปรแกรมด้วย UML กับโปรเอิ๊ก ตอนที่ 1 การเขียน Requirement Card และ Use case   

[![IMAGE ALT TEXT](http://img.youtube.com/vi/u9sNT6x0Mlo/0.jpg)](http://www.youtube.com/watch?v=u9sNT6x0Mlo "เรียนการออกแบบโปรแกรมด้วย UML กับโปรเอิ๊ก ตอนที่ 1 การเขียน Requirement Card และ Use case " target="_blank") 

* How to draw a UML Use Case Diagram

[![IMAGE ALT TEXT](http://img.youtube.com/vi/UzprPX82Nac/0.jpg)](http://www.youtube.com/watch?v=UzprPX82Nac "How to draw a UML Use Case Diagram" target="_blank") 

## Use Case Diagram Tutorial (VTC)

* 3.01_Use Case Basics  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/tLJXJLfLCCM/0.jpg)](http://www.youtube.com/watch?v=tLJXJLfLCCM " 3.01_Use Case Basics " target="_blank") 

* 3.02_Modeling Use Case Elements  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/_JCsqdNf8bA/0.jpg)](http://www.youtube.com/watch?v=_JCsqdNf8bA " 3.02_Modeling Use Case Elements " target="_blank") 
 
* 3.03_A Use Case Diagram for an ATM  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/SmcBTsPsbIY/0.jpg)](http://www.youtube.com/watch?v=SmcBTsPsbIY " 3.03_A Use Case Diagram for an ATM" target="_blank") 

 

* 3.04_The ''include'' Dependency  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/q7O2EAZ_s7M/0.jpg)](http://www.youtube.com/watch?v=q7O2EAZ_s7M " 3.04_The ''include'' Dependency " target="_blank") 

 

* 3.05_The ''extend'' Dependency  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/bL_Bl_Xl7wQ/0.jpg)](http://www.youtube.com/watch?v=bL_Bl_Xl7wQ " 3.05_The ''extend'' Dependency" target="_blank") 

 
* 3.06_Generalization  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/x5LkaZlLT28/0.jpg)](http://www.youtube.com/watch?v=x5LkaZlLT28 " 3.06_Generalization" target="_blank") 

 
* 3.07_Putting It All Together  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/gYmOzpU7DDI/0.jpg)](http://www.youtube.com/watch?v=gYmOzpU7DDI " 3.07_Putting It All Together" target="_blank") 
 
