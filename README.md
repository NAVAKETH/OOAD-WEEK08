# OOAD-WEEK08
##ส่งการบ้าน USE CASE นวเขตต์ พลอยโพธิ์ 57030182
###USE CASE 1.
   Code
   ```
   @startuml
title CURE
:ME: -- (appointments)
(appointments) -- Manager
:ME: -- (Cancel)
(Cancel) -- Manager
:ME: -- (Cure)
(Cure) -- Doctor
:ME: -- (Pay)
(Pay) -- Cashier
@enduml

   ```
Diagram

<img src="http://www.plantuml.com/plantuml/img/SoWkIImgAStDuIh9BCb9LN0E3NBbil9rjLBGrLNGI2meoC_CAybDpIifrkH2vO8K-2Rc9QQd5Y4qE2Vc9QVc09L26TWLbHQbWfI0A920ItvoIJwIV41Y9L0QH8Auped56Pb0xGwfUIaWTm80">

###USE CASE 2.
Code

```
@startuml
title OPEN FAN 
:ME: --> (Check  Plugs)
:ME: --> (Select Speed)
(Select Speed) --> (FAN)
@enduml
```

Diagram
<img src="http://www.plantuml.com/plantuml/img/SoWkIImgAStDuIh9BCb9LV0FSFLJS7FqK-2oydMrKj3LjLFGSCv8JSvMK0Z8AKqlraGI3qxDIKqkKGWkI4rDqUH2vK9K00tIv798pKi1MW00">

###USE CASE 3.
Code

```
@startuml
title BUY Slip Mobile Online 
left to right direction
skinparam packageStyle rect
actor ME
actor Cashier
rectangle STEP {
    ME -- (Number) : Tell
   (Number) -- Cashier : Put
    ME -- (Money): Give 
   (Money) -- Cashier : receive
 
    Cashier -- (Slip) : Give
    (Slip) -- (ME) : receive

}
@enduml
```

Diagram
<img src="http://www.plantuml.com/plantuml/img/LP313e8m38RlVOeUvS0BU38QmWarGGyU9rHi71iPnSGOtzqE3C6Tjl_hrsxRz6A23Aq5OR64s_C5IyiT5lxAUZuuouuGBDq4nMFWvYvOSw1As3le7-mw4qoBdQaUfg5INgf53AOI7x38VfkTwUzC0I8phj6gyfGTyGsegyWmJN6r7zehXGJNU29h8vaZnRyEIe-3BBN2EtebQypvgNUDrfJyIpgOj036YZcFVdnn79gFEFfJClREaeKB7zYGg_N3lW00">

###USE CASE 4.
Code

```
@startuml
title class room 
left to right direction
skinparam packageStyle rect
actor STUDENT
actor Teacher
rectangle INCLASS {
    Teacher -- (subjects) : Teach
    (subjects) -- STUDENT : Learn
    (Time out) -- Teacher : Change
}
@enduml
```

Diagram
<img src="http://www.plantuml.com/plantuml/img/JSyx3i8m303GFQVm24ClqAceC21LNH8EO5BJXkPJ9Uw047Sd_I3XpVQpBLU9CVBih633ba1RJ0bY20w4fGS31uYc7nWw4qcp2LwaqVW98pgOK8_Oa-HN7btQ0ZM725BTpfTMxPaYr0D5iG3qVQRNjcvEKi9RG8wz3qK1XpJVdvcb8vHRVHL_vOpsxLaqXD5lGXb746PUnMzZ2VMGBvBuY8fybz_y0W00">

###USE CASE 5.
Code

```
@startuml
title Dorm 
left to right direction
skinparam packageStyle rect
actor Owner
actor Renter
rectangle dorm {
     Owner -- (Rental agreement) :Do 
    (Rental agreement) -- Renter :Do
    Owner -- (Money): Pay
    Renter -- (Money) : receive
    (Renter) -- (rorm) : Stay
}
@enduml
```

Diagram
<img src="http://www.plantuml.com/plantuml/img/RP1D2i9034RtSueixQ8NwAgBRaMn9mXj78VEJqcZKiIxEnaBHN1M6RxtFKBQHP3b7hmH9vwWInp0UBeAI09szYOmEgP1N8fccLoSaJ70ZCE4bdfPSqbZWuCaXjCp4c_pXQBaZwOORUP6bRyCw2iWr3KS54CFQ9aevBc2fajGg3zPRdozIfbVqp55Mgi6phYMP0Ft21hTbTo3TZrnaHuuBwT0BxdzDYt5CP_b0m00">
