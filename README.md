<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->





<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
--




<!-- PROJECT LOGO -->
<br />

  <h3 align="center">MapChat Hyper-Local Social Network</h3>

  <p align="center">
    The worlds best adventure-based social networking application
    <br />
    <a href="https://github.com/chrisboyd/MapChat/tree/master/Docs"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/chrisboyd/MapChat/blob/master/Docs/main_GUI_example.jpg">View Demo</a>
    ·
    <a href="https://github.com/chrisboyd/MapChat/issues">Report Bug</a>
    ·
    <a href="https://github.com/chrisboyd/MapChat/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Goals](#goals)
* [User Story](#user-story)
* [Requirements](#requirements)
* [Challenges](#challenges)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

Current social networks are based around producing as large and widely-distributed groups as possible. While this approach is great for remaining in contact with people all over the world and promoting your own social brand, it provides little value in increasing your quality of life on a day-to-day basis. MapChat aims to reverse this trend by promoting and maintaining a new form of hyper-local groups.

A hyper-local group means focusing on a small geographic area or around a well defined community. MapChat would create/maintain this new form of hyper-local groups by allowing the users to create a new community or join an existing one. The creation of a community is based on a geographical location. A community can be open for all or have restricted access, depending on the creator’s desires. Every group on the map can create their own flag. A popular group’s flag can be a marker for adventure, thereby leading other groups to explore a new community or attraction. Each flag is linked with a picture and brief description of the area written by the group. MapChat will also have a messaging system so the users can communicate and build a vibrant community. Ultimately, the purpose of MapChat is to encourage our users to get out and experience the world around them.


### Built With
MapChat will be hosted on AWS. Further technologies are still being discussed. Any recommendations will be greatly appreciated and rewarded with a digital pint of beer.



<!-- GETTING STARTED -->
## Getting Started

Check back in once we have passed the initial Project Proposal Stage.

### Prerequisites

Check back in once we have passed the initial Project Proposal Stage.

### Installation

MapChat runs entirely within your mobile web browser so there will never be any additional software to install.

<!-- GOALS -->
## Goals
* Creation and deletion of user accounts
* Creation and remove hyper-local groups
* Discovery of nearby groups
* Post media tied to locations to group members
* Interaction of group members

The main focus of MapChat is to help individuals build a community around venturing out in the world. This community is maintained with our message and flag interactions. These systems allow users to connect in a way they can feel comfortable with. Users can either use MapChat to find already existing groups in an area or create a new group to invite other users to. MapChat wants our users to feel completely comfortable with sharing their location data. With this in mind, MapChat guarantees to not provide any user data to third-party entities. We consider our user’s data of top priority, so if any user decides to deactivate their account all of their historical data will be permanently removed from all MapChat systems.



<!-- USER STORY -->
## User Story

* Story Name: Join an existing MapChat Social Group
* Description: User wants to find an existing Social Group so they can make new friends
* Conversation:
  * What is User’s activity goal with their new friends?
  * When does User want to perform said activity?
  * What are User’s requirements for a new Social Group?
    * Selections for: age, distance, gender, interests
  * How long does User want to be a part of their new Social Group?
* Confirmation:
  * As a user can I find local Social Groups?
  * As a user can I join local Social Groups?
  * As a user can I interact with other members of the local Social Group?
  * As a user can I leave a local Social Group?
  
<!-- REQUIREMENTS -->
## Requirements
**Priority 1**
1. Users can sign up for an account through an account creation process. 
1. Users can login through a login process.
1. Users can create a map-group by selecting a location.
1. Users can invite other users to join their own map-group. 
1. Users can upload a photo or video to a map-group (through mobile app), where it will appear as a flag for other users to interact with. Media has the coordinate meta data.
1. Users can select a flag in a map-group (mouse-click, touchscreen press), that will launch the picture or video for viewing.
1. Users can jump between different map-groups through a GUI.

**Priority 2**
1. Users with sufficient privileges can remove other users from a map group. 
1. A map-group interface will have a chat box.
1. A user can choose to make the content of their flag hidden, requiring another user to visit the location in order to access the content.
1. A user can create a chain of flags meant to be visited in sequence, where each node unlocks the next successive node.
1. Administrator users (those who created a map-group) can delegate group-member privileges: invitation, removal, chat-enabled, chat-muted.
1. User can choose to display only certain layers of flags. e.g: choose to only see one other user’s flags).

**Priority 3**
1. Implement recommendation system for discovering new groups.
1. Enable businesses to sponsor pop-up events for groups

<!-- CHALLENGES -->
## Challenges
1. Differentiating from other services: this is very similar to Google My Maps
   1. Come up with some way to incentivize people going outside
   1. Strip down the features of My Maps to make it simpler to use
1. Map generation: This can be a blackbox in the prototype, Google Maps integration may be needed.
   1. Basic Custom map generation: scrape google maps or another service, take a static snapshot from the map
   1. Third party software or service: connect it to the system as a component
   1. Develop more advanced map generation
1. High volume of users


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Chris Boyd - chrisboyd360@gmail.com

Mason D’Arcy - masondarcy@gmail.com

Marc Chami - whimm337@my.yorku.ca

Indeep Singh - indeep.singh99@gmail.com

Raza Memon - raza9999ali@gmail.com


Project Link: [https://github.com/chrisboyd/MapChat](https://github.com/chrisboyd/MapChat)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GitHub Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [AWS Educate](https://aws.amazon.com/education/awseducate/)
* [Best README Template](https://github.com/othneildrew/Best-README-Template)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/chrisboyd/MapChat/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=flat-square
[forks-url]: https://github.com/chrisboyd/MapChat/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=flat-square
[stars-url]: https://github.com/chrisboyd/MapChat/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/chrisboyd/MapChat/blob/master/LICENSE
[product-screenshot]: images/screenshot.png
