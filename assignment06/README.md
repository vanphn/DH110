# Assignment 6: Interface Design
Vanessa Phan | DH 110 | Spring 2022


## Project Summary
With my project, I aim to create a music learning platform capable of providing direct and accessible resources and connections for beginners. Originally a website, my redesigned app will make it more convenient for users to access information with their mobile devices, allowing for learning to happen anywhere at any time. 

The purpose of this interface design is to refine previous low-fidelity prototype into a digitized design that is optimized for user control, comfort level, and decreased cognitive load. This includes tending to proper spacing, graphics, layout, consistency, typography, etc. to ensure that the user can seamlessly interact with the product. 

First, I began by analyzing and thought about changes to my example wireframe. The link to the digitized wireframe can be found [here](https://whimsical.com/dh-a5-9QYvVVPojsS7JtwnCEQJCK). 


## Design System

<img width="749" alt="Screen Shot 2022-05-14 at 3 14 34 AM" src="https://user-images.githubusercontent.com/63387277/168421561-eb5a0b63-b182-42ac-b647-40f78824bd32.png">

### Typographic Variation
I decided one three different fonts for my design:

1. Poppins: After a bit of researching, I found that Poppins and similar typefaces are often used in mobile and desktop design for its simplicity and clean finish. Because it is used so prevalently in the design world, I thought that it would create familiarity for users.

2. Barlow: Like Poppins, this typeface is simple and easy to read. I chose this font because of its slimmer appearance, which resembles the typeface of the original site. Part of my thinking is that I wanted users to relate the app to the original website design. 

3. Chalkboard. This is a fun typeface and is more whimsical than the other two. I thought it would be worthwhile to test a typeface that is more exciting to remind the users that learning music should be fun. In the end, I decided against this typeface because it reminds me too much of comic sans, which looks a little too unprofessional in my opinion

<img width="941" alt="type variation" src="https://user-images.githubusercontent.com/63387277/168421576-24a4388f-6594-4ef2-95c8-ad09b468b6a0.png">


I made slight changes to the font sizes of each of the typefaces since some vary in sizes. The font sizes were chosen according to the human interface guidelines [listed by Apple](https://developer.apple.com/design/human-interface-guidelines/ios/visual-design/typography/). In the end, I decided to proceed with Poppins since it is simple and easy to read yet still looks and feels casual and fun. This font family will be the only one I used throughout my design. 


### Shape Variation
Since sharp square designs tend to look and feel outdated compared to more modern designs, I know that I wanted to add more roundness to the features of apps which were missing in the original website’s design. I tested three different variations for the shape of my components.

1. Angled: this iteration consisted of mostly sharply angled corners which resembled the original site the most. However, I did keep the corners of some chips rounded to break up the harshness of the angled corners. 

2. Rounded: I fully utilized the round corner features in almost all components in this version. While this design seems very friendly and fun, it doesn’t look as professional and cohesive as the other designs in my opinion. I noticed that the rounded corners of the posts tend to look more like dialog boxes than discussion posts. I wanted to draw the most attention to this section of the page, so it was important that the post remain somewhat angled (since sharp corners signal danger and alert our attention). 

3. Hybrid: In this version, there is a compromise between the roundness and angled corners. The angles are 50% less round than the rounded version of the design. The posts are also minimally rounded so that they don’t compete with the rounded corners of the navigation bar. The “new post” button is also slightly rounded so that users know that they can interact with it whereas the sharp angle version feels like a reminder or announcement. 

In the end, I found that the hybrid version worked best for my design. The elements are arranged according to the grid (I used 4pt) so that the posts are 8pt apart.  also added drop shadow (level 5 depth) to some of the choice chips during this process to make it look more cohesive 

<img width="920" alt="shape var" src="https://user-images.githubusercontent.com/63387277/168421597-3b68f6af-ac32-4dcb-a39a-fad8c221043a.png">

### Color Variation
For the color palette of the app, I decided to do a variation of the original website color by opting for a slightly less vibrant green as my primary color. I then picked a more blue-ish variant of that color as my secondary (this is because I thought the colors blended nicely together as a gradient since they belong to the same color family). I had to change the hue of the green and blue/green colors several times until they were in accordance with the WCAG compliant. For the dark mode color scheme, I slightly lowered the shade of the primary colors so they do not clash with the dark background. I then checked the contrasts for all other components such as buttons and navigation. 

<img width="828" alt="color variation" src="https://user-images.githubusercontent.com/63387277/168453985-7adcbd24-dc28-4bf8-b60f-31e7091f2942.png">

### Impression Test
#### Summary
Typography
* Chalkboard font seems too bold and jarring
* Prefers a mix between the Poppins and Barlow font: liked the Poppins font for header and Barlow for body text because it is easier to read

Shape
* Thought that the sharp corners are jarring, prefers the rounded shape design
* Prefers the rounded shapes to still have some rectangular features
* Enjoys the drop shadow of the button chips

Color
* Reminds the users of the dark/light theme of IOS platforms
* Users did not enjoy the color scheme of the dark feature -- the dark green feels too heavy
* The dark mode does not show the drop shadow of the chip button, which was a feature that the user liked.
* The gradient of the buttons and title were too harsh

The link to the impression test can be found (here)[https://drive.google.com/file/d/1u9JUqpM7mBD-YjOrjTEErU-vjLnqKBaL/view?usp=sharing]


### Final Design and Summary
After the impression test, I reviewed the notes I got from my interviewee and made some changes that I thought was most important: 
* I decided to incorporate two font faces in my design. I chose Poppins for the headline and buttons since it was bold and eye-catching. Barlow was used for the body since it was easy to read and most similar to the typeface of the original site (this helps keep some continuity between the website and the app)
* The background color for the dark theme was changed from a dark forest green to a more neutral black/grey so it is less jarring for the user
* A slight drop shadow was added to the dark theme
* The gradient was made less drastic and changed from vertical gradient to horizontal gradient. The colors of the headline were changed from gradient to solid.

The link to the final design can be found [here](https://www.sketch.com/s/986a40d0-0d1c-4be2-926f-f61a547e44e0/p/3951C7BF-9D7D-476B-B9E9-50BFD24911D3). 

<img width="837" alt="Final design" src="https://user-images.githubusercontent.com/63387277/168453993-fb2b3dee-c954-4095-a278-cddf545c9720.png">

Overall, I had a very fun time during this process and seeing all my research applied to a prototype. I designed this portion on Sketch instead of Figma and it was definitely a learning curve. I quickly found that it was very necessary to keep track of all the layers with proper layers to help ease editing later on (this will probably also help developers in the process). It was very helpful to get feedback from someone else when designer since I did not realized how deep I was in my head when designing that I did not notice where parts of my design were not cohesive (such as the dark theme background color). 
