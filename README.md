# Creating a static website in 5 minutes using S3 on AWS
### • Cloud platform: AWS • Tools used: Atom (Text editor), S3 (AWS) • Languages: Html

[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)

The following gist is part of my `AWS` Solution Architect - Associate exam preparation.<br>
It can help you as a web entrepreneur, web bloggers, to deploy a static website very quickly using AWS.
<hr>
<b>Steps</b><br>
1. Create a bucket on S3 named <b>mywebsitebucket054485</b><br>
2. Change the number since you must have a unique bucket name on S3)<br>
3. Create three files, <b>index.html</b>, <b>error.html</b>, <b>about.html</b><br>
4. Upload the files in the S3 bucket<br>

<h2>Solution architecture</h2> 
  
[![isaac-arnault-aws-solution-architect.png](https://i.postimg.cc/15KgSrtx/isaac-arnault-aws-solution-architect.png)](https://postimg.cc/Yhh2fgY8)

<h2>Bucket creation</h2>

<details>
<summary>🔵 See in AWS</summary>
<p> 

[![mywebsitebucket.png](https://i.postimg.cc/xT36hr3Q/mywebsitebucket.png)](https://postimg.cc/F71bkB6C)

</p>
</details>

<h2>Files upload on S3 bucket</h2>

<details>
<summary>🔵 See in AWS</summary>
<p> 

[![file-upload.png](https://i.postimg.cc/R0LCnZc8/file-upload.png)](https://postimg.cc/McXJCx3b)

</p>
</details>

5. Go to <b>S3 </b> > select your bucket > Edit Public Acess Settings > unselect "Block all public access" > Save > Confirm<br>

6. Click on your bucket > select your 3 files > click on Actions > Make public<br>

7. Click on Properties > Static Website Properties > select "Use this bucket to host a website" > Index document: type index.html > Error document: type error404.html

<details>
<summary>🔵 See in AWS</summary>
<p> 

[![isaac-arnault-aws-5.png](https://i.postimg.cc/k5CscqHK/isaac-arnault-aws-5.png)](https://postimg.cc/pm0KVbRL)

</p>
</details>

  > Click on Static Website Hosting to get the endpoint url.
  
There you go! Your website is online, you can visit it using the provided endpoint url.
  
[![website.png](https://i.postimg.cc/VkVtPhb5/website.png)](https://postimg.cc/21ny42Gf)

<hr>
  <a href="http://mywebsitebucket054485.s3-website-us-east-1.amazonaws.com/" tartget="_blank"> Visit my S3 static website</a>
  </div>

## Author

* **Isaac Arnault** - AWS Cloud series - Related tags: #S3 #Bucket #StaticWebsite
