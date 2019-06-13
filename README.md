# vuexpress-first-page
Simple project with express server, index page and some Vue js components.

## Part One

At the beginning we take official VUE JS Introduction: https://vuejs.org/v2/guide/ .

*Into index.html file add link to all new html files, you add to project.*

### 1.

In the src/public folder create new *rendering.html* file and rewrite [Declarative Rendering](https://vuejs.org/v2/guide/#Declarative-Rendering) section samples.

### 2.

In the src/public folder create new *conloop.html* file and rewrite [Conditionals and Loops](https://vuejs.org/v2/guide/#Conditionals-and-Loops) section samples.

### 3.

In the src/public folder create new *input.html* file and rewrite [Handling User Input](https://vuejs.org/v2/guide/#Handling-User-Input) section samples.

### 4.

In the src/public folder create new *composition.html* file and rewrite [Composing with Components](https://vuejs.org/v2/guide/#Composing-with-Components) section samples.

## Part Two

Part one was about "first look" to VUE js framework. Now we will apply our knowledge to create simple form page.

*Into index.html file add link to form.html file.*



Create form with those imputs:

- Name
- Surname
- Email (check if its valid form)
- Age (expect only number)
- Pet (select from this list [Alien, Predator, Peter Porker, Godzilla, Arachnit])



On top of form page create info text with:

"This is registration to extraordinary squad."



On bottom of form create button with text: **Become Extra**.



On button press form show message:

#### If all items of form are filled and age is up 18

*Dear **John** **Doe**, and of course your lovely pet **Alien**. Welcome to extraordinary squad. We send you message to your mail **my@mail.com**.*

#### If all items of form are filled and age is under 18

*We are really sorry. You are to young to die. Please wait (18-age) and we'll be happy to welcome you to extraordinary squad*.

#### If all items of form are not filled

Please fill all form items!
