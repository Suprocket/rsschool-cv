# Maxim Samokhvalov

## Junior frontend developer

### Contact information

Phone: +79911083606  
Telegram: [sa_max_valoff](https://t.me/sa_max_valoff)  
github: [suprocket](https://github.com/Suprocket)

### Briefly About Myself:

Hi! I'm passionate about creating cool, interactive websites that drive business success.
I love learning new things from the IT world and applying them immediately.
I believe that front-end development will help me achieve my goals in the IT industry.

### Skills and Proficiency:

1. HTML (Emmet)
2. SASS (Tailwind, Bootstrap)
3. JS (React)
4. Git
5. Figma & Photoshop
6. VS Code

### Work projects

- [Create SPA for stmwater.ru](https://stmwater24.ru/)
- [Pet-projects in my github](https://github.com/Suprocket)

### Code example:

My example of creating an aggregation with a reduce method:

```
import readlineSync from 'readline-sync';

const completeRounds = 3;

const engine = (gameInfo, gameData) => {
  console.log('Welcome to the Brain Games!');

  const name = readlineSync.question('May I have your name?: ');
  console.log(`Hello, ${name}`);

  console.log(gameInfo);

  for (let correctAnswers = 0; correctAnswers < completeRounds; correctAnswers += 1) {
    const [gameQuestion, compAnswer] = gameData();
    console.log(`Question: ${gameQuestion}`);
    const userAnswer = (readlineSync.question('Your answer: '));
    if (userAnswer !== compAnswer) {
      console.log(`'${userAnswer}' is wrong answer. Correct answer was '${compAnswer}'`);
      console.log(`Let's try again, ${name}!`);
      return;
    }
    console.log('Correct!');
  }
  console.log(`Congratulations, ${name}!`);
};

export default engine;
```

### Courses:

Result school (junior frontend dev, february 2022)  
Hexlet (junior frontend dev, october 2022)

### Languages:

English B1,  
French A2.
