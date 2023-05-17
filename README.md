# Regex Quiz

This is a Regex Quiz implemented in HTML, where users can test their knowledge of regular expressions. 
The quiz consists of fill in the blank questions, and the user's answers are validated using regex pattern matching.

## Instructions

1. Clone or download the repository to your local machine.
2. Open the `index.html` file in a web browser.
3. The quiz will be displayed with a series of questions related to regular expressions.
4. Choose the most appropriate answer for each question by checking the values in the value field and the regex expression in the regex field.
5. Correct answers will be highlighted with a green border, while incorrect answers will be highlighted with a red border.
6. Review your answers and try the quiz again if desired.

Alternatively, you can also visit the webpage hosted on vercel, via: https://regex-quiz-delta.vercel.app/

## Regex Pattern Validation

Each question in the quiz has an associated regex pattern that represents the expected answer. 
When the user enters their answers, the provided answers are checked against these regex patterns using the HTML `pattern` attribute.

The regex pattern matching ensures that the answers adhere to the specific pattern requirements. 
If an answer does not match the expected pattern, the field is highlighted in red color. 
Users can match their answers with the expected answers provided in the footer of the webpage.

## Customizing the Quiz

You can customize the quiz by modifying the HTML code in the `index.html` file. 
You can add or remove questions, change the regex patterns for answer validation, 
or modify the quiz layout to suit your needs. 
The quiz is implemented using only HTML, and some CSS, so basic knowledge of these technologies is beneficial for customization.

## Acknowledgements

This quiz was created using HTML, and some CSS. It was inspired by Mr. Murtaja Raza's form challenges. You can check out his project here, https://github.com/murtraja/form-challenges.

If you have any feedback, suggestions, or issues, please feel free to open an issue.

Enjoy the quiz and have fun learning about regular expressions!
