# digital-card-app
Gone are the days of carrying around stacks of paper cards or relying on outdated designs. With Digital Business Card, you can easily create and share your digital cards with just a few taps on your phone or tablet.

- Poduction deploy avaliable on AWS: http://100.26.109.233/

### Nice design
![image](https://user-images.githubusercontent.com/98609823/228962312-95e4da8c-7fad-4d82-a40d-fcc13b6b9c7a.png)


### Simple to use
![ezgif com-video-to-gif](https://user-images.githubusercontent.com/98609823/228964982-2f3f5893-bec0-40df-b16e-4b941c398f89.gif)

## Technologies
The following tools and frameworks were used in the construction of this application:

### * Front-End

  ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
  ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
  ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
  ![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white)
  ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
  ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
### * Back-end
  
  ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
  ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
  ![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
  ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
  ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
  ![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white)
  ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
  ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)


## How to run

1. Clone this repository

```
git clone https://github.com/Tavares-ltc/digital-card-app.git --recurse-submodules
```

2. Create .env like the .env.example file (make sure to do that on back-end and on the front-end)

 - On back end .env i didn't create a mongodb service in docker compose, I chose to make a database using Altas. I recommend you do the same.
 - Atlas: https://www.mongodb.com/atlas/database
    
3. With docker run (Don't want to start both aplication with docker compose? No problem, check the repositories individually and follow the documentation.)

```bash
docker-compose up --build
```
4. Thats it, just navigate to http://localhost:3000
