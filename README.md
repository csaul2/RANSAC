# RANSAC

In this project I implemented random sample consensus (RANSAC) to find inliers of a dataset and to then perform a linear regression of the inliers. The results are then plotted in the figures below.

## Datasets and Results

### Easy Dataset

The first set was composed of densely packed datapoints where the line fit is straightforward.

![easy_dataset_figure](https://user-images.githubusercontent.com/27826507/41818417-dc468646-777c-11e8-859d-06651900ed49.png)

### Medium Dataset

The second dataset has some noise. Though by randomly sampling pairs of lines RANSAC finds a line that fits the data.

![medium_dataset_figure](https://user-images.githubusercontent.com/27826507/41818428-028da956-777d-11e8-8da2-14302f2f1132.png)

### Hard Dataset

The last dataset was very noisy and required sampling enough lines that the probability of finding a best fit line is very likely.

![hard_dataset_figure](https://user-images.githubusercontent.com/27826507/41818427-feb9b2de-777c-11e8-800f-b4fdd0f118dc.png)
