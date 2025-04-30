<Task>Create a brand story for a product the user submits following Seth Godin’s approach to brand storytelling with four clear sections - ‘setting the scene’, ‘introducing the challenge', ‘overcoming obstacles’, and finally ‘the transformation’.   
   
<Inputs>{Product_Name}</Inputs><Instructions>  
   
<step>Setting the Scene: Create a narrative for ‘Setting the Scene’. This section should introduce the product's customer and brand and the problem space the product operates within. It should be easy to understand and jargon free. It should entice the reader to consume the entire story and learn about how the product could make their life better. Add this narrative to the variable $scene to be used later in this prompt</step>  
   
<step>Introducing the Challenge: Next you need to clearly introduce the core challenge the customer of the product has, the challenge this product will solve. Introducing the challenge the hero customer faces is crucial because it creates tension that demands resolution. This tension captures the audience's attention and keeps them engaged, as they’ll want to see how the challenge is overcome. It's also an opportunity to highlight the specific problems the product solves. Add this narrative to the variable $challenge to be used later in this prompt</step>  
   
<step> Overcoming Obstacles:Next you’ll move to the part where the story delivers on its promise, showcasing how the hero confronts and overcomes the challenge. It's a demonstration the product in action, providing concrete examples of how obstacles are surmounted. This part of the story builds credibility and illustrates the effectiveness of the product to solving the customers problem. It's also where empathy and inspiration come into play, as the audience sees the journey of overcoming obstacles as both relatable and aspirational. Add this narrative to the variable $obstacles to be used later in this prompt</step>  
   
<step>The Transformation: This is the culmination of the story, the transformation, is the payoff for the audience. It’s the evidence that change is possible, and it directly ties the journey to a positive outcome. This is where you highlight the benefits and value of the product, showing not just a change in circumstances, but a change in the hero's life or state of being. The transformation is what turns the story from a narrative into a testimonial of success, illustrating not just what your product does, but why it matters. Add this narrative to the variable $transformation to be used later in this prompt</step>  
   
<step>Present your completed brand story including the product name into a table that should be structured as follows:  
   
First Row: [Setting the Scene][Introducing the Challenge][Overcoming Obstacles][The Transformation]  
Second Row:[$scene][$challenge][$obstacles][$transformation]  
   
Also provide a visual storyboard to illustrate this brand story to a CEO in an easy to understand jargon free way.</step>  
   
BEGIN BRAND STORYTELLING  
Product Name: {$PRODUCT_NAME}  
</Instructions>