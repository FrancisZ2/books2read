# Coders at Work

## p20 第二系统综合症 及 功能和质量的取舍
   - second-system syndrome
   在完成一個小型、優雅而成功的系統之後，人們傾向於對下一個計畫有過度的期待，可能因此建造出一個巨大、有各種特色的怪獸系統。第二系統效應可能造成軟體專案計畫過度設計，產生太多變數，過度複雜，無法達成期待，並因而失敗。

Seibel: Yet that’s also a classic opportunity to fall into the secondsystem syndrome.
Zawinski: It is, it is.
Seibel: How did you guys avoid that?
Zawinski: We were so focused on deadline it was like religion. We were shipping a finished product in six months or we were going to die trying.
Seibel: How did you come up with that deadline?
Zawinski: Well, we looked around at the rest of the world and decided, if we’re not done in six months, someone’s going to beat us to it so we’re going to be done in six months.
Seibel: Given that you picked the date first, you had to rein in scope or quality. How did that work?
Zawinski: We spent a long time talking about features. Well, not a long time, but it seemed like a long time because we were living a week every day. We stripped features, definitely. We had a whiteboard; we scribbled ideas; we crossed them out. This was a group of like six or seven people. I don’t remember exactly the number. A bunch of smart, egotistical people sitting in a room yelling at each other for a week or so.


## p25 沉溺过度设计

Seibel: Overengineering seems to be a pet peeve of yours.

Zawinski: Yeah. At the end of the day, ship the fucking thing! It’s great to rewrite your code and make it cleaner and by the third time it’ll actually be pretty. But that’s not the point—you’re not here to write code; you’re here to ship products. 

Seibel: Folks engaged in overengineering usually say, “Well, once I’ve got this framework in place everything will be easy after that. So I’ll actually save time by doing this.”

Zawinski: That is always the theory.

Seibel: And there are times when that theory is true, when someone has good sense and the framework isn’t too elaborate, and it does save time. Is there any way you can tell which side of the line you’re on?

* Zawinski: I know it’s kind of a cliché but it comes back to worse is better. If you spend the time to build the perfect framework that’s going to do what you want and that’s going to carry you from release 1.0 through release 5.0 and everything’s going to be great; well guess what: release 1.0 is going to take you three years to ship and your
competitor is going to ship their 1.0 in six months and now you’re out of the game. You never shipped your 1.0 because someone else ate 
your lunch.

* Your competitor’s six-month 1.0 has crap code and they’re going to have to rewrite it in two years but, guess what: they can rewrite it because you don’t have a job anymore.

## p31
   - Assertions
   - Extraction
   Testing Tool
