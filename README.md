# The Schaak Guide to Audios

If I had to trace my love of audio and audio equipment back to somewhere, it would be my uncle.

My uncle used to let me tag along at a very young age, when he would run the audio for local council events. Whether it was a dance concert at the local town hall, or outside broadcasts at the local festival. I not only got to see how it all went together, but also had some hands-on experience with microphones, amplifiers. different kinds of speakers, cueing tracks, mixing, and most importantly problem solving a signal chain.

Those memories are burned into my brain; the differences between mains and monitors; the way to perfectly set a cue point on a cassette with a pen; how to figure out which speaker is left and right with a torch battery; and how to ride the faders to avoid feedback in a hall with shitty acoustics and performers with bad mic technique.

Since then I've gotten to record music at home and in studios; recorded and produced podcasts; performed live music, solo and with a band; streamed both voice and live music over Twitch; and had to route audio in many other wonderful and wacky ways.

I've been asked some questions about how I do my vocal audio for podcast and streams, and what I would recommend, so I thought I would document some of that info here. This will be a work in progress guide, solely focussing on capturing a person talking into a microphone. I'll add to it as I tweak and change, or as more questions arise.
### First things
This isn't a total beginners guide, but it's also not an exhaustive tech deep dive. Beginners will definitely learn some things, but I'm not suggesting my approach is where you jump in. When I was young and just getting into purchasing my own audio equipment, my parents told me "Don't try and keep up with your uncle" and that was good advice. I was able to use the knowledge I learned from him to make some good choices that could grow with me - some of those purchases still serve me well today.

For total beginners I'd say start simple and then slowly figure out what YOU need and what YOUR setup requires. If I've learnt anything, it's that there's not one way to do it, and anyone saying there is, is probably trying to sell you something. Of course some ways are better than others, and it pays to understand the whys behind the 'rules' - but Prince has recorded vocals with an sm57 at the mixing desk, and Zeppelin has recorded drums in a stairwell. In the end you'll find what works for you.
### Second things
These are my experiences; my requirements; and the way I set my stuff up. As I said above, there are a multitude of other ways to capture and route audio; start small and slowly build and upgrade the parts you need, as you need them.
### Third things
I am not a gatekeeper of creating content. If all you have is a work supplied USB conference headset and a passion to create - go forth and make!! Will better audio make for a more pleasant experience for both you and your listeners? Yes! But it's never more important than having the opportunity and desire to create in the first place.
### Forth things
I'll try and keep the detailed tech talk to a minimum, but we'll touch on some nitty gritty stuff as we go. Try not to let your eyes glaze over too much, I promise you it'll be worth it. If you want more information after you finish, this guide will leave you with enough knowledge to at least start hunting for it.

# OK let's go!
## The Overview
We should probably begin with the basics of what it takes to get the sound of your voice into a recorded format. There are not a lot of parts to it, but knowing a little more about each of them can help you make some informed decisions.

Our aim is to capture a quality analogue source; amplify it to a level suitable for capture; convert the analogue signal to a high resolution digital signal; and save that data to a file. 

At it's most basic, the signal chain to achieve this looks like this:
##### Voice > Microphone > Preamp > A/D Converter > Recording Device

The most important thing to understand is that your voice is an analogue source. It's rich; full of subtleties; and has infinite degrees of range. On the other hand, the quality and range of a digital signal is determined by the bit depth and sample rate it's captured at - and like image resolution, it's better to start with the highest res we can. 

Let's dive a little deeper into the signal chain.

## The Voice
Oh, hey there! Yeah we're starting with you, and how you effect the sound. Crazy right! Part of getting good sound from a microphone is learning how to talk into a microphone. How to direct your voice; stop the dreaded plosives; and how use the proximity effect.

Microphones used for speech are designed to be used up close. In controlled conditions I would say 2-3 fingers width away (singing on a loud stage I'll be almost touching the grille). The further away you get the thinner and quieter your voice will sound and the more of the room noise you will capture when you have to turn up the gain to compensate.

Plosives are those weird loud sounds you get on Ps and Bs. They come from balls of air from your mouth hitting the mic capsule and exploding. You can avoid them either with a pop screen or changing your mic technique slightly and talking into your mic at a slight angle so the balls of air travel across the mic instead of into it.

The proximity is just that - how the sound of your voice changes the closer or further away you get to the mic. The closer you get, the more bassy or boomy your voice will get. The further you get away the opposite. 

Learn how your mic feels and responds to distances and angles. Your microphone is another tool you can use to aid in your communication and should be an integral part of your performance - not just vaguely in the room with you.

## The Room
Now let's talk about the giant thing you most likely can't do much about (and if you can and are building a recording booth or studio, you are probably already outside the scope of this guide).
The room you are recording in or broadcasting from, and it's contents, can and will effect your sound. Most of the time, under most of the circumstances, you shouldn't need to do too much - if anything. I find general soft furnishings and the natural angles you'll find in a home office or bedroom are enough to tame the more annoying reflections. 

If you're in a larger room with big flat surfaces you'll probably have more problems taming these echoes. The easier solution is to find a different place to record, but if that's not an option, some simple acoustic treatment may be needed. I've been lucky enough not to need any treatment other than what has been in my rooms (sometimes having junk, and collectibles actually comes in handy).

If you need to find a new spot to record, a single clap in the middle of a room will give you a good idea of how  echoey it will be. In most home cases you don't need a completely dead room, just one that doesn't sound like a bathroom.
## The Mic
OK you have a place to record - congrats! Now comes the fun part.

Microphones come in all shapes, sizes, and types. Before we get down to choices and recommendations, it pays to understand some key differences between mics. This is by no means an exhaustive list of all the options, but the main things we'll need to consider.
### XLR vs USB
Microphones need to connect to other things in order for sound to be captured. The two connection types we'll be talking about, are XLR and USB.

XLR connectors are balanced audio connectors that can also supply low voltage power to condenser mics. They're identifiable by their chunky, three pin connectors that can carry their ground, positive and negative signals over long distances with little degradation. Microphones with XLR connectors are just that. They need to be plugged into an audio interface before their signal can be captured by a PC, but are also often used in conjunction with mixers, preamps, processors. 

USB mics on the other hand, connect directly to a PC. They are a microphone and audio interface in one, and often have built in gain and mute controls, as well as outputs for headphones. The main upside to USB mics is that all you need to do is plug them into the computer and you're ready to go - the downside is they come with some significant quality trade-offs.

The trade-off generally comes in the form of lower quality parts than you would get if you had dedicated components, the biggest trade-off of which is often in the Analogue to Digital converter. Remember we talked about how the human voice is rich, and emotive, and dynamic? Well a trade-off in A/D conversion is a trade off in communicating those qualities. 

Without getting too much into the details of it all, most USB mics will come with a 16bit/24kHz converter which kinda means splitting up each chunk of data into 16 pieces and capturing that at a rate of 24kHz. A lower bit rate will often translate to a higher noise floor (the ambient hiss you'll often hear in recordings), and an amplification of that noise floor when we try an do cool stuff like EQ and compression later in the chain - especially if you don't capture a loud enough signal to begin with.
### Dynamic vs Condenser
You may have already heard the terms Dynamic and Condenser being used when referring to microphones, often in conjunction with other phrases like "cardioid dynamic" or "large diaphragm cardioid condenser". Here's a simple description of each.

**Dynamic microphones** are passive, as in they don't need electricity to operate. AC voltage is created when your vocal waves hit a diaphragm and conductive coil vibrates within a magnetic field. Because they require energy to pick up sounds, they are not great for  higher pitched sounds (they have a fall off at about 10k), but they do generally have a slight natural boost around 1-5k, which makes them perfect for voice and vocals.

**Condenser microphones** on the other hand are active, powered by phantom power supplied through the mic cable (or USB cable). These mics convert sound waves to electrical energy through a vibrating diaphragm, and electrostatic principals. Condenser mics are a a lot more sensitive than dynamic mics - they excel in picking up fine details and higher pitched sounds. Because of their sensitivity, they are not a great choice for untreated environments as they will easily pick up room noise, computer fans, and keyboard and mouse clicks. One area they would probably work great in though, is ASMR.
#### Cardioid vs Supercardioid vs Hypercardioid
This describes the pickup pattern for your microphone, ie. the directions and angles that a microphone is sensitive to. The most common pickup pattern you will see is Cardioid, which means your mic is sensitive to the front, and has some level of sound rejection fro the sides and rear, which s great for lessening the sounds from keyboards or monitors. Super/Hyper cardioid have a tighter window at the front of the mic for more focussed pickup but it's often at the expense of some rear rejection.
#### End address vs Side address
Not as technical as the previous two points, but worth mentioning so you understand that their is a difference (and don't look silly talking into the wrong part of your fancy mic). As I mentioned above, mics are directional, bit it's not always from the same direction. Some mics you talk into the end of, and some mics you talk into the side of. As a general rule, dynamic mics are mostly end address, and condenser mics are mostly side address (I'm not definitive about either of these statements because there are a few exceptions).

Now you are knowledged up, let's talk about some mics I have had experience with and would recommend!
### **Shure SM7b**
*Cardioid Dynamic Microphone*

https://www.shure.com/en-ASIA/products/microphones/sm7b

I'm sure you've seen these in radio stations, and on streams and podcasts everywhere. Originally released in 1973, these big, black, chunky mics have stood the test of time for a reason. They're a solid vocal mic, that won't emphasise any particular frequency which makes them very easy to EQ. It has that classic voice/announcer sound that cuts extremely well, and it's low sensitivity helps reject a lot of ambient noise, so it works well in untreated spaces. The downside to this mic is that it does need a fair amount of gain to get the most out of it. Most audio interfaces can't supply the 60db of gain it needs so I pair it with a cloud lifter to boost the signal before it hits the interface for conversion. It is on the expensive side of things but it's built like a truck and will last a lifetime.
### **Shure SM58**
*Cardioid Dynamic Microphone*
https://www.shure.com/en-ASIA/products/microphones/sm58
Primarily a live, handheld microphone (only the most widely used live vocal mic ever) - I include it here mainly because it has a very similar frequency response to the SM7b and maybe a lot more readily available. If you're not sure about a SM7b and want to get the vibe of one, you may be able to get your hands on one of these to try out. There are some differences between the two, the biggest one to keep in mind when comparing the two is probably that the mic capsule is set further into the SM7b than on the SM58 so keep a little more distance from a 58 to get the vibe. I probably wouldn't recommend a 58 for serious streaming/podcast use, but I am putting together a mobile podcast setup based around 4 SM58s and a solid state recorder.
### **Audio Technica BP40**
*Hypercardioid Dynamic Microphone*
https://www.audio-technica.com/en-au/bp40
I originally picked up this mic because I liked what Audio Technica were doing with their headphones and I wanted to hear their take on a broadcast mic. I'd read it was kinda like all the benefits of a dynamic mic but with a little more of the condenser vibe. It has ended up being my primary voice mic for over a year now. It's EQ isn't as flat as a SM7b, it has a nice little presence bump which gives the sound some more clarity (or sparkle I guess), it has a tighter polar pattern which I had to get used to, but it also has a really useable proximity effect thanks to the capsule being closer to the grille. I really enjoy how this mic sounds - My current  setup uses this mic for talking, and an SM7b for singing.
### **Rode NT-1A**
**Cardioid Large-Diaphragm Condenser**
https://rode.com/en/products/nt1a
I've included this because it was my first decent mic. I've used it for streaming, and podcasts, and recording vocals, and acoustic guitar. It's was a great first condenser but, much like any condenser, I always found myself trying to tame excess sounds, whether it be room noise, or keyboards or computer fans, even rustling of clothes. It did teach me a lot about good microphone technique because even with a foam wind shield it was prone to plosives (a pop screen was better but a lot to have in front of you when streaming). After owning and using this mic I really understood how a dynamic mic better suited the environments I was using, and trying to counteract the problems was fighting a losing battle.
### **Rode Podmic**
*Cardioid Dynamic Microphone*
https://rode.com/en/products/podmic
I've only had a small amount of experience with this mic, but I've included it to say that you don't need to spend a lot of money to get started with a semi-decent XLR dynamic mic. It's not as flat or classic sounding as a SM7b, so you might need to do a bit more work in the EQ to get it sounding how you want, but it's a quality mic at a good price that might leave you with some extra cash to spend on the rest of your signal chain. There is a USB version of this mic as well but if you stick with the XLR you'll have a mic that is still useful years into the future, even if you have since upgraded to something else.

I've touched on a few mics to get you started, at a variety of price points. There are many more mics out there to choose from, and it's worth finding something that not only suits your voice, but one that you love to use.

There are a few classic broadcasting mics I would still love to try out - at the top of that list is the RE20.
### **Electro-Voice RE20**
*Cardioid Dynamic Microphone*
https://products.electrovoice.com/na/en/re20
This mic, along with the SM7b are synonymous with that classic broadcasting sound. There's generally a reason a classic mic earns that title and I'd like to experience what all the hype is about for myself. 

## The Processing
Now here's where my signal chain may deviate from a lot of others, and it's really based on a piece of hardware and what it has taught me about modern audio.
### **DBX 286s**
*Microphone Pre-amp Processor*
https://dbxpro.com/en/products/286s

I do all of my signal processing externally, using an external piece of equipment. It's not some rare vintage thing that will be impossible to find and break the bank - you can get one new, now,  for not too much money. It's the DBX 286s channel strip. As single, 1U, rack mount channel strip that includes a pre amp, compressor, de-esser, eq and noise gate all in one. The 286s is the piece of equipment that has been part of my setup for the longest. It has stayed through mic changes, audio interface replacements, and PC upgrades. It has been the very definition of set and forget (plus it has cool blinky lights on it).

*"But I can do all of that with plugins for free on my PC"* I maybe, probably hear you say. And I agree, yes! You can! But hear me out... The only parts of my signal chain I have ever had problems with, are the digital ones. The 286s on the other hand, won't crash, won't be borked by updates, won't be superseded by the next fancy connection protocol, and just, works, regardless of what you plug it into. This thing is so integral to my setup that a few years ago I bought a second one as a backup, and have never needed it.

If you rely on great sounding audio for voice in any capacity, I highly recommend you check out the DBX 286s. There are also other

Regardless on how you do it, processing audio is integral to a getting s great sound. It doesn't have to be much, but a little nip and tuck here and there will make all the difference to clarity, cut through, and most importantly, listenability of your sound.

Let's take a look at each of the steps. Note: if you are going the plugin route, these steps will take pace after the **Audio Interface** stage.
### Preamp
We can't just use a microphone signal as it comes out. Every mic expects a certain level of pre amplification to reach its optimal working level. If a preamp isn't powerful enough to drive a mic it can feel dull and lifeless and all the processing in the world won't get you out of that hole. Mics like the SM7b require a lot of preamp gain so check what your preamp specs before buying (or get something like a Cloudlifter which will increase overall gain of a signal by a fixed amount before it hits your preamp)
#### **Cloudlifter CL-1**
Mic Activator / Gain Box
https://www.cloudmicrophones.com/cloudlifter-cl-1

Our aim is to capture a strong source signal with a broad range of dynamics, so we're starting with a quality signal before processing and A/D Conversion. If you're not doing external processing the preamp duties will be handled by your audio interface.
### Compression
Ah compression... Everyone has heard about it but few seem to know why they need it, or how it works. Honestly, I understand the confusion because compression shouldn't really be noticeable until you remove it. I'm going to have a go at describing this elusive effect, as clearly as I can. Let's go...

An uncompressed audio signal, like a recording of your voice, has a large range - from whisper quiet to yelling loud. Setting a level for an uncompressed track is tricky, because either the quiet bits get lost amongst other sounds, or the loud bits are too loud and the signal clips.

Compression aims to reduce the distance between the loudest bits and the quietest bits, so the whole signal can be made to sound louder. The result of a well compressed track is a fuller, clearer sound that still has the majority of it's dynamics intact.

Witchcraft right?! 

Kinda, yeah. There are five main settings for a classic compressor; as we step through them, I hope you'll start to get a picture of how it works.
### Threshold
To preserve dynamics, we want to keep the majority of the signal untouched, so we set a threshold level. If the signal gets louder than this threshold level, the compressor kicks in to action. The lower the threshold, the more of your signal will be compressed and the less dynamics you will have. Sometimes when figuring out how much compression to use I will record a section of me speaking and look at the levels and peaks and use a number that would cut the high levels of a peak as a starting point. From there, if it feels too compressed I'll raise the level, and if it needs more I'll lower the level. 
### Ratio
The ratio is the amount the volume gets turned down once the signal passes the threshold. You don't want this to be too high, as to sound like the loud bits are getting suddenly cut off, or two low that nothing is actually happening. I generally start at a ratio of 6:1 and see how it feels. And work up or down from there.
### Attack
This setting tells the compressor how fast after a signal passes the threshold, it should kick in. Voice peaks are fairly short and quick, so we need to be able catch them on time. set a fairly fast attack speed, I generally start at 10 milliseconds.
### Release
You've probably guessed this one already, but the release setting tells the compressor how long after the signal dips back below the threshold should it stay active. Not only are voice peaks short and quick, they also tend to come in short groups, so keeping a slightly longer release time will ensure the compressor stays open long enough to catch any extra peaks. I generally start at 100 milliseconds.
### Output gain
Remember when I said that we want compression to be unnoticeable? Well doing all of the above, by it's very nature will make your track quieter. The reason compression works is that it reduces the peaks of the loud bits, so that when we can turn the whole track up again, and the quiet parts can be louder. Set the output gain so that your track is no louder or softer when the effect is engaged.

Congratulations! You just compressed a thing.

Some compressors have fewer or more settings but the theory is generally the same.
### EQ
I'll be honest, I don't know much about EQ. I don't have the ability to listen to a track and identify which frequencies are too high or low. I tend to use the simplest EQ I can find and tweak very little. EQ is something I would love to learn more about. Luckily the EQ section of the 286s is very simple - just a knob for low frequency detail and a knob for high frequency detail. I thought my sound needed a tiny bit of top end to it so I turned the HF up very slightly.

Generally I would say EQ with care, it's easy to go too far and make things worse if you don't know what you're doing.
### Noise gate
Because very few of us record from a fully treated studio, a noise gate comes in very handy. Noise gates turn the volume down on your source when it drops below a certain level. Simple noise gates have a threshold and a ratio (remember these from our compressor adventures?). The easiest way to set these is start at zero and turn the ratio slowly up until you can just hear your ambient room noise, then turn it back down one click so it silences it. I generally set my ratio at about 2:1 so it doesn't sound like the audio is getting suddenly cut off when the noise gate kicks in.

Note: you will be able to hear the background noise again when you start to talk, but it shouldn't be as noticeable because it's competing with your voice. It's still important to have an environment to record in that is as free from extraneous noise as possible.  
### Output gain
If you've got a few steps of image processing in a chain you might find that  your signal is a little quiet or a little loud. You can reset this level with a boost or cut in output gain.
## The Interface
OK! We have a quality signal, it's time to turn it into something useable by a PC. Enter the world of the Audio Interface! Audio interfaces come in all shapes and sizes at all the price points. I've tried super cheap ones, expensive ones, and middle ground ones.

The good news is that if you're just capturing voice, you don't need a huge amount of inputs or features, just a quality A/D Converter, a decent build quality, and a decently powered preamp if you're not doing external processing.

Here are the two I've used the most.
#### **Presonus AudioBox**
https://au.presonus.com/products/audiobox-usb
This is the audio interface I started with. It's cheap, a little rough around the edges, and sometimes slightly noisy depending on what else is nearby. I've included it to point out that even this cheap interface does 24bit/48kHz conversion, which is better than you get with most USB mics.
#### **Focusrite Scarlett**
https://focusrite.com/scarlett
Which leads me to the Focusrite Scarlett range. These interfaces are a great cross section of features, quality and price. They have good preamps, quality 24-bit/192 kHz A/D Converters and have a solid build quality. I'd suggest starting here.

Note: if you're doing your processing with PC based plugins these will happen after this stage. There are ways to do this processing at a system level with software like WaveLink by Elgato but along with the previously stated issues around upgrades and crashing, I've never been a massive fan of the latency this method adds to the signal when you're monitoring your voice.

There are other methods of connecting microphones to computers, like the GoXLR or RODEcaster. These are an Audio Interface and effects in one. I've honestly had no experience with them but have heard good things from people who have. If you follow good practices as outlined above you can get great results out of a variety of different approaches.

As I've said... Start simple and figure out what your needs are.

I definitely started this guide with the intention of making it informative and simple to follow. It's ended up quite long but I hope these principals are upheld. I'll update this guide over time to include new information and finessed opinions. the world of audio is a fun journey to undertake.

I hope you enjoy the ride.
