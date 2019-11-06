Subject "System verification and testing / Formal model checking" as part of the Master of Software Engineering

### References
|Article/Book| Authors |  Comments 
|--|--|--|
[Timed Automata](https://github.com/evowilliamson/model-checking-research/blob/master/Timed%20automata.pdf) | Alur | A survey of the theory of timed automata, 2003
[A theory of timed automata](https://github.com/evowilliamson/model-checking-research/blob/master/A%20theory%20of%20timed%20automata.pdf) | Alur, Dill |
[Model Checking](https://github.com/evowilliamson/model-checking-research/blob/master/Model-Checking%20(Personal%20digital%20copy).pdf) | Clarke | Textbook used in the course | 
 [Model-Checking for Real-Time Systems](https://github.com/evowilliamson/model-checking-research/blob/master/Model-Checking%20for%20Real-Time%20Systems%20-%20Larsen%20Pettersson%20Yi.pdf) | Larsen, Pettersson, Yi | Creators of UPPAAL, 2005 |
 [An introduction to timed automata](https://github.com/evowilliamson/model-checking-research/blob/master/An%20introduction%20to%20timed%20automata%20-%20Patricia%20Bouyer-Decitre.pdf) | Patricia Bouyer | Presentation |
 [Model Checking Real-Time Systems - Patricia Bouyer](https://github.com/evowilliamson/model-checking-research/blob/master/Model%20Checking%20Real-Time%20Systems%20-%20Patricia%20Bouyer.pdf) | Patricia Bouyer, Uli Fahrenberg, Kim Larsen, Nicolas Markey, Joël Ouaknine, James Worrell | Article on which the presentation [An introduction to timed automata](https://github.com/evowilliamson/model-checking-research/blob/master/An%20introduction%20to%20timed%20automata%20-%20Patricia%20Bouyer-Decitre.pdf) was based  |
[An introduction to bisimulation and coinduction](https://github.com/evowilliamson/model-checking-research/blob/master/An%20introduction%20to%20bisimulation%20and%20coinduction.pdf) | Davide Sangiorgi  |jkjkj|
[UPPAAL Tutorial](https://github.com/evowilliamson/model-checking-research/blob/master/An%20introduction%20to%20bisimulation%20and%20coinduction.pdf) | UPPAAL  |Contains a summary of timed automata|
 [Youtube CTL* video](https://www.youtube.com/watch?v=_2E5Q3CZ7g4&t=1343s) | Model Checking  |Good visual explanation of the concepts of CTL*|
[Youtube CTL video](https://www.youtube.com/watch?v=Blh060Hgbm8) | Model Checking  |Good visual explanation of the concepts of CTL|
 
 


### Study notes
|Date| Note |
|--|--|
| 09/15/2019 | Started with Clarke's [Model Checking](https://github.com/evowilliamson/model-checking-research/blob/master/Model-Checking%20(Personal%20digital%20copy).pdf), finished chapter 1 |
| 09/20/2019 | Finished chapter 2 of  [Model Checking](https://github.com/evowilliamson/model-checking-research/blob/master/Model-Checking%20(Personal%20digital%20copy).pdf) |
| 09/25/2019 | Chapter 17 of Clarke's [Model Checking](https://github.com/evowilliamson/model-checking-research/blob/master/Model-Checking%20(Personal%20digital%20copy).pdf) ***raised some doubts regarding relationship between states and locations***. Used the references in the book and decided to read [A theory of timed automata](https://github.com/evowilliamson/model-checking-research/blob/master/A%20theory%20of%20timed%20automata.pdf) first. Also [Model-Checking for Real-Time Systems](https://github.com/evowilliamson/model-checking-research/blob/master/Model-Checking%20for%20Real-Time%20Systems%20-%20Larsen%20Pettersson%20Yi.pdf) by the creators of UPPAAL seems to be a good reference regarding timed automata|
| 09/26/2019 | Video about overview of timed transition systems and a demo about UPPAAL: [https://www.youtube.com/watch?v=tUSxi_rSXwo](https://www.youtube.com/watch?v=tUSxi_rSXwo)
| 09/27/2019 | [A theory of timed automata](https://github.com/evowilliamson/model-checking-research/blob/master/A%20theory%20of%20timed%20automata.pdf) mentions that timed automata must be able to accept ω-regular languages. This video explains a bit about Buchi automata (one form of ω-automata): [https://www.youtube.com/watch?v=KOu6IUssxbs](https://www.youtube.com/watch?v=KOu6IUssxbs). The concept of ω-automata is important in the light of model-checking as it introduces the problem of infinite runs  |
| 09/28/2019 | [A theory of timed automata](https://github.com/evowilliamson/model-checking-research/blob/master/A%20theory%20of%20timed%20automata.pdf) read until paragraph 3.5 |
| 10/03/2019 | [An introduction to timed automata](https://github.com/evowilliamson/model-checking-research/blob/master/An%20introduction%20to%20timed%20automata%20-%20Patricia%20Bouyer-Decitre.pdf), presentation by Patricia Bouyer explains well the concepts, especially region equivalence and relation between locations in timed automata and states in state transitions diagrams. Also based on the paper [Model Checking Real-Time Systems - Patricia Bouyer](https://github.com/evowilliamson/model-checking-research/blob/master/Model%20Checking%20Real-Time%20Systems%20-%20Patricia%20Bouyer.pdf) |
| 10/04/2019 | [Model Checking](https://github.com/evowilliamson/model-checking-research/blob/master/Model-Checking%20(Personal%20digital%20copy).pdf) ***mentions bisimulation, but chapter 11 of that book doesn't explain quiet clearly the concept***. Found another reference: [An introduction to bisimulation and coinduction](https://github.com/evowilliamson/model-checking-research/blob/master/An%20introduction%20to%20bisimulation%20and%20coinduction.pdf) by Davide Sangiorgi 
| 10/04/2019 | Started reading [An introduction to bisimulation and coinduction](https://github.com/evowilliamson/model-checking-research/blob/master/An%20introduction%20to%20bisimulation%20and%20coinduction.pdf) by Davide Sangiorgi to get more acquinted with LTS equivalence and the concept of bisimulation. These terms are prerequisites in order to continue with [Model Checking](https://github.com/evowilliamson/model-checking-research/blob/master/Model-Checking%20(Personal%20digital%20copy).pdf)|
| 10/05/2019 | After reading [An introduction to bisimulation and coinduction](https://github.com/evowilliamson/model-checking-research/blob/master/An%20introduction%20to%20bisimulation%20and%20coinduction.pdf) the notion of bisimularition is understood|
| 10/11/2019 | Reading [UPPAAL Tutorial](https://github.com/evowilliamson/model-checking-research/blob/master/An%20introduction%20to%20bisimulation%20and%20coinduction.pdf). Reachability, safety and liveness are  mentioned in section 2.2 as important subjects. Started reading [Timed Automata](https://github.com/evowilliamson/model-checking-research/blob/master/Timed%20automata.pdf) to get more information regarding reachability|
| 10/12/2019 | Reading [UPPAAL Tutorial](https://github.com/evowilliamson/model-checking-research/blob/master/An%20introduction%20to%20bisimulation%20and%20coinduction.pdf) again, section 2.3 and chapter 7 about patterns|
| 11/6/2019 | Started reading chapter 3 in the textbook [Model Checking](https://github.com/evowilliamson/model-checking-research/blob/master/Model-Checking%20(Personal%20digital%20copy).pdf). Used the [Youtube CTL* video](https://www.youtube.com/watch?v=_2E5Q3CZ7g4&t=1343s) and [Youtube CTL video](https://www.youtube.com/watch?v=Blh060Hgbm8) to get more clarification about CTL and CTL*|




<!--stackedit_data:
eyJoaXN0b3J5IjpbLTY1NDM0MzY1OCwxMjM3ODM0MDMxLC0yMT
M5Mjc3OTE3LC01OTk3OTAwMDEsMTA0MTI2OTMwMywxNjcxNzI0
MDMsMTIzMjQ1NjMyMiwtMTM5ODI3NzM3NywyMDA3MjMwNTQyLC
0yNDYxODU4NjAsLTEwNTYyMTA1NzcsMzE5NjI5NzEsLTgxMTU3
ODM4NiwtMTgyMTE5MTk2MywtMTM0MzE4OTI4LDE3MTQ4ODY1MT
AsLTExNzUyMjgzNSwtMTQxNjI3MTYzNSwtMTk0ODAwMjE4OCwt
OTU4MDQ1OTY3XX0=
-->