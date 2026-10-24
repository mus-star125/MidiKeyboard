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

 <img width="765" height="698" alt="Screenshot 2026-10-20 7 22 49 AM" src="https://github.com/user-attachments/assets/908defba-af0b-49b0-8fc2-11d5bba91453" />
<img width="1880" height="908" alt="Screenshot 2026-10-19 10 07 08 PM" src="https://github.com/user-attachments/assets/503951bc-9449-4710-8c8f-d51a473a5a8c" />


 **DAY 4:**
 I completely restarted everything  from the beginning because I messed up and nothing was working, and its still not working and i think im a bit burnt out so i will take a break and finish it up someone 
I kept missing things from my schematic, like the Xiao wasnt importing, anyways i redid it for the third time (the schematic) and changed my U1 to waveshare becasue I was soo confused at this point

<img width="1157" height="836" alt="Screenshot 2026-10-20 10 57 58 PM" src="https://github.com/user-attachments/assets/c321b898-6674-4de3-8ea8-8c302e013724" />
<img width="576" height="597" alt="Screenshot 2026-10-21 7 57 20 PM" src="https://github.com/user-attachments/assets/61aa348a-f32f-4e6a-a53e-02522ba2969d" />
<img width="1442" height="872" alt="Screenshot 2026-10-22 8 30 05 PM" src="https://github.com/user-attachments/assets/71954dc7-7553-48c4-ad7e-45bb0fab0964" />

 
 **DAY 5:**
 i finally got it, my mistake was very silly. I kept forgetting to save. Once I realised this i was so annoyed at my mistake lol. Anyways thats how we learn :) I made my footprints circles but am not sure if they are going to work or not

 <img width="907" height="519" alt="Screenshot 2026-10-24 10 37 45 AM" src="https://github.com/user-attachments/assets/62f8192c-686d-441f-bf45-880509da4fd0" />

I finished the schematic but was struggling with the footprints at this point and just couldn't figure out how to make it like piano key whihc I ended up turning into circles in the (kinda shape) of a flower 

<img width="936" height="694" alt="Screenshot 2026-10-24 10 05 23 AM" src="https://github.com/user-attachments/assets/13d7f1c2-5daf-487f-a793-285b23fbeb44" />


**DAY 6: LOCKK IN AND FINISH!**
As you can guess, today is day 6, I<img width="728" height="678" alt="Screenshot 2026-10-24 1 06 33 AM" src="https://github.com/user-attachments/assets/ea3bd2c9-f0a7-46ca-ac6b-440bd065e0cd" />
 spent 2 hours perfecting i did the wiring and deleted on of the flowers cuz it WAS NOT wirin. I also uploaded all the files on github and did my readme, yoo i still gotta do the BOM 

<img width="859" height="657" alt="Screenshot 2026-10-24 1 48 07 PM" src="https://github.com/user-attachments/assets/2792a5c8-ec51-4147-9e73-ebb40e0a5c13" />
<img width="900" height="652" alt="Screenshot 2026-10-24 1 48 21 PM" src="https://github.com/user-attachments/assets/d4bc5c28-16bb-4e4c-a47e-e04461de650d" />


## Lessons
This project taught me that things don't always work the way you expect them to, especially when you're designing something yourself.

I had to redo my schematic multiple times because I kept missing things, and I learned the hard way that forgetting to save can cause a LOT of unnecessary frustration.

I also learned that it's okay to change your original design. I started with the idea of making piano keys, but when I couldn't figure out how to create the footprints properly, I decided to experiment with a different layout.

The biggest lesson for me was to save my work regularly, double-check my schematic before moving on to the PCB, and take breaks when I'm getting frustrated instead of repeatedly restarting everything.

Even though I had to redo a lot of things, I learned more from the mistakes than I probably would have if everything had worked perfectly the first time.

I'm still figuring things out, but that's part of the process!

## Bill Of Materials (BOM)

## Bill of Materials (BOM)

This is the current bill of materials for my custom MIDI keyboard. Since the design is still in progress, some components, quantities, and prices are yet to be confirmed.

| Component | Quantity | Purpose | Price |
|---|---:|---|---:|
| Waveshare microcontroller board | 1 | Processes key inputs and handles MIDI communication | $16.78 |
| Key switches / buttons | 7 | Detect which keys are pressed | $1.71|
| Custom PCB | 1 | Holds and electrically connects the components | $5.20 |
| Other electronic components | TBD | Additional components required by the final circuit | TBD |

**Total estimated cost:** 


**(MORE PHOTOS IN THE IMAGES!)**
