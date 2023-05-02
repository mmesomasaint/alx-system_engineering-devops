# Load Balancer

### Background Context
You have been given 2 additional servers:

* `gc-[STUDENT_ID]-web-02-XXXXXXXXXX`
* `gc-[STUDENT_ID]-lb-01-XXXXXXXXXX`

Let’s improve our web stack so that there is **[redundancy](https://intranet.alxswe.com/rltoken/xnAaJdhmAxx7PoH3l6EwDg)** for our web servers. This will allow us to be able to accept more traffic by doubling the number of web servers, and to make our infrastructure more reliable. If one web server fails, we will still have a second one to handle requests.

For this project, you will need to write Bash scripts to automate your work. All scripts must be designed to configure a brand new Ubuntu server to match the task requirements.

### Resources
1. **[Introduction to load-balancing and HAproxy](https://intranet.alxswe.com/rltoken/B7f3oz8i3Xvvom_YQZzLnQ)**
2. **[HTTP header](https://intranet.alxswe.com/rltoken/sZ9v3Vq2tgLwN_PWVQketw)**
3. **[Debian/Ubuntu HAProxy packages](https://intranet.alxswe.com/rltoken/2VRAgtKKR9g6Xfb0xzGiSg)**

### Tasks
* Double the number of webservers

  configure web-02 to be identical to web-01. Fortunately, you built a Bash script during your web server project, and they’ll now come in handy to easily configure web-02. Remember, always try to automate your work!

* Install your load balancer
  
  Install and configure HAproxy on your lb-01 server.
  
* Add a custom HTTP header with Puppet
  
  Add a custom HTTP header with Puppet. 
