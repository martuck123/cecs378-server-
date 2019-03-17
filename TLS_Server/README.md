

Step I: Setup your Node, Nginx server on a Ubuntu AWS instance

For this task, follow Setting up a Node Nginx server running on Ubuntu AWS (e.g., this tutorial). You can use whatever tech you want (any OS, any cloud provider like DigitalOcean, ....). Make sure you can SSH to your server. Make sure you setup your github repo and can pull changes from your github repository onto your server.

Next, get a free domain (register with namecheap using your .edu email). In your DNS records, make sure your domain points to your aws instance. Make sure all is good and "It works".

You will demonstrate that your server is up and running and you can pull your github repo from your sever. The deadline for this step will be determined in class.

Step II: A simple HTTPS Server (separate deadline from the above step)

By now, you have a simple HTTP server that runs on either Nginx or Node.

Next, use "Let's Encrypt" to setup a free certificate (all instructions on Let's Encrypt). Test your TLS configuration with SSL Labs.  Take a look at the "SSL Config" tutorials (SSL Config for Nginx as Reverse Proxy or SSL Config for Node).

You will be graded based on your SSL Labs performance. Make sure to follow the feedback that you receive from SSL Labs and you receive an "A+" grade from their tests.

