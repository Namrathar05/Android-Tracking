# Android-Tracking                                                                                        Date:15/02/2019
                                                                                                           week 1-day 2
Introduction

The use of mobile devices has become part of our daily routine. Recently, mobile devices like mobile phones or portable digital displays (PDAs) are equipped with global positioning system (GPS) receptors that allow us to get the device geographic position in real time. This paper describes a tracking application tool, called mobile tracker, which uses location-based services (LBs) like GPS or global system for mobile (GSM) network to track a mobile device. Through the known geographic position, this application enables the user to track a mobile device and send alerts if it is out of the radius around an interest point, previously defined by the application administrator.

Gps/Gsm Tracker is a mobile application. The main aim of this Android project is to assist users in finding their relevant location according to their source and destination. By using this application, User can find out the location of the person. Moreover, users can also get to track another user.  
This project is about the design and implementation of device tracking system using (GPS, GSM). It comprises of integration between Gps technology and a Gsm module.  This combination of technology will produce a tracking system.  
This project can be divided into two main parts software and hardware development. GSM module is used for tracking and GPS is used for navigation.

OBJECTIVE:
The scope of this project includes the security of the architecture as well as the accuracy of tracking unit.  

BASE PAPER REFERENCE:
Journal Name: International Journal of Engineering Research & Technology (IJRET) Feb 2017
Title: Mobile Tracking System Using Web Application and Android Apps

Literature Survey:
Referred base papers for tracking mobiles in case of theft, tracking pilgrims, women and children.

                                                                                                            week 2 day 2
Algorithm used for tracking: improved tracking using a simple motion model

  Is the target stationary  ?
        fixed <-false
while target is moving do
the location and DTW of the target will be estimated
the difference between positions of the target will be calculated as distance
if target is stationary and distance >  max range then,
the last postion  within the range is taken as the final position of the target
end if
if DTW > threshold value (pre-defined)
target fixed (stationary)
end if
end while



