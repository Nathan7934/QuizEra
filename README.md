See the library in action at the [QuizEra landing page](https://quiz-era.herokuapp.com/) (Mobile incompatible)

## Getting Started
Due to its target audience, QuizEra is designed to be extremely simple to use, requiring little programming knowledge to utilize. After creating a QuizEra instance, the user can call the createNode() function to add up to 26 events to the timeline. When they are finished, they can call generateQuiz() to generate the quiz, specifying where they want the quiz to be placed in their webpage using the 'parent_element_id' argument. An example code snippet is included in the landing page, where the functions' signatures can also be found. Since all the developer needs to utilize QuizEra are two simple functions, there is no dedicated documentation page for QuizEra.

The script tags (with defer) should be placed in the following order in your HTML 'head' tag:
1. jQuery
2. QuizEra
3. Your script that utilizes QuizEra

E.g.:
```HTML
<script defer src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script defer type="text/javascript" src='QuizEra.js'></script>
<script defer type="text/javascript" src='examples.js'></script>
```
