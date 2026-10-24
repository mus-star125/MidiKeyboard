# MidiKeyboard

<img width="859" height="657" alt="Screenshot 2026-10-24 1 48 07 PM" src="https://github.com/user-attachments/assets/27fa569a-4611-42af-b71e-d2f56bf2f948" />


## Whats a midi keyboard and why are you making it?
A MIDI keyboard is a device that lets you create and control music using keys. Instead of producing sound by itself, it sends MIDI signals to a computer or another device that can turn those signals into music.

I'm making my own custom MIDI keyboard as a hardware project for half-life week 3. I felt that this was a unique build,  a project to test my limits like, learn how keyboards work, and get more experience designing my own PCB.

## How does the keyboard work?
The keyboard work by pressing one of the keys and sending the info of the key through the MPI
Key press: When a key is pressed, the keyboard detects the input.

Microcontroller: The microcontroller processes the key press.
MIDI signal: The keyboard sends a MIDI message containing information about the note.
Computer: A computer or music software receives the MIDI message.
Sound: The software turns the MIDI information into an actual sound.

*MIDI doesn't contain the actual audio. It communicates information about notes and other musical controls.*

## devlogs

**DAY 1:**
 just started the project, its already way easier because we did PCB's in week 1 but also the guide is crystal clear! I acutally enjoyed and technically just started the schematic sketch.  Also it's the first time iim kinda changing the instructions I'm using XIAO instead of Waveshare so i'd consider that a win! Anyways, its going pretty well so far! *hah I spoke to soon*
 
 

 **DAY 2:**
 today i finished the schematic up, and used my brain to wire it all. its was pretty hard but i got it and im debating whether i should add more keys or just leave it at 7. My project is quite different from the guide but i hope it works just as well! *im still in the air btw*

 **DAY 3: The reality check**
 I finished the first pcb but then i realized its not going to work (AT ALL) and had to redo the whole schematic again :( but i finished remaking the schematic and am going to start my PCB tommorow (YAY!) we will see how that goes. here are some pic updates!

 **DAY 4:**
 I completely restarted everything  from the beginning because I messed up and nothing was working, and its still not working and i think im a bit burnt out so i will take a break and finish it up someone 
I kept missing things from my schematic, like the Xiao wasnt importing, anyways i redid it for the third time (the schematic) and changed my U1 to waveshare becasue I was soo confused at this point
 
 **DAY 5:**
 i finally got it, my mistake was very silly. I kept forgetting to save. Once I realised this i was so annoyed at my mistake lol. Anyways thats how we learn :) I made my footprints circles but am not sure if they are going to work or not

I finished the schematic but was struggling with the footprints at this point and just couldn't figure out how to make it like piano key whihc I ended up turning into circles in the (kinda shape) of a flower

## Lessons
This project taught me that things don't always work the way you expect them to, especially when you're designing something yourself.

I had to redo my schematic multiple times because I kept missing things, and I learned the hard way that forgetting to save can cause a LOT of unnecessary frustration.

I also learned that it's okay to change your original design. I started with the idea of making piano keys, but when I couldn't figure out how to create the footprints properly, I decided to experiment with a different layout.

The biggest lesson for me was to save my work regularly, double-check my schematic before moving on to the PCB, and take breaks when I'm getting frustrated instead of repeatedly restarting everything.

Even though I had to redo a lot of things, I learned more from the mistakes than I probably would have if everything had worked perfectly the first time.

I'm still figuring things out, but that's part of the process!

## Bill Of Materials (BOM)
