 Static Website Hosting on AWS S3

✅ Create S3 Bucket

Created a new bucket with a unique name.

Enabled static website hosting in bucket properties.

![image_alt](https://raw.githubusercontent.com/gawali-priyanka/Brainwave-Matrix-Intern-task2/ca5e3dfea4760e00ee470a79ca462a5a594e2c35/screenshorts/Screenshot%202025-07-18%20185103.png)
✅ Upload Files

Uploaded HTML, CSS, and any other required static assets (e.g., images, JS files) to the bucket.

Configure Static Website Hosting

Enabled the "Static website hosting" option.

✅ Set:

Index document: index.html

Error document: error.html (to handle 404 errors)

✅ Make Files Public

Added a bucket policy to allow public read access.

Verified file permissions so the site can be accessed publicly.

✅ View Static Website

Accessed the website using the S3 website endpoint URL.

Confirmed that the homepage (index.html) loads correctly.

✅ Error Page Handling

Tested invalid URLs to verify that error.html is displayed as the custom error page.

