# Audio Book - Some notes for development
1. All the code is self-contained in index.html
2. dictionary.js is used to integrate the page with Dictionary API to get meanings on double click.
3. At present, JS is written in index.html file. All the content you see on the page is extracted from a variable 'syncData'[object].
4. Quizzes can be loaded into the page by adding new elements to syncData.
5. If your new element should be a quiz, modify the keys, 'start' -> 'quiz', 'end'->'<quiz_heading>', 'text' -> array of questions
6. 'text' key could also contain elements with markup. Prefix 'note:' to such element and you will get a black-bordered container instead of question.

# What's not done
1. Feature to add different kinds of quiz. At prsent only textarea can be added
2. A flexible way to include quizzes. 
