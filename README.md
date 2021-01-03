# Tourism AI
The tourism AI project with both backend and frontend projects.

Tourism AI is a case-based reasoning Artificial Intelligence to recommend places to visit based on Season, cost disponibilitty,how many people are in the group and wich type of place you wanna visit. (The actual project contains recommendations just for Brazil - SC).

## Getting Started

This project is the union of other two projects:
* The AI backend available [here](https://github.com/Hilson-Alex/tourism_api).
* The frontend project available [here](https://github.com/Hilson-Alex/tourism-app).

If You wanth to see the project working, visit [our deploy in heroku](https://tourism-reco-app.herokuapp.com). Here you can see the project fully working.

### Prerequisites

If you want to run this project fully locally see the README.md from [tourism_api](https://github.com/Hilson-Alex/tourism_api/blob/main/README.md) and from [tourism-app](https://github.com/Hilson-Alex/tourism-app/blob/main/README.md). There are important instructions of how to made them work locally, like the need of a MONGO_URL on the api .env.

### Installing

To install and run this project, run the follow comands to clone and install the dependecies for every submodule:
```bash
git clone https://github.com/Hilson-Alex/tourism-ai.git
cd ./tourism-ai
git submodule update --init --recursive --remote
git submodule foreach git pull origin main
npm install
```
### Scripts

there are three scripts to run the project.
- ```npm run start``` run both backend and frontend;
- ```npm run start:api``` run the backend alone;
- ```npm run start:app``` run the frontend alone;

## Authors
This code was implemented by:
* [@Hilson-Alex](https://github.com/Hilson-Alex)
* [@rick32132](https://github.com/rick32132)
* [@TheMarhsall007](https://github.com/TheMarhsall007)
* And Bruna Rebello, who doesn't have an account at the moment this was posted

## License
This project is under the MIT License, that you can see in [LICENSE](/LICENSE) file
