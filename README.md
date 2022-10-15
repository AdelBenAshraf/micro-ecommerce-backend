
# Micro-ecommerce

I made a micro ecommerce backend with a team of other interns as part of my summer internship at Dayra, using PHP, Laravel, Mysql.

<p align="left"> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://laravel.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-plain-wordmark.svg" alt="laravel" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> </p>


<h2>Things I learnt during this project</h2>

<ul>
<li>I got introduced to the concept of REST APIs and I developed the application with this in mind. </li>
<li>I learnt about cron jobs and how to make one in laravel. </li>
<li>I learnt about quality assurance and testing, we tested each others work and we reviewed and merged each others work. </li>
<li>We have learnt and worked using the gitflow work flow method where we make three branches (main, dev and qa), main is the production, dev is the branch that we develope in it as we take feature branchs from it then making a pull request then the code get reviewed and merged to the dev, the qa is the branch where we make the quality assurance.</li>
<li>We have made the ERD diagram for the project so we have learnt alot about database design. </li>
</ul>


<h2>This is the ERD diagram</h2>

![](https://github.com/AdelBenAshraf/micro-ecommerce-backend/blob/main/project_showcase/micro-ecommerce-erd-digram-v4.png)

<In this ecommerce you can be either an admin or a user as an admin you must register and login to get an authentication token, we use sanctum for authentication then after that you can add categories, brands and products.
As a user you can see the available products add them to your cart then checkout but if you didn't checkout in a certain amount of time let's say you did't checkout before 12 hours the cron job will empty your cart.>

<h2>This some samples of the REST API responses</h2>

<h3>Admin register</h3>

![](https://github.com/AdelBenAshraf/micro-ecommerce-backend/blob/main/project_showcase/admin-register.PNG)

<h3>Admin login</h3>

![](https://github.com/AdelBenAshraf/micro-ecommerce-backend/blob/main/project_showcase/admin-login.PNG)

