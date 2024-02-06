A combination of visuals and sound, [this site](http://listen.hatnote.com/) utilizes edit data from Wikipedia and among the many tools used, one is D3! Other tools include HowlerJs, Sound eXchange. This project was insipred by Maximillian Laumeister's [BitListen](https://www.bitlisten.com/), which is essentially the same concept,
but instead of the data being Wikipedia edits, it uses realtime Bitcoin transactions.

On the visual side, bubbles are tagged with the name of the Wikipedia article being edited, with the size being determined by the size of the edit in bytes added/removed. Green circles show edits from unregistered users, with purple circles
being automated bot actions. No color is assumed to be from registered users. 

Connected to the English Wikipedia:
![image](https://github.com/FullStackGoogler/reflections/assets/71947872/7c035343-966c-4b87-be6c-a6f0e500df41)

A box below the bubble visual includes a real-time feed of the edits received:
![image](https://github.com/FullStackGoogler/reflections/assets/71947872/3688e0b6-3038-4f0c-9739-97462ebfbdf4)

The real cool part is the audio that plays along each edit that appears; in their about section, bells indicate additions, string plucks indicate subtractions. Size of the edit also affects the pitch of the edit, with larger edits creating deeper ntoes.

Some other features include the ability to change languages, or to filter edits by tags.
