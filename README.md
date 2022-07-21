# Background_People_Removal

Implementation of http://stanford.edu/class/ee367/Winter2018/li_li_ee367_win18_report.pdf

1. Detect the location of both the person to keep and unwanted background people using Viola Jones algorithm
2. Exemplar based inpainting to fill the gaps created after removing unwanted people from the background
3. Non Local Means Filtering to denoise the image

