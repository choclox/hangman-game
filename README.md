# About

Basic hangman game, just gess a letter to complete the word in the less posibles attemps.

# Steps to install

- Clone the repository 
- Build docker file
```sh
docker-compose build
docker-compose up -d
docker-compose exec app bash
cd app
python hangman-game.py
```

