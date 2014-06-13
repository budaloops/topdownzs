topdownzs
=========
A 2D top-down zombie shooter where you have to survive waves of different zombies plus protect your animals from becomming zombies and your wife & children from becoming food.

<img src="http://i.imgur.com/5mKGUer.jpg"/>
<img src="http://i.imgur.com/e1VGFkZ.jpg"/>
<img src="http://i.imgur.com/KECSMni.jpg" />
<h1>Game Design Document</h1>

Contents
<ol>
  <li>Project Decisions</li>
  <li>Gameplay
    <ol>
      <li>Story</li>
      <li>Objective</li>
      <li>Features</li>
      <li>Obstacles</li>
      <li>Levels</li>
    </ol>
  </li>
  <li>Controls</li>
</ol>

<h1>1. Project Decisions</h1>
<ul>
  <li>Genre: high-score based 2D top-down zombie shooter</li>
  <li>Platform Java or ActionScript</li>
  <li>Art style: stylized 2D</li>
  <li>Gameplay length: ~5 minutes until it gets repetitive (repetitively intense)</li>
  <li>Game length: ~15 minutes to see all the game’s features</li>
  <li>Screen size: 800 x 450px</li>
  <li>Custom soundtracks composed for the game</li>
</ul>

<h1>2. Gameplay</h1>

<h2>2-i. Story</h2>
<p>Dominican estate workers from the 1870s have resurrected from their grave on the anniversary of their massacre, which was done secretly by their beloved master. Now the zombie workers have returned and they seek to continue working like they never died. Unfortunately for you, who have built your home and farm on the estate, the zombies sees you and your family as “trespassers”, and they seek to get you off the estate… or under it.
(The master was going through stress that arose for estate owners in the emancipation period of the Caribbean and saw this act of mass murder as an easy way out of his problems)

<h2>2-ii. Objective</h2>
Fight off zombies with guns and melee weapons.

<h2>2-iii. Features</h2>
<ul>
  <li>Your farm animals can turn into zombies. Store them away!</li>
  <li>Special zombies and boss zombies appear over the course of the next few waves</li>
  <li>Your children come outside to play and randomly spawn ammo but are vulnerable to zombies while they’re outside, and you interact with them by shouting at them to send them back inside.</li>
  <li>You have the ability to shout and kick; shouting at and front-kicking zombies pushes them away from you.</li>
  <li>Your wife comes outside to switch weapons with you and to refill your ammo</li>
  <li>Your health auto-regenerates when you avoid damage for a certain amount of time<li>
  <li>The farm where the game is played is on top of a scenic  mountain just above a small village and its constantly raining in either drizzle, rain or lightning storm form to help set an unsettling mood to the game</li>
</ul>

Your means of attacking zombies, in order of weakest to strongest, are:
<ol>
  <li>Shout (0 damage but pushes zombies far away)</li>
  <li>Jab with an empty gun</li>
  <li>Front-kick (fairly pushes zombies away)</li>
  <li>Pistol</li>
  <li>Cutlass & cricket bat (pushes zombies away a little)</li>
  <li>AK-47</li>
  <li>Rifle</li>
  <li>Bombs (Molotov cocktails)</li>
</ol>


<h2>2-iv. Obstacles</h2>
<ul>
  <li>Return your farm animals to their sheds because if they get bitten then you have to fight them as zombie animals which are more difficult than the basic and special zombies.</li>
  <li>Your farm animals are out on the field and if they get bitten they become zombies that you have to fight. You can return them to their sheds to avoid them getting bitten. One of your animals may be pregnant and if it’s bitten then it spawns very fast fetus monsters</li>
  <li>Mobs of zombies try to kill you</li>
  <li>If a zombie makes contact with your wife or 3 children then it’s an instant game over</li>
  <li>Your 3 children come out of the house every now and then and you have to protect them and shout at them to return inside.</li>
  <li>The enemies become more difficult with each next level</li>
  <li>A boss zombie which is the most difficult enemy spawns every 5 levels</li>
  <li>You take damage from your bombs if you throw them too close to you</li>
  <li>Zombies prefer to target the defenseless: your family and your animals</li>
  <li>Your ammo depletes so you have to keep refilling it from picking up ammo randomly spawned by your children or it auto-refills when your wife comes to see if you want to switch out a weapon</li>
  <li>If you shout too close to an animal it will kick you in fright</li>

</ul>
<h2>2-v. Levels</h2>
The game takes place on a farm. The area is enclosed by rainforest trees and within the farm space there is the farmer’s house, a couple animal sheds and a few beds of grass for the farmer’s animals to graze on.

<h1>3. Controls</h1>
<ul>
  <li>WASD to move</li>
  <li>Mouse to aim</li>
  <li>Left click to use weapon/ pick up & place down animals by their collar-rope/interact with children</li>
  <li>Right click to use throw bomb</li>
  <li>Mouse wheel (or 1 to 3) to switch weapons</li>
  <li>Space to shout, or front-kick (while the shout is recharging from its last usage)</li>
  <li>R to reload</li>
