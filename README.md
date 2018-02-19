# hello-world
The Raspberry Pi is a series of small single-board computers developed in the United Kingdom by the Raspberry Pi Foundation to promote the teaching of basic computer science in schools and in developing countries.The original model became far more popular than anticipated,selling outside its target market for uses such as robotics. It does not include peripherals (such as keyboards, mice and cases). However, some accessories have been included in several official and unofficial bundles.

According to the Raspberry Pi Foundation, over 5 million Raspberry Pis were sold by February 2015, making it the best-selling British computer.By November 2016 they had sold 11 million units,and 12.5m by March 2017, making it the third best-selling "general purpose computer". In July 2017, sales reached nearly 15 million.

They are made in a Sony factory in Pencoed, Wales.
Overview
The Raspberry Pi Zero, a US$5 model first introduced in 2015
Several generations of Raspberry Pis have been released. All models feature a Broadcom system on a chip (SoC) with an integrated ARM compatible central processing unit (CPU) and on-chip graphics processing unit (GPU).
Processor speed ranges from 700 MHz to 1.2 GHz for the Pi 3; on-board memory ranges from 256 MB to 1 GB RAM. Secure Digital (SD) cards are used to store the operating system and program memory in either SDHC or MicroSDHC sizes. The boards have one to four USB ports. For video output, HDMI and composite video are supported, with a standard 3.5 mm phono jack for audio output. Lower-level output is provided by a number of GPIO pins which support common protocols like I²C. The B-models have an 8P8C Ethernet port and the Pi 3 and Pi Zero W have on-board Wi-Fi 802.11n and Bluetooth. Prices range US$5 to $35.
The first generation (Raspberry Pi 1 Model B) was released in February 2012, followed by the simpler and cheaper Model A. In 2014, the Foundation released a board with an improved design, Raspberry Pi 1 Model B+. These boards are approximately credit-card sized and represent the standard mainline form-factor. Improved A+ and B+ models were released a year later. A "Compute Module" was released in April 2014 for embedded applications. The Raspberry Pi 2 which added more RAM was released in February 2015.
A Raspberry Pi Zero with smaller size and reduced input/output (I/O) and general-purpose input/output (GPIO) capabilities was released in November 2015 for US$5. Raspberry Pi 3 Model B was released in February 2016 and has on-board WiFi, Bluetooth and USB boot capabilities. By 2017, it became the newest mainline Raspberry Pi. On 28 February 2017, the Raspberry Pi Zero W was launched, a version of the Zero with Wi-Fi and Bluetooth capabilities, for US$10.
The organisation behind the Raspberry Pi consists of two arms. The first two models were developed by the Raspberry Pi Foundation. After the Pi Model B was released, the Foundation set up Raspberry Pi Trading, with Eben Upton as CEO, to develop the third model, the B+. Raspberry Pi Trading is responsible for developing the technology while the Foundation is an educational charity to promote the teaching of basic computer science in schools and in developing countries.
The Foundation provides Raspbian, a Debian-based Linux distribution for download, as well as third-party Ubuntu, Windows 10 IoT Core, RISC OS, and specialised media center distributions. It promotes Python and Scratch as the main programming language, with support for many other languages. The default firmware is closed source, while an unofficial open source is available.

Hardware
The Raspberry Pi hardware has evolved through several versions that feature variations in memory capacity and peripheral-device support.
Raspberrypi block function v01.svg
This block diagram depicts Models A, B, A+, and B+. Model A, A+, and the Pi Zero lack the Ethernet and USB hub components. The Ethernet adapter is internally connected to an additional USB port. In Model A, A+, and the Pi Zero, the USB port is connected directly to the system on a chip (SoC). On the Pi 1 Model B+ and later models the USB/Ethernet chip contains a five-point USB hub, of which four ports are available, while the Pi 1 Model B only provides two. On the Pi Zero, the USB port is also connected directly to the SoC, but it uses a micro USB (OTG) port.

Processor
The Raspberry Pi 2 uses a 32-bit 900 MHz quad-core ARM Cortex-A7 processor.
The Broadcom BCM2835 SoC used in the first generation Raspberry Pi is somewhat equivalent to the chip used in first modern generation smartphones (its CPU is an older ARMv6 architecture),which includes a 700 MHz ARM1176JZF-S processor, VideoCore IV graphics processing unit (GPU),and RAM. It has a level 1 (L1) cache of 16 KB and a level 2 (L2) cache of 128 KB. The level 2 cache is used primarily by the GPU. The SoC is stacked underneath the RAM chip, so only its edge is visible.
The earlier V1.1 model of the Raspberry Pi 2 used a Broadcom BCM2836 SoC with a 900 MHz 32-bit quad-core ARM Cortex-A7 processor, with 256 KB shared L2 cache.[24] The Raspberry Pi 2 V1.2 was upgraded to a Broadcom BCM2837 SoC with a 1.2 GHz 64-bit quad-core ARM Cortex-A53 processor,[25] the same SoC which is used on the Raspberry Pi 3, but underclocked (by default) to the same 900 MHz CPU clock speed as the V1.1. The BCM2836 SoC is no longer in production (as of late 2016).
The Raspberry Pi 3 uses a Broadcom BCM2837 SoC with a 1.2 GHz 64-bit quad-core ARM Cortex-A53 processor, with 512 KB shared L2 cache.[26]

Performance
The Raspberry Pi 3, with a quad-core ARM Cortex-A53 processor, is described as 10 times the performance of a Raspberry Pi 1.[26] This was suggested to be highly dependent upon task threading and instruction set use. Benchmarks showed the Raspberry Pi 3 to be approximately 80% faster than the Raspberry Pi 2 in parallelized tasks.[27]
Raspberry Pi 2 V1.1 included a quad-core Cortex-A7 CPU running at 900 MHz and 1 GB RAM. It was described as 4–6 times more powerful than its predecessor. The GPU was identical to the original.[24] In parallelized benchmarks, the Raspberry Pi 2 V1.1 could be up to 14 times faster than a Raspberry Pi 1 Model B+.[28]
While operating at 700 MHz by default, the first generation Raspberry Pi provided a real-world performance roughly equivalent to 0.041 GFLOPS.[29][30] On the CPU level the performance is similar to a 300 MHz Pentium II of 1997–99. The GPU provides 1 Gpixel/s or 1.5 Gtexel/s of graphics processing or 24 GFLOPS of general purpose computing performance. The graphical capabilities of the Raspberry Pi are roughly equivalent to the performance of the Xbox of 2001.
The LINPACK single node compute benchmark results in a mean single precision performance of 0.065 GFLOPS and a mean double precision performance of 0.041 GFLOPS for one Raspberry Pi Model-B board.[31] A cluster of 64 Raspberry Pi Model B computers, labeled "Iridis-pi", achieved a LINPACK HPL suite result of 1.14 GFLOPS (n=10240) at 216 watts for c. US$4000.[31]

Overclocking
Most Raspberry Pi chips could be overclocked to 800 MHz, and some to 1000 MHz. There are reports the Raspberry Pi 2 can be similarly overclocked, in extreme cases, even to 1500 MHz (discarding all safety features and over-voltage limitations). In the Raspbian Linux distro the overclocking options on boot can be done by a software command running "sudo raspi-config" without voiding the warranty.[32] In those cases the Pi automatically shuts the overclocking down if the chip reaches 85 °C (185 °F), but it is possible to override automatic over-voltage and overclocking settings (voiding the warranty); an appropriately sized heat sink is needed to protect the chip from serious overheating.
Newer versions of the firmware contain the option to choose between five overclock ("turbo") presets that when used, attempt to maximize the performance of the SoC without impairing the lifetime of the board. This is done by monitoring the core temperature of the chip, the CPU load, and dynamically adjusting clock speeds and the core voltage. When the demand is low on the CPU or it is running too hot the performance is throttled, but if the CPU has much to do and the chip's temperature is acceptable, performance is temporarily increased with clock speeds of up to 1 GHz depending on the individual board and on which of the turbo settings is used.
The seven overclock presets are:
none; 700 MHz ARM, 250 MHz core, 400 MHz SDRAM, 0 overvolting
modest; 800 MHz ARM, 250 MHz core, 400 MHz SDRAM, 0 overvolting,
medium; 900 MHz ARM, 250 MHz core, 450 MHz SDRAM, 2 overvolting,
high; 950 MHz ARM, 250 MHz core, 450 MHz SDRAM, 6 overvolting,
turbo; 1000 MHz ARM, 500 MHz core, 600 MHz SDRAM, 6 overvolting,
Pi 2; 1000 MHz ARM, 500 MHz core, 500 MHz SDRAM, 2 overvolting,
Pi 3; 1100 MHz ARM, 550 MHz core, 500 MHz SDRAM, 6 overvolting. In system information CPU speed will appear as 1200 MHz. When in idle speed lowers to 600 MHz.[32][33]
In the highest (turbo) preset the SDRAM clock was originally 500 MHz, but this was later changed to 600 MHz because 500 MHz sometimes causes SD card corruption. Simultaneously in high mode the core clock speed was lowered from 450 to 250 MHz, and in medium mode from 333 to 250 MHz.
The Raspberry Pi Zero runs at 1 GHz.
The CPU on the first and second generation Raspberry Pi board did not require cooling, such as a heat sink or fan, even when overclocking|overclocked, but the Raspberry Pi 3 may generate more heat when overclocked.[34]

RAM
On the older beta Model B boards, 128 MB was allocated by default to the GPU, leaving 128 MB for the CPU.[35] On the first 256 MB release Model B (and Model A), three different splits were possible. The default split was 192 MB (RAM for CPU), which should be sufficient for standalone 1080p video decoding, or for simple 3D, but probably not for both together. 224 MB was for Linux only, with only a 1080p framebuffer, and was likely to fail for any video or 3D. 128 MB was for heavy 3D, possibly also with video decoding (e.g. XBMC).[36] Comparatively the Nokia 701 uses 128 MB for the Broadcom VideoCore IV.[37]
For the later Model B with 512 MB RAM initially there were new standard memory split files released( arm256_start.elf, arm384_start.elf, arm496_start.elf) for 256 MB, 384 MB and 496 MB CPU RAM (and 256 MB, 128 MB and 16 MB video RAM). But a week or so later the RPF released a new version of start.elf that could read a new entry in config.txt (gpu_mem=xx) and could dynamically assign an amount of RAM (from 16 to 256 MB in 8 MB steps) to the GPU, so the older method of memory splits became obsolete, and a single start.elf worked the same for 256 and 512 MB Raspberry Pis.[38]
The Raspberry Pi 2 and the Raspberry Pi 3 have 1 GB of RAM.[39][40] The Raspberry Pi Zero and Zero W have 512 MB of RAM.

Networking
The Model A, A+ and Pi Zero have no Ethernet circuitry and are commonly connected to a network using an external user-supplied USB Ethernet or Wi-Fi adapter. On the Model B and B+ the Ethernet port is provided by a built-in USB Ethernet adapter using the SMSC LAN9514 chip.[41] The Raspberry Pi 3 and Pi Zero W (wireless) are equipped with 2.4 GHz WiFi 802.11n (150 Mbit/s) and Bluetooth 4.1 (24 Mbit/s) based on Broadcom BCM43438 FullMAC chip with no official support for Monitor mode but implemented through unofficial firmware patching[42] and the Pi 3 also has a 10/100 Ethernet port.

Peripherals
The current Model B boards incorporate four USB ports for connecting peripherals.
The Raspberry Pi may be operated with any generic USB computer keyboard and mouse.[43] It may also be used with USB storage, USB to MIDI converters, and virtually any other device/component with USB capabilities.
Other peripherals can be attached through the various pins and connectors on the surface of the Raspberry Pi.[44]

Video
The early Raspberry Pi 1 Model A, with an HDMI port and a standard RCA composite video port for older displays
The video controller can emit standard modern TV resolutions, such as HD and Full HD, and higher or lower monitor resolutions and older standard CRT TV resolutions. As shipped (i.e., without custom overclocking) it can emit these: 640×350 EGA; 640×480 VGA; 800×600 SVGA; 1024×768 XGA; 1280×720 720p HDTV; 1280×768 WXGA variant; 1280×800 WXGA variant; 1280×1024 SXGA; 1366×768 WXGA variant; 1400×1050 SXGA+; 1600×1200 UXGA; 1680×1050 WXGA+; 1920×1080 1080p HDTV; 1920×1200 WUXGA.[45]
Higher resolutions, such as, up to 2048×1152, may work[46][47] or even 3840×2160 at 15 Hz (too low a frame rate for convincing video).[48] Note also that allowing the highest resolutions does not imply that the GPU can decode video formats at those; in fact, the Pis are known to not work reliably for H.265 (at those high resolutions), commonly used for very high resolutions (most formats, commonly used, up to Full HD, do work).

Although the Raspberry Pi 3 does not have H.265 decoding hardware, the CPU is more powerful than its predecessors, potentially fast enough to allow the decoding of H.265-encoded videos in software.[49] The GPU in the Raspberry Pi 3 runs at higher clock frequencies of 300 MHz or 400 MHz, compared to previous versions which ran at 250 MHz.[50]

The Raspberry Pis can also generate 576i and 480i composite video signals, as used on old-style (CRT) TV screens and less-expensive monitors through standard connectors – either RCA or 3.5 mm phono connector depending on models. The television signal standards supported are PAL-BGHID, PAL-M, PAL-N, NTSC and NTSC-J.[51]

Real-time clock[edit]
None of the current Raspberry Pi models have a built-in real-time clock, so they are unable to keep track of the time of day independently. As a workaround, a program running on the Pi can retrieve the time from a network time server or from user input at boot time, thus knowing the time while powered on. To provide consistency of time for the file system, the Pi does automatically save the time it has on shutdown, and re-installs that time at boot.

A real-time hardware clock with battery backup, such as the DS1307, may be added (often via the I²C interface).
Operating systems[edit]

Various operating systems for the Raspberry Pi can be installed on a MicroSD, MiniSD or SD card, depending on the board and available adapters; seen here is the MicroSD slot located on the bottom of a Raspberry Pi 2 board.
The Raspberry Pi Foundation recommends the use of Raspbian, a Debian-based Linux operating system. Other third party operating systems available via the official website include Ubuntu MATE, Windows 10 IoT Core, RISC OS and specialised distributions for the Kodi media center and classroom management.[103]

Many other operating systems can also run on the Raspberry Pi.

Other operating systems (not Linux-based)
RISC OS Pi (a special cut down version RISC OS Pico, for 16 MB cards and larger for all models of Pi 1 & 2, has also been made available.)
FreeBSD[104][105]
NetBSD[106][107]
Plan 9 from Bell Labs[108][109] and Inferno[110] (in beta)
Windows 10 IoT Core – a no-cost edition of Windows 10 offered by Microsoft that runs natively on the Raspberry Pi 2.[111]
xv6[112] – is a modern reimplementation of Sixth Edition Unix OS for teaching purposes; it is ported to Raspberry Pi from MIT xv6; this xv6 port can boot from NOOBS.
Haiku – is an opensource BeOS clone that has been compiled for the Raspberry Pi and several other ARM boards.[113] Work on Pi 1 began in 2011, but only the Pi 2 will be supported.[citation needed]
HelenOS – a portable microkernel-based multiserver operating system; has basic Raspberry Pi support since version 0.6.0[114]
Other operating systems (Linux-based)
Android Things – an embedded version of the Android operating system designed for IoT device development.
Arch Linux ARM – a port of Arch Linux for ARM processors.
openSUSE[115]
SUSE Linux Enterprise Server 12 SP2[116]
Raspberry Pi Fedora Remix[117]
Gentoo Linux[118]
CentOS for Raspberry Pi 2 and later
RedSleeve (a RHEL port) for Raspberry Pi 1
Slackware ARM – version 13.37 and later runs on the Raspberry Pi without modification.[119][120][121][122] The 128–496 MB of available memory on the Raspberry Pi is at least twice the minimum requirement of 64 MB needed to run Slackware Linux on an ARM or i386 system.[123] (Whereas the majority of Linux systems boot into a graphical user interface, Slackware's default user environment is the textual shell / command line interface.[124]) The Fluxbox window manager running under the X Window System requires an additional 48 MB of RAM.[125]
OpenWrt – is primarily used on embedded devices to route network traffic.
Kali Linux – is a Debian-derived distro designed for digital forensics and penetration testing.
SolydXK – is a light Debian-derived distro with Xfce.
Ark OS – is designed for website and email self-hosting.
Sailfish OS with Raspberry Pi 2 (due to use ARM Cortex-A7 CPU; Raspberry Pi 1 uses different ARMv6 architecture and Sailfish requires ARMv7.)[126]
Tiny Core Linux – a minimal Linux operating system focused on providing a base system using BusyBox and FLTK. Designed to run primarily in RAM.
Alpine Linux – is a Linux distribution based on musl and BusyBox, primarily designed for "power users who appreciate security, simplicity and resource efficiency".
Void Linux – a rolling release Linux distribution which was designed and implemented from scratch, provides images based on musl or glibc.
Fedora 25 – supports Pi 2 and later (Pi 1 is supported by some unofficial derivatives, e.g. listed here.).
Media center operating systems
Daylight Linux – An ultra-lightweight operating system with the Fluxbox interface
Raspberry Digital Signage – An operating system designed for digital signage deployments.
Driver APIs[edit]
See also: VideoCore § Linux support

Scheme of the implemented APIs: OpenMAX, OpenGL ES and OpenVG
Raspberry Pi can use a VideoCore IV GPU via a binary blob, which is loaded into the GPU at boot time from the SD-card, and additional software, that initially was closed source.[127] This part of the driver code was later released.[128] However, much of the actual driver work is done using the closed source GPU code. Application software use calls to closed source run-time libraries (OpenMax, OpenGL ES or OpenVG) which in turn calls an open source driver inside the Linux kernel, which then calls the closed source VideoCore IV GPU driver code. The API of the kernel driver is specific for these closed libraries. Video applications use OpenMAX, 3D applications use OpenGL ES and 2D applications use OpenVG which both in turn use EGL. OpenMAX and EGL use the open source kernel driver in turn.[129]

Firmware[edit]
The official firmware is a freely redistributable[130] binary blob, that is closed-source.[113] A minimal open source firmware is also available.[131]

Third party application software[edit]
AstroPrint – AstroPrint's wireless 3D printing software can be run on the Pi 2.[132]
C/C++ Interpreter Ch – Released 3 January 2017, C/C++ interpreter Ch and Embedded Ch are released free for non-commercial use for Raspberry Pi, ChIDE is also included for the beginners to learn C/C++.[133]
Mathematica & the Wolfram Language – Since 21 November 2013, Raspbian includes a full installation of this proprietary software for free.[134][135][136] As of 24 August 2015, the version is Mathematica 10.2.[137] Programs can be run either from a command line interface or from a Notebook interface. There are Wolfram Language functions for accessing connected devices.[138] There is also a Wolfram Language desktop development kit allowing development for Raspberry Pi in Mathematica from desktop machines, including features from the loaded Mathematica version such as image processing and machine learning.[139][140][141]
Minecraft – Released 11 February 2013, a modified version that allows players to directly alter the world with computer code.[142]
RealVNC – Since 28 September 2016, Raspbian includes RealVNC's remote access server and viewer software.[143][144][145] This includes a new capture technology which allows directly-rendered content (e.g. Minecraft, camera preview and omxplayer) as well as non-X11 applications to be viewed and controlled remotely.[146][147]
UserGate Web Filter – On 20 September 2013, Florida-based security vendor Entensys announced porting UserGate Web Filter to Raspberry Pi platform.[148]
Software development tools[edit]
Arduino IDE – for programming an Arduino.
Algoid – for learning programming for kids and beginners.
BlueJ – for teaching Java to beginners.
Greenfoot – Greenfoot teaches object orientation with Java. Create 'actors' which live in 'worlds' to build games, simulations, and other graphical programs.
Julia – an interactive and cross-platform programming language/environment, that runs on the Pi 1 and later.[149] IDEs for Julia, such as Juno, are available. See also Pi-specific Github repository JuliaBerry.
Lazarus – a Free Pascal RAD IDE resembling Delphi
LiveCode – educational RAD IDE descended from HyperCard using English-like language to write event-handlers for WYSIWYG widgets runnable on desktop, mobile and Raspberry Pi platforms.
Ninja-IDE – a cross-platform integrated development environment (IDE) for Python.
Object Pascal[150] – an object oriented variant (the one used in Delphi and Lazarus) of Niklaus Wirth's original Pascal language. Free Pascal is the compiler in Lazarus
Processing – an IDE built for the electronic arts, new media art, and visual design communities with the purpose of teaching the fundamentals of computer programming in a visual context.
Scratch – a cross platform teaching IDE using visual blocks that stack like Lego™ originally developed by MIT's Life Long Kindergarten group. The Pi version is very heavily optimised[151] for the limited compute resources available and is implemented in the Squeak Smalltalk system.
Squeak Smalltalk – a full scale open Smalltalk.
V-Play Game Engine – a cross-platform development framework that supports mobile game and app development with the V-Play Game Engine, V-Play apps and V-Play plugins.
Xojo – a cross-platform RAD tool that can create desktop, web and console apps for Pi 2 and Pi 3.
C-STEM Studio – a platform for hands-on integrated learning of computing, science, technology, engineering, and mathematics (C-STEM) with robotics.
Reception and use[edit]
Technology writer Glyn Moody described the project in May 2011 as a "potential BBC Micro 2.0", not by replacing PC compatible machines but by supplementing them.[152] In March 2012 Stephen Pritchard echoed the BBC Micro successor sentiment in ITPRO.[153] Alex Hope, co-author of the Next Gen report, is hopeful that the computer will engage children with the excitement of programming.[154] Co-author Ian Livingstone suggested that the BBC could be involved in building support for the device, possibly branding it as the BBC Nano.[155] Chris Williams, writing in The Register sees the inclusion of programming languages such as Kids Ruby, Scratch and BASIC as a "good start" to equip kids with the skills needed in the future – although it remains to be seen how effective their use will be.[156] The Centre for Computing History strongly supports the Raspberry Pi project, feeling that it could "usher in a new era".[157] Before release, the board was showcased by ARM's CEO Warren East at an event in Cambridge outlining Google's ideas to improve UK science and technology education.[158]

Harry Fairhead, however, suggests that more emphasis should be put on improving the educational software available on existing hardware, using tools such as Google App Inventor to return programming to schools, rather than adding new hardware choices.[159] Simon Rockman, writing in a ZDNet blog, was of the opinion that teens will have "better things to do", despite what happened in the 1980s.[160]

In October 2012, the Raspberry Pi won T3's Innovation of the Year award,[161] and futurist Mark Pesce cited a (borrowed) Raspberry Pi as the inspiration for his ambient device project MooresCloud.[162] In October 2012, the British Computer Society reacted to the announcement of enhanced specifications by stating, "it's definitely something we'll want to sink our teeth into."[163]

In February 2015, a switched-mode power supply chip, designated U16, of the Raspberry Pi 2 Model B version 1.1 (the initially released version) was found to be vulnerable to flashes of light,[164] particularly the light from xenon camera flashes and green[165] and red laser pointers. However, other bright lights, particularly ones that are on continuously, were found to have no effect. The symptom was the Raspberry Pi 2 spontaneously rebooting or turning off when these lights were flashed at the chip. Initially, some users and commenters suspected that the electromagnetic pulse (EMP) from the xenon flash tube was causing the problem by interfering with the computer's digital circuitry, but this was ruled out by tests where the light was either blocked by a card or aimed at the other side of the Raspberry Pi 2, both of which did not cause a problem. The problem was narrowed down to the U16 chip by covering first the system on a chip (main processor) and then U16 with Blu-Tack (an opaque poster mounting compound). Light being the sole culprit, instead of EMP, was further confirmed by the laser pointer tests,[165] where it was also found that less opaque covering was needed to shield against the laser pointers than to shield against the xenon flashes.[164] The U16 chip seems to be bare silicon without a plastic cover (i.e. a chip-scale package or wafer-level package), which would, if present, block the light. Unofficial workarounds include covering U16 with opaque material (such as electrical tape,[164][165] lacquer, poster mounting compound, or even balled-up bread[164]), putting the Raspberry Pi 2 in a case,[165] and avoiding taking photos of the top side of the board with a xenon flash. This issue was not caught before the release of the Raspberry Pi 2 because while commercial electronic devices are routinely subjected to tests of susceptibility to radio interference, it is not standard or common practice to test their susceptibility to optical interference.[164]

In June 2017, Raspberry Pi won the Royal Academy of Engineering MacRobert Award.[166] The citation for the award to the Raspberry Pi said it was "for its inexpensive credit card-sized microcomputers, which are redefining how people engage with computing, inspiring students to learn coding and computer science and providing innovative control solutions for industry."[167]

Community[edit]
The Raspberry Pi community was described by Jamie Ayre of FLOSS software company AdaCore as one of the most exciting parts of the project.[168] Community blogger Russell Davis said that the community strength allows the Foundation to concentrate on documentation and teaching.[168] The community developed a fanzine around the platform called The MagPi[169] which in 2015, was handed over to the Raspberry Pi Foundation by its volunteers to be continued in-house.[170] A series of community Raspberry Jam events have been held across the UK and around the world.[171]

Use in education[edit]
As of January 2012, enquiries about the board in the United Kingdom have been received from schools in both the state and private sectors, with around five times as much interest from the latter. It is hoped that businesses will sponsor purchases for less advantaged schools.[172] The CEO of Premier Farnell said that the government of a country in the Middle East has expressed interest in providing a board to every schoolgirl, in order to enhance her employment prospects.[173][174]

In 2014, the Raspberry Pi Foundation hired a number of its community members including ex-teachers and software developers to launch a set of free learning resources for its website.[175] The Foundation also started a teacher training course called Picademy with the aim of helping teachers prepare for teaching the new computing curriculum using the Raspberry Pi in the classroom.[176]

The educational DIY computer kits made by London-based computing company Kano include the Raspberry Pi.[177][178][179]

Use in home automation[edit]
There are a number of developers and applications that are leveraging the Raspberry Pi for home automation. These programmers are making an effort to modify the Raspberry Pi into a cost-affordable solution in energy monitoring and power consumption. Because of the relatively low cost of the Raspberry Pi, this has become a popular and economical solution to the more expensive commercial alternatives.[180]

Use in industrial automation[edit]
In June 2014, TECHBASE, Polish industrial automation manufacturer designed the world's first industrial computer based on the Raspberry Pi Compute Module, called ModBerry. The device has numerous interfaces, most notably RS-485/232 serial ports, digital and analog inputs/outputs, CAN and economical 1-Wire buses, all of which are widely used in the automation industry. The design allows the use of the Compute Module in harsh industrial environments, leading to the conclusion that the Raspberry Pi is no longer limited to home and science projects, but can be widely used as an Industrial IoT solution and achieve goals of Industry 4.0.[181]

Use in commercial products[edit]
OTTO is a digital camera created by Next Thing Co. It incorporates a Raspberry Pi Compute Module. It was successfully crowd-funded in a May 2014 Kickstarter campaign.[182]

Slice is a digital media player which also uses a Compute Module as its heart. It was crowd-funded in an August 2014 Kickstarter campaign. The software running on Slice is based on Kodi.[183]

Astro Pi[edit]
A project was launched in December 2014 at an event held by the UK Space Agency. The Astro Pi competition was officially opened in January and was opened to all primary and secondary school aged children who were residents of the United Kingdom. During his mission, British ESA astronaut Tim Peake deployed the computers on board the International Space Station.[184] He loaded the winning code while in orbit, collected the data generated and then sent this to Earth where it was distributed to the winning teams. Covered themes during the competition included Spacecraft Sensors, Satellite Imaging, Space Measurements, Data Fusion and Space Radiation.

The organisations involved in the Astro Pi competition include the UK Space Agency, UKspace, Raspberry Pi, ESERO-UK and ESA.

History[edit]

This section is in a list format that may be better presented using prose. You can help by converting this section to prose, if appropriate. Editing help is available. (February 2015)

An early alpha-test board in operation using different layout from later beta and production boards
In 2006, early concepts of the Raspberry Pi were based on the Atmel ATmega644 microcontroller. Its schematics and PCB layout are publicly available.[185] Foundation trustee Eben Upton assembled a group of teachers, academics and computer enthusiasts to devise a computer to inspire children.[172] The computer is inspired by Acorn's BBC Micro of 1981.[186][187] The Model A, Model B and Model B+ names are references to the original models of the British educational BBC Micro computer, developed by Acorn Computers.[156] The first ARM prototype version of the computer was mounted in a package the same size as a USB memory stick.[188] It had a USB port on one end and an HDMI port on the other.

The Foundation's goal was to offer two versions, priced at US$25 and $35. They started accepting orders for the higher priced Model B on 29 February 2012,[189] the lower cost Model A on 4 February 2013.[190] and the even lower cost (US$20) A+ on 10 November 2014.[53] On 26 November 2015, the cheapest Raspberry Pi yet, the Raspberry Pi Zero, was launched at US$5 or £4.[191]

Pre-launch[edit]
July 2011: Trustee Eben Upton publicly approached the RISC OS Open community in July 2011 to enquire about assistance with a port.[192] Adrian Lees at Broadcom has since worked on the port,[193][194] with his work being cited in a discussion regarding the graphics drivers.[195] This port is now included in NOOBS.
August 2011 – 50 alpha boards are manufactured. These boards were functionally identical to the planned Model B,[196] but they were physically larger to accommodate debug headers. Demonstrations of the board showed it running the LXDE desktop on Debian, Quake 3 at 1080p,[197] and Full HD MPEG-4 video over HDMI.[198]
October 2011 – A version of RISC OS 5 was demonstrated in public, and following a year of development the port was released for general consumption in November 2012.[199][200][201][202]
December 2011 – Twenty-five Model B Beta boards were assembled and tested[203] from one hundred unpopulated PCBs.[204] The component layout of the Beta boards was the same as on production boards. A single error was discovered in the board design where some pins on the CPU were not held high; it was fixed for the first production run.[205] The Beta boards were demonstrated booting Linux, playing a 1080p movie trailer and the Rightware Samurai OpenGL ES benchmark.[206]
Early 2012 – During the first week of the year, the first 10 boards were put up for auction on eBay.[207][208] One was bought anonymously and donated to the museum at The Centre for Computing History in Cambridge, England.[157][209] The ten boards (with a total retail price of £220) together raised over £16,000,[210] with the last to be auctioned, serial number No. 01, raising £3,500.[211] In advance of the anticipated launch at the end of February 2012, the Foundation's servers struggled to cope with the load placed by watchers repeatedly refreshing their browsers.[212]
Launch[edit]
19 February 2012 – The first proof of concept SD card image that could be loaded onto an SD card to produce a preliminary operating system is released. The image was based on Debian 6.0 (Squeeze), with the LXDE desktop and the Midori browser, plus various programming tools. The image also runs on QEMU allowing the Raspberry Pi to be emulated on various other platforms.[213][214]
29 February 2012 – Initial sales commence 29 February 2012[215] at 06:00 UTC;. At the same time, it was announced that the model A, originally to have had 128 MB of RAM, was to be upgraded to 256 MB before release.[189] The Foundation's website also announced: "Six years after the project's inception, we're nearly at the end of our first run of development – although it's just the beginning of the Raspberry Pi story."[216] The web-shops of the two licensed manufacturers selling Raspberry Pi's within the United Kingdom, Premier Farnell and RS Components, had their websites stalled by heavy web traffic immediately after the launch (RS Components briefly going down completely).[217][218] Unconfirmed reports suggested that there were over two million expressions of interest or pre-orders.[219] The official Raspberry Pi Twitter account reported that Premier Farnell sold out within a few minutes of the initial launch, while RS Components took over 100,000 pre orders on day one.[189] Manufacturers were reported in March 2012 to be taking a "healthy number" of pre-orders.[168]
March 2012 – Shipping delays for the first batch were announced in March 2012, as the result of installation of an incorrect Ethernet port,[220][221] but the Foundation expected that manufacturing quantities of future batches could be increased with little difficulty if required.[222] "We have ensured we can get them [the Ethernet connectors with magnetics] in large numbers and Premier Farnell and RS Components [the two distributors] have been fantastic at helping to source components," Upton said. The first batch of 10,000 boards was manufactured in Taiwan and China.[223][224]
8 March 2012 – Release Raspberry Pi Fedora Remix, the recommended Linux distribution,[225] developed at Seneca College in Canada.[226]
March 2012 – The Debian port is initiated by Mike Thompson, former CTO of Atomz. The effort was largely carried out by Thompson and Peter Green, a volunteer Debian developer, with some support from the Foundation, who tested the resulting binaries that the two produced during the early stages (neither Thompson nor Green had physical access to the hardware, as boards were not widely accessible at the time due to demand).[227] While the preliminary proof of concept image distributed by the Foundation before launch was also Debian-based, it differed from Thompson and Green's Raspbian effort in a couple of ways. The POC image was based on then-stable Debian Squeeze, while Raspbian aimed to track then-upcoming Debian Wheezy packages.[214] Aside from the updated packages that would come with the new release, Wheezy was also set to introduce the armhf architecture,[228] which became the raison d'être for the Raspbian effort. The Squeeze-based POC image was limited to the armel architecture, which was, at the time of Squeeze's release, the latest attempt by the Debian project to have Debian run on the newest ARM embedded-application binary interface (EABI).[229] The armhf architecture in Wheezy intended to make Debian run on the ARM VFP hardware floating-point unit, while armel was limited to emulating floating point operations in software.[230][231] Since the Raspberry Pi included a VFP, being able to make use of the hardware unit would result in performance gains and reduced power use for floating point operations.[227] The armhf effort in mainline Debian, however, was orthogonal to the work surrounding the Pi and only intended to allow Debian to run on ARMv7 at a minimum, which would mean the Pi, an ARMv6 device, would not benefit.[228] As a result, Thompson and Green set out to build the 19,000 Debian packages for the device using a custom build cluster.[227]
Post-launch[edit]
16 April 2012 – Reports appear from the first buyers who had received their Raspberry Pi.[232][233]
20 April 2012 – The schematics for the Model A and Model B are released.[234]
18 May 2012 – The Foundation reported on its blog about a prototype camera module they had tested.[235] The prototype used a 14-megapixel module.
22 May 2012 – Over 20,000 units had been shipped.[236]
July 2012 – Release of Raspbian.[237]
16 July 2012 – It was announced that 4,000 units were being manufactured per day, allowing Raspberry Pis to be bought in bulk.[238][239]
24 August 2012 – Hardware accelerated video (H.264) encoding becomes available after it became known that the existing license also covered encoding. Formerly it was thought that encoding would be added with the release of the announced camera module.[240][241] However, no stable software exists for hardware H.264 encoding.[242] At the same time the Foundation released two additional codecs that can be bought separately, MPEG-2 and Microsoft's VC-1. Also it was announced that the Pi will implement CEC, enabling it to be controlled with the television's remote control.[63]
5 September 2012 – The Foundation announced a second revision of the Raspberry Pi Model B.[243] A revision 2.0 board is announced, with a number of minor corrections and improvements.[244]
6 September 2012 – Announcement that in future the bulk of Raspberry Pi units would be manufactured in the UK, at Sony's manufacturing facility in Pencoed, Wales. The Foundation estimated that the plant would produce 30,000 units per month, and would create about 30 new jobs.[245][246]
15 October 2012 – It is announced that new Raspberry Pi Model Bs are to be fitted with 512 MB instead of 256 MB RAM.[247]
24 October 2012 – The Foundation announces that "all of the VideoCore driver code which runs on the ARM" had been released as free software under a BSD-style license, making it "the first ARM-based multimedia SoC with fully-functional, vendor-provided (as opposed to partial, reverse engineered) fully open-source drivers", although this claim has not been universally accepted.[128] On 28 February 2014, they also announced the release of full documentation for the VideoCore IV graphics core, and a complete source release of the graphics stack under a 3-clause BSD license[248][249]
October 2012 – It was reported that some customers of one of the two main distributors had been waiting more than six months for their orders. This was reported to be due to difficulties in sourcing the CPU and conservative sales forecasting by this distributor.[250]
17 December 2012 – The Foundation, in collaboration with IndieCity and Velocix, opens the Pi Store, as a "one-stop shop for all your Raspberry Pi (software) needs". Using an application included in Raspbian, users can browse through several categories and download what they want. Software can also be uploaded for moderation and release.[251]
3 June 2013 – 'New Out Of Box Software or NOOBS is introduced. This makes the Raspberry Pi easier to use by simplifying the installation of an operating system. Instead of using specific software to prepare an SD card, a file is unzipped and the contents copied over to a FAT formatted (4 GB or bigger) SD card. That card can then be booted on the Raspberry Pi and a choice of six operating systems is presented for installation on the card. The system also contains a recovery partition that allows for the quick restoration of the installed OS, tools to modify the config.txt and an online help button and web browser which directs to the Raspberry Pi Forums.[252]
October 2013 – The Foundation announces that the one millionth Pi had been manufactured in the United Kingdom.[253]
November 2013: they announce that the two millionth Pi shipped between 24 and 31 October.[254]
28 February 2014 – On the day of the second anniversary of the Raspberry Pi, Broadcom, together with the Raspberry Pi foundation, announced the release of full documentation for the VideoCore IV graphics core,[clarification needed] and a complete source release of the graphics stack under a 3-clause BSD license.[248][249]


Raspberry Pi Compute Module

Raspberry Pi Model B
7 April 2014 – The official Raspberry Pi blog announced the Raspberry Pi Compute Module, a device in a 200-pin DDR2 SO-DIMM-configured memory module (though not in any way compatible with such RAM), intended for consumer electronics designers to use as the core of their own products.[56]
June 2014 – The official Raspberry Pi blog mentioned that the three millionth Pi shipped in early May 2014.[255]
14 July 2014 – The official Raspberry Pi blog announced the Raspberry Pi Model B+, "the final evolution of the original Raspberry Pi. For the same price as the original Raspberry Pi model B, but incorporating numerous small improvements people have been asking for".[54]
10 November 2014 – The official Raspberry Pi blog announced the Raspberry Pi Model A+.[53] It is the smallest and cheapest (US$20) Raspberry Pi so far and has the same processor and RAM as the Model A. Like the A, it has no Ethernet port, and only one USB port, but does have the other innovations of the B+, like lower power, micro-SD-card slot, and 40-pin HAT compatible GPIO.
2 February 2015 – The official Raspberry Pi blog announced the Raspberry Pi 2. Looking like a Model B+, it has a 900 MHz quad-core ARMv7 Cortex-A7 CPU, twice the memory (for a total of 1 GB) and complete compatibility with the original generation of Raspberry Pis.[256]
14 May 2015 – The price of Model B+ was decreased from US$35 to $25, purportedly as a "side effect of the production optimizations" from the Pi 2 development.[257] Industry observers have skeptically noted, however, that the price drop appeared to be a direct response to the C.H.I.P., a lower-priced competitor.[258]
26 November 2015 – The Raspberry Pi Foundation launched the Raspberry Pi Zero, the smallest and cheapest member of the Raspberry Pi family yet, at 65 mm × 30 mm, and US$5. The Zero is similar to the Model A+ without camera and LCD connectors, while smaller and uses less power. It was given away with the Raspberry Pi magazine Magpi #40 that was distributed in the UK and US that day – the MagPi was sold out at almost every retailer internationally due to the freebie.[58]
29 February 2016 – Raspberry Pi 3 with a BCM2837 1.2 GHz 64-bit quad processor based on the ARMv8 Cortex-A53, with built-in Wi-Fi BCM43438 802.11n 2.4 GHz and Bluetooth 4.1 Low Energy (BLE). Starting with a 32-bit Raspbian version, with a 64-bit version later to come if "there is value in moving to 64-bit mode". In the same announcement it was said that a new BCM2837 based Compute Module was expected to be introduced a few months later.[259]
February 2016 – The Raspberry Pi Foundation announces that they had sold eight million devices (for all models combined), making it the best-selling UK personal computer, ahead of the Amstrad PCW.[260][261] Sales reached ten million in September 2016.[7]
25 April 2016 – Raspberry Pi Camera v2.1 announced with 8 Mpixels, in normal and NoIR (can receive IR) versions. The camera uses the Sony IMX219 chip with a resolution of 3280 × 2464. To make use of the new resolution the software has to be updated.[262]
10 October 2016 – NEC Display Solutions announces that select models of commercial displays to be released in early 2017 will incorporate a Raspberry Pi 3 Compute Module.[263]
14 October 2016 – Raspberry Pi Foundation announces their cooperation with NEC Display Solutions. They expect that the Raspberry Pi 3 Compute Module will be available to the general public by the end of 2016.[264]
25 November 2016 – 11 million units sold.[9]
16 January 2017 – Compute Module 3 and Compute Module 3 Lite are launched.[265]
28 February 2017 – Raspberry Pi Zero W with WiFi and Bluetooth via chip scale antennas launched.
