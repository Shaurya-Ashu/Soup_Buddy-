# soup buddy

**the world is ending!!** do you want to spend your last hours in *sadness*? in *despair*? in *anxiety*?  NO! so we introduce soup buddy! many people have been saying soup is evil 😭, but this is anti-soup propoganda! he is here to make you happy! 🥹
so we introduce soup buddy, which simply attaches to your laptop, if soup sees your sad, he will give you a big hug/slap to make u happy again! why on a laptop u ask? well, we know ull still want to be grinding all the ysws programs before u die, and we dont want to have sadness get in your way!

<img width="682" height="955" alt="image" src="https://github.com/user-attachments/assets/eb6235ea-dc9b-47fb-9576-3854f2e1c818" />

- todo: add updated zine
- also with the zine, need to add images of the finished project + wiring or a 3d model with the screen added.

## demo here
https://demovideo.com/67

TODO: finish this...

## pictures

some pictures here....
<img width="1685" height="744" alt="image" src="https://github.com/user-attachments/assets/1502ff50-eba9-4df5-9537-d8a78847cf34" />

- upclose of the wiring

## schematic

TODO add the wiring schematic
- just do it in a website or something and just show the connections.

## firmware

found in the firmware folder

## so how does this project work?
- there are 8 possible emotions that soup can detect (using your laptop webcam)
- if soup sees you are sad
- then come up to the laptop as you are about to get slapped/hugged (which ever way you want to look at it 😜)
- if your happy, then soup is happy! and just continue with what you're doing being happy!

## the technical bits
- a pretrained vision model from hugging face is used, that has a range of 8 emotions trained on
- then in order to move each arm we have do servos that they can move on, allowing for a wide range of motions
- these servos run on an esp32 (xiao-esp32-s3)
- the esp32 communicates via your laptop webcam by USB!
- the stand on the laptop consists of a rubber band mechanic, which means that the stand is flexible for different laptop sizes!

## assembly instructions
- first print off the cad model
- then put the 2 servos in their correct place on either arm
- then solder on all the components, matching that of the schematic diagram
- connect via usb to your computer
- load up the 3d model so soup can actually understand and react to your facial expressions!
- attach the rubber bands to the clamp mechanism
- then clamp onto the side of the laptop
- place the electronics part in the right place (in the soup head cut out bit!)
- then you should be good to go!!!
