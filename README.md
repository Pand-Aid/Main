# Pand-Aid

## Purpose

### Basic MVP functionality
Pand-Aid is a simple tool that does the following:

1. It aggregates data on the supply needs of immunocompromised and elderly individuals and places them in a secure central database. In the future this may include the needs of people who are currently or potentially ill with Covid-19 along with data on the symptoms they are presenting with.

2. It allows for NPOs, medical facilities, and government bodies to filter and "checkout" groups of individuals based on things like need-type and location. 

3. Once any indivudual or group of needs are met, it is checked off, a confirmation email sent to the at-risk individual (just in case they were mistakenly removed) and that particular need or set of needs is removed from any and all instances in the database. 

### Health education and volunteer health safety training steps
In addition to the above, the web-app will provide guidelines supported by our best professionals on how to train volunteers in pick up and delivery of items in order to reduce risk of accidental exposure as much as possible. 

## User types 

### NPOs
Non-profit organizations will be given access to health training content aimed at pick-up, delivery, and interaction with vulnerable populations updated as needed by our local health authorities. They will also have the ability to check out groups of individuals based on needs such as household products (including food) and services (eg: counceling or care), and location (eg: zip code, county, city, etc.).  

### Medical Facilities 
Confirmed medical facilities may check out individuals based on medical needs and location. For example medical supply needs (eg: medicine, equipment, masks), medical services (eg: in-home or video checkup), and illness/symptom tracking. Details are still being worked out on how medical facilities may use the app.

We are aiming to provide Up-to-date health training content for health care practitioners on interaction with patients in their home or when providing outreach health services. 

### Government programs 
Confirmed government entities may checkout groups based on needs such as food, services, or illness and symptom tracking. Most likely use would either be distrobution of supplies or sending pertinent items to individuals in the mail. However exact use of app for government purposes is still being discussed. 

Government agencies will be given access to health training content aimed at pick-up and delivery of goods as well as interacting with individuals in their home or in the office. 

### Individuals in need 
Individuals will be given a unique ID and asked to provide a verified non-google phone number in order to make an account. Other information will be prompted for (email, address, if they are ill, symptoms, etc.), but will not be required. 

The MVP will not have health information prompted for in order to get the app out sooner. However future versions will ask the user if they are ill. If they answer yes, they will be prompted on whether they have any of a list of symptoms associated with Covid-19. They can check off the symptoms, and enter in their temprature. This information will be updated in the database and the changes tracked. The user will also be prompted on whether they would like this information tied to their name, or to be anonymous. If it is anonymous then their general geo-location will be recorded (zip-code), and they will have an ID assigned like other users for updates on their health, but their name and other identifying information will not be recorded together with their self recorded health data. 

### Anonymous health tracking individuals - After MVP

After the MVP we will also add in the ability for those not at high risk to create a "health tracking" account where they may enter in their own data on whether they feel sick, what symptoms they have, and their primary geo-location. Users will be prompted for a verified non-google phone number to help avoid duplicate accounts. 

## Public pages

### Basic health and safety information - in MVP
On the client side there will be information on steps individuals can take to maintain their own safety as well as emergency phone numbers and other pertinent information. This information will be made editable by only those with special admin rights given to government and health center Covid-19 health response teams or those in close contact with them.  

### Maps and stats - After MVP
After the MVP has been rolled out we may work on a map visualizing self reported illness. It is possible this map and information may only be made available to medical and government facilities. 

We will also concentrate on aggregating data from both Oregon and the other states and displaying a rough estimate of total diagnosed cases, recovered, and deaths based on that information since the CDC is no longer providing this information.  

## Summary
This tool is meant to allow multiple organizations to spread the workload of responding to our vulnerable populations in an organized fashion and avoid duplication of work. In addition it aims to maintain health and safety standards that may otherwise be difficult to train for. For example there are google docs "sign-up" sheets going around for individuals to help other individuals. However there is no health safety training, or precautions in place for the general safety of those either delivering or receiving help. 

## Stack 
Pand-Aid will be using a Python-Django-JavaScript stack. 

### Current details of stack. Once we move out of the design phase accurate version numbers will be listed. 
- AWS 
- Amazon ECS (tentative)
- Python 3.6 
- PostgresSQL
- Docker CE 
- Django 3.0
- Vue or React for pages that need close to real-time updates. We have not decided which yet.
- Vanilla JS for pages that do not require real-time updates
- O-Auth
- HTML5/CSS 

# MVP
The MVP will allow any organization granted access via an admin to checkout individuals/groups who have registered with needs of some kind. They will be able to filter the need types, contact the individual, and check them off of the list when a need has been fulfilled.  An email will be sent to the individual to confirm, and all instances of that particular need for that particular individual will be removed from the active database groups are being pulled from. 

The MVP will also allow individuals to sign up with name, phone number, and email (optional?) and select from a list the needs they have, or to enter in a need in a written field. They will be prompted for their zip code and city/state. 

The MVP will include health safety information on the public frontend for individuals as well as emergency numbers. 

The MVP will include basic health and safety training documentation on the organization end for pick-up and delivery of items to vulnerable individuals. 





