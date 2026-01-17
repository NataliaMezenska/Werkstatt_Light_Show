# Werkstatt Light Show

## Project idea
This project is a live-controlled light installation made for the reopening of Werkstatt, a cozy cultural bar and nightlife venue in the old town of Chur. The idea was to create an engaging light show that supports the DJ and band performances and makes the stage stand out. Instead of using fully automatic, music-reactive lights, the visuals were controlled by hand in TouchDesigner, allowing for a better match with the beat and mood of the music. This made the light show feel more natural and cleaner. The system changes colors, rhythm, and brightness in real time, adjusted to each performer. By discussing the visual style with both the DJ and the band, the experience became enjoyable not only for the audience, but also for the artists on stage.

## Technical documentation

<img src="component-diagram.png" width="900" alt="Component diagram">

### Hardware:
- Microphone: Picking up the sound
- Latlights: The actual visuals
- Wifi Router: Connect everything on the location
- XLR converter: Connect the wifi to the latlights
- 4 Drawers with electronics: This will run the latlights.

### Software:
Touchdesigner: Makes the system work.


### Reproducibility: 
01. Connect Latlights
02. Make sure the internet is connected
03. Open Touchdesigner
04. Make Chop: Audio device in
05. Connect Chop: Audio Analysis
06. Test surrounding audio and see which stands out the most
07. Connect a Chop: Null for easy oversight
08. Connect a Chop: Select and select the one that stands out
09. Add a Chop: Override and button as back up
10. Add a Chop to... and connect it to a level
11. Be creative with the settings in the level
12. Make a ramp with a cool colour scheme
13. Connect the level and ramp to a top: Comp
14. Add that to the Latlights

### Touch Designer:
<img src="touchdesigner-musicreactive.png" width="900" alt="touch designer music reactive">
The audio device picks the sound up from the microphones and then the audio analysis picks the right frequencies. We select those frequencies and put it to a TOP. Then the audio waves change the intensity of the brightness and gamma. We put this in the comp and then add a colour ramp. So the levels change things in the comp and the colours. Then we move this to the latlights.

### Backup Plan that we used:
<img src="touchdesigner-backupplan.png" width="900" alt="touch designer backup plan">
This includes the different color combinations and speed that the artists and bands wanted. Ready to be changed anytime at will.

## Videos
Below you can watch the final result and the Making Of, showing how the installation was created.
### Show - Final Result:
[![Show - YouTube](https://img.youtube.com/vi/l6kuGrbUQPU/0.jpg)](https://youtu.be/l6kuGrbUQPU)

### Making Of:
[![Making Of - YouTube](https://img.youtube.com/vi/PhwRHotGnew/0.jpg)](https://youtu.be/PhwRHotGnew)

## Making process/reflection
From the start, our group quickly agreed that we wanted to collaborate with Werkstatt. This collaboration allowed us to work closely with music and create something visually interesting for both the artists and the audience. After individual brainstorming and discussions with Jan, we decided to work with the light beams available at Medienhaus. We then began experimenting in TouchDesigner, focusing on what kind of lighting would work well during a DJ set.

Our initial concept was to create a fully music-reactive light show. This idea stayed central for a long time, but on the day of the event we realized that the result did not look as clean or controlled as we wanted. The visuals felt too chaotic and did not properly match the DJ’s music. Because of this, we made a quick decision to switch to manual control. As the DJ gradually increased the BPM during his set, we were able to adjust the speed of the lights by hand. This approach gave us more freedom to play with rhythm, timing, and colors, resulting in a more natural and visually pleasing light show.

The day of the event itself went relatively smoothly. We made sure all materials were already at the venue so we could start setting up immediately. Due to the band’s soundcheck later that afternoon, we had to work within a strict schedule. During installation, the Werkstatt staff suggested involving the corner of the stage more in the lighting concept. This was challenging because our original setup was not designed for that area. Together with Anouk, we quickly brainstormed an alternative solution that would shift more visual focus toward the corner. Even though this change was made last minute, it turned out to be a much better solution and significantly improved the overall result.

Werkstatt also asked if we could use the lights during the band’s performance before the DJ. We agreed and created a new TouchDesigner template specifically for the band. This design was softer and more atmospheric. Before the evening started, we spoke with both the band and the DJ about their color preferences. The band asked for warm colors such as orange and yellow, while the DJ preferred as much color as possible. The Werkstatt staff also shared their preference for colorful lighting, but asked us to avoid green, as it did not fit the venue’s atmosphere. We adjusted the visuals accordingly and did not use green throughout the night.

Overall, the evening was very successful and we received positive feedback from the Werkstatt team and the artists. We also received the following feedback on our collaboration:

“We’ve had the pleasure of collaborating with three international students from the FHGR for our opening event at the Werkstatt Chur bar. The students came up with their own ideas, were very open for feedback and showed great flexibility with their work. On the day itself the concept had to be changed very quickly since the original concept didn’t completely convince us. For the future we suggest a full setup for viewing in advance so that the location knows in advance what the concept effectively will look like. All the other challenges of the day (new space, big crowds, safety issues and last minute demands) were met by the students professionally and enthusiastically. Our team from Werkstatt Chur is grateful for their participation and we will look forward to welcoming them back at Werkstatt if they ever make their way back to Chur again!” - Anouk 

We are very happy with this feedback and will take it with us into future projects. Considering that we had no prior experience in creative technology, we are proud of the result we achieved. For future collaborations, we would present a full visual setup earlier to the client, but overall we delivered a strong project with a satisfied client under real-world conditions.

## Project Info
This project was created as part of the Creative Technology minor in the Multimedia Production degree program at the University of Applied Sciences Graubünden.

Students: Jeroen de Groot, Fiene Hogeweg, Natalia Mezenska
