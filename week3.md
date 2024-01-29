![image](https://github.com/cehrensperger/reflections/assets/19954402/067df1bd-1b2c-4ffe-bc06-cd131d0154e7)</br>

This data visualization comes from a paper by OpenAI on new methods they are using to train their large language models. My general understanding of the context is 
that there are two main training methods they want to determine the performance of and they do so by testing the methods on a set of 1860 problems. They then have the 
model attempt each question 10 times in a row, 100 times in a row, and up to 1000 times in a row. The model tries to pick the best response it generated out of those 
as its final answer. Given this context, the visualiation clearly shows that the process-supervised reward method outperforms the outcome-superviced reward method, as 
well as the majority voting baseline method. What's interesting to me about this visualization is the way they show variance and what appears to be a logarithmic 
horizontal scale. I don't I have seen this kind of continuous representation of variance, but I like how it depicts they way it changes as the number of tries the 
model has increases. This is especially visible for the baseline method. A nice design choice was also to make this way of depicting variance slightly transparent 
like we have been doing for the scatter plot markers for assignment 2. As for the logarithmic scale, I know this is often times frowned upon and I have to 
agree with that sentiment for this visualization. It is fairly difficult to imagine how this visualization would look withou logarithmic scaling and I have to 
trust that logarithmic scales were the right choice for this data, and not a way to exaggerate/bend the truth.</br></br>

![image](https://github.com/cehrensperger/reflections/assets/19954402/0f43fe0b-545f-4a3c-b3aa-4d631ed2c389)</br>
Further down in this paper, they use this same kind of visualization, but across different question difficulties. I think this gives a lot of insight into what they are 
trying to communicate which is that this training method has a positive impact on performance even as question difficulty increases. The design decision I like here 
the most is the decision to simplify each individual graph. This allows the trend between difficulties to be the focus of the reader's attention, while still being 
able to look more closely at each graph if desired. One thing I might consider is making an interactive visualization to communicate this idea which animates between 
the different difficulties. I think this could give the viewer a greater sense of the direction of change between each difficulty through the eye-catching mechanism of 
motion.
