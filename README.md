# Orange Pi Zero 2W Community Wiki
A community supported full wiki for OrangePi Zero 2w and Zero3.

This GitHub repository contains all the information you need about the Orange Pi Zero 2W board. I have used other projects in my wiki. Don't forget to check out their GitHub repositories, too!

If you ever have a question about this SBC, Don't hesitate to ask the community or me directly.

### Table of Contents:
  1. Operating Systems and Building Them.


## 1.Operating Systems and Building Them.

### a. Choosing Your OS

Choosing your os if you're going to use your sbc as game console or multimedia player.I probably recommend you to use Android roms such as https://blogs.yajatkumar.com/ (Yajatkumar's OmniRom)
But if you're with Linux then avoid using official google drive builds they are so outdated.(don't use official android rom too)
Instead Use Armbian xfce https://www.armbian.com/orange-pi-zero-2w/ but I prefer building my own Armbian or OrangePi OS. Sometimes Armbian breaks itself or not performs well as Orange Pi OS in my opinion.

### b. Building Your Own OS

To build your own OS you need a Ubuntu machine or if you're using Arch Linux/Debian or Maybe Windows you need a virtual machine like Qemu Virt-Manager or WSL.
Its easy as followng the steps of https://github.com/armbian/build or https://docs.armbian.com/Developer-Guide_Build-Preparation/ .

### c. Prebuilt Images
You can download images from https://www.armbian.com/orange-pi-zero-2w/ here or directly from this Repository.

### d. Flashing Images
I usually use Balena Etcher for Linux images, but I haven't found a way to flash Android images on Linux yet. https://github.com/YuzukiTsuru/OpenixCard It doesn't work for me. If you ever manage to get it to work, let me know.
