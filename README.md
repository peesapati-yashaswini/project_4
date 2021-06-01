# project_4
This is a project about an  e-seva portal which helps us give conformation about ticket status for travel pass during Covid-19 times.
As we all have seen, we will need a travel pass to go around from one state to another.
This project sends you the conformation through whatsapp.
For sending conformation through Whatsapp , twilio was used , It has a individual sid and token 
The message to which it should come is also given in the code
The data was retrived from realtime data "https://api.covid19india.org/v4/data.json"
This project was done using Pycharm, installed flask 
Inside the templates folder we have the html files
one for entering the date, the other for displaying.
as soon as u enter ur details the screen shows u the status and u get a message in Whatsapp
for the first time twilio users, They need to send the code to the twilio contact
finally, this gives the conformation status
