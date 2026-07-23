# Servo-Actuated-Bionic-Eyes #

A pair of model eyes which pivot and rotate via linkages, in the x and y axis. This will mimic real eyes following a person. If time permits, I could also try training my own simple convolutional neural network on tensorflow or pytorch. My goals of the project are for the relationships to be simplistic and easy to replicate and for it to achieve a somewhat lifelike look. 

```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Leo N | Amador Valley | Mechanical Engineering | Incoming Freshman

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

went through 3 different open source CNN models -- two found on open source Edge Impluse platform built on base model FOMO (Faster Objects More Objects), not accurate enough -- many variables, like lighting, resolution, etc that cannot be altered, had to pivot to an older, better documented CV model, Haar Cascade, but delivers on reliablity. 

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

After four physical iterations of my design, I finally ended up with one I was satisfied with. My first few versions had a few unplanned additions, like for instance, washers between the eyelid screw joints that act like spacers in order to prevent friction between the two 3D parts. I had to use wood screws to tap the 3D printed holes for the M2 screws to thread at all, and at the end I realized that the eyelids could be smaller in order for the whole assembly to have a more realistic feel (although I left this challenge for later). I discovered numerous clearance and tolerance issues as apart of my first few assemblies, which were easy but tedious fixes. I was definitely caught off guard with the amount of time I would spend on the blinking motion (around 2-3 days) in which I went through a lot of struggle. After a lot of tinkering with the 3D printed linkages I was planning to use, I came to the realization that I would have to use another design, which ultimately was the right choice. One of my favorite parts of this milestone's period was when I fixed a recurring issue with a passive and simple solution. I was having trouble balancing the eyelids on the screw joints, in which they would slide or push each other off and ruin the blinking. I experimented with fastening washers to the ends of the joints when I found a novel solution which would indirectly fix the sliding. For the eyelid to slide off the joints, the opposite side of the lid joint part would have to have enough clearance to slide as well. If I could obstruct the other joint from moving towards the end of the joint, then I could inversely stop the sliding. Thus, I used two nuts on the ends of the joints as a way to passively fix the sliding. These types of satisfying solutions are why I find mechanical engineering so fascinating. My next steps will be integration my hardware with the software. 



- two physical versions
- v1 had a few unpalnned additions:
- washers between eyelid screw joints as spacer-type may add washer between two eyelids to prevent from friction
- wood screws to tap 3d printed holes for the m2 mounting holes
- put together v1 and found out:
- changes to eyelid size for more realistic
- discovered clearance issues between servos & eyelid-linkage issues which are easy fixes
- servos are not a tight fit - must add M2 mounting holes 
For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

# First Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

My project is a servo-driven system which imitates the human eye. The mechanism consists of a series of simple linkages which allow for pitch, roll, and blinking motions. Most of the parts were custom designs and 3D printed. They are joined by M2 and M3 screws, although wood screws may be needed to tap the screw holes. As of now, I have a complete assembly with all the necessary parts for a physical version of the model. I faced many challenges with the CAD. I went through three design iterations using different joints, like the universal joint. However, these designs were bulky and ineffective, so I pivoted to a ball-joint for the movement of the eyes. I created custom housing for the servos and balljoint, which led me to my second challenge, which was tolerances. It took a lot of prototyping to achieve a rigid or rotating relationship between two 3D printed parts with the printers at BlueStamp, and adjusting the assemblies once I had the tolerances figured out was a tedious and frustrating process. I also ran into clearance issues with my balljoints: Once I simulated the motions of my mechanism in the assembly, I realized I could not use a spherical eyeball in spherical eyelids. Instead, I pivoted to a mesh eyelid design that proivded clearance for the pitch and roll movements. Through this trial and error, I learned necessary skills in CAD, like how to properly assign joints in assemblies and how to work with mesh and curved bodies. I plan to complete a full physical version, revise my CAD in case of tolerance or clearance issues, and then experimenting with the integration of a vision model (either CNN or kNNs).

# Schematics 

## CAD

### CAD Prototypes - 

### V1-1 - Universal Joint
<img width="564" height="624" alt="design iteration 1 1" src="https://github.com/user-attachments/assets/0456477b-895d-4367-b48c-4a0380ddaf93" />

### V1-2 - 3d printable
<img width="432" height="402" alt="Screenshot 2026-07-02 at 9 43 00 AM" src="https://github.com/user-attachments/assets/189173cd-d25f-41a6-a040-cd8cceea0cb7" />

### V2 - Ball Joint
<img width="318" height="410" alt="Screenshot 2026-07-02 at 12 21 08 PM" src="https://github.com/user-attachments/assets/23b09bd0-9b5b-4942-8e2a-34c448b49650" />

### V2 - Ball Joint Assembly 
<img width="518" height="459" alt="Screenshot 2026-07-06 at 12 22 20 PM" src="https://github.com/user-attachments/assets/161c9bf3-ff01-4e5b-b465-c3eb82926428" />

### V2 - Ball Joint Eyelid Assembly
<img width="438" height="409" alt="image" src="https://github.com/user-attachments/assets/1d928edc-2352-4ac5-b89a-fb74b36f5999" />

### V2 - Ball Joint Assembly - clearance issue
<img width="360" height="321" alt="Screenshot 2026-07-08 at 12 20 06 PM" src="https://github.com/user-attachments/assets/d390e336-4aed-41a3-808c-6ddcaa4100b3" />
<img width="250" height="298" alt="Screenshot 2026-07-08 at 12 20 23 PM" src="https://github.com/user-attachments/assets/fcdef343-da75-45cd-bc67-b3d63daeb2c3" />
<img width="278" height="276" alt="Screenshot 2026-07-08 at 12 20 29 PM" src="https://github.com/user-attachments/assets/3ca1b02f-cc93-4dd8-a53f-d06d7602f2a0" />
As you can see, the eye does not fit into the eyelids with this version-- it either needs more clearance or a fitting shape. 
# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

|:--:|:--:|:--:|:--:|
| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Pi Zero 2W | MCU | $40.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> 
|:--:|:--:|:--:|:--:|
| 2 MG90 servos | Drives mechanism | $8.88 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> 
|:--:|:--:|:--:|:--:|
| Acrylic Eyeballs | Mock eyes for realisms | $7.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> 
|:--:|:--:|:--:|:--:|
| Joystick | Manual control for mechanism | $6.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> 
|:--:|:--:|:--:|:--:|
| Breadboard | Prototyping electronics | $6.83 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> 
|:--:|:--:|:--:|:--:|
| M3 screws, bolts & nuts | Joining 3d printed parts together for a final product | $7.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> 
|:--:|:--:|:--:|:--:|
| 6V - 4 AA battery supply | Power source for servos | $4.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> 
|:--:|:--:|:--:|:--:|
| Perfboards | Final draft of electronics | $4.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> 
|:--:|:--:|:--:|:--:|

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)
