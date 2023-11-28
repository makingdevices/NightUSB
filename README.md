<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Instagram][ig-shield]][ig-url]
[![PCBWAY][sponsor-shield]][sponsor-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://makingdevices.com/links/">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Making Devices</h3>

  <p align="center">
    Open Source projects where we struggle with engineering, electronics, coding and who knows what else... Night USB is a very small USB dev board for the PIC18F14k50, so hopefully you may find it interesting ;)
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#Build-one">Build one</a>
      <ul>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#Sponsor">Sponsor</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Bytes Counter Shot][product-screenshot]](https://makingdevices.com/NightUSB)

The PIC18F14k50 is USB-2.0 fully compatible, so this small dev board aims to explore the USB communication: Simulating mouse&keyboard, make small scripts for BADUSB behaviour, and so much else can be done with this microcontroller. However, it does not count on isolation between the PIC and the USB, so it should be handled quite carefully. 

On the other hand, most of the IO pins of the PIC18F are available in the board, so even if you dont have any project with an USB, you can use the board as a normal dev board.

This project is finished, and the provided .hex file and software code is tested. The code simulates a small movement of the mouse every 15s, with a small blink of the LED. This will keep your PC alive for longer sesions of automated tests or anything else. (NOT FOR Remote work abuse!!)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

[![Microcontroller][PIC]][PIC-url]
[![MPLAB C][MPLAB-C]][MPLAB-C-url]
[![Kicad][kicad-shield]][kicad-url]
[![SPONSOR][sponsor-icon]][sponsor-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Build one
Documentation is updated.

1. Get the gerber files for the latest version: [V0.1](https://github.com/makingdevices/NightUSB/blob/main/Gerber/nightUSBv01.zip) 
2. Send them to a PCB manufacturer ([Our Sponsor is PCBWAY][sponsor-url])
3. You should solder all the components in the board. ([The schematic is available here v0.1][schematic-url])

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

Instructions of use:

- The .hex files and software provided will emulate a mouse that will avoid your computer to go into sleep or standby.
- Dev Board. Only your imagination can tell you what to do with it :)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Finish the firmware for the PIC18F14K50
- [x] Assembly & First tests


See the [open issues](https://github.com/makingdevices/NightUSB/issues) for a full list of proposed features (and known issues).

State: Project <b>FINISHED</b> - 28/11/2023

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under three licenses:
- [Hardware](/License/HW_cern_ohl_s_v2.pdf)
- [Software](/License/SW_GPLv3.0.txt)
- [Documentation](/License/Documentation_CC-BY-SA-4.0.txt)

[![GPL v3 License][license-shield]][license-url] 
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Making Devices - [@MakingDevices](https://www.instagram.com/makingdevices/)

Project Link: [https://github.com/makingdevices/NightUSB](https://github.com/makingdevices/NightUSB/)

Other Links: [LinkTree](https://makingdevices.com/links/)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/makingdevices/NightUSB.svg?style=for-the-badge
[contributors-url]: https://github.com/makingdevices/NightUSB/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/makingdevices/NightUSB.svg?style=for-the-badge
[forks-url]: https://github.com/makingdevices/NightUSB/network/members
[stars-shield]: https://img.shields.io/github/stars/makingdevices/NightUSB.svg?style=for-the-badge
[stars-url]: https://github.com/makingdevices/NightUSB/stargazers
[issues-shield]: https://img.shields.io/github/issues/makingdevices/NightUSB.svg?style=for-the-badge
[issues-url]: https://github.com/makingdevices/NightUSB/issues
[license-shield]: /images/license.png
[license-url]: https://github.com/makingdevices/NightUSB/tree/main/License
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/company/making-devices/
[sponsor-shield]: https://img.shields.io/badge/SPONSOR-PCBWAY-black.svg?style=for-the-badge&colorB=1200
[sponsor-url]: https://www.pcbway.com/?from=makingdevices
[sponsor-screenshot]: /images/PCB_sponsor.png
[product-screenshot]: images/screenshot.jpg
[PIC]: https://img.shields.io/badge/PIC18LF14K50-000000?style=for-the-badge
[PIC-url]: http://ww1.microchip.com/downloads/en/devicedoc/40001350f.pdf
[kicad-shield]: https://img.shields.io/badge/kicad-0b03fc?style=for-the-badge&logo=kicad&logoColor=white
[kicad-url]: https://www.kicad.org/
[YT-screenshot]: images/YT_assembly.PNG
[sponsor-icon]:  https://img.shields.io/badge/-PCBWAY-black.svg?style=for-the-badge&colorB=1200
[ig-shield]: https://img.shields.io/badge/instagram-a83297?style=for-the-badge&logo=instagram&logoColor=white
[ig-url]: https://www.instagram.com/makingdevices/
[MPLAB-C]: https://img.shields.io/badge/MPLAB%20C18-DD0031?style=for-the-badge&logo=C&logoColor=white
[MPLAB-C-url]: https://www.microchip.com/en-us/development-tool/SW006011
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
[schematic-url]: /Output_PDF/schematic_V0_1.pdf