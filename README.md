# Fight-or-Flight

### Gamified VR Simulator for Acrophobia and Arachnophobia Exposure Therapy


VR fear-oriented project, called ​Fight-or-Flight,​ which presents a training platform that will expose its audience to two most common phobias (arachnophobia and acrophobia) in order to slowly eliminate the fear. It will allow the therapists to control the environment entirely, making VR extremely convenient. A medium between reality and simulation, it will allow battles with phobias in a safer way.

### Team:
Adilet Majit (adilet@nyu.edu, github: adyoka)

Amina Kobenova

Sayazhan Sagynay


---

#### Table of contents:
* [Why VR?](https://github.com/adyoka/Phobia-VR-Exposure#why-virtual-reality)
* [Objectives](https://github.com/adyoka/Phobia-VR-Exposure#project-objectives)
* [Overview](https://github.com/adyoka/Phobia-VR-Exposure#project-overview)
* [Installation](https://github.com/adyoka/Phobia-VR-Exposure#installation)
* [Tech](https://github.com/adyoka/Phobia-VR-Exposure#tech)


---


#### Why Virtual Reality?
In attempt to treat various fears, modern medicine borders with Virtual Reality, which has great medical potential according to Chris Brewin, a professor of clinical psychology at University College London. Practicing a technique called exposure therapy, experts make patients gradually and consistently face a specific fear. Most studies agree that patients are substantially more comfortable with virtual reality immersion treatments. They promote clinical interaction and medication adherence. Simulating a fear exposure, the user is able to explore the roots of the phobia within the constraints of VR.Virtual reality provides many benefits, such as: accessibility, privacy, facilitation of care, patient safety, financial gain, and more:
######  ● Enhanced security
Virtual Reality Exposure means introducing the patient to a virtual environment that includes the expected stimulus instead of placing the patient in a real environment or making the patient visualize the stimulus. The actual environment can be unpredictable. The therapist controls the virtual environment by means of the computer keyboard, ensuring exposure to the programmed situations.
###### ● Better Treatment and Simple Scheduling
Deliberately designed to support anxiety disorder exposure therapy, the VR software and virtual environments models provide more efficient treatment along with the convenience of scheduling. As it usually requires leaving the office of the therapist and consequent extended sessions, Standard exposure therapy can be very expensive. Within the standard therapy hour (usually 45-50 minutes) and within the confines of the therapist's office, virtual reality programs can achieve the same exposure. In the same week, multiple sessions may be scheduled.

###### ● Limitless interactions of distresses
Having VR allows the therapist to monitor ultimate stimulation for optimal viewing. For example, only one take-off and landing per flight is bound by real-world limitations.VR training helps the therapist to thoroughly manipulate conditions, such as landing the digital aircraft, in order to best match the patient.


### Project Objectives:
* To take advantage of VR as potentially an extremely powerful tool for the psychiatric community.
* To utilize up-to-date modern technologies to benefit its creators.
* To create a sense of presence for total immersive experience.
* To use our current skillage to attempt to tame one of the most ever-lasting problems of
medicine and psychology.
* To provide patients with a strong feeling of enhanced security to stimulate the clinical
progress.
* To showcase the feasibility of implementation and of search of solutions to eliminate
phobias for various groups: college students, teachers, graduate school students and even
high school students.
* To learn a cross-platform game engine - Unity 3D engine.
* To master the application of Oculus Rift VR platform.
* To acquire a knowledge of a general-purpose programming language - C#.



---


### Project Overview
Our application mainly consists of three scenes: a menu from which the user selects a feared phobia and two phobia scenes-acrophobia and arachnophobia respectively.

**Menu Scene**

This scene's aim is to get a user choice and then move the user to a chosen scene.

![Menu Scene snapshot](https://github.com/adyoka/Phobia-VR-Exposure/blob/master/img/menu-screen.png)

**Game 1​ — Acrophobia Scene**

The goal was to make a virtual reality where the patient faces his/her fear of heights to overcome acrophobia in the most challenging way - by walking down high-altitude tightrope.
We took an intimidating picture for the basis of a woman walking down the rope at an altitude and simulating her surroundings and conditions.

![Idea](https://github.com/adyoka/Phobia-VR-Exposure/blob/master/img/idea.png)

![Game 1 Scene snapshot](https://github.com/adyoka/Phobia-VR-Exposure/blob/master/img/game1.png)

![](https://github.com/adyoka/Phobia-VR-Exposure/blob/master/img/game1-1.png)


**Game 2​ — Arachnophobia Scene**

The goal was to create an environment of virtual reality where the user is constantly surrounded by large spiders; wherever the user goes, spiders move around him/her.


![Game 2 Scene snapshot](https://github.com/adyoka/Phobia-VR-Exposure/blob/master/img/game2.png)




### Installation


1. Choose a place on your computer for the project to reside and open a terminal to that location.
2. Execute the following git command: 
```sh
git clone https://github.com/adyoka/Phobia-VR-Exposure phobia-sim
cd phobia-sim
```

3) Find and Open Fight-or-Flight.exe.
4) In the menu, select a phobia.
5) Test your fear.

For acrophobia:
* Use ‘WASD’ keyboard OR allow the patient to walk by himself/herself.
* Walk along the tightrope; If user accidentally falls down the platform, the program will return
the user to the initial position.

For arachnophobia:
* Use ‘WASD’ keyboard OR allow the patient to walk by himself/herself.
* Walk around; wherever the user goes, spiders will follow and constantly surround him/her.


### Tech
* Scripts were written in C#

* Game scenes were developed in Unity 3D engine using Oculus Integration Package assets

