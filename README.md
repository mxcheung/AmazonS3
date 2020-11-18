# AmazonS3
Creating a Static Website Using Amazon S3



# Creating a Static Website Using Amazon S3
In this live AWS hands-on lab, we will create and configure a simple static website. We will go through configuring that static website with a custom error page. This will demonstrate how to create very cost-efficient website hosting for sites that consist of files like HTML, CSS, JavaScript, fonts, and images.


https://github.com/ACloudGuru-Resources/Course-Certified-Solutions-Architect-Associate/tree/master/labs/creating-a-static-website-using-amazon-s3


{
  "Version":"2012-10-17",
  "Statement":[{
     "Sid":"PublicReadGetObject",
     "Effect":"Allow",
     "Principal": "*",
     "Action":["s3:GetObject"],
     "Resource":["arn:aws:s3:::<MY_BUCKET>/*"]
  }]
}



http://scubasyndrome-835424530591.s3-website-us-east-1.amazonaws.com/

)

![alt text1](https://github.com/mxcheung/AmazonS3/blob/main/LabDiagram.jpg)

![alt text2](https://github.com/mxcheung/AmazonS3/LabDiagram.jpg)


