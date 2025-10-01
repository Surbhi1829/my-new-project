# Painting with AI

Final project for the Building AI course

## Summary

This is a course project dedicated to exploring and implementing a specific Artificial Intelligence technique to innovate or assist in the field of digital painting and art creation.


## How is it used?

The "Painting with AI" solution is an intuitive tool designed to transform conceptual ideas into digital art almost instantly. The process of using it is simple:

    Input the Vision: The user accesses the application and enters a detailed text prompt describing the image they want (e.g., "A neon-lit cyberpunk street with flying cars, highly realistic digital painting").

    Generate: The user clicks the 'Generate' button. The underlying AI model (a generative model) processes the text prompt, translating it into a unique visual composition, style, and color palette.

    Download/Iterate: Within seconds, the AI presents the generated artwork. The user can either download the image or refine their initial prompt (e.g., by adding "Van Gogh style" or "darker tones") to generate endless variations until they achieve their desired result.

Situations and Environment

This solution is needed whenever there is a demand for rapid visual content creation or creative conceptualization without the time, budget, or skills required for traditional art.

    Environment: It is designed to be used in any digital environment, such as a web browser or a dedicated desktop application.

    Time: It excels in situations demanding fast prototyping, such as client pitches, tight content deadlines, and creative brainstorming sessions where instant visualization is key.

Who are the Users?

The tool is built for a wide range of users, bridging the gap between imagination and visualization:

    Concept Artists & Designers: They use it to quickly generate reference images, explore complex scenes, and overcome creative block.

    Writers & Storytellers: They use it to visualize characters, settings, and scenes for their books or scripts.

    Marketing & Content Creators: They use it to generate unique, copyright-free imagery for social media, blogs, and ad campaigns.

    Hobbyists & General Users: Anyone without drawing skills who wants to bring their imaginative ideas to life instantly for personal use.

User Needs to Consider

The solution is designed to be highly accessible, prioritizing an intuitive interface where natural language (text) is the primary input, while ensuring the output quality is high enough for professional or personal use.
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

    Technical Accuracy: The AI model often struggles with structural precision, specifically generating correct human anatomy (like fingers) and creating legible text or logos within the image.

    Prompt Interpretation: It can be difficult to make the AI model perfectly follow complex instructions, especially regarding the spatial relationship between multiple objects in the prompt.

    Ethical Concerns (Bias): The model may unintentionally perpetuate social biases (e.g., race, gender) that were present in its massive training dataset, leading to stereotypical outputs.

    Intellectual Property: Since the model is trained on existing art, using the output raises ongoing questions about originality and copyright ownership when the source material was used without direct permission from the original artists.


## What next?

Project Growth and Future Features

    Iterative Refinement and Editing Tools:

        Integrate a "masking and inpainting" feature that allows users to select specific areas of a generated image (like a face or an object) and edit them using a new text prompt, significantly enhancing creative control.

        Develop "Outpainting" capabilities to expand the image canvas beyond the original boundaries, creating larger, panoramic artworks.

    Increased Control over Style and Composition:

        Implement Style-Blending: Allow users to upload two reference images—one for content and one for style—to generate a completely new artwork that combines both.

        Add Pre-defined Parameters: Introduce sliders or numerical inputs for advanced users to control aspects like lighting, camera angle, color saturation, and level of detail.

    Community and Collaboration:

        Create a "Prompt Sharing" platform where users can post their generated art alongside the exact text prompt used, fostering a community of prompt engineers and accelerating learning.

    Addressing Limitations:

        Focus on fine-tuning the model specifically to reduce common errors, particularly generating correct human anatomy (hands) and legible text.

Required Skills and Assistance

To transition this project from a prototype to a deployable tool, the following skills and resources would be necessary:

    Advanced ML Engineering: Expertise in model fine-tuning (using concepts like LoRAs) and optimization for faster inference speed.

    Backend Development (API): Assistance in creating a robust, scalable API to handle high volumes of simultaneous generation requests.

    Cloud Infrastructure: Resources for deploying the model on powerful GPU-accelerated cloud services (like AWS, Azure, or GCP) to manage the intensive computational load.

    UI/UX Design: Professional design input to create a more polished, user-friendly interface that simplifies the prompt-writing and editing process.



## Acknowledgments

This project was made possible by the following resources and communities:

    Building AI Course: This project serves as the final submission for the Building AI Course by the University of Helsinki / Elements of AI, which provided the foundational knowledge for this development.

    Generative Model Architecture: Inspired by the pioneering work on Diffusion Models and large-scale text-to-image synthesis, specifically the research concepts introduced by models like Stable Diffusion and DALL-E.

    Training Data (Conceptual): Conceptual understanding derived from large-scale, publicly available image-text datasets like LAION-5B, which demonstrate the power of web-scraped data for training generative models.

    Tools and Libraries: Reliance on open-source Machine Learning frameworks, particularly PyTorch or TensorFlow, and associated libraries used for building and managing the model pipeline.

    Inspiration: The creative and ethical discussions within the wider AI Art Community regarding prompt engineering, intellectual property, and the future of human-AI collaboration in the arts.

