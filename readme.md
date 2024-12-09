# **Welcome to my collection of Docker-Compose files.**

I use these for my home docker servers for doign random and weird things!

## **Contents:**

### **Dashy**
https://dashy.to/

A cool web-dashboard for pulling all of your favourite links together.
You could use bookmarks, but why when this is cooler!

### **HomePostgresDB
**
This is a Postgresql database that I am experimenting with and feeding data back to.
I use some of my home sensors to send MQTT data via NodeRed and Mosquitto then push it into tables in the
database.
Warning - I have tried setting up replication but not sure if I got it working properly yet!

### **NginxProxyManagerWithDB**

A NPM (Nginx Proxy Manager) with a Maria database.
I use this to self host my own website, this way I can proxy the traffic and use SSL.

### **NginxWebsiteHost**

As it says on the can... A website hosting docker.
I use this with access to a folder on my Pi making it easier to update the HTML directly on the Pi without
messing round in Docker.
(Used behind NPM)

### **NodeRed**

Who doesnt love a bit of IFTTT!
A wonderful automation and amazing interface.
I use it primarily for catching MQTT messages and posting them straight to my database.

### **TechnitiumDNS**

I was tired of Pihole not offering some of the more advanced DNS features.
This server allows me to control my internal DNS and also allows blocklists - just like PiHole but better.
