---
layout: default
---
# My Projects
* * *
[_**2018.5 R&D of a Multi-finger Prosthetic Hand**_](https://www.youtube.com/watch?v=pflYb0izIks)

	This is a self-designed myoelectric controlled prosthesis. 
The sEMG is collected from the right stump limb by a MYO, the left limb is attached with a vibrator which indicated the force and hand aperture information. 
The total training time is less than 20 min, this video showed great stability compared with the state of art in pattern recognition based prosthesis.

![Multi-Finger_Hand](./picture/Multi-Finger_Hand.png)
* * *
[_**2015.3 R&D of a two-wheeled motorized personal vehicle**_](https://www.youtube.com/watch?v=EZ2f1EtyZls)

	After the Freescale cup car racing competition, my tutor suggested building a two-wheeled car for carrying a person, just like segway. 
I bought the mechanical framework and two DC brush motors, but the remaining I need to figure out by myself. 
	
	This was also my first time to design both the software and hardware. One of the core issues is the design of motor driver. 
I built a full-bridge MOSFET for driving DC brush motor. At the beginning, the MOSFET are easily burnt out, I dived into the principle of circuit and changed many plans, but producing little effect.

	After asking my engineer uncle and a warm-hearted friend Slloyd, I adjusted the weight distribution of the car, making it much balanced between front and back.
Then I added a reliable heat dissipation on all MOSFET (this is also my first moment to realize the importance of heat dissipation), It finally worked normal.


![Segway](./picture/Segway.png)
* * *
[_**2014.7 R&D of CV based autonomous two-wheeled car**_](https://www.youtube.com/watch?v=Ga9hf_LiJlc)
	In the summer of 2014, when I was a second-year undergraduate student, I took part in a national competition where every school designed a little car that can autonomously driving along the road. 
Cars are mainly divided into three groups, each year the organizer would set some rules to increase difficulties. We were the group of CMOS camera based two-wheeled car, the other two groups are linear-CCD 
based four-wheeled car and electromagnetic based four-wheeled car.
	
	In this project, I was in charge of the balance control and speed control of the car. I dived into it from Nov 2013 to July 2014, knowing how to use PID, and how to program the Freescale MCU for peripherals interaction. 
Meanwhile, I obtained many truths from numerous failures. The most impressive I always remembered was that a two-wheeled car with lower gravity center, lighter weight and more powerful motor, is much easier to control, so a good mechanical design relieves much pressure from control algorithm.

![Freescale](./picture/freescale.png)
<!--
[^_^]:
	Text can be **bold**, _italic_, or ~~strikethrough~~.

	[Link to another page](./another-page.html).

	There should be whitespace between paragraphs.

	There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

	# Header 1

	This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

	## Header 2

	> This is a blockquote following a header.
	>
	> When something is important enough, you do it even if the odds are not in your favor.

	### Header 3

	```js
	// Javascript code with syntax highlighting.
	var fun = function lang(l) {
	  dateformat.i18n = require('./lang/' + l)
	  return true;
	}
	```

	```ruby
	# Ruby code with syntax highlighting
	GitHubPages::Dependencies.gems.each do |gem, version|
	  s.add_dependency(gem, "= #{version}")
	end
	```

	#### Header 4

	*   This is an unordered list following a header.
	*   This is an unordered list following a header.
	*   This is an unordered list following a header.

	##### Header 5

	1.  This is an ordered list following a header.
	2.  This is an ordered list following a header.
	3.  This is an ordered list following a header.

	###### Header 6

	| head1        | head two          | three |
	|:-------------|:------------------|:------|
	| ok           | good swedish fish | nice  |
	| out of stock | good and plenty   | nice  |
	| ok           | good `oreos`      | hmm   |
	| ok           | good `zoute` drop | yumm  |

	### There's a horizontal rule below this.

	* * *

	### Here is an unordered list:

	*   Item foo
	*   Item bar
	*   Item baz
	*   Item zip

	### And an ordered list:

	1.  Item one
	1.  Item two
	1.  Item three
	1.  Item four

	### And a nested list:

	- level 1 item
	  - level 2 item
	  - level 2 item
		- level 3 item
		- level 3 item
	- level 1 item
	  - level 2 item
	  - level 2 item
	  - level 2 item
	- level 1 item
	  - level 2 item
	  - level 2 item
	- level 1 item

	### Small image

	![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

	### Large image

	![Branching](https://guides.github.com/activities/hello-world/branching.png)
-->