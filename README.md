# My Pet Planner

# Description:

Pet log will be a full crud application where you can log and track the growth of your pet. As someone who has a 6 month old puppy, I would like to be able to have something where I can see how he has grown in size, weight, eating schedules, vet visits, grooming appointments, or whatever else you would like to log.

# Technologies To Be Used

-JavaScript 
-React
-CSS


# Component Architecture 

![image](https://user-images.githubusercontent.com/116233849/220708665-55ba3019-0412-4aed-904b-c7ddd53eba1c.png)

## The Route Table

| Route | Element | Loader | Action | Summary |
|-------|---------|--------|--------|---------|
| / | Home | indexLoader | | Home page |
| /logs | index | indexLoader |  | returns all logs|
| /logs/:id | show | logShowLoader |  | returns single log|
| /logs/create |  | | logCreateAction | creates log |
| /logs/update |  | | logUpdateAction | update log |
| /logs/delete |  | | logDeleteAction | deletes log |

# Trello Board

https://trello.com/invite/b/z1Aelja2/ATTI25a93af6fe70eb313dd8c5cf63c290e36CD2C1CD/pet-log

# Wire Frames
![image](https://user-images.githubusercontent.com/116233849/220703812-133ab782-3e6d-4eb1-bded-6f9d3bac6141.png) 

![image](https://user-images.githubusercontent.com/116233849/220703939-b251491f-2e15-449c-8a4b-5288cd1cb7e6.png)


# Link to Project
[Render Deploy](https://pet-planner-backend.onrender.com)




