---
layout: default
---

# CS 294-277, Robots That Learn (Fall 2024)

## Logistics

UC Berkeley Course Number 34334

Time: Mondays 3-5PM

Location: Room 1203 @ [Berkeley Way West](https://maps.app.goo.gl/thh2ey5nUR7VsMFB8)

Instructor: [Jitendra Malik](https://people.eecs.berkeley.edu/~malik)

TA: [Toru Lin](https://toruowo.github.io/)

### [[Zoom link]](https://berkeley.zoom.us/j/92472805220?pwd=zzCeqo78fcf2nDiTQ0a6QgMhe6HZym.1)

## ~ Welcome from Jitendra ~

Robotics has been late to the deep learning revolution compared to computer vision and natural
language processing, mainly because "big data" is not so readily available. However significant
advances have been made in the last few years, and the purpose of this class is to present a
coherent framework for studying these advances.

My goal is to build machines that can emulate the remarkable capabilities of humans and other
animals at motor control, defined as connecting perception to action in the physical world. Hence
there will be a distinct preference for legs over wheels, multi-finger hands over parallel jaw
grippers, rich visual and tactile perception over minimal sensing, humanoid robots in the home
over specialist robots on the factory floor. The course itself will have three main parts (1)
biological motor control basics for inspiration (2) main paradigms for robot motor skill
acquisition (3) case studies of locomotion, navigation and manipulation.

### Prerequisites
This is a graduate level class, and prerequisite knowledge at the level of Deep Learning (Bishop
& Bishop), and Reinforcement Learning (Sutton & Barto) will be assumed.

**We have now closed class enrollment. [Here](https://docs.google.com/document/d/10Ue1Vnsc9asUhDXR-cOjPxOLiELoEtKu0GEJUaW3q4M/edit?usp=sharing) is a list of self-evaluation questions for interested students to see whether they are ready for the class.**

## Course Format

Each session consists of a two 1-hour lectures with a 10 minute break in between, i.e. 3:10-4 PM and 4:10-5PM. We will use notations A/B to denote the sub-sessions: e.g. Lecture 1A, 1B, 2A, 2B, ...

## Schedule

The following schedule is a tentative assignment and will evolve in real time. Weekly materials will be added.

* Lecture 1A (9/9) Introduction [[slides]](https://docs.google.com/presentation/d/1UKZNyoHFu8mWRt0XFhaX-5VzRanN-cjR/edit?usp=sharing&ouid=100618406782889124957&rtpof=true&sd=true)
* Lecture 1B (9/9) Biomechanics of walking and running [[slides]](https://docs.google.com/presentation/d/1f394PmuISnU3F_I7eluYVfl1ImPhnsZp/edit?usp=sharing&ouid=100618406782889124957&rtpof=true&sd=true)
* Lecture 2A (9/16) Robot mechanisms - kinematics and dynamics [[slides]](https://docs.google.com/presentation/d/1Qy1wLVB8vfIeROXJg6NoSIredIjrc8Eu/edit?usp=sharing&ouid=100618406782889124957&rtpof=true&sd=true) [[video]](https://drive.google.com/file/d/1qtep5QVViDW7rvdXWt7DLDgbIRbYVoop/view?usp=sharing)
* Lecture 2B (9/16) The human hand and dexterous object manipulation
* Lecture 3A (9/23) Robot hands [[slides]](https://docs.google.com/presentation/d/13oX9ucOYo4WkWkm9LX7lGhQKiZnyoHZV/edit?usp=sharing&ouid=100618406782889124957&rtpof=true&sd=true) [[video]](https://drive.google.com/file/d/12V3xa6jonkklXauQCIbwml4EQufg8E0_/view?usp=sharing)
* Lecture 3B (9/23) Proprioception and tactile perception [[slide]](https://docs.google.com/presentation/d/1RNP3zXqSS9H71bPs6zg-PV4iFkSwhrn4/edit?usp=sharing&ouid=100618406782889124957&rtpof=true&sd=true) [[video]](https://drive.google.com/file/d/12V3xa6jonkklXauQCIbwml4EQufg8E0_/view?usp=sharing)
* Lecture 4A (9/30) Vision for action [[slide]](https://drive.google.com/file/d/1Ly9pzqWH_R6SB9N6ZqCpiGK5TrYT0KnR/view?usp=sharing) [[video]](https://drive.google.com/file/d/1UwiBsTV5JqMENDkKWr0DlVFz3tcjgluW/view?usp=sharing)
* Lecture 4B (9/30) The developmental perspective on motor control [[slide]](https://drive.google.com/file/d/1_6jJp2tpgMV9Kobwbgp2jkpU9iS0c_sZ/view?usp=sharing) [[video]](https://drive.google.com/file/d/1R5TzzT34Em6ToH0-Kcd2jDnuxZh4Fs2e/view?usp=sharing)
* Lecture 5A (10/7) Robot dynamics, control, and motion planning [[slide]](https://drive.google.com/file/d/1zuBwmd1igHun76r41DAyx2BOw3qmmp9P/view?usp=sharing) [[video]](https://drive.google.com/file/d/1Lg_r7QsSusHigRSUO1e2zCRGOUsTmQvC/view?usp=sharing)
* Lecture 5B (10/7) Computational neuroscience perspective on prediction and control [[slide]](https://drive.google.com/file/d/1Pp8oCOdSTGlImExUWYk4AVVyOJwR1KOH/view?usp=sharing) [[video]](https://drive.google.com/file/d/1fofpZDHeFhAp3blPq54sZD1RGyNSZRRW/view?usp=sharing)
* Lecture 6AB (10/14) Reinforcement Learning
* Lecture 7AB (10/21) Behavior cloning
* Lecture 8AB (10/28) Visual Imitation
* Lecture 9AB (11/04) Case Studies in Locomotion
* Veterans Day (11/11)
* Lecture 10AB (11/18) Case Studies in Navigation
* Lecture 11AB (11/25) Case Studies in Dexterous Manipulation
* Lecture 12AB (12/2) Long horizon planning and the role of language
* RRR Week (12/9) Final Project Presentations

Please see below ("Reading Materials") for link to reading assignment submission form.

## Coursework

- 10% Weekly Reading Assignment
- 10% Lecture Scribing
- 30% Midterm
- 50% Final Project

**Weekly Reading Assignment**: For every weekly reading, each student should come up with 2 multiple choice questions, and supply with answers. We will send out a Google form for submission each week.

**Lecture Scribing**: For each lecture, two student scribes will organize lecture notes in LaTeX. The students can decide to submit a single note together or individually; grades will be assigned based on note quality. The lecture notes should be ready by the same Friday. Sign-up sheet [here](https://docs.google.com/spreadsheets/d/1TQzGYdRPp4Wtx0MXxJ19brMyj-wWIv6f1JznIZG42Lk/edit?usp=sharing).

*Note: since the lecture content does not necessarily align with lecture title, each scribe is only required to cover the time slot they have signed up for.*

**Midterm**: About two-thirds into the semseter we will have a mid-term exam based on questions sourced from the weekly reading assignments. One 8.5”x11”, double-sided cheat sheet will be permitted.

**Final Project**: Can be done in a group of 1-4. More details to come.


### ❗Assignment Deadlines
- Weekly Reading: 23:59PM PT, the Friday after assignment release
- Lecture Scribing: 23:59PM PT, the Friday after scribed lecture

## Background Materials

* [Deep Learning (Bishop & Bishop)](https://www.bishopbook.com/)
* [Reinforcement Learning (Sutton & Barto)](http://incompleteideas.net/book/the-book-2nd.html)

## Reading materials

### Lecture 1

#### Lecture 1B

- T. K. Uchida and S. L. Delp. Biomechanics of movement: the science of sports, robotics, and rehabilitation. Mit Press, 2021.
- P. Ramdya and A. J. Ijspeert. The neuromechanics of animal locomotion: From biology to robotics and back. Science Robotics, 8(78):eadg0279, 2023. [[PDF]](resources/Locomotion-biology-robotics-scirobotics.pdf)

(It is not expected to read the Uchida-Delp book, but we will cover a couple of chapters from it.)

### Lecture 2

[[Reading Assignment Submission Form]](https://forms.gle/2zMSe3yZd1P35VuQ9)

#### Lecture 2A

In advance of lecture 2A, students should try to familiarize themselves with how 3D rotations and translations are represented. We would like students to learn about "exponential coordinates" - how a rotation matrix is the exponential of a skew-symmetric matrix corresponding to the axis of rotation, and when rotation is accompanied by translation, we use the exponential of a twist. This formalism results in an elegant way to specify the forward kinematics of a robot using the product of matrix exponentials. The Li-Murray-Sastry textbook and the Lynch-Park textbook are good sources. You can find lectures on YouTube for Lynch-Park. I recommend the ones corresponding to Chapter 3.
[[link]](https://www.youtube.com/watch?v=29LhXWjn7Pc&list=PLggLP4f-rq02vX0OQQ5vrCxbJrzamYDfx&index=10)

#### Lecture 2B

- Video on human hand anatomy [[link]](https://www.youtube.com/watch?v=-y69D76RdMs)

### Lecture 3

[[Reading Assignment Submission Form]](https://forms.gle/XhSEZDLZrH7QNemg7)

#### Lecture 3A

- Piazza, Cristina, et al. "A century of robotic hands." Annual Review of Control, Robotics, and Autonomous Systems 2.1 (2019): 1-32. [[PDF]](resources/century-of-robotic-hands.pdf)
- [LEAP Hand](https://leaphand.com/), [LEAP Hand v2](https://openreview.net/forum?id=eQomRzRZEP)

#### Lecture 3B

- Jones, L. A. "Human hand function." (2006). [[PDF]](resources/Human_Hand_Function.pdf)
- Esther P Gardner, "Touch" (2010). [[PDF]](resources/Gardner-ELS2010.pdf)


### Lecture 4

[[Reading Assignment Submission Form]](https://forms.gle/c6MEzrEdSyzVqcpx9)

#### Lecture 4A

- Land, M et al. “The roles of vision and eye movements in the control of activities of daily living.” Perception vol. 28,11 (1999): 1311-28. doi:10.1068/p2935 [[PDF]](resources/teamaking-land-mennie-rusted-1999.pdf)

#### Lecture 4B

- Loquercio, Antonio, Ashish Kumar, and Jitendra Malik. "Learning visual locomotion with cross-modal supervision." 2023 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2023. [[PDF]](resources/ICRA23_Learning_to_see_by_walking_blind.pdf)
- Smith, Linda B. and Michael Gasser. “The Development of Embodied Cognition: Six Lessons from Babies.” Artificial Life 11 (2005): 13-29. [[PDF]](resources/6_lessons.pdf)

### Lecture 5

[[Reading Assignment Submission Form]](https://forms.gle/58JgvRAUpsLXgS8e7)

- Kawato M. Internal models for motor control and trajectory planning. Curr Opin Neurobiol. 1999 Dec;9(6):718-27. doi: 10.1016/s0959-4388(99)00028-8. PMID: 10607637. [[PDF]](resources/Kawato-internal-models.pdf)
- Flanagan JR, Bowman MC, Johansson RS. Control strategies in object manipulation tasks. Curr Opin Neurobiol. 2006 Dec;16(6):650-9. doi: 10.1016/j.conb.2006.10.005. Epub 2006 Nov 3. PMID: 17084619. [[PDF]](resources/FlanaganBowmanJohansson06.pdf)

### Lecture 6

[[Reading Assignment Submission Form]](https://forms.gle/misbrav9rGMuK4rX9)

### Lecture 7

[[Reading Assignment Submission Form]](https://forms.gle/a7ZeFuxKT4MQnYXG6)

### Lecture 8

[[Reading Assignment Submission Form]](https://forms.gle/ZXGXN9vCNKV9vzgY6)

### Lecture 9

[[Reading Assignment Submission Form]](https://forms.gle/DwWDEcRkyVcyPZPo6)

### Lecture 10

[[Reading Assignment Submission Form]](https://forms.gle/BNdnEAgWiLkbNNzz7)

### Lecture 11

[[Reading Assignment Submission Form]](https://forms.gle/GULLmqVsMu8ArDLx8)

### Lecture 12

[[Reading Assignment Submission Form]](https://forms.gle/Wd5qUdopPefZmKfy9)