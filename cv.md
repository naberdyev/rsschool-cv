# Nikita Berdyev

## Contacts

- **Location:** Samara, Russia
- **Phone:** +7 987 942-84-82
- **Email:** naberdyev@gmail.com
- **GitHub:** [naberdyev](https://github.com/naberdyev)
- **Telegram::** [naberdyev](https://t.me/naberdyev)
- **Discod:** naberdyev#0479

## About Me

Having started my career as an employee in local printing office I gained experience in designing lots of printing content. In a free time I was learning basics of HTML, CSS and JS. Main reason I was interested in web development is instantly seeing results of your work just like in designing process. While studing JS I realised that I very much enjoy the succsess of compliting the tasks. The more complex the task was the more saticfied I felt. I have decided I should study web develompent (specificly front-end) in a more systematic and deep way. That's why I signed up for a RSS JS course.

In my previous job I have developed good communication skills. It was easy for me to work in a team and my boss considered me as an reliable worker. I belive that skills I got working there would help me to start a new career as Front-End developer. I'm very excited for the cource and can't wail to learn and develop new skills.

## Skills and Proficiency

- HTML5/ basics of PUG
- BEM
- CSS/ basics of SASS
- JavaScript (Basics)
- Git, GitHub (Basics)

## Code Example

DropCaps means that the first letter of the starting word of the paragraph should be in caps and the remaining lowercase, just like you see in the newspaper.

But for a change, let"s do that for each and every word of the given String. Your task is to capitalize every word that has length greater than 2, leaving smaller words as they are.

_\*should work also on Leading and Trailing Spaces and caps._

```
"apple" => "Apple"
"apple of banana" => "Apple of Banana"
"one space" => "One Space
" space WALK " => " Space Walk "
```

**Note:** you will be provided atleast one word and should take string as input and return string as output.

**My solution:**

```
function dropCap(n) {
return n.replace(/\b\w{3,}\b/g, (match) => match.charAt(0).toUpperCase() + match.slice(1).toLowerCase())
}
```

## Pet Projects

1. ### [Covid Statistics Telegram bot](https://github.com/naberdyev/covid19stats_bot)
   Small telegram bot whitch shows you current statistics on the spread of COVID-19 by country. \
   **Used skills:**
   - JS
   - Node JS
   - Telegram API
2. ### [Portfolio Site](https://github.com/naberdyev/portfolio-site)
   Simple portfolio site. \
    **Used skills:**
   - HTML
   - BEM
   - CSS
   - SCSS
   - JS
   - JQuery

Check it out: [click](https://denisnovikov.netlify.app)
