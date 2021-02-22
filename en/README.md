# Learning Binary
This is an educational resource, submitted to Science in School, to foster the learning of the binary notation by young students.

## How it works
The project is divided in 2 main files: [the student's interface](student.html), and the [teacher's interface](teacher.html). Both are self contained HTML pages, with no need to download extra software manually - everything runs in the browser.
Supporting images can be found under the [images](images/) folder, and the game logic under the [js](js/).

### Student's interface

#### The game

The student begins by uploading a words file in the main interface:

![student-upload](https://user-images.githubusercontent.com/5713037/106389127-bf17e780-63d9-11eb-8428-d74ac954629f.png)

Afterwards, he/she has to start the game. Then, a table with a binary encoded word appears, and the student has to fill the first column with a letter in each line, corresponding to the encoded letter.

![student-table](https://user-images.githubusercontent.com/5713037/106389159-e4a4f100-63d9-11eb-8e6b-171c1119ff02.png)

Afterwards, the student validates his or her answer, and gets a green point if it is correct, and a red point if it is wrong.

A new word can only be generated after getting the previous one right.

#### Informations tab

The student also has access to a tab with more info regarding numeration, binary, among other subjects.


### Teacher's interface

This interface is meant for teachers to generate tables to eventually share with students, to ease the explanation of how binary works.

![teacher-interface](https://user-images.githubusercontent.com/5713037/106389226-29c92300-63da-11eb-8965-b62836447fac.png)

Another tab is also available, meant to aid with online explanations, where a blackboard may not exist. In this other tab, cards can be flipped to create a binary number, which is then converted to a decimal number and a letter:

![teacher-online](https://user-images.githubusercontent.com/5713037/106389237-3baac600-63da-11eb-9e68-a5cb3bdff135.png)




# Roadmap
The next step would be to convert the HTML files to an Electron App, due to the bigger familiarity users have with launching apps (as opposed to opening `.html` files).
