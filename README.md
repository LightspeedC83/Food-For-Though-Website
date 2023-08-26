# Food For Thought Website
This is a repository for the Food For Thought (FFT) website. Food For Thought is an anonymous, student led, food pantry that focuses on relieving food insecurity for students. 

The main functions of the website are:
1. Provide information about FFT
2. Have a method to anonymously order food (ie. an order form that doesn't record personal information)
3. interface with a database of the food in stock and update it according to orders that come in
4. have a login for admins for FFT so that they can update the database when they get new supplies

## Ordering food with FFT website
- When someone makes an order, they provide the number of people they need to feed and select a food type (options are presented to them based on what's availiable in the database)
- Upon Ordering, a unique word/code is assigned to the order and given to the user. This code along with the order information is stored in the database (and maybe it should send an email to the FFT admins)