## Inspiration
My inspiration comes from the growing number of people exercising at home due to the COVID-19 pandemic. With restrictions gradually lifting, many are resuming their exercise routines both at home and in gyms. Proper form is crucial for making exercises easier, more efficient, and effective, while poor form can lead to injuries and long-term physical damage.

Verifying your form can be challenging without a friend or personal trainer, which not everyone can afford. This highlights the need for an application that can analyze your form anytime, anywhere.

## What it does
Form Checker AI is a web application that uses computer vision to track users' joints during workouts. It compares the data to a model trained on Olympic athletes to identify issues with form. If the form is poor, the landmarks will be highlighted in red; if the form is good, they will be blue.

## How I built it
I used Flask, Python, HTML5, and CSS for the front end, and JavaScript, Pandas, OpenCV, MediaPipe, and Scikit-learn for the back end.

## Challenges I ran into
I faced the challenge of not having a well-formatted dataset available online, so I had to hand-pick my own training data, which led to an immature model. Additionally, one team member left at the last minute, reducing the team size.

## Accomplishments that I'm proud of
I successfully built my first machine learning pipeline.

## What I learned
I learned Flask and JavaScript and improved my web design skills, including implementing buttons to attach files.

## What's next for Form Checker AI
Currently, Form Checker AI only works on weightlifting exercises. I plan to improve the model by expanding it to cover more types of exercises, including body-weight exercises that can be performed at home. This will involve gathering high-quality data on both good and poor forms for these exercises.