# Audio Bible

I am [Adrián Mirabel](https://www.linkedin.com/in/m1r4b3l/), Student of the [CITM](https://www.citm.upc.edu/ing/estudis/graus-videojocs/) Balchelor's Degree in Video Games by UPC at CITM. This content is genereated for the second year's subject Project 2, under supervision of lecturer [Ramon Santamaria](https://www.linkedin.com/in/raysan/).

## Who is responsible for the creation of the Audio Bible?

The Audio Bible is a document created by the Audio Director and the Sound Designer; always maintaining a close collaboration with the director of the project, the art team and the design team.
That collaboration is crucial, being the main problem in indie companies.
This document is designed to help the audio team, as well as the programmers who will need the document to implement the sound into the game. 
[Keith Ziza](http://keithzizza.com/) in one of his interviews said:

```markdown
Designers will want to absorb it, 
programmers will demand it, 
and producers, along with just anyone else who is involved on the project, 
will want to at least skim it. 
Whether it’s one page or one hundred, 
it should be as descriptive as it needs to be for you and for your development team. 
The end result, hopefully, is a harmonious one… working with and enhancing graphics, 
writing, game design, and the overall gaming experience. 
(Keith Ziza 2000).
```

![Team](https://github.com/M1R4B3L/Research-Audio-Bible/blob/master/docs/Images/Team.jpg)

## How it affects the creation of audio?
![Mayer](https://github.com/M1R4B3L/Research-Audio-Bible/blob/master/docs/Images/jonathanmayer.jpg)
As I said before it’s a team effort with an attention to detail that puts the audio experience over the top.  When you’re establishing your audio vision, make sure that you are taking the elements of Music, Sound-Design (Effects), Voice-Over, and Technology into account.  Each element has their subcomponents and everything needs to work together to make for the most cohesive experience.  If one element is neglected or “tacked-on”, it can throw your entire audio direction into disarray.

This is a list of parameters/questions you need to take into account while selecting/designing your audio.

### Audio Pillars

A brief description about a set of features that will be taken into account during the audiocreation, that define the game’s audio aesthetics. Extremely similar to the ones define in design and art.

### Music

**_Genre:_** Description about the theme, Dark for suspense? Medieval?

**_Style:_** Is it a big, bombastic orchestral score or is it a minimalist score that creates more of an ambience?

**_Instrumentation:_** What instruments will be performing the themes that the designers have chosen. There’s a big difference between each instrument and the way it sounds; it definitely can change player’s feels during the game.

**_Implementation:_** Is going to be a single music in a layer and the effects in other one, or is going to be more than one layer for different musics? Is going to change during player actions or game situations?

### Effects

**_Ambience:_** How complex and layered is the world sound that is around the user?Are you on a sci-fi alien planet with moaning winds and twisting thunder crackling around in the skies above? Material?

**_Player:_** Basic player action effect like running, jumping...

**_Creatures/Enemies/Obstacles:_** What sort of “encounters” will the player come across?
Are they small little bunnies? A Gigantic Boss? or a Plant?                                 

**_UI elements:_** You need some UI audio triggers for creating a more accessible and fancy to the user.

![Character](https://github.com/M1R4B3L/Research-Audio-Bible/blob/master/docs/Images/smallorbig.jpg)

### Voice Over

**_Style:_** This could range from age type, gender type, etc…Each voice has its own collection of frequencies and timbre qualities, so it’s good to know what sort of pool you’ll have.

**_Visualizations:_** Tutorial dialog? Indications for the user?

**_Player/Creatures/Enemies:_** The player is going to have a voice, the enemies? The creatures are voice modifications?

### Technology:
You need to take into account the platform you are creating the game for and the sound extension.

**.OGG** for Music and Dialogs 

![Ogg](https://github.com/M1R4B3L/Research-Audio-Bible/blob/master/docs/Images/ogg.png)

**.WAV** for Effects 

![Wav](https://github.com/M1R4B3L/Research-Audio-Bible/blob/master/docs/Images/wav.png)

In this part you should talk about how the sound is going to be implemented in your game, audio transitions and spatial music is a good option for your project. Your music is going to loop? How are you going to handle the superposition of the audio?
A good way to handle your music is diving it in Layers at least 4 layers explaining in each one what are you going to reproduce there.

### Reference Material

Some games can help you develop and surpass a situation they have already handled. 

## Audio Creation

### Tools

### 

## Audio organization 
The most essencial thing in audio is organization, in a game is possible to have more than 1000 sounds; each of them should be structured and accepted by the director, and all the differents leaders. 

### Naming
In terms of naming, this is again something that can be done in many ways, but I’d say that one of the most important things is that, once you’ve decided on a certain terminology, remain coherent with it. And be careful to name the events in your audio engine exactly the way you named them in your design document. Otherwise you will very rapidly get confused between all those similarly named versions of a same event, and won’t know which one is the correct one to use.

```
Example: 
I want no capital letters and the space between words with and underscore

**player_move_water_number (a number may not always be required)**

- First the category. (for example the object type/space)  "player" 

- Second the subcategory. (for example the action type/more specific space) "move"

- Third Description. (add more details about what this event refers to) "water"

- Last number. (there are more than 1 sound) "?"
```
The naming document have to be shared among all the members of the project.


### Folder organization
Whether you are working as a one person department on your own machine or you are sharing a repository for all the audio assets, a clear way of organising these will be crucial.
Following the naming you should create your own organization.

Examples:

![Audio](https://github.com/M1R4B3L/Research-Audio-Bible/blob/master/docs/Images/audio.PNG)

![Music](https://github.com/M1R4B3L/Research-Audio-Bible/blob/master/docs/Images/music.PNG)
![Fx](https://github.com/M1R4B3L/Research-Audio-Bible/blob/master/docs/Images/fx.PNG)

![Category](https://github.com/M1R4B3L/Research-Audio-Bible/blob/master/docs/Images/category.PNG)
![Type](https://github.com/M1R4B3L/Research-Audio-Bible/blob/master/docs/Images/type.PNG)

Good: It has his own naming criteria and follows a folder organization.

![Isaac Fx](https://github.com/M1R4B3L/Research-Audio-Bible/blob/master/docs/Images/isaac_fx.jpg)

![Isaac Music](https://github.com/M1R4B3L/Research-Audio-Bible/blob/master/docs/Images/issac_music.jpg)

Bad:  It has his own naming criteria but does not follows a folder organization (Everything is in the same folder)

![Terraria](https://github.com/M1R4B3L/Research-Audio-Bible/blob/master/docs/Images/terraria.jpg)

## Examples
[Ashlee McCarthy Audio Bible](https://ashleemccarthy.wordpress.com/2013/06/06/sound-design-document/)

## References
[Guide by Zachary Quarles](https://www.asoundeffect.com/game-audio-design-document/)

[Guide by Zachary Quarles](http://zacharyquarles.com/blog/?p=518)

[Interview with Aram Shahbazians](https://professionalcomposers.com/sound-design-for-video-games/)

[Guide Lines](http://www.dreamquakestudios.com/ADD.html)

[Tips for Sound Desing](https://gameanalytics.com/blog/9-sound-design-tips-to-improve-your-games-audio.html)

[Evolution of audio](https://altagram.com/es/music-sound-design-video-games/)

[Book](https://books.google.es/books?id=gnw0Zb4St-wC&pg=PA89&lpg=PA89&dq=audio+design+document+(add)+responsable&source=bl&ots=4cmXkwxntF&sig=ACfU3U0viWwpUndyN551hSTlHPfxwWd2Iw&hl=es&sa=X&ved=2ahUKEwiIzqCw4P7nAhUL6OAKHWm9DrQQ6AEwAXoECAoQAQ#v=onepage&q&f=false)

[Book](http://ptgmedia.pearsoncmg.com/images/9780321961587/samplepages/9780321961587.pdf)

[Audio Organization](https://annesoaudio.com/2016/07/07/game-audio-asset-naming-and-organisation/)

[Template](https://docs.google.com/spreadsheets/d/1Nbn7e6UWmtJ4XOHbYsWqGUJNTdJXgSUZLlATrdIarSM/edit#gid=0)

## Interesting conferences
[Jonathan Wayer](https://www.youtube.com/watch?v=7p9rqo2I_Hs)

[Bjørn Jacobsen](https://www.youtube.com/watch?v=HLOmk6ly_CE&t=829s)



