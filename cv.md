![The photo of Anastasiia Vorobiova](./assets/av.png)

# Anastasiia Vorobiova

#### Front-End developer

## Contacts

- **Phone:** +38 067 1809644
- **E-mail:** anastasiiavorobiova2403@gmail.com
- **Telegram:** @Anastasiia_ova

## About

A motivated and results-oriented front-end developer, leveraging new technologies, enjoying growing my technical skill set to increase the real commercial value of customer's products and deliver effective solutions.
Utilized strong attention to detail for creating the visual part of the application as well as analytical skills to turn business challenges into real outcomes.
Energized by problem solving and value team interaction.

## Skills

- Javascript
- HTML
- CSS | Sass | Less
- React
- Redux
- Typescript

## Code examples

[Codewars profile](https://www.codewars.com/users/petru6e4ka)

```
function shift(n){
  const alphabets = ['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z'];
  const alphabets2 = ['A','B','C','D','E','F','G','H','I','J','K','L','M','N','O','P','Q','R','S','T','U','V','W','X','Y','Z'];
  const index = alphabets.indexOf(n);
  const index2 = alphabets2.indexOf(n);

  if(index > -1) {
    return alphabets[(index + 13) % alphabets.length];
  }

  if(index2 > -1) {
    return alphabets2[(index2 + 13) % alphabets2.length];
  }

  return n;
}


function rot13(message){
  let result = '';

  for(let i = 0; i < message.length; i++) {
    const newLetter = shift(message[i]);

    result += newLetter;
  }

  return result;
}
```

## Experience

[The test task](https://github.com/petru6e4ka/eliftech)

## Education

**Harkivs'kij Deržavnij Pedagogicnij Universitet im. G.S. Skovorodi**
Master's degree, Fine Arts and Design

## English

B2
