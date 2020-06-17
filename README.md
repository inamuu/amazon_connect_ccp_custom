amazon connect ccp custom
===

# Introductions

Amazon Connect provides a Library to customize your contact control panel.  
For example, If you use amazon connect stream api you can insert ccp into your web site.  

https://github.com/amazon-connect/amazon-connect-streams 

This example which is implemented to our website when I wanted to display contact attributes of Amazon Connect.

# contact.getStatus().type

Title | Value
:-- | :--
Calling | connecting
While talking | connected
End calling | ended

Link
https://dev.classmethod.jp/articles/how-to-display-the-value-set-on-contact-flow-on-amazon-connect-on-the-screen/

# How to use

First, You needs to prepare a web server to upload this sources.  
You may use a static web hosting services like Amazon S3.  
When you use S3 web hosting functions, But S3 provides a link which customer can access url but you can access the link trough only http.  
If you wants to as https site, You needs to setup CloudFront and ACM, or S3 URL.  
When you don't needs to original domain, You may use S3 URL which start with https://s3-XXXX.amazonaws.com/YOURBUCKETNAME/.    

