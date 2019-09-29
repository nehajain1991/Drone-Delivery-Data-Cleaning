# Drone-Delivery-Data-Cleaning
A Python code to analyze the Drone delivery dataset, find and fix the problems in the data using machine learning techniques 

Exploring and understanding the data is one of the most important parts in the data wrangling process. In this task both graphical and non-graphical EDA methods are utilised to understand the data first and then find the data problems.

As a starting point, information about the dataset in hand: The dataset is about delivering packages using drones in Victoria, Australia. The description of each data column is shown below:

    Drone type: A categorical attribute for the type of the drone. WKT each type of drone has three phases of flight ( namely takeOff , onRoute , and Landing ). The drone may have different speeds at different phases. takeOff and Landing phases only take five minutes.
    Post type : A categorical attribute for the type of delivery (0:normal, 1:express)
    Package weight : The weight of the package
    Origin region : A categorical attribute representing the region for the origin of the delivery
    Destination region : A categorical attribute representing the region for the destination of the delivery
    Origin latitude : Latitude of the origin
    Origin longitude : Longitude of the origin
    Destination latitude : Latitude of the destination
    Destination longitude : Longitude of the destination
    Distance : Distance of the journey
    Departure date: Date of the departure
    Departure time : Time of the departure. WKT the delivery company has a specific rule to define morning (6:00:00 - 11:59:59), afternoon (12:00:00 - 20:59:59), and night (21:00 - 5:59:59)
    Travel time: Travel time (i.e., duration) of the journey
    Delivery time: The time of the delivery
    Delivery price: Delivery fare. We know that the fare has a linear relation with some of the attributes of the dataset.

