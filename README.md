# The-Investgation-of-Gabo-Kitty-Cat-Kidnapping

<h1> This is an exercise provided by the TryHackMe DFIR course </h1>

 
 #### All images and copyrights are protected for TryHackMe

<h2>Description</h2>
Project: A cat kidnapping investgation case
Objective: Analyze the provided documents to find Gado. See the cat photo:




<h2> Scenario </h2>
 Gado, the cat pictrued below, has been kidnapped. The kidnapper has sent us a document with their requests in MS Word Document format. We have converted the document to PDF format and extracted the image from the MS Word file for your convenience.
 
 ![Gado](https://github.com/TheRashaSharif/The-Investgation-of-Gabo-Kitty-Cat-Kidnapping/assets/98124961/50d2d756-36f2-4ca9-9f62-1fbc4f43a93d)
 
<h2>Tools/ Utilities Used</h2>

- <b> Linux Virtual /attack machine</b> 
- <b> Command line </b>

Tasks:
-Explore the folder the kidnapper provided.
- Using pdfinfo, find out the author of the attached PDF file to find the metadata.
- Using exiftool or any similar tool, try to find where the kidnappers took the image they attached to their document. What is the name of the street?
- What is the model name of the camera used to take this photo?

Investgation:

In the command line we type the folder and use  ls to list the files in it:

![Gado rooms](https://github.com/TheRashaSharif/The-Investgation-of-Gabo-Kitty-Cat-Kidnapping/assets/98124961/e29edccc-4c0c-4d05-a397-b7f098a3fe8d)

To answer task 1 , we have to use the command pdfinfo and find the pdf metadata.  The provided pdf was created by Ann Gree Shepherd as the results:

![Cado pdf](https://github.com/TheRashaSharif/The-Investgation-of-Gabo-Kitty-Cat-Kidnapping/assets/98124961/2a6f1108-65bf-4858-b55c-23771158c219)


Analyzing the photo sent can help locate Gado and find information of the camera used to take the photo. In order to track it and find the kidnappers:
FOr this we will use the command tool: exiftool letter-image.jpg

![Gado camera canon](https://github.com/TheRashaSharif/The-Investgation-of-Gabo-Kitty-Cat-Kidnapping/assets/98124961/3e235c31-9b48-4111-938d-57c41e34ee31)

The camera that was used is a canon and the location it was taking is in the metadata and can be located by searchign it in Bing:
51.517776, -0.09675

Conclustion:
By finding the name, the location and tracking the camerz Gado was located and saved by the digital forensics. Shs is back and warm with her family.

