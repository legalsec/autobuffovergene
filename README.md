A simple programme, written in c++ to guide a user through a step by step process in creating a buffer overflow exploit for a given application.

To begin with (in no particular order):

1. Consider questions which would need to be asked
2. Identify dependencies (such as msfvenom)
3. Consider limitations
4. Create an application which works well on a particular vulnerable programme (I am aware that the OSCP contains an example based on syncbreeze 10.0.28 - perhaps this would be an appropriate place to start).
5. Test and expand the application to work on other programmes
6. Identify areas of future expansion - fuzzing script generator? All-in-one shell generator?

I am surprised that I am unable to find anything like this programme out in the wild. It may be that there is simply no need for it, given that if you're capable of identifying the information which this script will be asking, you'll probably just throw a script together yourself just as quickly (not to mention your fuzzer will contain a lot of the coding already, and could just be adapted into a final exploit). It could also be that what I am attempting to do is completely unreasonable and overly difficult to implement in any meaningful way - I refuse to believe this (and so will proceed ahead, until I prove myself wrong).

