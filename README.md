# YaDig: Review and Share your favourite Albums

YaDig is a social media application that allows users to connect through music taste

### How to run: 
#### in the back-end directory:
1. create a .env file:
```
APP_PORT=3030
DATABASE_URL={YOUR_POStGRES_URL}
JWT_EXPIRES_HOURS=6
JWT_SECRET={Free LastFM API Key}
```
2. run 
```
$ npm i
$ npx prisma generate
$ npx ts-node ./utils/seed.ts
$ npm start
```
#### in the front-end directory:
1. create a .env file:
```
NEXT_PUBLIC_API_URL=http://localhost:3030
NEXT_PUBLIC_LASTFM_API_KEY=78f1f6e5eaaf7d27216635ecedaaadc6
```
2. run 
```
$ npm i
$ npm start
```
#### Testing (backend and frontend):
```
$npm test
```
