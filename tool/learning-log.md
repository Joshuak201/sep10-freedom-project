# Tool Learning Log

## Tool: **A-frame**

---

### 3/9/35:
#### Overview
* [A-frame introduction video](https://www.youtube.com/watch?v=QaXnXuHMkaI) + [Pickcode](https://app.pickcode.io/home/sandbox)
     * Watched this video to give me a brief overview of a-frame
       * Found out how to add entities and how to utilize light to create scenes
 * I tinkered with the starter code of a-frame which was:
```
<html>
  <head>
    <script src="https://aframe.io/releases/1.7.0/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
      <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
      <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>
  </body>
</html>
```
* I then tried to recreate the code from the video above with limits(like not switching tabs too much to challenge myself. Here is the result:
```
  <a-scene background="color:black">
      
      <a-box position="-1 0 -4" color="red"
            shasow="cast:true;"
      ></box>

      <a-entity
            geometry="primitive:sphere; radius:1;"
            material="color:lightgrey; emissive:lightgrey;"
            position="4 4 -4"
            ></a-entity>
            

      <a-plane
           width="40"
           height="40"
           color="red"
           position="0 -1 -4"
           rotation="-90 0 0
           shadow="recieve:true;"
           ></a-plane>

      <a-entity
            light="typepoint; shadow:true; color:grey; intensity:1; distance:50"
            position="4 4 -4"
           ></a-entity>
  ```
#### Challenge
* This was a challenge for me as the code didnt display properly
    * The resulting code didn't display my shadows correctly and the light wasn't blended well enough
        * Furthermore, the shading off the moon is also wonky.
#### Questions
* How do I blend my background colors + textures together?
* What was wrong with my code?
* How do I utilize an entity more than what I did?
#### What I will try next
* I will learn more about how to create more 3D elements on one project/webpage.
    * I will watch videos and continue to tinker.
* Study more
    * Take notes in class about general things like the importance of my tool and the role it will play into my webpage.
 
### 3/24/25
#### Overview
* I started learning how to make a fresh project by notusing any a-frame starter code.
    * This will help me along the lines because I will need fresh code for the freedom project.
* I tinkered with my code and made some progress.
* I made a scene with grass and a sun. Here's how it looks:
  ![Screenshot 2025-03-28 1 12 04 PM](https://github.com/user-attachments/assets/aa7a16b5-7fd9-4bdb-86d2-00b73ff30849)
#### Challenge
The only challenge I had was that I did it fully from scratch. This was difficult but very helpful because it giving me pratice for my end of the year project.
#### Questions
* How do I create oe single model that will allow me to move it around and observe it?
* How do I create a fully polished scene?
* Can I import png and other models to manipulate my own model?
#### What I will try next
* Next, I will try to create one single model of tool. I will create a few to test out how they look and if I even want them to look like that.
* I will try to create a scene with the moon instead of the sun.

  
 


<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
