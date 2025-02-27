# Segmentation-Network-Mars-Terrain
Description
In this assignment, you will receive 64x128 grayscale real images from Mars terrain. Pixels in these images are categorized into five classes, each representing a particular type of terrain. This is a semantic segmentation problem, so your goal is to assign the correct class label to each mask pixel.

⚠️ Please note that for this Homework, as stated in the Rules section, all pretrained models are forbidden. Neural networks must be trained from scratch, without relying on existing trained architectures.

Evaluation
For each team, the evaluation of this homework comprises the final leaderboard score and the report score, as in Homework 1. The combined total of these scores will range from 0 to 5.5 and will be added to your written exam score.

🥇 Leaderboard Metrics
Your models will be evaluated according to the mean intersection over union metric, computed as
1|C|∑c∈C1(y=c)∧1(y^=c)1(y=c)∨1(y^=c),
given the set of classes, the ground truth, and the model predictions.

Please note that the background class, identified with the label 0 will be ignored in the evaluation, following the same procedure outlined in the exercise session on semantic segmentation.

We strongly advise to start from this notebook containing a minimal working example with the correct metric evaluation and csv construction procedure.

To prevent overfitting, during the entire competition period your submissions will be evaluated on a specific subset of the test set. The final results evaluated on a separate test subset will be available on December 14, 23:59.

Please remember that for this Homework, pretrained models are forbidden. All neural networks must be trained from scratch, without relying on existing trained architectures.
