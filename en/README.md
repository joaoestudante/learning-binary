# Learning Binary
This is an educational resource, submitted to Casa das Ciências, to foster the learning of the binary notation by young students. The content is in Portuguese.

## How it works
The project is divided in 2 main files: [the student's interface](binario_estudante.html), and the [teacher's interface](binario_professor.html). Both are self contained HTML pages, with no need to download extra software manually - everything runs in the browser.
Supporting images can be found under the [images](images/) folder, and the game logic under the [js](js/).

### Student's interface

#### The game

The student begins by uploading a words file in the main interface:

![student-upload](https://user-images.githubusercontent.com/5713037/81111773-7ea43f80-8f15-11ea-8b67-6594a86b070e.png)

Afterwards, he/she has to start the game. Then, a table with a binary encoded word appears, and the student has to fill the first column with a letter in each line, corresponding to the encoded letter.

![student-table](https://user-images.githubusercontent.com/5713037/81111826-967bc380-8f15-11ea-8486-9158fded71ed.png)

Afterwards, the student validates his or her answer, and gets a green point if it is correct, and a red point if it is wrong.

A new word can only be generated after getting the previous one right.

#### Informations tab

The student also has access to a tab with more info regarding numeration, binary, among other subjects.

![student-info](https://user-images.githubusercontent.com/5713037/81112013-e0fd4000-8f15-11ea-8c79-f57d5a41e2bd.png)

### Teacher's interface

This interface is meant for teachers to generate tables to eventually share with students, to ease the explanation of how binary works.

![teacher-interface](https://user-images.githubusercontent.com/5713037/81112053-fa05f100-8f15-11ea-9263-d53ae6b2d825.png)


# Roadmap
The next step would be to convert the HTML files to an Electron App, due to the bigger familiarity users have with launching apps (as opposed to opening `.html` files).
