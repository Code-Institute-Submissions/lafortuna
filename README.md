# La Fortuna Restaurant

This is the website for La Fortuna Restaurant, Food Truck and Catering service provider located in Edinburgh. It is intended to showcase all the services of the business and its different areas. In order to achieve this, each part of the business (restaurant, food truck and catering services) have its own page on the website.

## UX

This website is made for customers to be able to find all the information they may need on a simple, quick and intuitive way, without many clicks or very long scrolling.

All pages follow the same structure, facilitating the navigation through all the pages and helping the user to fastly familiarise with how the website works, only changing the main content of each page to reflect the information related to that particular page. 
All of them share the following:
- A header, which includes the logo, the brand name, a line listing the different areas of the business and a button to change the language of the site to either English or Spanish.
- A central section consisting of two parts. A sidepanel on the left hand side with a navigation menu, a button to make reservations and some additional info. The other part of this section contains the main content of each page. This last part is what is different on each page.
- A footer including contact details (email and phone number) and links to social media sites.

Regardless of where on the website the user is, they can access any of the other pages or content in only one click on tablet, laptop and computer versions; and in a maximum of two clicks on mobile version, as the navigation menu it's only accessible via the navbar at the top of the page, navbar which is always visible even when scrolling all the way down to the bottom of the screen.

All links to external sites (email and social media) and files (restaurant menus in pdf) open in a new tab, allowing the user to keep the site also open with no need to use back or forward buttons on device/browser to navigate from one to the other.

All external links are configurated on the same way, they will change font-colour when user hovers over them (tablet and computer) or taps on them (handheld devices).

For internal links or navigation within the site, it's the background colour what changes to a slightly darker shade when the user hovers over them. 

In the case of all buttons, the whole colour combination changes when hovering on a laptop or computer and when tapped on touchscreen devices.

The design is fully responsive to screen sizes and type of device, with all content being the same on all of them with only some layout changes to better adapt to the screen size.

## Technologies used

1. HTML
2. CSS
3. Bootstrap CDN (4.3.1)

## Features

This project uses Bootstrap grid system for design responsiveness.

For mobile devices, in order to reduce the real state of the different contents, the navigaion menu is accesible by a toggler on the navbar located at the top of the screen. This navbar will not be visilbe on larger devices and its contents are showing on the sidepanel on the left hand side instead.

On the "Location/Donde estamos" page, there is a Google map showing the location of the restaurant, map which is fully functional with all the utilities that Google Maps offers.

### Featues left to implement

The project will include a customer reviews feed for all the different services taken form one of the most popular review websites/apps such as Tripadvisor or Google Reviews.

Also, the addition of some media such as photos and videos showcasing the services and products in offer will help to promote the business.

## Testing

The project has been tested on laptop computers (Windows 10 and Chromebook), mobile devices (Huawei 20 Lite, Huawei 10, Samsung Galaxy 7 and Sony Xperia Z), and also using different web browsers (Internet Explorer and Google Chrome). 

On the index, restaurant and food truck pages, the user can read a bit of the history of the business and what products could have by accesing the menus via the links on the restaurant page. 

On the Catering page, as the nature of this service in more "tailor-made", it depends on the type of service required, the user can find a form to fill in in order to request more info or make an enquiry. This form has some required fields and some with validation that require the correct data type (email address, phone number, etc.) to be input in them in order for the form to be send. If there is invalid data or empry required fields on the form, this will not send and will show a message on the fields that need to be checked by the user. Once all required are filled in and all data is valid, by clicking on the "submit/enviar" button, the form will send and the page will reload.

## Deployment

This project is hosted using a GitHub repository that can be run locally using https://github.com/JK27/lafortuna

## Credits

All written content on all the different pages of this project, in both languages (English and Spanish), were composed by myself.

All icons on this site used in navigation menus (navbar and sidepanel) and social media links located on footer, were downloaded from fontawesome.com

The Spanish and British flags used for the "translation" buttons were accquired from the repository titled "flag-icon-css" hosted on GitHub by the username "lipis" (https://github.com/lipis/flag-icon-css/tree/master/flags)

The brand logo is inspired on the drawing titled "Don Quijote" by Pablo Picasso with the addition of the brand name "La Fortuna" by myself.







