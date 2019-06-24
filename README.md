# AWS-SNS-SMS with NodeJS
A quick example of sending an SMS with AWS SNS and NodeJS

Download this repository

`git clone https://github.com/Sean-Bradley/AWS-SNS-SMS-with-NodeJS.git`

`$ cd AWS-SNS-SMS-with-NodeJS`

`$ npm install`

`$ npm start`

Open browser and visit something like,

http://localhost:3000/?message=**_Your Message_**&number=**_Your Number_**&subject=**_Your Subject_**

The mobile number should be E.164 format but without the + character.
eg, 
You want to send a message to a number,
The country code is 44
The mobile number is (0)7700 900123
The E.164 format would be +447700900123
Remove the + character
Then Visit 
`http://localhost:3000/?message=my message&number=447700900123&subject=My Subject`

