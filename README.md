<p align="center">
  <img src="TelepassDigital.png" alt="TelepassDigitalLogo" width="350">
</p>

# Gotta insure 'em all
Develop a REST service that allows a trainer to insure **only** their fire, water, and grass-type Pokémon.

To use the service, the trainer must enter their name, surname, and trainer code, a unique and secret code issued by the Pokémon League. This API will return a random and unique MT code to be used to authorize all subsequent API calls.

To get a quote, the trainer will have to enter the name of the Pokémon to be insured, one at a time. The trainer will have to pay for each Pokémon insured an amount equal to € 9.50, plus € 0.50 if the Pokémon should also be of the flying type. A quote will therefore be identified by the price for each insured Pokémon. If the Pokémon isn't insurable due to its type, return a specific error.

Finally, the web service must allow the trainer to purchase the quote and record the effective transaction date. Integration with any payment system is not required for this test.

## Getting started
- Put your project on a public repository on GitHub

## Guidelines
- Use https://pokeapi.co/ as a RESTful Pokémon API
- Use a programming language and a framework of your choice
- Model the service database as per specifications (no specific DBMS is required)
- Write an exhaustive README.md justifying the choices made
- Write automated tests for your code

## Bonus
- Produce the Swagger to document your APIs
- Write a Dockerfile
