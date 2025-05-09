Hello everyone,

I developed this game with C++Builder for the Minesweeper Programming Challenge. My game introduces a unique feature for the first time: the use of Voronoi patterns in the layout of the game cells. In addition, any pattern that can be defined with polygons can be added to the game as a custom one or loaded at runtime.

![MQMinesweeper_2025_Screen_001](https://github.com/user-attachments/assets/7a0697a9-4d6e-4266-b547-d909814c37cb)

MQMinesweeper_2025 is an exciting and exciting experience in the world of puzzle games that defines unique and new features.

The variety in gameplay is one of the strengths of this game. Players can choose from several different modes and get a different experience each time. This variety not only increases the appeal of the game, but also ensures that players face new challenges each time and prevents the game from becoming repetitive.

The attractive and diverse color scheme of the game also adds to its beauty. The use of related and harmonious colors provides a pleasant visual experience for players and makes each game look fresh and lively.

In addition, the new pattern in the arrangement of cells allows players to use different strategies to solve puzzles and find mines.

The game's user interface is uniquely designed. This modern, minimal, and user-friendly design allows players to easily engage with the game environment and allows them to fully focus on solving puzzles. The game's user interface is designed in a minimalist style and eliminates distracting elements so that players can focus on their main goal.


![MQMinesweeper_2025_Screen_003](https://github.com/user-attachments/assets/44870688-c06f-4d17-8fff-bd95436b91e2)


In addition to the classic quadrilateral pattern inspired by the original Windows version of the game and its dimensions can be adjusted, new and innovative patterns are introduced for the first time in the game that make the game completely unique from other similar versions. This idea came to my mind when I had played the original Windows game a lot and had learned all the modes and it was repetitive for me and I was thinking of various patterns that would present different polygons with random arrangements together. So I got to work and wrote my idea. I recommend that you definitely experience it.


![MQMinesweeper_2025_Screen_002](https://github.com/user-attachments/assets/a8364e71-841c-4230-a0c9-0909c81e0e38)
![MQMinesweeper_2025_Screen_004](https://github.com/user-attachments/assets/b05803bc-66d2-421c-bfc3-4e607fcdf9d0)
![MQMinesweeper_2025_Screen_005](https://github.com/user-attachments/assets/5df0bb95-8749-417c-b514-c0410cef77a1)


Predefined patterns that include designs for products from the reputable Embarcadero company are included in the game, which both makes the game more attractive for programmers and invites and encourages ordinary people to enter the exciting world of programming.

In addition, polygonal patterns can be imported from outside the software.

Minesweeper is not just an ordinary puzzle game; it is an exciting journey into a world of challenges and puzzles that encourages each player to explore mines with creative and strategic thinking, while enjoying a unique experience.

I thank you in advance for your attention and support. And I hope you enjoy this game and that this game can play its small role in interacting with the C++ Builder and Delphi programming community and promote more communication and exchange of ideas in the RAD Studio programming community.


==================================================================

This is my wallet address and if you wish, encourage me to continue on this path with your financial support.

BTC (Bitcoin) Address

bc1qgskagr8hg0qwg0z5t2kqsu97p8csm64em9jjxl

==================================================================

Below, I would like to draw your attention to some of the game's features and explain some technical points about playing the game:



- How to select a desired geometry from the menu or load an external file in MSPM format
 
https://github.com/user-attachments/assets/67e4665a-6046-448e-acf5-caa36d03ad6d



- You can view the neighborhoods by pressing the mouse wheel key or pressing the CONTROL key and moving over the cells. Due to the variation in the number of sides of polygons and consequently the variation in the number of neighborhoods, such an auxiliary tool seems necessary. This tool helps you to correctly identify the neighborhoods.

https://github.com/user-attachments/assets/92d5a9cd-073c-45b0-aacd-8893643e1ecd



- An interesting and innovative feature added to this version of the game is the life feature. You are allowed to make a mistake up to three times without failing and ending the game, and each time you lose one of your lives, until the fourth time the final explosion occurs, resulting in a loss.

https://github.com/user-attachments/assets/dbd214c7-7867-41ac-9d14-c1b4530d8709



- Play the game with your favorite color theme. Ability to choose different skins with various color schemes from within the menu

https://github.com/user-attachments/assets/f678a054-2ab2-407d-8f57-824067842d56



- To export your own customized polygons into the game, you can use 3dsmax software and the script in the Source\minswp\minswp_3dsmaxscript folder in the source code from the Editable_Poly object
Save a MinsweeperPolyMesh file with the MSPM extension and load it into the game.
Also, I myself try to put more designs in the PolyMesh source folder over time. Like the hexagonal design I recently added
(Note that the object in 3dsmax software must be located in the 0.0 to 1.0 area of ​​the xy coordinate plane to be displayed correctly in the game viewport)

![MQMinesweeper_2025_Screen_006](https://github.com/user-attachments/assets/83f65cfb-9b14-4e1f-91e7-6ecb8e77c452)


