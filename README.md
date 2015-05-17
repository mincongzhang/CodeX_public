#Code - X 
An action packed two-player VR game. Survive with your companion, maintain your humanity and escape becoming a feast among the dead.

http://vrjam.challengepost.com/submissions/36953-code-x  
https://www.youtube.com/watch?v=aaNRMh3VMtg

##Prologue 


By 2050, artificial intelligence far exceeds mankind's. With great intent, the creators of Eris, the worlds most advanced AI system was programmed to resolve what humanity continues to struggle with, famine, war, disease and inequality.

In an unexpected succession of events, Eris’ answer is to sift through humanity and do away those who hold her from utopia.

Set in an underground complex, home to her experimental test subjects. Eris executes her 4-stage project:

#####1.Physical agility (Initial Room, Zombie Room)
初始房间, 以及第一关: 僵尸囚笼

Players must fend off waves of bloodthirsty zombies by finding the hidden tools and either plow through the monstrosities or run past them to complete the stage. 

两个玩家进入初始房间了解剧情后, 接下来就可以去第一个关卡探索. 
第一关需要玩家配合开门, 拿到武器, 射杀僵尸, 并且找到关键道具之一"钥匙卡". 在射杀了一定数量的僵尸后, 才能解除警报进入下一个关卡.

<img src="https://github.com/mincongzhang/CodeX_public/raw/master/1.jpg" alt="1" title="1" height="400"/>
<img src="https://github.com/mincongzhang/CodeX_public/raw/master/2.jpg" alt="2" title="2" height="400"/>

#####2.Mind game (Maze Room)
第二关:脑力游戏

Players must venture through a maze room with intricate arrangement. Clues are scattered around the maze and must be found in order to gain access to the next room. Both players must think beyond conventional ideas. 

在第二关, 玩家会发现线索散落在各个房间. 拿到手电筒道具之后, 玩家需要配合手电筒和镜子发现墙上的密码, 之后输入到全息密码锁, 打开房间找到第二个"钥匙卡".
两个玩家都拿到钥匙卡后, 需要同时给同伴打开下一关的门, 才能成功通关.

<img src="https://github.com/mincongzhang/CodeX_public/raw/master/3.jpg" alt="3" title="3" height="400"/>


#####3.Cooperation (Laser and Gas Room)
合作模式(激光室/毒气室)

Deliberate intentions to separate players lead them into pre-assigned environments: laser and gas rooms. Players must watch one another suffer as they negotiate through their respective challenge. The player must successfully avoid all strategically placed motional lasers in order to allow player 2 to proceed. The final section requires both players to cooperate and find missing codes for the other to enter within the time limit before being exposed to poisonous gas. 

玩家在这里会被分开到两个房间, 激光室和毒气室. 在进入这两个房间后玩家都会被锁在里面无法逃脱.
毒气室的玩家可以观测到追踪激光生成的位置并且提醒激光室的伙伴躲避. 在激光室的玩家需要同时躲避移动的激光和追踪激光, 并且在尽头打开毒气室的密码的开关. 
毒气室密码的开关打开后, 两个玩家要拼接两个房间提供的全息密码, 毒气室的玩家按顺序触发密码开关后, 两个玩家才能逃脱进入下一关.

<img src="https://github.com/mincongzhang/CodeX_public/raw/master/4.jpg" alt="4" title="4" height="400"/>

#####4.Emotion (Final Escape)
最后的最后

The final stage tests each player’s mental strength and determination to judge their willingness to sacrifice for one another as Eris announces that only one can survive. The final struggle is intensified when a wave of zombies is released, and the decision of life and death is to be made instinctively. The conclusion of this game of trials sees a final twist in the storyline. Who will be the one to survive? 

当玩家穿过最后的尸潮后, 会发现结局仍然是二选一, 你可以牺牲自己, 让同伴逃脱, 或者说服同伴, 自己得以脱身. 但最后真正活下来的, 究竟是谁呢? 并且在最后活下来的玩家会发现, 这并不是结束, 这只是另一个开始.

<img src="https://github.com/mincongzhang/CodeX_public/raw/master/5.jpg" alt="5" title="5" height="400"/>

##Control:
Code-X requires Samsung Gear VR and game pad controller. 

##Mechanics:

The game tests each player’s ability to follow tasks, find clues and cooperate together in a new effective way to progress to the next level. There are twists and turns within the storyline in an attempt to take the players off course and lose hope. Both will require their mental agility to be able to fight off what’s around the corner. Failure for both players to survive will result in the termination of the game. All in all designed to make this game a thrilling and unique experience. 

##Innovation:

The game design is centred around real world Escape Room games, based upon attractive or popular themes. To escape, players will need to solve various puzzles. 

A few limitations in the real world scenarios (such as, cost, small range of locations, unimaginative puzzles) can be overcome in VR setting. The VR Gear can help experience the impossible in the real world and achieve a far superior and immersive feel. 

“Code-X” is the first theme of a series, designed for our VR escape room game.




##Getting started:



This is a two-player game. Both players must download our “apk” and install on Galaxy Note 4.

Upon starting, follow the UI first before placing in VR headset:
 
<img src="https://github.com/mincongzhang/CodeX_public/raw/master/server_UI.jpg" alt="Server_UI" title="Server_UI" height="400"/>
 
Player 1 should choose “Start Server”. Player 2 should choose “join escape”. Following the pairing process, both players will join the game and be able to see one another at base. 

Then, you can place your Galaxy Note 4 in Gear VR. Use your touch pad controller to navigate through the game.

The functions of the game pad controller are illustrated below:
 
 <img src="https://github.com/mincongzhang/CodeX_public/raw/master/game_pad.png" alt="Server_UI" title="Server_UI" height="400"/>

##Techniques:

•	Photon Unity 3D Networking Frameworks SDKs to implement our multiplayer function.  

• Serialized views in Photon are implemented in order to sync multiplayers' action and scene objects.

•	Design Enemy AI system to make the enemies work more intelligently.  

•	Implement holographic effects to make the scene meet our game theme (Sci-Fi).  

•	Use ray cast mechanism in unity to make a interactive ways of manoeuvring within the game.  

•	Orchestrated all music within the game to enhance immersion.   

•	Several ways are used to recude the drawcalls to fit mobile platform, like occlusion, light mapping, and clipping planes in camera etc. 

赛事:
 VR JAM的比赛是由Oculus举办,历时1个月,有500多个队伍报名参加.分为四次上交参赛资料.在第三次的时候,由于100多个队伍没有按时完成被淘汰.总奖金高达102万美元.

团队:  
由5人组成,全部是伦敦大学的学生.一名在读博士生,三名研究生,一名本科生.  

感想:  
虚拟现实游戏的特点就是让玩家能身临其境地体验游戏, 感觉更爽,新奇,光影效果更赞;
我们设计的游戏需要两个玩家互相配合,在紧张的游戏环境下体验互相配合的乐趣;
我们的游戏算是个解谜游戏,除了爽快地射击打僵尸,还需要各种配合解谜, 类似密室逃脱.
虽然现在有很多真人密室逃脱的体验游戏,但是现实中有局限,很多高难度的东西玩不了,玩家可能会受到伤害, 一些复杂的器械在现实中成本很高, 难以实现. 但是在虚拟现实游戏中就不一样啦,只要想得到的就能做给你看,一些危险的解谜,毒气+激光+僵尸毫无压力,玩家可以尽情体验紧张刺激的游戏)

但开发虚拟现实游戏的时候,也要考虑到眼镜的局限性,比如3D眩晕:开发的游戏在视角镜头的移动(玩家移动速度和镜头旋转的速度)上要做适当的控制,如果速度过快,会使得玩家有眩晕的感觉.
而且得考虑移动设备运算能力,虽然现在的手机运算能力很高,但毕竟比不上电脑,,所以得尽可能降低运算负荷,使得移动设备上可以达到一个基本令人满意的效果(我们也花了很多时间在这上面).
