+++
title = "My thoughts about the Framework 13"
date = "2025-06-21"
description = "My experience with using the Framework 13 as my laptop"
tags = ["linux", "hardware"]
+++

# My thoughts about the Framework 13

![The Framework 13 laptop in the palm of my hand](img/framework.jpeg)

In 2020, I managed to get an old Lenovo Thinkpad X1 Yoga 1st Generation, a 2-in-1 convertible laptop from Lenovo. I got this laptop from a family member due to a broken fan that instead of spinning up, would spin up partially and then make this *horribly loud* "zzztt" noise, bring the fan to a stop, before the laptop would repeat the cycle all over again. Not only did the fan not work to cool the laptop, but it would also make everyone within a 20m radius look at you like you came from another planet, just because of how loud and weird the fan noise was. I managed to fix the fan issue by adding some lubrication to the fan motor, leaving me with a used but very competent and thin laptop.

The old Yoga Thinkpad was a good machine for a few reasons:
- Great keyboard, with big arrow keys and nice key feeling
- Built-in Wacom encoder in the touchscreen could be used with the included stylus (which charges in a slot inside the laptop, very cool) for 3d sculpting, note-taking, drawings, and precise touch input.
- Very robust I.O. with 3 usb-A ports, HDMI, Mini DP, microSD, and a proprietary barrel jack
- Bright 1080p display was easy to read

However, there were many things about the Thinkpad Yoga that were not ideal:
- Dual core, 4th gen i7 lacked enough compute for smooth usage in even basic applications
- Due to being worn, and powering an old processor, the battery did not last very long before dying (1-2 hours)
- A sharp edge right where I put my palms when typing made my palms hurt after more than 5 minutes
- The soldered 8GB of memory ran out quickly when opening several pages of Google Docs and other websites, which I needed to do for school

I had originally heard of the framework laptop promoted in a video from youtuber Linus Tech Tips and while the modular design interested me, I didn't like how expensive it was considering I already had a working laptop and I didn't even know first hand whether the Framework laptop was *even worth the premium price*. This meant that when 3 of my friends had ordered their own Framework 13s, I was able to get a hands-on look at the hardware and see if it was actually good. And it turns out, I initially liked the core parts that mattered: the keyboard, screen and IO. Since my friends are also Linux nerds, I also knew that a standard Fedora install works absolutely perfectly on the device, with things like the Fingerprint sensor working, which is something that didn't work on my Thinkpad.

Since I was soon changing schools and going to University, I wanted something more powerful and a bit more dependable than my aging Thinkpad Yoga, so I planned to buy a laptop for this purpose. I wanted something with moderate CPU and Graphics capabilities, but wanted to avoid a dedicated GPU for the extra power draw and complexity that would cause. I also wanted either something with a ridiculous amount of storage and RAM (32GB and 2TB respecively) or for that storage and RAM to be upgradable. I also wanted something dependable, since I was going to be using it daily, which meant nothing *too* sketchy in terms of software. I was going to continue using Linux on whatever computer I chose, so if a feature did not have Linux support, it might as well not exist.

Given my requirements, I had a few options that I considered:
- **MINISFORUM V3** - I liked how I could use a stylus for notes and 3d sculpting and I also liked the compact form factor, but the flimsy keyboard + trackpad, the non-upgradable storage and ram and the lack of information about Linux support made this a poor option.
- **M Series Macbook** - While apparently the base model Macbooks are pretty good value, expecially for the screen, materials, performance and Battery life, they had *waaay* too many caveats for me to buy one. While the base models are good value, the base models have a *laughable* amount of storage and memory, and the premium you pay to upgrade these non-upgradable components are absurd: *$200 to go from 8GB of memory to 16GB!? WTF!? I can buy a 16GB stick of DDR5 for less than $100*. Also, since NAND is a wear component, the laptop is basically a ticking time-bomb before it become a brick, though it would probably last long enough. Being somewhat privacy minded and adapted to using Gnome on Fedora, I was going to run Asahi Linux on the Macbook, but this meant I would be missing *basic* features, like proper hardware acceleration for 3d, camera, and other little quirks that I might not notice until I actually start using it daily. Considering how rotten Apple is and the glued-together nature of their products, the Macbook, while it looked like an ok option at a glance, is a **hard no** for me.
- **A Snapdragon X Elite Laptop** - These laptops had just come out around the time I was considering a laptop, and looked compelling given their efficient and powerful processors, but the complete lack of Linux support and early-adopter nature put me off completely.
- **HP Dev One** - While having official Pop_OS support looked promising, the fact that the laptop was from HP and all the horror stories I've heard about their laptops put me off from this option.
- **A System 76 Laptop** - While these have official support for System76's Pop_OS, the fact that they are just rebranded laptops, made me suspect of the build quality, which is an important part of my decision.

However, all of these options had compromises that I was not okay with. While the Framework 13 also had compromises, specifically, I didn't like the high cost and lack of touchscreen, however, having tried my friends' Framework 13s allowed me to know that what the Framework 13 did have, it did well. So that's what I bought.

I ended up purchasing a Framework 13 AMD with an AMD Ryzen 5 7040U and with RAM from Canada computers and the SSD from the Thinkpad. I kind of wonted to get the Intel version instead, especially with how well my Intel Arc A750 handles compute tasks, however, looking at benchmarks at the time, the AMD iGPU was almost x2 as good as the intel iGPU for Vulkan tasks, so I went AMD. All in, taxes and shipping, it came out to around $1400 CAD, which is a large sum of money, though I justified the cost with the potential value I will get out of a Framework laptop in the future: Mainly the ability to upgrade my initial 16GB of ram to 32GB for cheap, the ability to easily replace worn ports, the keyboard or screen without buying a new device and the ability to turn the motherboard into a standalone PC later once the laptop is no longer useful as a portable device. In order to get my choice of IO modules, bezel, keyboard, and Bring-Your-Own storage and RAM, I needed to get the "DIY" version, which while versatile, would require me to assemble some of the parts, though I'm pretty comfortable with that sort of stuff. Also, the AMD Ryzen 5 7040U is a beast of a processor, with 6 cores and decent enough integrated graphics for light gaming and Blender work, making this laptop future resistant.

When I got the disassembled laptop in the mail, I immediately started to assemble it. I pretty soon realized that I had bought DDR4 RAM instead of DDR5, so I had to delay assembly while I replaced the RAM. The kit came with everything I needed to easily and confidently assemble the laptop: Good instructions found online and a good included screwdriver. Assembly was straightforward except when I hit a snag: My bezel would not snap down completely. Turns out that the display cable was in the way, but at the time, there was no instruction to make sure the display cable was not in the way. Once I figured that out, I had a fully assembled laptop. Since I transplanted my SSD, I didn't even need to reinstall my OS.

I started using the Framework 13 for daily use immediately, and that's where I learned what I really liked about the laptop, and what I don't like as much:
- 🟩 **The Trackpad** is a joy to use: It's big, slippery, and has a good click. 
- 🟩 **The Speakers** Are loud and put my thinkpad speakers to shame. They have a pleasant sound on a hard, wood, surface, though it becomes very bass-heavy when put on cloth or other soft surfaces.
- 🟩 **The Keyboard** Is exactly what I want out of a keyboard, with a dedicated function row, print screen and delete keys, and a generic "super" key instead of that ugly "Windows" key" I do think the keyboard is a *sight* downgrade over my thinkpad, since it's a bit smaller and the micro arrow keys do feel kinda bad to use.
- 🟩 **The Build** is made of metal on the outside, leaving a durable surface where the laptop will come into contact with tables and bags, The White bezel that I got also looks amazing with the whitish metal.
- 🟩 **The Processor** is a Beast and does all I want it too. It runs my webapps and Blender great and can do light gaming very well, like Minecraft or Celeste. It can also run Mistral LLM fast enough to be actually useful.
- 🟩 **The IO** is good, though that could change based on your usage. I rarely plug anything more than a single USB-A or USB-c and headphones into my laptop, so that's all I really need.  It's also nice to know that I could add DP or HDMI if I wanted. It's also really nice to be able to charge all of my devices off the same USB-c charger.
- 🟩 **The Camera** is good enough: It's 1080p, has a hardware switch, and looks good enough in low light. I rarely use it though, so I don't really care how good it is.
- 🟨 **The screen** Is bright, High DPI, and taller than the 16:9 screen on my thinkpad, which I like. However, the screen can sometimes exhibit pretty bad ghosting and the screen is a pretty soft plastic on the outside, meaning it gets scratched from the keyboard and any debris you have in the laptop.
- 🟨 **The Battery** Lasts several hours, much better than my thinkpad, though I still wish the battery lasted longer.

Overall, the Framework 13 is a pretty good laptop for my needs and has been a great, no-bullshit option for my portable computing needs.
