**1. Spotlight the Hero:** Focus on your customer as the main character of your story. How does your product or service fit into their epic tale?

**Prompt:** <Task>Identify the "hero" customer or user in [insert_brands] product story based on the provided product details. Focus on the customer as the main character of the brands story and identify how does your product or service fit into their epic tale?</Task>

<Inputs> {$PRODUCT_DETAILS} </Inputs> <Instructions> You will be analyzing a set of product details to identify the "hero" customer or user that the brand is positioning as the central focus of their product story. The "hero" is typically the type of person or user that the product is designed to serve and benefit the most. 

<step>Carefully review gather the product details from the suggested following places:

1. The products website
2. Review websites like TrustRadius and G2
3. Written articles about the product online 

to understand the target audience, primary use cases, and key benefits for customers.</step>

<step>Identify the specific type of customer or user that seems to be the main focus or emphasis of the product description. This could be based on demographic details, lifestyle characteristics, or the specific problems/needs the product is meant to address.</step>

<step>Consider how this "hero" customer or user is portrayed and positioned within the product details. Look for language that highlights their importance, unique challenges, or centrality to the product experience.</step>

<step>Summarize the "hero" customer or user in 1-2 sentences, explaining why they appear to be the primary focus or most important beneficiary of the product based on the information provided. Write your summary inside <answer></answer> tags.</step>

<step>If you are unable to clearly identify a "hero" customer or user, state that the provided product details do not contain enough information to determine the hero of the product story.</step>

BEGIN ANALYSIS  
{$PRODUCT_DETAILS}  
</Instructions>

**2. Identify the Villain:** Pinpoint the challenges or problems your hero faces that your product can help overcome.  
   
**Prompt:** <Task>Identify the key challenges or "villain" that the hero customer faces, which the [insert_product] product is designed to help address</Task>

<Inputs> {$PRODUCT_DETAILS} </Inputs> <Instructions> You will be analyzing the provided HubSpot CRM product details to identify the main challenges, problems or "villain" that the hero customer faces, which the product aims to solve.

<step>Carefully review the product details to understand the target customer or user that is positioned as the "hero" of the product story.</step>

<step>Identify the specific challenges, pain points or problems that this hero customer seems to be facing, based on the product description and how it positions the value it provides.</step>

<step>Consider how these challenges or problems are framed within the product messaging. Look for language that highlights the difficulties, frustrations or inefficiencies that the hero customer experiences prior to using the HubSpot CRM.</step>

<step>Summarize the key "villain" or challenges that the hero customer faces in 1-2 sentences, explaining how the HubSpot CRM product is positioned to help overcome these issues. Write your summary inside <answer></answer> tags.</step>

<step>If you are unable to clearly identify the "villain" or challenges based on the provided product details, state that the information given is insufficient to determine the key problems the product is designed to solve for the hero customer.</step>  
   
BEGIN ANALYSIS  
{$PRODUCT_DETAILS}  
</Instructions>

**3. Craft the Journey:** Describe how your product aids the hero in their quest, detailing the struggle and eventual victory.

**Prompt:** <Task>Describe the hero's journey and how the HubSpot CRM product helps them overcome the key challenges they face</Task>

<Inputs> {$PRODUCT_DETAILS} {$HERO_PROFILE} {$VILLAIN_CHALLENGES} </Inputs> <Instructions> You will be crafting a narrative that describes the hero's journey and how the HubSpot CRM product enables them to overcome the key challenges or "villain" they are facing.

<step>Review the provided details about the hero customer profile and the challenges or "villain" they are up against, as identified in the previous prompts.</step>

<step>Imagine the hero's journey - the struggles they face, the frustrations they experience, and the obstacles they must overcome in their day-to-day work or business. Paint a vivid picture of their struggle.</step>

<step>Describe how the HubSpot CRM product enters the hero's journey and serves as the ally or guide that helps them confront and defeat the "villain" - the key challenges they were facing.</step>

<step>Explain how the specific features, capabilities and benefits of the HubSpot CRM product empower the hero to overcome their struggles and achieve victory. Highlight the transformative impact the product has on the hero's life or business.</step>

<step>Craft a 3-5 paragraph tedtalk that tells the hero's complete journey, from their initial challenges to their ultimate triumph with the help of the HubSpot CRM. The story should captivate the audience. Write this narrative response inside the <story></story> tags.</step>  
   
BEGIN STORYTELLING  
</Instructions>

**4. Highlight the Transformation:** Conclude with the positive change in the hero’s life, thanks to your product.

**Prompt:** Great, now from that story highlight the positive change in the hero’s life, thanks to your product. Do them as a bullet point list.