# steeleye_shrhs
#for steeleye interview

1. Run the cloudformation template "vpc.json" to create the vpc with public and private subnets.
2. while creating the EC2 (web) on public subnet add web.txt contents in the user data section this installs nginx.
3. while creating the other 2 Ec2 (app) on privae subnet add app.txt contents in the user data section this install the application. 
4. save the contents of the nginx file in /etc/nginx/sites-available/default and restart nginx service. (nginx by default uses round robin lb)
