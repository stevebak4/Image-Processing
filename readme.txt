# Project Folder Contents

This folder contains the resources and materials used in our style transfer project, where we applied neural style transfer techniques to combine the artistic style of one image with the content of another.

## Contents

1. **Images**  
   - **starry_night.png**: The image used to extract the artistic style (Van Gogh’s "Starry Night").  
   - **thames_river.png**: The image used for the content (a view of the Thames River).  
   - **best_output.png**: The best result obtained using all convolutional layers from `1_1` to `5_2`, with style and content weights set as `style = 5` and `content = 2`.

2. **Project Documentation**  
   - A detailed document explaining the project objectives, methods, and results.

3. **Presentation Slides**  
   - A set of slides used for presenting the project, highlighting key steps, results, and insights from the process.

4. **Colab Notebook**  
   - **final.ipynb**: The Google Colab notebook used for executing the neural style transfer process, including the model and parameter tuning.

5. **Best Output Image**  
   - **best_output.png_2**: This is the final output image obtained using the following configuration:  
     - **Content layer**: `5_2`  
     - **Style layers**: All layers  
     - **Weighting**: `weight_style = 5`, `weight_content = 2`

## Notes
- The project utilizes neural style transfer, where style and content weights are fine-tuned to produce the most visually appealing result. The settings used in the best output image can be replicated in the provided Colab notebook.
