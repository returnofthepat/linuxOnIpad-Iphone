
# Video script(Self explanitory)

Hello, my name is Pat Quintana and my senior engineering capstone
project is a phone that runs linux. During this video I will be
discussing my design process, problems encountered, and more! I hope
you enjoy

## Software

The goal of this project was originally to modify a version of linux
and install it onto a iphone or ipad. The reason behind the project is
my desire to edit and run code on a portable device. Obviously a
computer would be faster, and is somewhat portable however it is
limited. I dove into researching this project and found a couple of
guides emulating linux onto a iphone using a raspberry pi and third
party apps. So I decided to pivot my goals to attempt to recreate
these guides with my own modification. All of the guides I found that
were attempting to emulate linux were using ipads and raspberry pi
4b's I didnt think this would present much issue. The biggest
modifications I made were using alternative apps instead of the
perferred apps and using a iphone SE. The first and most critical
issue I ran into was the SSH key. For those of you who are unfamiliar
with an SSH key its a way to have two devices securily communicate
with each other. When I was prompted for the password for the
raspberry pi I entered it and was told it was incorrect. I tried the
password 10 times, changed the password, tried connecting the SSH on a
different device, tried different operating systems and was still
unable to connect to the raspberry pi. I tried reconffiguring the SSH
key a few times, but again to no avail. Despite this project not being
succesful I believe is was still a great learning experience. I got to
learn more about SSH keys, different operating systems, and
networking.

## Next steps

My next steps for this project can be broken into two categories the
ideal approach and the realistic approach.

### Ideal approach

The ideal approach to solve this issue is to proceed with my original
plan. I want to rework a 32-bit version of linux to be installed
directly onto the iphone without the need for a raspberry pu or other
decie to helpo emmulate linux. onto the raspberry pi. This would
entail a lot more work but i belive it would be advantageous not
only for myself but for others who want to run linux on their iphone.
I would want to be able to dual boot iphone - os and linux onto the phone
so that the usability of the device would not be limited. Alternatively
finding a way to make a linux os for a phone would be increadibly
intersting and useful. This would mean that the phone would be able to
function as exactly that but also have the benefits on a laptop. So you
could make calls, work in the terminal, text, play games, etc. 

### Realistic approach

I believe a realistic approach to this would be understanding exactly
what went wrong with the SSH key past the surface level. I belive that
the setup would be fairly simple after getting through the SSH key
issue. Besides that I just need more time to have a realistic approach
to solving this issue.


## 3D modeling

One of my favorite parts of engineering has been 3d modeling and I wanted
to find a way to incorporate that into my project. So I thought about the
user interaction with the project. Carrying around a raspbery pi in your
pocket isnt the best idea for a multidue of reasons but it's also very
incovienent and uncomfortable. So I made a model and printed a custom case
to carry the raspberry pi and the portable charger that powers it. This was
challenging and a bit time consuming but seeing a succesful print of the
case restored my hope for my project. The current itteration of the case is
a little chunky and will be need to be carried in cargo shorts, but it leaves
me room to improve and redesign to better fit the use case in the future.


## Conclusion

I want to reiterate how much I truly appreciate this
project. Althought it was frustrating and discouraging at times by
perservering through it I feel accomplished despite it not working
properly. All of the missed steps and frustraiting moments taught me
more than if I would've just coasted through this project. Please feel
free to ask me any questions that you may have and if you're interested
in looking at some of my other work please check out my github.


## Ad

Do you like iphones, do you like open source development? Hi, my name
is Pat Quintana and for my capstone project I attempted to combine
them both into a little something I call a Linux Phone. Using 3d modeling
and shell commands I tried my hand at creation. If this sounds intriguing
come and find me and Ill tell you more!