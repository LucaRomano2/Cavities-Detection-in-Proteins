# Comparison results

## Co-crystallized ligand

The results obtained by the algorithm that calculates the coverage of the co-crystallized ligand for the two methods are listed in the
table below:

| Ligand  | PASS coverage |PASS coverage without the last filter| POCASA coverage - radius 3Å | POCASA coverage - radius 4Å |
| :---:   |    :----:     |          :---:                      |          :---:              |          :---:              |
| 1a0q    | 74.42%        | 74.42%                              | 76.74%                      | 79.07%                      |
| 1a0t    | 97.78%        | 97.78%                              | 0.00%                       | 68.89%                      |
| 1a1b    | 17.95%        | 20.51%                              | 17.95%                      | 19.23%                      |
| 1a1c    | 20.55%        | 23.29%                              | 20.55%                      | 21.92%                      |
| 1a2c    | 54.35%        | 54.35%                              | 25.00%                      | 44.57%                      |
| 1a3e    | 8.33%         | 8.33%                               | 3.85%                       | 8.97%                       |
| 1a4g    | 100.00%       | 100.00%                             | 18.60%                      | 100.00%                     |
| 1a4h    | 63.75%        | 63.75%                              | 16.25%                      | 82.50%                      |
| 1a4m    | 100.00%       | 100.00%                             | 100.00%                     | 100.00%                     |
| 1a4q    | 96.36%        | 96.36%                              | 34.55%                      | 92.73%                      |
| 1a5g    | 82.76%        | 82.76%                              | 42.53%                      | 70.11%                      |
| 1a5h    | 81.03%        | 81.03%                              | 43.10%                      | 58.62%                      |
| 1a5v    | 0.00%         | 5.88%                               | 0.00%                       | 2.94%                       |
| 1a07    | 12.16%        | 12.16%                              | 4.05%                       | 13.51%                      |
| 1a7c    | 100.00%       | 100.0%                              | 80.28%                      | 98.59%                      |
| 1a7t    | 100.00%       | 100.00%                             | 11.54%                      | 96.15%                      |
| 1a7x    | 44.76%        | 46.15%                              | 3.50%                       | 27.27%                      |
| 1a08    | 20.00%        | 20.00%                              | 17.50%                      | 21.25%                      |
| 1a8i    | 100.00%       | 100.00%                             | 44.83%                      | 100.00%                     |
| 1a8t    | 63.79%        | 63.79%                              | 36.21%                      | 53.45%                      |
| 1a09    | 26.83%        | 31.71%                              | 21.95%                      | 26.83%                      |
| 1a9u    | 74.42%        | 74.42%                              | 23.26%                      | 76.74%                      |
| 1a37    | 6.78%         | 6.78%                               | 0.00%                       | 0.00%                       |
| 1a42    | 73.33%        | 73.33%                              | 24.44%                      | 44.44%                      |
| 1a46    | 77.65%        | 77.65%                              | 34.12%                      | 52.94%                      |
| 1a50    | 100.00%       | 100.00%                             | 100.00%                     | 100.00%                     |
| 1a52    | 100.00%       | 100.0%                              | 38.64%                      | 100.00%                     |
| 1a61    | 83.56%        | 83.56%                              | 45.21%                      | 73.97%                      |
| 1a85    | 80.00%        | 80.00%                              | 41.82%                      | 78.18%                      |
| 1a86    | 88.24%        | 88.24%                              | 45.10%                      | 74.51%                      |
| 1bio    | 88.89%        | 88.89%                              | 88.89%                      | 94.44%                      |
| 1ddm    | 17.68%        | 17.68%                              | 1.22%                       | 9.76%                       |
| Average | 64.23%        | 64.78%                              | 33.18%                      | 59.11%                      |

## Cavities

The results obtained by the algorithm that calculates the coverage of the cavities for the two methods are listed in the
table below:

| Protein | POCASA(radius 3) versus PASS | POCASA(radius 3) greatest cavities versus PASS | POCASA(radius 4) versus PASS | POCASA(radius 4) greatest cavities versus PASS | PASS versus POCASA(radius 3) | PASS versus POCASA(radius 4) | 
|:-------:|:----------------------------:|:----------------------------------------------:|:----------------------------:|:----------------------------------------------:|:----------------------------:|:----------------------------:| 
|  1a0q   |            77.96%            |                     92.09%                     |            66.89%            |                     74.53%                     |            81.63%            |            88.97%            |                           
|  1a1b   |            63.49%            |                    100.00%                     |            55.90%            |                    100.00%                     |            75.00%            |            87.51%            |              
|  1a1c   |            59.33%            |                     98.80%                     |            52.96%            |                     98.29%                     |            71.23%            |            89.04%            |                         
|  1a2c   |            75.94%            |                     86.27%                     |            79.29%            |                     85.01%                     |            36.01%            |            80.28%            |                    
|  2a0c   |            92.59%            |                     99.14%                     |            85.20%            |                     91.33%                     |            56.20%            |            95.64%            |     
|  2a29   |            63.63%            |                     97.93%                     |            67.11%            |                     99.00%                     |            55.86%            |            98.12%            |    
|  2a2x   |            79.12%            |                     83.09%                     |            82.72%            |                     85.52%                     |            48.38%            |            91.79%            |    
|  2a3a   |            75.10%            |                     86.84%                     |            80.99%            |                     86.60%                     |            48.77%            |            97.54%            |    
|  2a3b   |            39.25%            |                    100.00%                     |            27.45%            |                     28.77%                     |            45.16%            |            74.19%            |    
|  2a3c   |            87.24%            |                     89.93%                     |            80.94%            |                     85.21%                     |            67.63%            |            86.20%            |    
|  2a1p   |            29.52%            |                     4.76%                      |            72.23%            |                     74.73%                     |            8.49%             |            78.70%            |    
|  2a1q   |            84.06%            |                     95.69%                     |            67.24%            |                     78.06%                     |            75.55%            |            96.11%            |    
|  2b1r   |            59.62%            |                     35.61%                     |            77.73%            |                     83.96%                     |            25.10%            |            97.48%            |    
|  2b1v   |            53.33%            |                    100.00%                     |            69.39%            |                    100.00%                     |            21.64%            |            66.91%            |    
|  2b1z   |            58.98%            |                    100.00%                     |            75.03%            |                    100.00%                     |            22.76%            |            71.91%            |    
|  2b4m   |            77.65%            |                     80.83%                     |            68.05%            |                     74.44%                     |            79.74%            |            85.34%            |    
|  2b1r   |            59.62%            |                     35.61%                     |            77.73%            |                     83.96%                     |            25.10%            |            97.48%            |    
|  2b5j   |            86.54%            |                     90.03%                     |            79.92%            |                     86.39%                     |            77.39%            |            82.28%            |    
|  2b7a   |            76.22%            |                     80.76%                     |            70.13%            |                     74.21%                     |            83.29%            |            89.97%            |    
|  2b7f   |            79.93%            |                     88.26%                     |            84.34%            |                     92.31%                     |            49.44%            |            91.87%            |    
|  2b81   |            86.33%            |                     93.26%                     |            79.65%            |                     82.97%                     |            82.97%            |            93.45%            |    
| Avarage |            57.89%            |                     82.80%                     |            71.47%            |                     88.12%                     |            54.13%            |            87.65%            |    