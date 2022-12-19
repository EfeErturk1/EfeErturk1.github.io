# Efe Erturk 21902620
### Travela
### Project ID: T2307
### Supervisor: Cevdet Aykanat

## CS491 LogBook
Logs after 24.10.2022
### 29.10.2022:
We got together and did the work allocation. I took responsibility of writing     
1	Introduction     
2	Current System   
3	Proposed System    
  3.1	Overview        
  3.5.4	Dynamic Models, Sequence and Activity Models    
  4.2	Risks and Alternatives
  4.3	Project Plan	   
  4.4	Ensuring Proper Teamwork   
  4.6	Planning for New Knowledge and Learning Strategies
  
I will be doing The part 3.5.4 with Efe Şaman and Çağla Ataoğlu

### 22.11.2022:
As the backend team with Efe and Çağla, we got together and did work allocation. I will be doing the travel side entity, repository, service and controls

### 26.11.2022:
I started the initial skeleton code of the backend artifact.

### 28.11.2022:
I completed the setup of the project, and added some spring security features. I connected the backend to a local database.

### 29.11.2022:
We did a meeting with our instructors Erhan and Tağmaç hoca, learned their expectations from us in the demo and in the project going forwards.

### 1.12.2022
I started the Accomodation service for the backend artifact, and finished it, pushed it to the master.

### 10.12.2022
I started to work on the recommendation system with Machine Learning. Finding data for a travel recommendation system is not easy, because of the KVKK and GDPR regulations. Instead of training our own model, I decided to use an external API of Amedeus's that does the job essentially. The API call is as follows

https://test.api.amadeus.com/v1/reference-data/recommended-locations?cityCodes=ROM&travelerCountryCode=US 

here, ROM is the city code, and US is the country code of the user. All the cities are available in the API, but only 9 nationalities are available that gives specialized recommendation to that nations culture. We decided to use the geographically closest country to the nations that the API does not have direct integration for.

"The current version of the API provides recommendations for travelers based in nine markets: France, United Kingdom, Germany, Italy, Spain, Netherlands, USA, Argentina and Mexico. 

However, the input city and outputs are global and not restricted to these markets. "

Usefull Links for the Amedeus External API integration:

https://developers.amadeus.com/blog/travel-recommendation-system-similar-destinations

https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262

https://developers.amadeus.com/get-started/get-started-with-self-service-apis-335

### 14.12.2022
I started the Event service for the backend artifact, and finished it, pushed it to the master.

### 18.12.2022
I started the Location service for the backend artifact, and finished it, pushed it to the master.

### 19.12.2022
I started the Trip service for the backend artifact, and finished it, pushed it to the master. Fixed some bugs related with city, country, transportation and location.
