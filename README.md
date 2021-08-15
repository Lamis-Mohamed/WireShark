# WireShark

PRACTICAL ACTIVITY WEEK  6-WIRESHARK 

 
explore several aspects of the HTTP protocol: the basic GET/response interaction, HTTP message formats, retrieving large HTML files, retrieving HTML files with embedded objects using Wireshark for Traffic Analysis.  

 

 

  

The activity entails exploration of HTTP by downloading a very simple HTML file - one that is very short, and contains no embedded objects. Do the following: 

**Steps**

Start up your web browser. 

Start up the Wireshark packet sniffer, Enter “http” (just the letters, not the quotation marks) in the display-filter-specification window, so that only captured HTTP messages will be displayed later in the packet-listing window. (We’re only interested in the HTTP protocol here, and don’t want to see the clutter of all captured packets).  

 Wait a bit more than one minute (we’ll see why shortly), and then begin Wireshark packet capture. 

Enter the following to your browser http://gaia.cs.umass.edu/wireshark-labs/HTTP-wireshark-file1.html Your browser should display the very simple, one-line HTML file. 

Stop Wireshark packet capture. 

**Instructions:**  

By looking at the information in the HTTP GET and response messages, answer the following questions. When answering the following questions, you should print out the GET and response messages and indicate where in the message you’ve found the information that answers the following questions. (add screenshots on this) 

 As for all questions in this course it is important that you clearly indicate what your answer is, how you obtained the answer, and (if applicable) discuss implications/insights regarding your answers. For example, in the questions below, can you elaborate on why you may have observed what you observed? 

Is your browser running HTTP version 1.0 or 1.1? What version of HTTP is the server running? 

What languages (if any) does your browser indicate that it can accept to the server? In the captured session, what other information (if any) does the browser provide the server with regarding the user/browser? 

What is the IP address of your computer? Of the gaia.cs.umass.edu server? 

What is the status code returned from the server to your browser? 

When was the HTML file that you are retrieving last modified at the server? 

How many bytes of content are being returned to your browser? 

By inspecting the raw data in the packet content pane, do you see any http headers within the data that are not displayed in the packet-listing window? If so, name one. 

  
