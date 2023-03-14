# emplyeePlatform

To run the platform go to steps:
1- git clone  https://github.com/enghesham/Employees-Management.git
2- composer update
3- copy .env.example and paste it in the file root and rename it .env
4- php artisan key:generate
5- php artisan migrate
6- npm install
7- npm run dev
8- php artisan serve

To make test email varification go to the link and follow the steps to make test 
Credentials : 
https://help.mailtrap.io/article/12-getting-started-guide?_ga=2.218323422.617175638.1678746750-64790640.1678746750
 
and copy Credentials in the .env like :
MAIL_MAILER=smtp
MAIL_HOST=sandbox.smtp.mailtrap.io
MAIL_PORT=2525
MAIL_USERNAME=*********
MAIL_PASSWORD==*********
MAIL_ENCRYPTION=tls

 user when register it must go to test mailtrap email to verfy email
 registerd user must inter code that send in his email  when he login (2fa) 
 
 
 video link :
 https://files.fm/u/sd2q4em86
 
