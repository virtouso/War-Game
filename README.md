# War-Game
project is at first stages and not ready to use.</br>

It's a Basic Test for Action Game AI and Animation.<br/>
----------------------------------------------------------------------------------------------------

In AI For A Video Game We Always Look For A TradeOff Between Fun And Rational. </br>
Fun: AI as Recreation of Reality or Realistic Pattern, Shouldnt Make The Game Som Simple Or So Hard; It Should Be Challenging<br>
Rational:AI Should be Adopted Based On Knowledge Of Player From Reality.
at the end it depends on you goals and direction. some games make it just fun with fast paced action with stupid AI NPC's and some make it more deep like... tlou 

------------------------------------------------------------------------------------------------------
Tactics:</br>
rules of tactics and formation are many verbal rules that can be translated to a computer program.</br>
these are the options to turn those rules to a computer program:
- Jason,XML
- Fuzzy Logic
- Expert System
- Architectural Techniques Like: behaviour Tree, Utility Teory

"Sun Tzu" has defined the most basic rules of war. These are The Rules:</br>

- Avoid What Is Strong And Strike At What Is Weak.
- Supreme Excellence Consists In Breaking The Enemy's Resistance Whithout Fighting. The Key Is To Know Your Enemy Well.(If The Enemy Is Arrogant, Pretend to be Weak; So He Will Undestimate You. If He's Relaxing, Attack. If They Are United, Seperate Them.)
- If You The Enemy and Know Yourself, You Need Not to Fear The Result Of Hundred Battles.
- All Warfare Is Based On Deception. Hence, When We Are Able To Attack, We Must Seem Unablle; When Using Our Forces, We Must Appear Inactive; When We Are Near, We Must Make The Enemy Believe We Are Far Away; When Far Away, We Must make Him Believe We Are Near.

------------------------------------------------------------------------------------------------------
Formation:</br>
 in most of action games we consider behaviour of platoons and squads instead of platoons and battalions as they are considered in sterategy games.
there are many formation that a platoon orr squad uses based on conditions for better fire power, safety and ...


---------------------------------------------------------------------------------------------------------
Rules:</br>
At this section we define some rules for behaviour of enemy soldiers when are in action. most of the time, only behaviour of enemy at close range can be noticed bye the player. so we only concentrate on close quarter combat behaviours.  

- Dont run to your death.
- Dont run to a barrel or anything explodable.
- slow until you are ready to go.
- weapon up or you are down.
- ambush.
- flank.
- surprise.
- use firepower for supression.
- use superiority in number.
- try to move the way to be less visible to enemy.
- try to keep enough distance from team mates to not to be goal of grenades or...
- choose the sections of battlefield that gives you the maximum freedom and safety
- select your position based on your weapon and and enemy's weapon.
- only go for melee if you are near to enemy and not in his sight.
- use suppressing ffire when not in cover.
- should'nt apear between enemy and friendly line of fire.
------------------------------------------------------------------------------------------------------
Behaviour:</br>
As AI Designer Or Programmer, We Need To Structure The Code For Behaviour Of Character, Actor, Agent...
For Realism, Every Character Should Have a Sensory System And a Database. 
A Database Is All Knowledge of Character from Environment And Other Stuff Including:</br>
  - being in a team or not.
  - at offence or defence.
  - health
  - capabilities and freedom
  - state(in action, patrol, idle,...)
  - number of enemies and number of team-mates
  - ...
  
  Sensory System Including Eyesight, Sound or Some Scripted or Hardcoded Stuff Update this Senory System. Some Times Sensory System Is More General And is Shared In All Groups All Player Enemies or in a Squad. The Data Is Fed To Structured Code To Performe any Wanted Behaviour. 
- State Machine: limited but suitable for a simple agents. there are extensions like HSFM to reduces limitations.
- GOAP: a series os action/result to achieve a  final goal
- Behavioural Tree:  a tree that leafs are actions and the algorithm searchs in the tree base of feedback from result of leaves
- Utility Teory: most generic way to make a behaviour for the character based on value of a certain action in a defined condition.


------------------------------------------------------------------------------------------------------
Swarm:<br/>
It's mostly considered as movement of birds or all types of enmey movement in a group. but in many futurisitic games it can be used as a type of attack. there are different types of flocking but there are 3 rules should be obeyed:</br>

- Separation - avoid crowding neighbours (short range repulsion)
- Alignment - steer towards average heading of neighbours.
- Cohesion - steer towards average position of neighbours (long range attraction)


------------------------------------------------------------------------------------------------------

