# Neural-Similarity-Predicts-Whether-Strangers-Become-Friends

To comply with the guidelines outlined in the Journal’s Code and Software Submission Checklist, a small, simulated dataset (with 10 subjects and timeseries across 100 TRs in 5 brain regions) is provided to demo the code. The source code uses the simulated dataset that is in the same format as the dataset used for the main analyses of the paper.

Python version 3.9.7 on a Mac OS Sonoma 14.4.1 were used to write and run the source code. On a 2021 MacBook M1 Pro with 16GB of RAM, it takes about 10 minutes to run through the code with this simulated dataset.

To run the source code, please first change filepath to your local path of the downloaded demo_code folder. You can run each block of code in demo.ipynb individually or all the blocks by clicking on the "Cell" menu and selecting "Run All" from the dropdown menu.

The source code produces the results in the friend_group_contrast and dist_change_contrast, corresponding to the main analyses outlined in our manuscript, within the derivatives folder. They are analogous to the output generated for the results reported in our manuscript, except that they are based on the simulated dataset.

The source_data.csv includes the source data at the dyad level (specifically, the inter-subject correlation and social distance data that we generated in this study, as well as dyadic similarities in demographic variables and dyadic similarities in ratings of enjoyment of and interest in the stimuli).

---
Copyright 2025 Yixuan Shen

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
