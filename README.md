# Maze-of-Stars-(繁星)
Inspired by Hu, Wang, and Wu's 2014 study of Dream of the Red Chamber using SVMs and a pseudo aggregate SVM-RFE approach, aims to apply similar methods to conduct stylometric analysis on novels of China's 20th century writers. 

Link to Hu, Wang and Wu's paper: https://arxiv.org/abs/1412.6211

## Highlights
- Aims to expand upon paper's algorithm to a one-v.s.-rest approach to develop models for each author
- Proposes and demonstrates effectiveness of a cutoff value function for data preparation

## Limitations
- Size difference in data between a single author and the other 14 may lead to higher inaccuracy
- Difference in output between authors demands extra attention to be paid to preventing features being skewed to any particular author
- Current approach does not take anything regarding sentence structure as a feature
- *GitHub specific:* Samples folder contains too many files to upload

## Coming Soon
- Implementation of the paper's pseudo aggregate SVM-RFE approach to refine models
- Once models for all 15 authors are finalized, any additional input could yield ranking of style similarity

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Can help trace evolution of vernacular Chinese novel writing since A Madman's Diary was published in 1918 

## Further Down the Road
- Mathematical proof for why the cutoff function performs so well (only demonstrated through simulation so far)
- Read paper's citation [10] (Juola) and [14] (Stamatatos) to look to include more advances in stylometric analysis
