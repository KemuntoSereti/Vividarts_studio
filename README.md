# Vividarts_studio
 Help Vividarts setup the right environment

 Below is how we achieved the final result;
 We downloaded the flask files to enable the availed app.py to run;
      'pip install flask'
Then edited the HTML file, to be able to upload photos for editing and thereafter confirm upload.

We then created an S3 bucket to host the photos during upload

Then created a lambda function that renames the photos

We then created another S3 Bucket where the edited photos will be stored

