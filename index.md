---
layout: default
---

# CS 294-277, Robots That Learn (Spring 2026)

## Logistics

Time: Mondays 3-5PM

Location: Room 1213 @ [Berkeley Way West](https://maps.app.goo.gl/thh2ey5nUR7VsMFB8)

Instructor: [Jitendra Malik](https://people.eecs.berkeley.edu/~malik)

TA: [Tara Sadjadpour](https://people.eecs.berkeley.edu/~tsadja/)

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

## Course Format

Each session consists of a two 1-hour lectures with a 10 minute break in between, i.e. 3:10-4 PM and 4:10-5PM. We will use notations A/B to denote the sub-sessions: e.g. Lecture 1A, 1B, 2A, 2B, ...

## Schedule

The following schedule is a tentative assignment and will evolve in real time. Weekly materials will be added.

* Lecture 1 (1/26) Introduction [[slides]](https://drive.google.com/drive/folders/1kOSrAYfnnHocNXC7KQtwE2ftnR5ABGA7?usp=sharing)
* Lecture 2A (2/2) Biomechanics of walking and running [[slides]](https://drive.google.com/file/d/17JA6jxcblXgU6t05C9Y_N92_OE1x_PTx/view?usp=sharing)
* Lecture 2B (2/2) Robot mechanisms - kinematics and dynamics [[slides]](https://drive.google.com/file/d/1qHlJCWIBN12GBn47gEtQaxWL9veM7IIZ/view?usp=sharing)
* Lecture 3 (2/9) Introduction to Diffusion Models (Guest Lecture: [Angjoo Kanazawa](https://people.eecs.berkeley.edu/~kanazawa/)) [[slides]](https://drive.google.com/file/d/1oTBxptFBSA8EvcGHCy3UCNOV8Kvhw2cu/view?usp=sharing)
* Lecture 4A (2/23) The human hand and dexterous object manipulation + Robot hands
* Lecture 4B (2/23) Proprioception and tactile perception
* Lecture 5A (3/2) The developmental perspective on motor control
* Lecture 5B (3/2) Robot dynamics, control, and motion planning
* Lecture 6A (3/9) Computational neuroscience perspective on prediction and control
* Lecture 6B (3/9) Video World Models
* Lecture 7AB (3/16) Reinforcement Learning
* Lecture 8A (3/30) Behavior cloning
* Lecture 8B (3/30) Visual Imitation
* Lecture 9AB (4/6) Case Studies in Locomotion
* Lecture 10AB (4/13) Case Studies in Navigation
* Lecture 11AB (4/20) Case Studies in Dexterous Manipulation
* Lecture 12AB (4/27) Long horizon planning and the role of language
* RRR Week (5/4) Final Project Presentations

Please see below ("Reading Materials") for reading assignments.

## Coursework

- 10% Weekly Reading Assignment
- 10% Lecture Scribing
- 30% Midterm (TBD, first hour of the class)
- 50% Final Project

**Weekly Reading Assignment**: For every weekly reading, each student should come up with 2 multiple choice questions, and supply with answers. We will send out a Google form for submission each week.

**Lecture Scribing**: For each lecture, two student scribes will organize lecture notes in LaTeX. The students can decide to submit a single note together or individually; grades will be assigned based on note quality. The lecture notes should be ready by the same Friday.

*Note: since the lecture content does not necessarily align with lecture title, each scribe is only required to cover the time slot they have signed up for.*

**Midterm**: During the first hour of class (date TBD), we will have a mid-term exam based on questions sourced from the weekly reading assignments so far. A total of about 30 multiple-choice questions will be given. One 8.5"x11", double-sided cheat sheet will be permitted.

**Final Project**: The goal of the final project is to explore and push the boundaries of robot learning, choosing from topics presented in this course. Here are a few examples of possible project formats: proposal and evaluation of new algorithms, investigation of a robotic application, benchmarking a range of existing methods, etc. Ideally, the project covers interesting new ground and could be the foundation for a future conference paper submission or product. The project can be done in groups of 1-4 people. Note that our expectations will scale linearly with the number of people in the group.

### Final Project Logistics

**Project Proposal**: To keep track of your final project progress, please submit a 1 page project proposal using [this](https://docs.google.com/document/d/13wMRXYPVz0wzIJRM1M3s06glfL8gYmlqSaTy6W1D2iY/edit?usp=sharing) template by TBD (the day after midterm). Please submit through a Google doc shared with the course instructor and TA, so we can give feedback and suggestions. Note that this proposal will not be graded.

**Project Presentation**: We will have the final project presentations during RRR week during our regular class time (starting at 3:10pm). Due to the large number of projects we have, every group will have 5 minutes to present (no Q&A). This will serve as the most important basis for grading.

**Project Report**: The final project report will be due by EOD 5/8. Please use CoRL format for the project report, with a maximum of 4 pages. We would like you to focus on the problem setting, why it matters and what's interesting/novel about it, your approach, your results, analysis of results, limitations, and future directions. Cite and briefly survey prior work as appropriate but don't re-write prior work when not directly relevant to understanding your approach. References will not be counted against the 4 pages.


### Assignment Deadlines
- Weekly Reading: 23:59PM PT, the Friday after assignment release
- Lecture Scribing: 23:59PM PT, the Friday after scribed lecture

## Background Materials

* [Deep Learning (Bishop & Bishop)](https://www.bishopbook.com/)
* [Reinforcement Learning (Sutton & Barto)](http://incompleteideas.net/book/the-book-2nd.html)

## Reading materials

### Lecture 1
N/A

### Lecture 2

[[Reading Assignment Submission Form]](https://forms.gle/FXTHKNBfcWZshCHn8)

#### Lecture 2A

- T. K. Uchida and S. L. Delp. Biomechanics of movement: the science of sports, robotics, and rehabilitation. Mit Press, 2021.
- P. Ramdya and A. J. Ijspeert. The neuromechanics of animal locomotion: From biology to robotics and back. Science Robotics, 8(78):eadg0279, 2023. [[PDF]](resources/Locomotion-biology-robotics-scirobotics.pdf)

(It is not expected to read the Uchida-Delp book, but we will cover a couple of chapters from it.)

#### Lecture 2B

In advance of lecture 2B, students should try to familiarize themselves with how 3D rotations and translations are represented. We would like students to learn about "exponential coordinates" - how a rotation matrix is the exponential of a skew-symmetric matrix corresponding to the axis of rotation, and when rotation is accompanied by translation, we use the exponential of a twist. This formalism results in an elegant way to specify the forward kinematics of a robot using the product of matrix exponentials. The Li-Murray-Sastry textbook and the Lynch-Park textbook are good sources. You can find lectures on YouTube for Lynch-Park. I recommend the ones corresponding to Chapter 3.
[[link]](https://www.youtube.com/watch?v=29LhXWjn7Pc&list=PLggLP4f-rq02vX0OQQ5vrCxbJrzamYDfx&index=10)

### Lecture 3

[[Reading Assignment Submission Form]](https://docs.google.com/forms/d/e/1FAIpQLScJzNNQugbrZeM-uwKYgbe18sY07tVtEh-3x0BccxNQk4hkkg/viewform?usp=sharing&ouid=100618406782889124957)

- Papamakarios, George, et al.  Normalizing Flows for Probabilistic Modeling and Inference. JMLR, 2021. [[PDF]](resources/normalizing_flows_paper.pdf)
- Lipman, Yaron, et al. Flow Matching for Generative Modeling. ICLR, 2023. [[PDF]](resources/flow_matching_paper.pdf)

<!--
### Lecture 3

#### Lecture 3A

- Video on human hand anatomy [[link]](https://www.youtube.com/watch?v=-y69D76RdMs)
- Piazza, Cristina, et al. "A century of robotic hands." Annual Review of Control, Robotics, and Autonomous Systems 2.1 (2019): 1-32. [[PDF]](resources/century-of-robotic-hands.pdf)
- [LEAP Hand](https://leaphand.com/), [LEAP Hand v2](https://openreview.net/forum?id=eQomRzRZEP)

#### Lecture 3B

- Jones, L. A. "Human hand function." (2006). [[PDF]](resources/Human_Hand_Function.pdf)
- Esther P Gardner, "Touch" (2010). [[PDF]](resources/Gardner-ELS2010.pdf)


### Lecture 4

#### Lecture 4A

- Land, M et al. "The roles of vision and eye movements in the control of activities of daily living." Perception vol. 28,11 (1999): 1311-28. doi:10.1068/p2935 [[PDF]](resources/teamaking-land-mennie-rusted-1999.pdf)

#### Lecture 4B

- Loquercio, Antonio, Ashish Kumar, and Jitendra Malik. "Learning visual locomotion with cross-modal supervision." 2023 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2023. [[PDF]](resources/ICRA23_Learning_to_see_by_walking_blind.pdf)
- Smith, Linda B. and Michael Gasser. "The Development of Embodied Cognition: Six Lessons from Babies." Artificial Life 11 (2005): 13-29. [[PDF]](resources/6_lessons.pdf)

### Lecture 5

- Kawato M. Internal models for motor control and trajectory planning. Curr Opin Neurobiol. 1999 Dec;9(6):718-27. doi: 10.1016/s0959-4388(99)00028-8. PMID: 10607637. [[PDF]](resources/Kawato-internal-models.pdf)
- Flanagan JR, Bowman MC, Johansson RS. Control strategies in object manipulation tasks. Curr Opin Neurobiol. 2006 Dec;16(6):650-9. doi: 10.1016/j.conb.2006.10.005. Epub 2006 Nov 3. PMID: 17084619. [[PDF]](resources/FlanaganBowmanJohansson06.pdf)

### Lecture 6

- "Learning to Walk via Deep Reinforcement Learning." RSS 2019. Tuomas Haarnoja, Sehoon Ha, Aurick Zhou, Jie Tan, George Tucker, Sergey Levine
- Learning Dexterous In-Hand Manipulation. IJRR 2019. OpenAI et al.

### Lecture 7

- Diffusion Policy [[Website]](https://diffusion-policy.cs.columbia.edu/) [[PDF]](resources/diffusion_policy_2023.pdf)

### Lecture 8

- Shaw K, Bahl S, Sivakumar A, Kannan A, Pathak D. Learning dexterity from human hand motion in internet videos. The International Journal of Robotics Research. 2024;43(4):513-532. doi:10.1177/02783649241227559 [[PDF]](resources/shaw-et-al-2024-learning-dexterity-from-human-hand-motion-in-internet-videos.pdf)

- Goyal, Mohit, et al. "Human hands as probes for interactive object understanding." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2022. [[PDF]](resources/Goyal_Human_Hands_As_Probes_for_Interactive_Object_Understanding_CVPR_2022_paper.pdf)

- Kumar, Ashish, Saurabh Gupta, and Jitendra Malik. "Learning navigation subroutines from egocentric videos." Conference on Robot Learning. PMLR, 2020. [[PDF]](resources/ashish_kumar19.pdf)

### Lecture 9

- Scott Kuindersma's talk on BD MPC [[Link]](https://youtu.be/mlTLxpKdHfA?feature=shared)

- Robin Deit's recent RSS talk on BD MPC to supplement Scott's talk [[Link]](https://www.youtube.com/watch?v=aQi6QxMKxQM)

- Russ Tedrake's lecture on humanoids covering ZMP [[Link]](https://www.youtube.com/watch?v=cRu4EqBswbk)


### Lecture 10

- Chang, Matthew, et al. "Goat: Go to any thing." arXiv preprint arXiv:2311.06430 (2023). [[PDF]](resources/59_goat_go_to_any_thing.pdf)

### Lecture 11

- Zhao, Tony Z., et al. "Learning fine-grained bimanual manipulation with low-cost hardware." arXiv preprint arXiv:2304.13705 (2023). [[PDF]](resources/Aloha23.pdf)

- Zhao, Tony Z., et al. "Aloha unleashed: A simple recipe for robot dexterity." arXiv preprint arXiv:2410.13126 (2024). [[PDF]](resources/447_ALOHA_Unleashed_A_Simple_R.pdf)

- Dalal, Murtaza, et al. "Local Policies Enable Zero-shot Long-horizon Manipulation." arXiv preprint arXiv:2410.22332 (2024). [[PDF]](resources/Dalal24.pdf)
-->
