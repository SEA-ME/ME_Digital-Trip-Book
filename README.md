# ME Project - Digital Trip Book  
</br>

- [ME Project - Digital Trip Book](#me-project---digital-trip-book)
  - [Introduction](#introduction)
  - [Project Goals \& Objectives](#project-goals--objectives)
  - [Project Timeline](#project-timeline)
  - [Submission](#submission)
  - [References](#references)


## Introduction

V2X Data Capture and Replay for Comprehensive Vehicle Trip Analysis. This project is a research project based on V2X (Vehicle-to-Everything) technology where you want to record digital signals within a vehicle during a fixed trip. It is a fascinating and ambitious project that involves aspects of data acquisition, signal processing, communication protocols, and possibly machine learning for replay. 

</br>


## Project Goals & Objectives

Here's a structured approach to guide you through the process:

1. Real-time Data Capture:
   - Develop a system to capture digital signals produced/transmitted across the V2X network within a vehicle. 
   - Is logging a good idea? Explore the correct methodology. 
   - What data should be considered for recording? sensor readings, communication messages, control signals ?
   - How should these data be recorded? Recording every single bit is going to cost you a universe, may be Claude Shannon can help you?
   - Define the parameters of a fixed trip, including route, duration, and specific scenarios (e.g., intersections, highway driving). Implement a mechanism to record data only during the fixed trip to avoid unnecessary data storage.
   - Design a structured database or file format to store the captured data efficiently. Consider compression techniques to minimize storage requirements.
   - And security? Implement encryption and authentication protocols to protect sensitive information.

2. Replay System:
    - Develop a replay system capable of reconstructing the vehicle's behavior based on the recorded data. Ensure synchronization of various signals for an accurate and realistic playback.
    - Create a user interface for visualizing the recorded data, allowing users to analyze the vehicle's behavior during the trip.
    - Implement tools for extracting insights, identifying patterns, and troubleshooting issues.
 
</br>


## Project Timeline

A tentative project timeline for the Digital Trip Book project would include the following phases:

1. Planning and Preparation (2-3 weeks)
2. System Architecture and Design (2-3 weeks)
3. Development and Integration (4-6 weeks)
4. Testing and Debugging (2-3 weeks)
5. Pilot / Proof of Concept Deployment (2-3 weeks)

Note that the timeline may vary depending on the complexity of the project, the availability of resources, and the expertise of the development team. However, the timeline provides a general idea of the phases and timeline involved in implementing a Digital Trip Book project.  
</br>

## Submission

Submit the following artifacts to GitHub:

1. Documentations:
   - A nice proposal of V2X communication standards. Would be in the form of thesis / research paper.
   - Entire system architecture, data structures, and algorithms used.
   - A comprehensive report detailing the methodology, challenges faced, and solutions implemented.
2. Proof of Concept: 
   - The source code.
   - Test Cases demonstrating the reliability and accuracy of the system.
3. Presentation: 
   - A presentation summarizing the project, including an overview of the system architecture, technical specifications, user interface, and test results.

</br>


## References

Here are some open source references that could be useful in developing a DriveScore TripBook project:

1. CAN Bus: The CAN Bus is a common automotive communication protocol used to exchange data between control units within a vehicle. A popular open source implementation of the CAN Bus is the SocketCAN project, which provides a set of Linux kernel drivers and user-space libraries for accessing CAN devices. (https://github.com/linux-can/can-utils)
2. Machine Learning Algorithms: Machine learning algorithms can be used to analyze and interpret driver behavior data, in order to calculate a driving score. The scikit-learn library is a widely used open source machine learning library in Python, providing a number of algorithms and tools for data analysis and modeling. (https://github.com/scikit-learn/scikit-learn)
3. User Interface Design: A user-friendly and visually appealing user interface is critical for the success of the DriveScore TripBook project. Bootstrap is a popular open source front-end framework for building responsive and mobile-first websites and applications. (https://github.com/twbs/bootstrap)
4. Digital Trip Book: The digital trip book system can be developed using a variety of open source technologies, including web frameworks like Ruby on Rails or Django, and database systems like MySQL or PostgreSQL. A popular open source digital trip book implementation is the OpenTripPlanner project, which provides a comprehensive platform for trip planning and itinerary management. (https://github.com/opentripplanner/OpenTripPlanner)

These open source references can serve as starting points for developing a DriveScore TripBook project, and can be combined and customized as needed to meet the specific requirements of the project.
