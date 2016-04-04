<img src="assets/SA-logo-web_100-black-v2.png" width="200">

# Job Ad
* What: javascript developer with 2-4 years experience
* Where: in Sydney
* When: now!

## Style Atlas
Style Atlas is the startup providing a fashion fitting solution for online shoppers. It allows shoppers to know if the clothing on their favourite fashion e-commerce sites will fit them, prior to purchase.

To achieve that mission, we are building an A-team of developers. We are building a suite of applications that works together to unlock the full capacity of the solution.

You would work closely with the tech-cofounder, and would play a key role in Style Atlas' success and growth, being one of the first developers to join our team.

## Development stack
We are on the look out for a developer fluent in Javascript with 2-4 years of professional experience. We are using ***NodeJS***, ***MeteorJS***, ***React***, etc... Yes, you guessed it, we're cool, we're rock stars. Join the band if you play any of these instruments.

No need to mention that the candidate would be confident with HTML & CSS.

We are using git as our versioning system, and are following the Github workflow to handle new features and fixes. No need for any expertise there, you can learn this on the job.

If you understand the function below and it returns `true` when applied to your experience, you may continue.

```
function validCandidate(languages) {
  let validCandidate = false
  let languageRegex  = /script$/
  if(Array.isArray(languages)) {
    validCandidate = !!languages.filter( (language)=> languageRegex.test(language) ).length
  } else if (typeof languages == 'string') {
    validCandidate = languageRegex.test(languages)
  }
  return validCandidate
}
```

Note: submit your responses in a Pull Request.

1. What does `validCandidate` expect and return?
2. Tell us the reason(s) why we've created a variable to store the regex?
3. Does it matter to use `==` or `===` when checking if `typeof languages` is equal to 'string' ?
4. Rewrite `filter` so it doesn't use `=>`. What does `=>` do? Was it necessary in this instance?
5. Update `validCandidate` to accept candidate knowing "ES2015", "ES6" or "ES7". Basically ES whatever. By the way, what does "ES" stand for?
6. Nice to have: write `validCandidate` unit tests.

## Soft skills

The ideal candidate is a talented developer, but one that has a burning desire to learn and grow their coding skills. A strong sense of initiative and desire to be part of a dynamic team is a must. An active participant in meetups or conferences, someone that codes on their own time by either contributing to open source project or their own projects, would be a good fit at Style Atlas.

This person must want to grow with the company.  A desire to progress into more senior roles as Style Atlas grows is important to us.

## Interview process
1. Send resumé and share some code (github or wherever)
2. Informal chat, either over Skype/Hangout, or at a local café
3. Pair programming session with Tech Co-Founder
4. Meet with the whole team
