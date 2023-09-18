<<<<<<< HEAD
# Programming the IoT - Python Components
This is the source repository for the Python components related to my Programming the Internet of Things book and Connected Devices IoT course. These are shell wrappers ONLY and are not a solution set (which is a separately repository, not yet released). For convenience to the reader, some basic functionality has already been implemented (such as configuration logic, consts, interfaces, and test cases).

The code in this repository is largely comprised of shell classes that are designed to be implemented by the reader and are NOT solutions. These shell classes and their relationships respresent a notional design that aligns with the requirements listed in [Programming the IoT Requirements](https://github.com/orgs/programming-the-iot/projects/1). These requirements encapsulate the programming exercises presented in my book [Programming the Internet of Things: An Introduction to Building Integrated, Device to Cloud IoT Solutions](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401).
=======
# Programming the IoT - Book Exercise Docs

If you're a student of Connected Devices, clone this repository so you can capture the documentation artifacts
for each Lab Module exercise you'll implement as part of this course.

If you're reading [Programming the Internet of Things](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/), whether as a student of my IoT course or for fun, you can also use this repository to help track your progress with the exercises using the simple Markdown checklists provided in each sub-directory.

# What You'll Find In This Project

Each sub-directory maps to a specific Lab Module, which also aligns to the exercises listed in [Programming the Internet of Things](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/).
Within each sub-directory are the Markdown files that correlate to the documentation you can fill out related to each Chapter's exercise, as follows:
  - CDA-REQ-CHECKLIST.md: Use this to check off the CDA-specific (Constrained Device App) exercise tasks for the named Lab Module. This file will only exist if there are CDA-specific tasks to complete.
  - GDA-REQ-CHECKLIST.md: Use this to check off the GDA-specific (Gateway Device App) exercise tasks for the named Lab Module. This file will only exist if there are GDA-specific tasks to complete.
  - CSF-REQ-CHECKLIST.md: Use this to check off the CSF-specific (Cloud Service Functions) exercise tasks for the named Lab Module. This file will only exist if there are CSF-specific tasks to complete.
  - README-CDA.md: Use this to document your CDA-specific design. This file will only exist if there is CDA-specific documentation to complete.
  - README-GDA.md: Use this to document your GDA-specific design. This file will only exist if there is GDA-specific documentation to complete.
  - README-CSF.md: Use this to document your CSF-specific design. This file will only exist if there is CSF-specific documentation to complete.
  - README-PROJECT-PROPOSAL.md: Use this to document your Semester Project Proposal. This file only exists as part of Lab Module 12.
  - README-PROJECT-FINAL.md: Use this to document your Semester Project Final Write-up. This file only exists as part of Lab Module 12.

If you're reading this Markdown page, you may be asking yourself, "do I need to complete this documentation?". If...
  - You're in my Connected Devices class, yes - these are required as part of each Lab Module submission.
  - You're reading [Programming the Internet of Things](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/), it's completely up to you.
  - Neither of the above apply to you, it's completely up to you.
>>>>>>> 7c53ecd04f90fab074733bced298abe593285f44

## Links, Exercises, Updates, Errata, and Clarifications

Please see the following links to access exercises, errata / clarifications, and the e-book:
 - [Programming the IoT Kanban Board](https://github.com/orgs/programming-the-iot/projects/1)
 - [Errata and Clarifications](https://labbenchstudios.com/programming-the-iot-book/programming-the-iot-1st-edition/)
 - [Programming the Internet of Things Book](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/)

<<<<<<< HEAD
## How to use this repository
If you're reading [Programming the Internet of Things: An Introduction to Building Integrated, Device to Cloud IoT Solutions](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401), you'll see a tie-in with the exercises described in each chapter and this repository. Most of the code in the main src tree is NOT implemented by design. It's intended for you - as the reader of my book (and possibly a student in one of my IoT courses) - to implement by filling in the implementation details as you work through each exercise.

A solution set is available, although I haven't yet released it. Stay tuned for updates on this topic.

## This repository aligns to exercises in Programming the Internet of Things
These components are all written in Python3, and correlate to the exercises designed for the Constrained Device Application (CDA) specified in my book [Programming the Internet of Things: An Introduction to Building Integrated, Device to Cloud IoT Solutions](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401).

Since Python is also used for various cloud computing activities, there are other components that may be introduced as Cloud Service Functions (CSF) in the future, as they will share some of the common data management code written for the CDA exercises.

## How to navigate the directory structure for this repository
This repository is comprised of the following top level paths:
- [config](https://github.com/programming-the-iot/python-components/tree/default/config): Contains basic configuration file(s).
- [src](https://github.com/programming-the-iot/python-components/tree/default/src): Contains the following source trees:
  - [src/main/python](https://github.com/programming-the-iot/python-components/tree/default/src/main/python): The main source tree for python-components. Keep in mind that most of these classes are shell representations ONLY and must be implemented as part of the exercises referenced above.
  - [src/test/python](https://github.com/programming-the-iot/python-components/tree/default/src/test/python): The test source tree for python-components. These are designed to perform very basic unit and integration testing of the implementation of the exercises referenced above. This tree is sectioned by part - part01, part02, and part03 - which correspond to the structure of Programming the Internet of Things.
- [simTestData](https://github.com/programming-the-iot/python-components/tree/default/simTestData): Contains sample simulated test data.
  - This simulated test data was generated as part of my own solution to Lab Module 5 as part of the exercises referenced above. Keep in mind that these data are from my own solution, which will likely be different from your own.

Here are some other files at the top level that are important to review:
- [basic_imports.txt](https://github.com/programming-the-iot/python-components/blob/default/basic_imports.txt): The core library dependencies - use pip to install.
- [cv_imports.txt](https://github.com/programming-the-iot/python-components/blob/default/cv_imports.txt): The optional CV library dependencies - STILL BEING TESTED - use pip to install.
- [README.md](https://github.com/programming-the-iot/python-components/blob/default/README.md): This README.
- [LICENSE](https://github.com/programming-the-iot/python-components/blob/default/LICENSE): The repository's LICENSE file.

Lastly, here are some 'dot' ('.{filename}') files pertaining to dev environment setup that you may find useful (or not - if so, just delete them after cloning the repo):
- [.gitignore](https://github.com/programming-the-iot/python-components/blob/default/.gitignore): The obligatory .gitignore that you should probably keep in place, with any additions that are relevant for your own cloned instance.
- [.project](https://github.com/programming-the-iot/python-components/blob/default/.project): The Eclipse IDE project configuration file that may / may not be useful for your own cloned instance. Note that using this file to help create your Eclipse IDE project will result in the project name 'piot-python-components' (which can be changed, of course).
- [.pydevproject](https://github.com/programming-the-iot/python-components/blob/default/.pydevproject): The Eclipse IDE and PyDev-specific configuration file for your Python environment that may / may not be useful for your own cloned instance.

NOTE: The directory structure and all files are subject to change based on feedback I receive from readers of my book and students in my IoT class, as well as improvements I find to be helpful for overall repo betterment.

# Other things to know

## Pull requests
PR's are disabled while the codebase is being developed.

## Updates
Much of this repository, and in particular unit and integration tests, will continue to evolve, so please check back regularly for potential updates. Please note that API changes can - and likely will - occur at any time.

# REFERENCES
This repository has external dependencies on other open source projects. I'm grateful to the open source community and authors / maintainers of the following libraries:

Lab Module Library References (not all are required for each lab module):

- [aiocoap](http://github.com/chrysn/aiocoap/)
  - Reference: Amsüss, Christian and Wasilak, Maciej. aiocoap: Python CoAP Library. Energy Harvesting Solutions, 2013–. http://github.com/chrysn/aiocoap/.
- [apscheduler](https://github.com/agronholm/apscheduler)
  - Reference: A. Grönholm. APScheduler. (2020) [Online]. Available: https://pypi.org/project/APScheduler/.
- [psutil](https://github.com/giampaolo/psutil)
  - Reference: G. Rodola. Psutil. (2009 – 2020) [Online]. Available: https://psutil.readthedocs.io/en/latest/.
- [numpy](https://numpy.org/)
  - Reference: NumPy. NumPy. (2020) [Online]. Available: https://numpy.org/.
- [matplotlib](https://matplotlib.org/)
  - Reference: [J. D. Hunter, "Matplotlib: A 2D Graphics Environment", Computing in Science & Engineering, vol. 9, no. 3, pp. 90-95, 2007.](https://ieeexplore.ieee.org/document/4160265)
  - DOI: https://doi.org/10.5281/zenodo.592536
- [Sense-Emu](https://sense-emu.readthedocs.io/en/v1.1/)
  - Reference: The Raspberry Pi Foundation. Sense HAT Emulator. (2016) [Online]. Available: https://sense-emu.readthedocs.io/en/v1.0/.
- [pisense](https://pisense.readthedocs.io/en/release-0.2/#)
  - Reference: D. Jones. Pisense. (2016 – 2018) [Online]. Available: https://pisense.readthedocs.io/en/release-0.2/.
- [paho-mqtt](https://www.eclipse.org/paho/)
  - Reference: Eclipse Foundation, Inc. Eclipse Paho™ MQTT Python Client. (2020) [Online]. Available: https://github.com/eclipse/paho.mqtt.python.
- [CoAPthon](https://github.com/Tanganelli/CoAPthon3)
  - Reference: G.Tanganelli, C. Vallati, E.Mingozzi, "CoAPthon: Easy Development of CoAP-based IoT Applications with Python", IEEE World Forum on Internet of Things (WF-IoT 2015)

Additional Library References (for in-class Computer Vision examples):

- [imutils](https://pypi.org/project/imutils/)
  - Reference: A. Rosebrock. imutils. (2020) [Online]. Available: https://pypi.org/project/imutils/.
- [opencv-python](https://pypi.org/project/opencv-python/)
  - Reference: O. Heinisuo. opencv-python. (2020) [Online]. Available: https://pypi.org/project/opencv-python/.
- [opencv-python-headless](https://pypi.org/project/opencv-python-headless/)
  - Reference: O. Heinisuo. opencv-python. (2020) [Online]. Available: https://pypi.org/project/opencv-python-headless/.
- [opencv-contrib-python](https://pypi.org/project/opencv-contrib-python/)
  - Reference: O. Heinisuo. opencv-python. (2020) [Online]. Available: https://pypi.org/project/opencv-contrib-python/.
- [rtsp](https://pypi.org/project/rtsp/)
  - Reference: M. Stewart. rtsp. (2020) [Online]. Available: https://pypi.org/project/rtsp/.

NOTE: This list will be updated as others are incorporated.

# FAQ
For typical questions (and answers) to the repositories of the Programming the IoT project, please see the [FAQ](https://github.com/programming-the-iot/book-exercise-tasks/blob/default/FAQ.md).

# IMPORTANT NOTES
This code base is under active development.

If any code samples or other technology this work contains, describes, and / or is subject to open source licenses or the intellectual property rights of others, it is your responsibility to ensure that your use thereof complies with such licenses and/or rights.

# LICENSE
Please see [LICENSE](https://github.com/programming-the-iot/python-components/blob/default/LICENSE) if you plan to use this code.

Please refer to the referenced libraries for their respective licenses.
=======
## About the Exercises

You can review the specific exercises for each Lab Module using the Kanban project board I setup at the following link:
[Programming the IoT Kanban Board](https://github.com/orgs/programming-the-iot/projects/1)

Here's the breakdown of each: 
  - [Lab Module 01: Setup](https://github.com/orgs/programming-the-iot/projects/1#column-9974937)
  - [Lab Module 02: Create Initial Apps](https://github.com/orgs/programming-the-iot/projects/1#column-9974938)
  - [Lab Module 03: Data Simulation](https://github.com/orgs/programming-the-iot/projects/1#column-10488379)
  - [Lab Module 04: Hardware Emulation](https://github.com/orgs/programming-the-iot/projects/1#column-10488386)
  - [Lab Module 05: Data Management](https://github.com/orgs/programming-the-iot/projects/1#column-10488421)
  - [Lab Module 06: MQTT Client - CDA](https://github.com/orgs/programming-the-iot/projects/1#column-10488434)
  - [Lab Module 07: MQTT Client - GDA](https://github.com/orgs/programming-the-iot/projects/1#column-10488499)
  - [Lab Module 08: CoAP Server](https://github.com/orgs/programming-the-iot/projects/1#column-10488501)
  - [Lab Module 09: CoAP Clients](https://github.com/orgs/programming-the-iot/projects/1#column-10488503)
  - [Lab Module 10: Edge Integration](https://github.com/orgs/programming-the-iot/projects/1#column-10488510)
  - [Lab Module 11: Cloud Integration](https://github.com/orgs/programming-the-iot/projects/1#column-10488514)
  - [Lab Module 12: Semester Project](https://github.com/orgs/programming-the-iot/projects/1#column-10488565)
  
# Other Things to Know

## Pull Requests

In general, PR's are disabled, at least while the codebase and documentation are being developed.

## Updates

Much of the tasks and issues representing requirements within this repository will continue to evolve, so you may want to check back regularly for potential updates. Please note that this repository is still under active development - you'll likely find typos and other errata.

# License

*This README.md File - Usage and License*

 - The following files are &copy; 2020 - 2022 by [Andrew D. King](https://andyking.me)</a> and licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/ " target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0 <img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a>
   - README.md

*All {prefix}-CHECKLIST.md and Additional README-{postfix}.md Files - Usage and License*

 - The following template files are &copy; 2020 - 2022 by [Andrew D. King](https://andyking.me)</a> and licensed under <a href="https://creativecommons.org/licenses/by/4.0/" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0 <img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a>
   - CDA-REQ-CHECKLIST.md
   - GDA-REQ-CHECKLIST.md
   - CSF-REQ-CHECKLIST.md
   - README-CDA.md
   - README-GDA.md
   - README-CSF.md
   - README-PROJECT-PROPOSAL.md
   - README-PROJECT-FINAL.md
>>>>>>> 7c53ecd04f90fab074733bced298abe593285f44
