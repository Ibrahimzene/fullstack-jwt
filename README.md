# et730-session-cookie-fullstack

- this is a full-stack MERN site that demonstrates the user of session/cookies for authorization

![grafik](https://github.com/edwardtanguay/830-mongo-book-app/assets/446574/93410dff-a5f0-4814-8b07-704616902efb)

![grafik](https://github.com/edwardtanguay/830-mongo-book-app/assets/446574/774fc786-e601-4b18-b331-5188f0e8d9d3)

![grafik](https://github.com/edwardtanguay/et730-session-cookie-fullstack/assets/446574/c638e8fe-6ca0-4bc7-a700-c4ca72e458b9)

## setup
 
create `.env` file with the following entries:
- connection string with name of the MongoDB database you want to use
- random session secret for session cookies
 
```
DB_URL = mongodb://localhost:27017/et431-jwt-fullstack
SESSION_SECRET = 123456789abcd
```	

## start

- `npm i`
- `npm run dev`
