# YaDig: Review and Share your favourite Albums

## YaDig is a social application that allows users to connect through music taste

<img width="1903" height="1037" alt="Screenshot From 2026-01-17 21-39-09" src="https://github.com/user-attachments/assets/a9efd7ab-b606-4bd1-bd65-3ffbaa8aa73d" />
<img width="1903" height="1037" alt="Screenshot From 2026-01-17 21-39-02" src="https://github.com/user-attachments/assets/f7c44eb7-c882-4d12-9625-ad96c68de7f6" />
<img width="1903" height="1037" alt="image" src="https://github.com/user-attachments/assets/09222581-5e0d-488f-b892-24e5a3aba7f6" />

### run demo: 
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
NEXT_PUBLIC_LASTFM_API_KEY={key}
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
