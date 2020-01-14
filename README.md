# home-WebGL-movingBall-cs-romanm

### Project description: 
This Project was intendet as an Unity Github and C# Exercise.
It contains a Button which triggers a public function for setting a Ball
randomly to 4 predefined positions. 
That was implemented using the c# Function Random.Range() and a SerializedField 
GameObject Array in which the predefined positions are saved.

To prevent that the Ball ist set to the same position in a row twice or more, i
wrote a while loop which repeats the Random.Range() Function as long as a new
position is found. Which might not be the most efficient way 
but for a Project that size it shouldn't be problem.

### Development platform: 

* Mac OS
* Visual Studio Code
* Unity 2019.1.14f1
* Scripting Runtime Version: 4.X

### Target platform: 
WebGL

### Necessary setup/execution steps: 
WebGL needs to be installed. 

### Third party material: 
Github Template: 3ahmnm-htlsbg/Unity2019114f1-2D-Template

### Project state: 
progress

### Limitations: 

None

### Lessons Learned: 

* How to use Random Numbers
* using  GameObject.tranform.position 
* Build for WebGL
* Host with Guthub Pages

This Readme ist copied from Kilian Reisinger and edited for my platform. 
