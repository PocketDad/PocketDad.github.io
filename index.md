# PocketDad
[GitHub Repository Link](https://github.com/PocketDad/pocketdad)

## Table of Contents
* [Motivation](#motivation)
* [Goals](#goals)
* [Usage](#usage)
* [Installation](#installation)
* [Development status](#development-status)
* [Usability testing](#usability-testing)
* [About us](#about-us)

## Motivation
Many young people have to navigate early adulthood without sufficient guidance for facing practical challenges. 
These challenges may include keeping up with regular maintenance tasks associated with their house or car, remembering to pay their taxes, or simply tying a tie.


## Goals
PocketDad is a personal digital assistant that will remind the user of important tasks, such as filing taxes, cleaning the air filters in their home, or checking the tread of their tires before the winter season.
It will also provide instructions on how to carry out these tasks as well as recommendations for specific maintenance services.
PocketDad will also be able to offer general advice directed toward the specific user based on its knowledge of them.


## Usage

### Phase 1: Currently our app consists of mockup pages.

| Choose Avatar | <img src="doc/chooseavatar.png" style="width: 100px"> | This page will display different Dad avatars for the user to choose from. |

| Check-in | <img src="doc/checkin-mockup.png" style="width: 100px"> | This page will inform the user of their tasks and reminders for the day. |

| Add Task | <img src="doc/add-task-mockup.png" style="width: 100px"> | This form will enable the user to add tasks to their to-do list. |

| Edit Task | <img src="doc/edit-task-mockup.png" style="width: 100px"> | The user will be able to edit existing tasks. |

| Display All Tasks | <img src="doc/tasks-mockup.png" style="width: 100px"> | This page will display a list of the user's existing tasks. |

| Completed Tasks | <img src="doc/completed-tasks-mockup.png" style="width: 100px"> | This page will allow the user to return to completed tasks for reference and tracking purposes. |

### Phase 2: Updating our app to include data from a hard-coded database and other mockup pages. These pages utilize User, Task, and Item databases that have been hard-coded with sample data.

| Items Page with Data | <img src="doc/itemspagewithdata.png" style="width: 100px"> | Items page implemented with sample data. |

| Sign-up Page (Mockup) | <img src="doc/sign_up.png" style="width: 100px"> | New users can register through the sign-in page. |

| Individual Tasks Page | <img src="doc/individual-task.png" style="width: 100px"> | Information for each task can be viewed independently. |

### Phase 3: Implementing Riverpod methods for databases and continuing to add to UI.

| Sign-up Page | <img src="doc/onboarding.png" style="width: 100px"> | The sign-up page adds a new user to the existing database of users. |

| Check-in | <img src="doc/check_in.png" style="width: 100px"> | Page displaying check-in information accessed through Riverpod providers. |

| All Tasks | <img src="doc/all_tasks.png" style="width: 100px"> | Page displaying all tasks for each user accessed through Riverpod providers. |

| Add Task | <img src="doc/add_task.png" style="width: 100px"> | Adds a new task to the existing database of tasks. |

| Choose Avatar | <img src="doc/choose_appearance.png" style="width: 100px"> | Sets or changes the Dad avatar. |

### Phase 4/5: Implementing Firebase and Freezed data models.

| Sign-up Page | <img src="doc/darkmode_register.png" style="width: 100px"> | The updated sign-up page adds a new user to the existing database. |

| Sign-in Page | <img src="doc/darkmode_signin.png" style="width: 100px"> | The updated sign-in page allows existing user to access their unique information. |

| Add Task | <img src="doc/updated-add-task.png" style="width: 100px"> | Added "Item" and "Users" fields. |

| Check-in (dark mode) | <img src="doc/darkmode_checkin.png" style="width: 100px"> | Updated Check-in page displaying upcoming tasks (dark mode). |

| Check-in (light mode) | <img src="doc/lightmode_checkin.png" style="width: 100px"> | Updated Check-in page displaying upcoming tasks (light mode). |

| Chat (dark mode) | <img src="doc/darkmode_chat.png" style="width: 100px"> | Mockup of chat page (dark mode) - user will be able to ask the Dad AI questions. |

| Chat (light mode) | <img src="doc/lightmode_chat.png" style="width: 100px"> | Mockup of chat page (light mode) - user will be able to ask the Dad AI questions. |

| Settings | <img src="doc/darkmode_settings.png" style="width: 100px"> | Change the settings (theme mode).

### Phase 5/5: Usability Testing
For a better view, please view this slideshow: [PocketDad Demo](https://docs.google.com/presentation/d/1ikDahWIkutANa-RMbdwFKOhb0F6RVPAidVvOYuwuW70/edit?usp=sharing)

## Installation
Download the source code found in the [PocketDad Repository](https://github.com/PocketDad/pocketdad).
In a terminal, cd into the pocketdad directory and run:
```
flutter run
```

## Development status
* [PocketDad Projectboard](https://github.com/orgs/PocketDad/projects/5)

## [Usability Testing](https://pocketdad.github.io/evaluation)

## About us
PocketDad is being developed by a team of three Computer Science students from the University of Hawaiʻi at Mānoa.

Team members:
* [Yong-Sung Masuda](https://github.com/yongsungm)
* [Sydney Kim](https://github.com/kimsyd)
* [Justin Jandoc](https://github.com/justinjandoc)
