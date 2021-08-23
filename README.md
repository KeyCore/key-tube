# Key Tube
Key Tube is an attempt at implementing a YouTube-like system using AWS technology.

This is not a customer case. It is a learning case. Thus, this system is not complete,
and probably never will be. The purpose is to learn how to use various AWS technologies
together. While a "fully functional / complete" system would be nice to have, it is
not by itself the main goal. The goal is learning. Of course, the more of the system
that is working, the more has confirmed to have been learned. 

The decision to create a YouTube-like system is to have a clear guide to pull me 
(or other learners) through an easy-to-understand use case + requirement set, 
which span a good portion of central and peripheric AWS services.


The Key Tube system could consist of:

 - A static website
 - User accounts (in DynamoDB - or Cognito?)
 - User information (media files uploaded + metadata etc.)
 - User preferences (based on watched / liked / disliked videos or explicit feedback)
 - Media file processing
   - Conversion to standard format (?)
   - Different resolution versions of the file (?)
   - Checking for copyright violations (video / audio)
   - Extracting transcripts from the media file (for subtitles, reading, and searchability)
   - etc.
 - Media file search function


The system uses the following AWS services:

 - S3
   - Storage of static website (HTML, images, scripts etc.)
   - Storage of media files (Video etc.)
 - Lambda
 - API Gateway
 - CloudFront
 - Route 53 (?) 
 - DynamoDB
   - Storage of user account information, such as media files uploaded etc.
 - Cognito (??) - for user authentication (??)
 - AWS Media services (??)
 - CloudFormattion or Cloud SDK

 - Other AWS services - depending on how far this project gets.




     
