# ICE-Connect-365
The ICE Connect 365 App is a synchronous communication listener.  Installed on client-side servers, ICE Connect 365 App listens for MS Office 365 meeting requests and generates Dynamic Conference ID’s for each meeting request identified. 
N.B. ICE Connect 365 App generates Dynamic Conference ID’s as distinct from Static Conference ID’s. (Static Conference ID’s present known security risks for clients as the access path through client firewalls or DMZ is compromised by the fact that the same Meeting ID {static}, is used for any meeting). Dynamic Conference ID’s are more secure as the conference ID changes, given a random number generation.


2.1	 Architecture and Design
The ICE Connect 365 App is written in java, this enables cross-platform architecture and design, simplistic tried and tested functionality. (The added bonus is ease of technical support as the java programming language is extremely well known in the development community)


2.2	 ICE Connect 365 App Design Interface
The model below provides an overview of how the ICE Connect 365 App is designed to interface with other business objects in order to facilitate execution. 
There are detailed descriptions of the operations provided by each business object, represented in the diagram below, as a reference.

<img src="http://assets.inhabitat.com/wp-content/blogs.dir/1/files/2016/12/ICEHOTEL6.jpg" />

Figure 1. ICE Connect 365 App design interface
