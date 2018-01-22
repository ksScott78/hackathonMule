# hackathonMule
working with a simple mule app to test working with flows


To use this, simply clone and import into anypoint studio.

Launch Issues :
  - Since I was running and testing this locally the app will run on port 8082. So make sure nothing else is running here. 
  Or, just edit the flow config.

Email Configuration:
  - Inspect the configuration XML of the flow
  - Raplace the content in the {} with the email address you want to send the HTTP payload to.
  - You can also add CC to the email message. See SMTP documentation for more options.
 
FIle Configuations:
  - Replace path={} with location of file to write to
  - Create the text file in this path and then replace the outPutPattern={} with your file name.
