**Hosting a website with AWS S3 service**

Open the AWS management console and then search for S3 service.

create an S3 bucket. (I named it marvel-103 in N. Virginia region).

![](./media/image1.png)

Open the public access settings for this bucket.

Uncheck the setting to block all the public access to the website, and
also enable the checkbox for the acknowledgement to turn of this block
setting.

![](./media/image2.png)

Click on create bucket.

![](./media/image3.png)

Now drag and drop the files from your local machine to the S3 bucket and
press the upload button.

![](./media/image4.png)

Now open the object ownership and enable the ACL's and save the changes.

![](./media/image5.png)

![](./media/image6.png)

![](./media/image7.png)

Open the uploads and select all the objects. Click on actions button and
select Make public using ACL's. click "Make Public" and save this.

![](./media/image8.png)

Open the edit static website hosting, and enable it. Fill the name of
index document of the project. then save it.

![](./media/image9.png)

Copy the object URL and paste it in a tab of the browser.

![](./media/image10.png)

The result is the website.

![](./media/image11.png){width="5.385416666666667in"
height="2.4895833333333335in"}

Reference: The website used was downloaded from the link

<https://www.tooplate.com/view/2115-marvel>
