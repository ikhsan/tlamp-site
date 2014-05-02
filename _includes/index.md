## The Talempong Experience: Translating Tradition to the Digital Context
{: .title}

######Muhammad Ikhsan Assaat
{: .author}

######MMus Music Technology and Computer Music
{: .author .no-uppercase}

######University of Leeds
{: .author .no-uppercase}

<br />

####Abstract

This website describes the background, the motivation and the creation of **Tlamp!** project. Tlamp! is an interactive music software that helps its user to learn and play an Indonesian musical instrument, [Talempong](http://en.wikipedia.org/wiki/Talempong). This study will also review past related works and how music software can be brought into the musical tradition's realm.

Numerous literatures argues about how effective software games teach its players to learn a musical instrument. The premise is that a software can teach basic skills that are transferable to the real instrument. Based on that premise, Tlamp! was built to conduct a simple experiment. It would explore how far could Tlamp! help to introduce traditional music to a broader audience.

#####Keywords

Talempong, rhythm based game, percussion ensemble, West Sumatra


###What is Talempong?

Talempong is an instrument, an ensemble and a type of music. Originated from West Sumatra, Talempong is still being used for occasions such as weddings, party for welcoming important guests or accompanying traditional dances or plays. It forms a small kettle gong that has a boss in its centre. Talempong has a short sustain which allows its players to play fast interlocking patterns \[3].

There are two ways of playing Talempong; stationary (*duduak*) and standing (*pacik*). The first way is pretty much the same to Gamelan, the player sits on the floor and hit each gongs with a mallet. The other way is to hold one or two gongs with one hand, and the other hand hit the gongs with a mallet. For this study, we will only investigate the latter. 

<ul class="large-block-grid-2">
	<li /><img src="/assets/talempong.jpg" />
	<li /><img src="/assets/talempong_pacik.jpg" />
</ul>

<div class="flex-video">
	<iframe width="560" height="315" src="//www.youtube.com/embed/VEmX-1_DQPA?rel=0" frameborder="0" allowfullscreen></iframe>	
</div>

###Background

> "What we lack is regeneration. Almost nobody wants to play this music anymore. If this condition stagnates then *Gondang Opung* would likely to disappear from Gema village in two years time." 
>
>
>[Suara diatas Lang Gulang (*Sounds from above Lang Gulang*)](https://vimeo.com/53866898)

Gondang Opung is one of the variants of Talempong music which comes from Gema Village, Riau Province \[2]. The tradition of *Gondang Opung* might meet its extinction sooner than we expected. 

Learning from the Gondang Opung's case, there should be initiative in order to prevent other tradition from extinction. These are the things that might contribute to Gondang Opung's current condition;

- Decreasing interest from the young people
- Lack of documentation
- Limited scope of exposure

###Related Works

Leading from those aspects, software could be a great option for answering those points above. It is important to find past research or related works on technologies that might help the growth Indonesian music tradition.

####Gamelan Elektrika
{: .center}

######[link](http://www.galaktika.org/elektrika.html) - [video](http://vimeo.com/26803278) - [paper](http://www.nime.org/proceedings/2011/nime2011_018.pdf)
{: .center}

<div class="row">
  <div class="small-8 large-6 small-centered large-centered columns">
	  <img src="/assets/gamelan_elektrika.png" class="project"/>
  </div>
</div>

Gamelan Elektrika is the first electric Gamelan that imitates the Balinese Gamelan instruments. It acts as a MIDI controller which is used for playing and transcribing Gamelan composition \[6].

####Gamelan Sampul 
{: .center}

######[link](http://work.antoni.us/Gamelan-Sampul) - [video](http://vimeo.com/43327034)
{: .center}

<div class="row">
  <div class="small-8 large-6 small-centered large-centered columns">
	  <img src="/assets/gamelan_sampul.png" class="project"/>
  </div>
</div>

Having the similar concept as Gamelan Elektrika, Gamelan Sampul squeezes Gamelan instrument to the point that it is portable. It imitates Gamelan's bonang, which has ten notes that is sticked to a Batik fabric. The fabric also acts a laptop sleeve \[9].

####Gamelatron
{: .center}

######[link](http://http://gamelatron.com) - [video](http://gamelatron.com/video.php)
{: .center}

<div class="row">
  <div class="small-8 large-6 small-centered large-centered columns">
	  <img src="/assets/gamelatron.jpg" class="project"/>
  </div>
</div>


A gamelan ensemble that is played by robotic actuators and controlled using MIDI signals. Gamelatron has been installed in high profile art galleries across the world, such as Bali, Singapore, Hong Kong and New York \[4].


###The Experiment

After reviewing the past related works and literatures, it would make sense to bring Talempong to the digital realm. Studies argued that music-based games helped students to train skills that is applicable to the real instrument \[8]. Russell-Bowie also suggested that music needs to be actively experienced by children, not just through listening but by making music themselves in a variety of ways \[7].

The Talempong will be presented as an interactive music software in the hope to answer those issues mentioned earlier in a new way.

####Software as Solution

Why software?

- Interactivity increases interest

	It has been reported that musical games (such as Rock Band and Guitar Hero) boost the sales of the real instrument.\[1] Wiradjaja also mentioned that his Gamelan Sampul functions as a great learning tool for children to learn non-western tuning systems \[9].

- Serves as a documentation

	Software has to live inside a storage. Whether it is in the personal computer or in a cloud server, software always be in a tangible form. This characteristic can act as a form of documentation.

- Ubiquitous means higher exposure

	Digital data has these advantages of from great infrastructure, which will give its user an ease of distribution. Once it is uploaded, everyone from anywhere in the world could have an access to the data. Video game, as one of the digital form, has the potential to be accessed by people from low socio-economic backgrounds for music and music education purposes \[5].


####Meet Tlamp!

<div class="row">
  <div class="small-8 large-6 small-centered large-centered columns">
	  <img src="/assets/tlamp.png" />
  </div>
</div>

**Tlamp! (v0.2)** is a tool to engage its user to learn and play traditional music. It is a ryhthm-based game that uses xbox controller to play the notes. It is played by two players who is responsible for two notes each.

#####Features
- Familiar interface (Youth Music reported that 51% from 1,163 respondents have played music-based console games) \[5]
- Simulate Talempong patterns using xbox drum controller
- Guides and reponds to a hit note

#####Limitation
- Omits the dampening technique of Talempong playing
- Differs from the real handling situation
- Does not know about note velocity (controller's limitation of hit detection)

#####Future Work
- MIDI support
- Create and record pattern
- Pattern sharing over (local or global) network

####Source Code

**Tlamp! v0.2 (Alpha)**

Chekc and/or fork the code at : [github](https://github.com/ixnixnixn/Tlamp)

Download: [zip](https://github.com/ixnixnixn/Tlamp/archive/0.2.zip), [tar.gz](https://github.com/ixnixnixn/Tlamp/archive/0.2.tar.gz)


####License

Tlamp! is available under the MIT License.

See [License](https://github.com/ixnixnixn/Tlamp/blob/master/License) for more detail.


####Contact

Tlamp! was created by Ikhsan Assaat. 

Feel free to contact me at [@ixnixnixn](http://twitter.com/ixnixnixn) or [ikhsan.assaat@gmail.com](mailto:ikhsan.assaat@gmail.com)


**Talempong Shop Link**

Ethnic-INA Indonesian Ethnic Musical Instrument Store: [Website](http://www.ethnic-ina.web.id) (currently offline), [Facebook Page](https://www.facebook.com/ethnic.music.store)

###References

\[1] Ahmed, Murad, "Guitar Hero Leads Children to Pick up Real Instruments", 2008 <[http://www.thetimes.co.uk/tto/technology/article1862082.ece](http://www.thetimes.co.uk/tto/technology/article1862082.ece)> [accessed 20 April 2014] <br />
\[2] Donora, Adhari, "Suara Diatas Lang Gulang (*Sounds from above Lang Gulang*)" (Indonesia, 2013) <[https://vimeo.com/53866898](https://vimeo.com/53866898)> [accessed 24 February 2014] <br />
\[3] Kartomi, Margaret J, "Sumatra", in The Garland Handbook of Southeast Asian Music, ed. by Terry A. Miller and Sean Williams (New York: Routledge, 2008) <br />
\[4] Kuffner, Taylor, "Gamelatron Project: The Marriage of Indonesian Sonic and Ritual Tradition with Modern Robotics", <[http://gamelatron.com](http://gamelatron.com)> [accessed 24 October 2013] <br />
\[5] Missingham, Andrew, "Why Console-Games are Bigger than Rock 'n' Roll: What the Music Sector Needs to Know and How it can get a Piece of the Action", Youth Music, 2007 <br />
\[6] Pardue, Laurel S., and others, "Gamelan Elektrika: An Electronic Balinese Gamelan", *Proceedings of the International Conference on New Interfaces for Musical Expression*, 2011, 18-23 <br />
\[7] Russell-Bowie, Deirdre, MMADD about the Arts: An Introduction to Primary Arts Education, Second Edition (Pearson Education Australia, 2009), p. 54 <br />
\[8] Stanley, Timothy Daryl and David Calvo, "Rhythm Learning with Electronic Simulation", *In Proceedings of the 10th ACM conference on SIG-information technology education (SIGITE '09)*, 2009, 24-28 <br />
\[9] Wiriadjaja, Antonius Oktaviano, "Gamelan Sampul: Laptop Sleeve Gamelan", *Proceedings of the International Conference on New Interfaces for Musical Expression*, 2013, 469-470