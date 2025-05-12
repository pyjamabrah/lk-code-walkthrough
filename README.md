# LK Code walkthrough
This repo hosts forked LK repo with some minor tweaks to make the qemu based ARM64 target
boot on Github codespaces environment

The main goal is:
* Setup a clean environment on Codespaces (removing dependency on personal device) and maintaining a coherent and working setup
* Little tweaks here and there to experiment and track the flow while walking through the codebase
* Understand what goes under the hood when LK boots and how it interacts with the system (mainly focusing on ARM64 based systems)


# Instructions
* Open up the Github codespaces.
* Install dependencies:
  * `sudo apt update`
  * `sudo apt upgrade`
  * `sudo apt install qemu-system-aarch64`
  * `sudo apt install gcc-aarch64-linux-gnu`
  * `sudo apt install crossbuild-essential-arm64`
* On the terminal, run `scripts/do-qemuarm -6` and that should compile LK and start qemu and boot to prompt.
  * Run `help` on prompt to check if its working
* Ctrl A + X to quit QEMU


# Disclaimer
The content demostrated here is only for education and teaching purpose only :)