**Business challenges**

Smartech QA team had a task to perform testing of Ecora web site http://www.ecora.com/ecora/ due to its moving to the new server system, and porting from Apache 1.x to 2.x, including upgrading to a newer version of Oracle database server. The updated web site had to maintain its previous functionality, have an updated view and capability of handling comfort serving up to 1000 simultaneous users. QA team successfully managed content and load testing of the web site update.

**Application description**

Ecora web site is an ASP web application that provides information about all Ecora products, hosts news and manages user accounts, allows purchasing licenses for products. The application is hosted on Apache 2.x web server on Unix operating system and uses Oracle database server to store user account information.

**Testing approaches**

What are requirements for a web site? Web site should be friendly for all users, including IT professionals and people who just started using PC. Web site should provide comfort work for the expected number of users. Navigation on a web site should be intuitively clear, and should require minimum actions to provide the expected result. Since working with client data, web site should provide robust and secure information transition. Based on these assumptions Smartech QA team used the following approaches to test Ecora web site: functional testing, UI testing, content testing, load and stress testing and security analysis.



- Functional testing included validation of all features supported by the site, such as user registration and authentication, downloading manuals and guides, downloading applications and updates, purchasing licenses, obtaining trial licenses for all products. Smart redirection (in case of link misprints) was checked as well.


- UI testing was paid extra attention during web site testing. Site navigation has been reworked, color gamma and fonts changed, other usability issues fixed.


- Content testing included verification that information provided on the site is accurate, automated spelling verification using TestComplete together with Microsoft Word spell checker (MS Word was accessed using available COM interfaces), automated validation of all links on site using Xenu’s Link Sleuth free tool.


- Load and stress testing included automated simulation of simultaneous numerous user activities targeting expected potential application bottlenecks such as user registration, user logon, etc.


- Security analysis was made to check that user sensitive data is sent via SSL connections only, site protection from unauthorized access and protection from SQL injection attacks.

**Summary**

During testing of Ecora web site Smartech QA team posted over 200 bugs and enhancements. Web site has been moved to the production server and is used till now.

**Tools used for testing**



- TrackIt and Aqdevteam bug trackers;


- TestComplete automated testing tool;


- Xenu’s Link Sleuth (http://home.snafu.de/tilman/xenulink.html).