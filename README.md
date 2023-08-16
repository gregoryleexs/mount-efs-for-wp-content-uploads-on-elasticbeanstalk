# mount-efs-for-wp-content-uploads-on-elasticbeanstalk
.ebextensions file to mount Amazon Elastic File System for wp-content/uploads on Elastic Beanstalk

# PROCEDURE
Set up an Elastic Beanstalk web server environment, an RDS database, and an EFS filesystem with mountpoints (remember to configure and use the appropriate security groups for EB to gain access to RDS and EFS
Download Wordpress zip from wordpress.org
Add .ebextensions folder, add the .gitignore file and the .platform folder
IMPORTANT: under wp-content, add a folder called 'uploads'
Then zip the wordpress folder and deploy to EB.

# CREDITS
Credits to Somnath Pawar (blog post: https://somnathpawar.wordpress.com/2021/09/24/how-to-mount-existing-wordpress-uploads-directory-to-efs-through-elastic-beanstalk/)
Got the .ebextensions script from the website but made small modifications to it
