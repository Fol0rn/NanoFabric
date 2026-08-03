## Should I use the Vulkan API for 26.2?
This is one question we may have... "Should I use the Vulkan API for 26.2"\
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

**The Downside for OpenGL Explanation**\
Vulkan is still a new API, so it isn't as polished as OpenGL is, so some problems may occur.
But this one is the biggest problem for you with Vulkan, if your computer parts was released before 2016, then your system doesn't support Vulkan and not even let you play Minecraft when using the Vulkan API.
Plus because it is new for mod/plugin developers, they don't have the knowledge or how it fully works like they did with OpenGL, making them go back to square one by learning how Vulkan works and communicates."\
**Below is a photo for comparison of OpenGL and Vulkan FPS.**

OpenGL
![image alt](https://github.com/Fol0rn/NanoFabric/blob/e41d6d6847ad14a6173e74b431e38cea8534766f/OpenGLPhoto.png)
Vulkan
![image alt](https://github.com/Fol0rn/NanoFabric/blob/e41d6d6847ad14a6173e74b431e38cea8534766f/VulkanPhoto.png)
testing was done with NanoFabric 1.0.7
