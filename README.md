# FaceSpark
## OUTFIT RECOMMENDER
### Pre-processing: 
* In male and female celebrities folders, each of the celebrities have their own folder of images.
* Their body proportions (chest, waist, hip and shoulder-length) are measured with respect to their height (given as input).
* A dataset is created, and these measurements are added.

### Recommendations:
A person's image (path to image) as well their height is given as input, the body proportions are measured and compared with the celebrities’ proportions, and most similar celebrity and their Indian outfits are given as recommendations.
### Future work:
* The images could have been refined and pre-processed (clearer images with less background noise).
* Celebrities could have been added in both female and male folders with diverse body proportions and facial features could have been used.
* Making the body proportions 3d. (With limited time constraint, only front facing images were used, so the body proportions are 2d)
Style as a factor could have been included.

### Errors Faced:
* The body measurements are approximate, not accurate.
* 4 female and 5 male celebrities’ images were given as input, but the female and male CSV containing the body proportions contained that of only 3 female and 3 male celebrities.
* The images of recommended celebrity could not be displayed. Only the name of the celebrity is given as output.
