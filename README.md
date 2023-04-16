# Outline
-[Purpose of the software](#Purpose-of-the-software)  
    -[Type of Software development process & reason](##Type-of-Software-development-process-&-reason)  
    -[Possible usage of your project](##Possible-usage-of-your-project)  
-[Software development plan](#Software-development-plan)  
    -[Development Process](##Development-Process)    
    -[Members](##Menbers)  
    -[Schedule](##Schedule)  
    -



# Purpose of the software
## Type of Software development process & reason
### Type
We chose the Agile methodology.
### Reason
1. Agile is a flexible and iterative development approach  
2. It emphasizes collaboration,customer satisfaction and delivering working software in short iterations.  
3. The requirements of minesweeper are relatively simple and may evolve throught the development process.   
4. Agile process allows for faster delivery of working software in short iterations.Our team can release new versions of Minesweeper more frequently and get to market faster.    
5. Ageli process places a strong emphasis on customer satisfaction and involves stakeholders throughtout the development process approach to meet the requirements of stakeholders.  

## Possible usage of your project
1. Casual Gamers  
2. Older Adults  
3. Education Institutions  
4. Moblie Users  
5. Outline Gaming Communities  

# Software development plan
## Development Process
   
 ***Feasibility analysis*** 
 
（1）Investment feasibility: Minesweeper occupies less memory and can be mounted on any platform, which has investment value.  
（2）Financial feasibility: From the perspective of the beneficiaries, it doesn't take much money to develop this minesweeper.  
（3）Organizational feasibility: feasible project planning, personnel allocation, good communication among team members, regular meetings and discussions to ensure timely delivery of projects.  
（4）Economic feasibility: it can create benefits for the enterprise, increase jobs for the society, and improve people's life quality.  
（5）Legal feasibility: Any product needs to ensure that it does not violate the law before it can be designed. But Minesweeper doesn't break any laws and doesn't come into conflict with companies. The development of the game does not violate anyone's interests, nor does it break the law.  
（6）Technical feasibility: The function of Minesweeper game is simple, only a slightly experienced developer can easily develop, so the technical aspect is not too big problem, the main need to understand the gameplay of minesweeper in order to better design and implementation of the game.  

***Design***

(1) *<font color = red>start()</font>*  
start method used to initialize game resources such as size of map,the number fo mines and the user interface of change the difficulty.  
(2) *createGame()*  
createGame method used to create elements of the game such as generating mine positions, calculating mine positions around each block, creating buttons and timers.  
(3) *handleLeftClick()*   
used to handle the left-click events.  
(4) *handleRightClick()*   
used to handle the right-click events.  
(5) *revealAdjacentButtons()*   
used to uncovered the surrounding squares.  
(6) *gameOver()*   
used to quit the game.  
(7) *checkWin()*  
used to Check whether the game is won.  
(8) *gameWon()*    
used to show the result of game。

***Process Planing***  

There are three parts: after the difficulty is selected, the first time the player clicks on the grid, and the automatic opening of the grid for non-mines.
After selecting the difficulty of the game, get the thunder number set by the difficulty and the interface size display interface, but there is no ray. When the player clicks the grid for the first time, the system randomly mines and activates the timer.  


![屏幕截图 2023-04-16 185857](https://user-images.githubusercontent.com/130427783/232303048-b335e4ab-173a-4e1d-87c1-d67ceb0726ad.png)  

***Interface Planing***  
<img src=https://user-images.githubusercontent.com/130427783/232304317-31475a89-a4ce-4ff8-8e4e-63b3a73dc6e1.jpg width= "400px">  
<img src=https://user-images.githubusercontent.com/130427783/232304433-43d5eefc-0c29-4519-8045-5a4f33abb26b.jpg width = "400px">
<img src=https://user-images.githubusercontent.com/130427783/232304490-7580b15c-c8ce-46dd-b7cc-fb56631596e8.jpg width = "400px">
<img src=https://user-images.githubusercontent.com/130427783/232304532-0fada794-d744-4b75-9562-9945388e8095.jpg width = "400px">








  
   








