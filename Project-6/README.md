# Implementing Loadbalancers with Nginx

## Introduction to Load Balancing and Nginx

![alt text](<Images/Screenshot 2024-06-17 103647.png>)

Load balancing is like having a team of helpers working together to make sure a big job gets done smoothly and efficiently. Imagine you have a lot of heavy boxes to carry, but you cannot carry them all by yourself because they are too heavy. Load balancing is when you  call your friends to help you carry the boxes. Each friend takes some of thr boxes and carries them to the right place. This way, the work gets done much faster because everyone is working together.

In computer terms, load balancing means distributing the work or task among several computers or servers so that no one computer gets overloaded with too much work. This helps to keep everything running smoothly and ensure that that websites and apps work quickly and don't get slow. It's like teamwork for computers!

Let's say you have a set of webservers serving your website, in order to distribute the traffic evenly between the webservers, a load balancer is deployed. The load balancer stands in front of the webservers, all the traffic gets to it first, it then distributes the traffic across to the set of webservers. This is to ensure that no one webserver gets over worked, consequently improving system performance.

Nginx is a versatile software, it can act like a webserver, reverse proxy, and a load balancer etc. All that is needed is to configure it properly to serve your use case.

In this project, Nginx is and configured as a load balancer.

## Setting up a Basic Load Balancer

Use two EC2 instances running on ubuntu 22.4 and install apache webserver in them. Open port 8000 to allow traffic from anywhere, and finally update the default page of the webserver to display their IP address.

Next, provision another EC2 instance running on 22.04, this time install Nginx and configure it to act as a load balancer distributing traffic across the webservers.