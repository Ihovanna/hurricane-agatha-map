# Hurricane Agatha Damage Assessment Map
Ada Developers Academy C18 Capstone Project by Ihovanna Huezo.

This web app utilizes Google's Cloud Platform Services to feature a map crafted 
through Google Maps API.

This map reflects data gathered after Hurricane Agatha hit the southern coast of
Oaxaca, Mexico in May 30th, 2022. [Hridaya Yoga's Community Development Department] 
(https://hridaya-yoga.com/community-development/) organized
a party to visit affected remote communities and perform appropriate damage assessments.
In the process, the department partnered up with the community of Agua Dulce to, 
instead of providing temporary monetary relief, utilize the funds gathered through
the [United for Oaxaca Campaign] (https://hridaya-yoga.com/hurricane-agatha/)
for a long-term community development project instead.

The data contained in the map reflects demographic data about each husehold in the
community of Agua Dulce and the conditions each family was living in during the weeks
following the hurricane. 

This web app aims to be a tool that the Hridaya Yoga's Community Development Department
can use to more easily reference their initial data as the project progresses. 


## Technologies
- **Front-end:** React.js  
- **Back-end:** Google Firebase (Back-End as a Service)  
- **Database:** Google Firestore  
- **Deployment:** Heroku  

## Dependencies
`firestore` & `firestore-tools`
`@react-google-maps/api`
`react-collapsible`
`react-player`

## Upcoming Features
- **User login**  
    This app in intended to be used by a specific sub-set of people. The data contained in
    the map is not intended for public use. Users will not have permmission to update any
    data or post any new households onto the map.

- **Report an issue form**  
    Users will be allowed to request a change in the data or report any mistakes they see
    reflected in the app via a form. 

- **User picture upload**  
    Logged in users will be allowed to upload images corresponding to each mapped household.
    Google Firebase Storage will be utilized to support this feature.

- **Picture gallery**  
    A gallery section will be added to the section right below the map to allow users to 
    see any pictures associaated to the household they click in the map.

- **Statistical analysis graphs**  
    A collapsible section will contain statistics summarizing the demographic data reflected
    in the map.
