![jetNEXUS Logo](/jetnexus.jpg)

## These Rules

These rules are mostly focussed on providing security features for either client browsers or web servers - directly or indirectly.

### Installation

Clone this repository, then, in the jetNEXUS GUI, browse to `Advanced > Configuration > Browse`, select the folder you cloned to and the rule you want and click on **Upload Config or jetPACK**. 

If you'd rather not use Git then click on the rule you want to install (above), then click **Raw** and then **Save [Page] As...** and download the text file to a suitable location. 

Then, in the jetNEXUS GUI, browse to `Advanced > Configuration > Browse`, choose the rule you downloaded and click on **Upload Config or jetPACK**.

Rules can be modified to suit your needs under: `Library > flightPATH`.

To assign rules to Virtual Services go to: `Services > IP Services > Virtual Services > flightPATH`.

### Caution

Most of these rules can be applied with little, if any, risk but in all cases you are advised to test thoroughly before deploying on any live site or service.

You are strongly advised to do suitable research and customise the following according to the content of and assets served through any public website:

- Any Content-Security-Policy HTTP Header Insertion rule

### User Guide

You can find the full flightPATH user guide [here](http://www.jetnexus.com/usercentral/4-1-4/flightpath.html).

### Tutorials

There are a number of useful tutorials available [here](http://www.jetnexus.com/load-balancer/resources/flightpath-tutorials/).

### Related Blogs

We've blogged in detail about many of these rules [here](http://blog.jetnexus.com/), in particular;

- [Simplifying Security HTTP Headers with jetNEXUS Traffic Management: X-Content-Type-Options](http://blog.jetnexus.com/post/102d9q0/simplifying-security-http-headers-with-jetnexus-traffic-management-x-content-ty)
- [A HTTP Security Header to Combat 'Clickjacking' – How to Improve your Site's Security with the X-Frame Options Header](http://blog.jetnexus.com/post/102davm/a-http-security-header-to-combat-clickjacking-how-to-improve-your-sites-sec)
- [How to Secure HTTP Traffic and Protect Users with the HTTP Strict Transport Security Header](http://blog.jetnexus.com/post/102dceg/how-to-secure-http-traffic-and-protect-users-with-the-http-strict-transport-secu)
- [Simple Content Security Policies to Defend Against XSS Attacks](http://blog.jetnexus.com/post/102dika/simple-content-security-policies-to-defend-against-xss-attacks)

### Contributing

We're always happy to receive contributions and pull requests.

### License

These rules are offered license and copyright free.
