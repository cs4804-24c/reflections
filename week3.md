https://www.youtube.com/watch?v=VYQVlVoWoPY

This week, I decided to torture my fellow classmates by looking at proofs. Specifically, 3Blue1Brown's "How to lie using visual proofs". There isn't time in class to watch a 20 minute video, so I'm going to focus on the first proof in the video and summarize what happens via text.

In the first proof, 3B1B shows that the surface area of a sphere is $\pi^2r^2$.

First, he divides the surface of the sphere into trianges, and arranges them to form a parallelogram.
![image](https://github.com/AndrewSalls/reflections/assets/77992504/cca1c14b-bcb1-4b85-9ba5-494ef0aff89a)

Then, he repeats this process with more and more triangles, recreating the idea of a limit to show that the parallelogram eventually looks like a rectangle. From there, he simply calculates the area of the rectangle as $\pi^2r^2$.
![image](https://github.com/AndrewSalls/reflections/assets/77992504/e01c8ced-2bb7-4513-ad45-90d9bd86b104)

This would be a very elegant visual proof... if it weren't for the fact that the surface area of a sphere is $4\pi r^2$. The trick here relies on human's poor ability to identify differences in 3d shapes and curves.
Despite looking like triangles on the 3d render of the sphere, the shapes on the spheres actually have curved sides. As a result, there is actually a lot of overlap between "triangles" that isn't accounted for, as seen below:
![image](https://github.com/AndrewSalls/reflections/assets/77992504/cd84e921-23e3-4fce-8033-21abb3f4e3b0)

I think that this video is important for showing just how easy it is to mislead people with visualizations. Both this proof, and the others in the video, rely on people's intuition making them assume properties (such as the wedges being triangles) are true.
Generally, when people think of misleading visualizations, they think of manipulating the numbers to make small differences look like large differences and vice versa.
A common trick for political advertisements is to create a bar chart where the axis are scaled to make a 1-2% polling difference seem massive. Viewers see the two bars on opposite sides of the y axis, and even though the actual numbers are similar, they assume that the higher bar has much more success in the polls.

This video shows that misleading visualizations aren't limited to those types of data-driven number manipulations. If any information is trying to be conveyed accurately via visualization, all of the details in the visual have to be considered for their influence on the viewer's intuition.
For instance, a common misleading visual very similar to the one from this video are high school geometry problems. I think most people will have seen an image that says something along the lines of "Calculate the perimeter of the shape below (image not to scale)", and then when they solve the problem they realize that the shape looks nothing like the image.
That isn't too big of a deal in high school, but imagine an engineer getting messed up by a poorly drawn image when designing healthcare equipment or a rocket engine.

As for the quality of this visualization, obviously it is supposed to be misleading, but 3B1B also includes an explanation of how the proof is wrong, using animation to show where the proof goes wrong and how it differs from other, similar looking proofs. All of the animation does a good job at (ironically) helping people understand the math visually, since most viewers probably aren't interested in reading a paper that meticulously disproves the false proofs.
