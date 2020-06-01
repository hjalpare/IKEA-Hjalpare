# IKEA-Hjalpare

Design Document

Taylor O’Black
Puran Kansakar
Chris Herman

## Introduction

Are your instructions for your new IKEA desk lacking in detail? Have you failed, time and time again, to attach the legs of your chairs the right way? Are you concerned about the large excess of screws you have once completing your new bed frame? IKEA hjälpare is here to be your helper!
With IKEA hjälpare, you can:
- View your furniture item as detailed in IKEA stores
- Watch a video tutorial for added visuals 
- Participate in a discussion board with fellow builders to ask any unanswered questions


## Class Diagram
![](images/class_diagram.PNG)
### Class Diagram Description
**MainActivity:** This is the main page that the user will spend more time on. It is simple so that the user can just find what they need and get to building

**InstructionDetailsActivity:** This screen shows the video link to constructing the furniture along with its Q&A section

**RetrofitClientInstance:** Bootstrap class required for Retrofit.

**Furniture:** Noun class that represents the furniture.

**Intructions:** Noun class that represents Instructions.

**IFurnitureDAO:** Interface for Retrofit to find and parse Instructions JSON.

**IIntructionsDAO:** Interface for Room store Instructions data
