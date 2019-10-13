# #100DaysOfCode Log - Round 2 - Jainnielyn Ching

The log of my #100DaysOfCode challenge, round 2! Fell off the wagon last time, was too inundated by worry. Let's try this again. 
Started on October 6, 2019.

## Log

### R1D1 
Was stuck on Udacity's Android Basics, Miwok app - Lesson 4 #15-16 where I need to change the color of a section of the screen, depending on which category was clicked. My first trial was ultimately the correct way to do it (efficient, etc.) but I couldn't get through the error messages. I then tried other more brute force ways, and got it to work. 

After watching the solution video, realized my original plan was the correct one, so reversed the brute force code, went back where I got stuck and realized why it wasn't working. I changed a constructor call in one activity, but didn't change it in the others so the app won't even run.

Also - learned some git! Came across it before, but now felt the need to learn it (how am I going to 'experiment' with code while keeping the working code intact?) This Youtube video is pretty informative without being overwhelming. He goes through some examples which makes it easier to understand. [link](https://www.youtube.com/watch?v=SWYqp7iY_Tc)

### ***Audio segment: Mini audio player***

### R1D2
Next task for Udacity's Miwok project (an app that teaches another language) is to add audio files (correct pronunciation) to each word. I had to create a separate small app to test out MediaPlayer. Very simple, it only has 2 buttons - play and pause.

Success! The best part is, it worked at first run!! How rare. I then added code to release resources on exit of the app.

### R1D3
Experimented with other functionality, added skip 10 seconds and rewind 10 seconds (getCurrentPosition and seekTo) to the mini project.

Went back to the Miwok project, next task is to add the little audio playback for each word. Action plan: 
1. Add play button to the UI
2. Save all the res files
3. Modify Word class to relate the audio file to the correct word
4. Set the onclick listener/method to play audio file.

Link to [audio mini project](https://github.com/jainnielyn/Basic-audio-player).

### ***Audio segment: Miwok project's audio***

### R1D4
So I had a choice how to implement the audio segment - either do it without tutorials, or with tutorials. I chose to do it without... but getting the play button just right was taking more time and energy than it should have!

Went back and picked to do it with tutorials instead. Oddly, they don't start with adding the play button (although on previews the play button is already there?) They instead ask the students to just play an audio file no matter which item on the ListView is clicked.

I can't quite focus as my brain is still trying to figure out how to place the play button. NOW I have it onscreen atleast, but it looks bad as it's another different square. It should just be floating on top of (overlay?) to the block of list item.

### R1D5
Hello RelativeLayout! I was able to get the play icon how I want it. I briefly thought of using RelativeLayout yesterday, but maybe there was another way without nesting another layout.

To test setOnItemClickListener, I first tried to do the above (set it to play one audio no matter which item was clicked). After some trial and error yesterday and today, I was able to do it!

Next up, setting each audio file to the correct word and playing the appropriate audio on item click.

### R1D6
I did it! In the Word class, I added a constructor with and int parameter for the raw resource ID. In the Activity, I added the appropriate raw resource ID to each initialization of my Word class. 

Then the tricky part was adding an event listener, set/onItemClick. I don't quite understand where it's getting the parameters (AdapterView parent, View view, int position, long id) from, but it should be explained in the Udacity videos. From there it was easy enough to call MediaPlayer.create() and start().

Implemented code changes to all the activites I had (different categories). After watching the Udacity walkthrough, I learned I could also use **get** for ArrayLists, instead of getItemAtPosition and typecasting the return value to Word. Kept both expressions in my code as a reminder.

### R1D7
Tried out Android Studio's auto-generated toString() method for the Word class.

Learned about async callbacks, went back to the mini audio player to display a Toast message after audio is finished playing. Spent a little time wondering why it wasn't working, realized had to include `show` to display message.
`Toast.makeText(this, "Song finished playing!", Toast.LENGTH_SHORT).show();`


### R1D8
### R1D9
### R1D10
### R1D11
### R1D12
### R1D13
### R1D14
### R1D15
### R1D16
### R1D17
### R1D18
### R1D19
### R1D20
### R1D21
### R1D22
### R1D23
### R1D24
### R1D25
### R1D26
### R1D27
### R1D28
### R1D29
### R1D30
