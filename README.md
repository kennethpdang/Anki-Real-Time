# Anki-Real-Time
This is an [Anki](https://apps.ankiweb.net/) plugin which permits the user to type in multi-line responses and also verifies the responses after each character is inputted. This allows the user to save time by verifying exactly when a character inputted deviates from the contents of the card, instead of having to verify once all the contents of the card are typed out.

## What's the Problem?
We are trying our best to simulate how "The Bible Memory" app works. This is a very well regarded app that also uses spaced-repitition similar to Anki. This app is used primarily by undercollegiate contestants (people in middle school and high school) to memorize Bible Verses for an annual Bible Bee where students can win fincancial prizes. In this app, we type out characters to our Bible verse and it highlights when the next character type is incorrect. See the GIF below:

![Bible Memory Example](readme_images/Bible%20Memory%20Example.gif)

The closest we can get to a similar feature in Anki without this plugin, is by adding a new card and using the "Basic (type in the answer)" card type.

## How Anki Plugins Work?
Our Anki plugin uses the Anki library which we can install by using:
> pip install anki

On visual studios.