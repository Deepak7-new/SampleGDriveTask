# SampleGDriveTask

<h3>Steps to run file</h3>

1. Get API KEY and WEB CLIENT ID by registering in google developers console and creating a project and enabling google drive api.
2. Go to Credentials then OAuth 2.0 Client IDs and select name of your OAuth and then under Authorized JavaScript origins add ``` http://localhost:8000 ```. To allow request from the port other than 80.
3. Update API KEY AND CLIENT ID in the code.
4. Run ``` python -m http.server 8000 ``` for python 3.x or ``` python -m SimpleHTTPServer 8000 ``` for python 2.x (As we are making a post request from different origin).
5. Go to your browser's address bar and type http://localhost:8000 and then select the folder where this html file is present.
6. Click on html file. And Authorize with the same mail id which you have used in google developers console.
7. Upload files from local computer and they will get uploaded in the Google Drive.
