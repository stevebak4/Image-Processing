Contents of this folder:

1.The two images used for style (starry night) and content (thames river) and the best output result we took by using all layers from 1_1 to 5_2 and tuning the weights of style and content such as style = 5 and content = 2.

2.The document made for this project.
3.The presentation slides.
4.A colab notebook named 'final.ipynb' wich was used to extract the results.
5.A folder named image processing_drive with all the extracted results.

In the non-weighted examples defeult weight was weight_style = 2 and weight_content = 5.
An example of the notation used in the folders is the following.
output_1 ->content(5_2) - style(1_1,2_1,3_1,4_1,5_1)
output_2 ->content(5_2) - style(1_2,2_2,3_2,4_2,5_2)
output_3 ->content(5_2) - style(1_2,2_2,3_3,4_3,5_4)
output_11 ->content(5_2) - style(1_1)
output_21 ->content(5_2) - style(2_1)
output_31 ->content(5_2) - style(3_1)
output_41 ->content(5_2) - style(4_1)
output_51 ->content(5_2) - style(5_1)
output_31_41 ->content(5_2) - style(3_1,4_1)
output_1_2 ->content(5_2) - style(1_1,1_2,,2_1,2_2,3_1,3_2,4_1,4_2,5_1,5_2)
output_1_2_3 ->content(5_2) - style(1_1,1_2,,2_1,2_2,3_1,3_2,4_1,4_2,5_1,5_2,5_3)
weighted_1 ->content(5_2) - style(all layers) and weight_style = 5, weight_content = 5
weighted_2 ->content(5_2) - style(all layers) and weight_style = 5, weight_content = 2
weighted_3 ->content(5_2) - style(all layers) and weight_style = 8, weight_content = 2
weighted_4 ->content(5_2) - style(all layers) and weight_style = 2, weight_content = 8
