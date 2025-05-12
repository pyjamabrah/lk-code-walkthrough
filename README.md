# LK Code walkthrough
This repo hosts forked LK repo with some minor tweaks to make the qemu based ARM64 target
boot on Github codespaces environment

The main goal is:
* Setup a clean environment on Codespaces (removing dependency on personal device) and maintaining a coherent and working setup
* Little tweaks here and there to experiment and track the flow while walking through the codebase
* Understand what goes under the hood when LK boots and how it interacts with the system (mainly focusing on ARM64 based systems)


# Instructions
* Open up the Github codespaces and hopefully that should be it (all the dependencies should be pre-installed).
* On the terminal, run `scripts/do-qemuarm -6` and that should compile LK and start qemu and boot to prompt


# Disclaimer
The content demostrated here is only for education and teaching purpose only :)