# Learning Binary
This is an educational resource, submitted to Casa das Ciências, to foster the learning of the binary notation by young students. The content is in Portuguese.

## How it works
The project is divided in 2 main files: [the student's interface](binario_estudante.html), and the [teacher's interface](binario_professor.html). Both are self contained HTML pages, with no need to download extra software manually - everything runs in the browser.
Supporting images can be found under the [images](images/) folder, and the game logic under the [js](js/).

### Student's interface

The student begins by clicking the big rectangle to generate a new word. Then, a table with a binary encoded word appears, and the student has to fill the first column with a letter in each line, corresponding to the encoded letter.

Afterwards, the student validates his or her answer, and wins a green point if it is correct, and a red point if it is wrong.

A new word can only be generated after getting the previous one right.

### Teacher's interface

This interface is meant for teachers to generate tables to eventually share with students, to explain how binary of works.


# Roadmap
The next step would be to convert the HTML files to an Electron App, due to the bigger familiarity users have with launching apps (as opposed to opening `.html` files).
