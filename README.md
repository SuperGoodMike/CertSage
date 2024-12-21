# CertSage 

**Credit goes to Griffin Software**

**Features**

*Easy webpage interface

*Optimized for cPanel install

*No commands to type, root not required

*Added Support for Subject Alternative Names (SANs)



**Introduction:**

Certsage is awesome but it allways had issues with Subject Alternative Names (SANs). I have added this feature, enjoy.

CertSage was designed for people of all ages and experience levels who want an incredibly quick and easy way to acquire Let's Encrypt TLS/SSL certificates. CertSage is especially helpful if you are using a shared hosting plan that does not allow root access, such as GoDaddy or tsoHost shared hosting. It's free, of course!

**Requirements**

PHP 7.0+

**Installation**

Assuming that your domain name is example.com...

*Download certsage.php.

*Upload certsage.php into the webroot directory of your website (often something like public_html) that contains the content that you access when you visit http://example.com.

**Usage**

Assuming that your domain name is example.com...

Visit http://example.com/certsage.php.

Your password can be found in the password.txt file in your CertSage directory, which by default is located in the parent directory of the directory where you installed CertSage. 
The CertSage directory and password.txt are created automatically by CertSage when you visit the CertSage page in your browser. Should you wish to change your password, simply replace the contents of password.txt with whatever password you wish to use.

Most people will want to enter example.com as their main domain and www.example.com as their Subject Alternative Names (SANs) when acquiring a certificate.

To ensure that your CertSage installation is working, you can acquire a staging (fake) certificate.

Once you are confident that your CertSage installation is working, you can acquire a production (real) certificate.

Once you have successfully acquired a production certificate, you can have CertSage install it into cPanel by pushing a single button.

To renew your certificate, simply revisit http://example.com/certsage.php every 60 days to acquire and install a new production certificate.

You can subscribe to receive certificate expiration notifications from Let's Encrypt to serve as backup reminders to renew your certificate. 

Once you have subscribed, you will continue to receive certificate expiration notifications for all future certificates you acquire with CertSage. 

Should you wish to use different email address(es) after subscribing, simply enter all the email addresses you wish to use in the email address box then click Update Contact Information. 

Should you wish to stop receiving certificate expiration notifications, simply leave the email address box blank then click Update Contact Information.

