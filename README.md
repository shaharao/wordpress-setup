# wordpress-setup
Shell Script to setup WordPress and LEMP stack on Ubuntu 

<h2>How To Use</h2>
<ol>
	<li>Clone or Download the project from https://github.com/shaharao/wordpress-setup.git</li>
	<li>Navigate to the project directory.</li>
	<li>Enter the required nginx configuration for the site in the <code>nginx.conf</code> file.
	<li>Execute the script using the command <code>./wpsetup.sh</code>.</li>
	<li>If no error occurs, your site can be accessed in the browser by entering your domain name.</li>
</ol>
<blockquote>Note: The script is by default executable. If problem occurs while executing the script, make the file <code>wpsetup.sh</code> executable by using the command <code>chmod +x wpsetup.sh</code>.</blockquote>

Tested on a Ubuntu 17.04 VM and AWS EC2 instance, works fine. But a lot of enhancement are to be done.
