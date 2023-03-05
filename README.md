# Automated-Parking-Management-System

In many parts of the city there is a lack of designated parking spaces. This leads to chocking of traffic in roads connecting main roads.

We will be developing a web application where a driver can :
- find parking station near him
- number of empty slots along with price
- would be able to reserve the slot 

Benefits:
- Time saving
- Convenience

How it will work?

The driver will find a suitable empty slot near him and book a slot or before starting the journey. For that he will provide his name, phone number and vehicle number as required information. When a driver fills out his information, it be associated with the particular parking slot selected by the driver while booking. 
At the parking station, there will be barriers infront of every slot which will open upon verificaton. For verification the system will detect the vehicle number and match it with the vehicle number associated with that particular slot. If it matches the barrier will automatically open and the driver can park his vehicle. When the vehicle leaves the barrier will again shut down.

Technologies used
- Python
- opencv
- Flask
