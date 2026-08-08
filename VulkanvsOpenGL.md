## Should I use the Vulkan API for 26.2?
This is one question we may have... "Should I use the Vulkan API for 26.2?"\
This document was made for the users who have this question. We will explain the upside and downside of Vulkan and OpenGL for Minecraft 26.2, and tell you which API is best for you.


### **OpenGL API**
**Upside**:\
Better compatibility with System and Mods\
Stable API\
More mods than Vulkan\
Better understanding at coding for mod/plugin developers

**Downside**:\
Worse FPS than Vulkan\
Very ancient API\
Bigger limits than Vulkan for mod/plugin developers

---

### **Vulkan API**
**Upside**:\
Better FPS and stability for some PC systems\
Fewer limits compared to OpenGL for mod/plugin developers\
Modern API

**Downside**:\
Not yet fully stable as OpenGL\
Actually harms FPS for some PC systems\
Less compatibility on systems compared to OpenGL\
Mods/Plugin developers doesn't have the experience like with OpenGL\
Less mods

---


**The Upside for OpenGL Explanation**\
OpenGL is more compatible to systems who was in the 90s to 2026, this helps users who has an old computer still run Minecraft and enjoy the game. 
And of course, because this API is older, it will be more stable from the recourse and time the developers put in the API to be stable.

Minecraft started using OpenGL since the game was made and seemed like they wouldn't change the API, so it'll be obvious that why learning Vulkan, an unsupported API to make mods was dumb,
this gave a chance for mod developers to learn and master how the OpenGL works, until Mojang announced about changing to Vulkan.

**The Upside for Vulkan Explanation**\
Vulkan is much better in FPS than OpenGL can do, for some systems it can improve FPS by a few to hundreds of more FPS, it does achieve this by using all threads and cores of your CPU unlike OpenGL.
And because it is a modern API, it has fewer limits from what you can do, it can improve the looks and performance of Minecraft even more than OpenGL could've done!

---

**The Downside for OpenGL Explanation**\
All though there are good about OpenGL, there is bad... the biggest problems, FPS wise and its old age as a main API.
All though the API is stable, it doesn't mean it gives the best FPS for Minecraft. OpenGL is known for using 1 thread on your CPU for rendering chunks,
as OpenGL was built for pc's with 1 thread in the 90s instead of 6-12 threads we have today.
This causes the main FPS, 1%, 0.1%, and stability to be terrible when rendering chunks or just standing in one spot. All though good for its time in the 90s, its not great for FPS in modern times now.

Another problem with OpenGL is that there are limits to what you can do with it. Because no one is now developing OpenGL, it doesn't get the new features like Vulkan that may improve the looks and performance for Minecraft.

**The Downside for Vulkan Explanation**\
Vulkan is still a new API, so it isn't as polished as OpenGL is, so some problems may occur.
And because it is new for mod/plugin developers, they don't have the knowledge or know how it fully works like they did with OpenGL, making them go back to square one by learning how Vulkan works and "communicates."

But this one is the biggest problem for you with Vulkan, if your computer parts was released before 2016, then your system doesn't support Vulkan and not even let you play Minecraft when using the Vulkan API. One other problem is that some AMD and Intel graphic cards can cause FPS loss for some, does it mean that all GPU's by AMD and Intel are affected? No, some does actually gain FPS but some
might actually lose FPS, and is best to try both before playing any games.\
**Below is a photo for comparison of OpenGL and Vulkan FPS.**

OpenGL
![image alt](https://github.com/Fol0rn/NanoFabric/blob/e41d6d6847ad14a6173e74b431e38cea8534766f/OpenGLPhoto.png)
Vulkan
![image alt](https://github.com/Fol0rn/NanoFabric/blob/e41d6d6847ad14a6173e74b431e38cea8534766f/VulkanPhoto.png)
testing was done with NanoFabric 1.0.7

This images show the FPS count, it may seem confusing for new users but its super easy when you understand it.\
The top is the average FPS. The p50, 1%, 0.1% are the actual reasons why it feels like its stuttering even though you have high average FPS. The p50 is not very important, but the 1% and 0.1% are the main focus. Also p98 is 1% and p99.5 is 0.1%, just to keep this a simple explanation.

If you have, lets say in this case... 250 FPS, the 1% and 0.1% has to be close in FPS to the average FPS, if there's a smaller gap between the 1%, 0.1%, and the average FPS, the better! The bigger the gap, the worse the lag may feel.\
A simple example if still confused is lets say you have a professional runner running, then he stops for a split second and then goes back to running and so on, all though the average speed is still quick, the runner is still stopping for no reason for a split second before running again making him go choppy and inconsistent, but if the gap in FPS is small, its like if the runner was still running and not stopping randomly. 

## Should I switch API?

I would recommend by saying **No**, all though NanoFabric versions are Vulkan, they are there for performance boost. **IF** you care about stability and not experiment that potential risk with Vulkan to your system, I would say OpenGL by miles. They have more mods, its more stable, and more compatible to your system if older.

But if you want to experiment, get that "free" FPS boost, don't care about the potential mods that aren't compatible... then go ahead for it. It is ready with just a few steps, and it does help for some systems by a lot! And plus, in the future Vulkan will be more stable  and mods will move to Vulkan too when developers fully understand how to work with it.


### Research Sites:
https://nemez.net/posts/20260410-minecraft-snapshot-opengl-vs-vulkan-nvidia-amd-intel/ \
https://mojira.dev/MC-308202 \
https://gurugamer.com/pc-console/minecraft-java-edition-graphics-guide-opengl-vs-vulkan-which-one-should-you-use-26627
