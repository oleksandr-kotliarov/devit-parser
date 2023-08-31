[DEMO](https://oleksandr-kotliarov.github.io/devit-parser-client/#/)

# Tech stack

## Backend:
> Framework: Express \
> Validation: Zod \
> ORM: Mongoose \
> DB: MongoDB \
> Api Protocol: REST \
> Auth: JWT 

## Frontend:
> Framework: React + Router \
> Forms: React Hook Form \
> State: Redux TK + Redux RTK \
> UI: Material UI

# About Project

### Registration
To register as an admin you need to have an access code. After success registration code will be removed from database. Here are some valid codes to register:
> ba718fa0-eaad-42b5-b132-fb5c2a2f516e \
> c85610ae-49e1-49db-8457-f65ca234223f \
> da6606fd-212e-40fe-b6be-bebfde9e5323 \
> e438ba65-83a4-4a0c-8ca1-280035523ef7 \
> 7245eab2-c10a-4ba8-aa78-69022179b4f5

### Login
To login you just need to enter your credentials. After sign in you will get an access to admin panel

### Articles
As an unauthorized user, you can visit public route with list of articles. You can use search (by full word), pagination, sort.
>
As an admin you can create, update, delete articles. As well as create a registration codes. Furthermore you can use article parser, it handles RSS Feed link and creates articles in database.
>
Here are some RSS links to test:
> https://rss.nytimes.com/services/xml/rss/nyt/Business.xml \
> https://rss.nytimes.com/services/xml/rss/nyt/Economy.xml \
> https://rss.nytimes.com/services/xml/rss/nyt/Technology.xml 
