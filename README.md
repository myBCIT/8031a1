# 8031a1
android tcp connection; upload and download images to/from a web server w/ multicast

Given below is your Assignment I for the course.  As you can see that I have removed the experimentation part for now and shifted the focus to the network API and its usage in the Android app.  We will do the experimentation later on.  The amount of code needed is not much.  There may be some issues dealing with images and interacting with a web server.  You can avoid images and interaction with web server by dealing with only plain text and any TCP server (just like the knock knock server) for partial marks.  

Assignment I

(a)    Create a simple Android app that downloads an image from a remote web server using TCP socket and displays the image in an Image View.  [2 marks; Due Before End of Class Jan 17th]

(b)   Create a simple Android app that uses TCP socket to upload an image to a web server. [2 marks; Due before End of Class Jan 17th]

(c)    Create a simple Android app that distributes the image to multiple recipients using multicast socket.  The recipients (i.e. multicast receivers) could be other Android apps or desktop apps.  The desktop recipients can collect the received multicast packets and save the reconstructed image on the file system (just like a web server) whereas the Android recipients can display the received image on an image view.  The sender and the receivers are connected over WiFi WLAN.  [2 marks; Due by Jan 24th]

After the demos in the class, please submit into D2L as follows:

Copy the Manifest file, any Layout file(s) and the Java code into a word document and submit.  Capture the packet trace using wireshark covering the TCP connection setup and teardown phases of parts (a) and (b), and a wireshark capture showing IGMP packets being transmitted during execution of part(c).  Submit the screen shots of the captured trace in the word document as well.   
