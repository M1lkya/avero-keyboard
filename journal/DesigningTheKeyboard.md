# Keyboard Design — Devlog

Time Spent: 4 Hours 3 Minutes 34 Seconds
Date: 07/21/26

Today I worked more on my keyboard design and figured out some of the features I wanted to add.

Some of the things I wanted were:

* A mini OLED screen that could show things like what music is playing or what keyboard profile I'm using.
* A way to switch between languages and have the active language show up on the OLED screen.
* A few macro buttons that I can customize to do whatever I want, like opening apps or doing other things quickly.

## First Attempt

At first, I tried designing my keyboard in a drawing program, but honestly, it didn't turn out that great. It looked pretty rough and wasn't really that professional. It was mostly just me figuring out what I wanted, and I ended up changing a lot of the ideas anyway.

![First keyboard sketch in krita](https://github.com/M1lkya/avero-keyboard/blob/main/journal/photos/FirstDesignSketch.png)

## Moving to Figma

I decided to switch to Figma because I could make the design look a lot cleaner and more professional.

At first, I wanted to make a 65% keyboard with the mini OLED screen angled out from the back. The idea was that you wouldn't have to look over the keyboard just to see the screen. Unfortunately, it ended up looking pretty ugly, and it also wouldn't work well with the PCB, so it wasn't really practical.

Then I tried making the keyboard flat and putting the screen next to the keys, but that didn't really work either.

Eventually, I decided to move away from my original 65% design and add a full function key row. I added all 12 function keys, an extra macro key, and put the OLED screen in between F12 and the macro key. This actually ended up looking pretty good while also being practical.

After that, I had a really hard time figuring out where to put the Raspberry Pi Pico. I've never designed or built a keyboard before, so I wasn't really sure how it was supposed to fit inside. I thought about making the keyboard have multiple layers, but that seemed like it would make things way more complicated than they needed to be.

I looked through the KEEB documentation and saw that the Pico was placed on the same level as the key switches. I couldn't really do that with my design without completely messing up the layout, so I decided to add an extra section sticking out from the left side of the keyboard where I could put the Pico.

I also had to give up on my original idea of having a low-profile USB-C connector on the left side. Since I can't place the Pico horizontally, I'm just going to use the regular USB-C setup instead.

## Final Design(for now)

![Final keyboard design](https://github.com/M1lkya/avero-keyboard/blob/main/journal/photos/Keyboard%20Top%20Design-Retro.png)

## Things Not Visible in the Design (Yet)

There are still a few things I want to add that aren't really shown in the design:

* Clicky switches that make a really loud noise. I just love the feeling and sound of typing on a loud keyboard, and honestly, I feel like it makes me more productive.
* RGB lighting, which I couldn't really show in the design mockup.
* Possibly flat keycaps — I'm still deciding on this one.
* Different keycap themes that I can choose from. I haven't fully decided on them yet, but I already have a favorite.
