<big><b> Author: Oweys Momenzada </big></b>

# Graph Neural Networks for effecient Recommender-Systems

#### What is this repository about?
In our research paper we introduce a Graph Neural Network approach to develop Recommender-Systems. Recently, Graph Neural Networks (GNNs) have been gaining a lot of popularity in various fields. Though, GNNs are considered to be a new field of research with great potential for the future, they already have been able to convince with excellent results.
In this repository I want to provide some technical workflows of GNNs based on <a href="https://www.dgl.ai/">DeepGraphLibrary (DGL)</a> and the <a href="https://arxiv.org/abs/1706.02263">GCMC model</a>. 

## Requirements

- Pytorch CPU version: 1.5.0 (or newer)
- DGL version: 0.5.3
- Sckit version: 1.1.1
- Python version: 3.8

#### How to install DGL 0.5.3
You need the 0.5.X version of DGL. Otherwise it can cause an memory error. 
Simply do:

<code>$ conda install -c dglteam "dgl<0.5.3" </code>
  
## Experiments
We apply the approach on Benchmark datasets; thus we can only focus on the technical implementation and use it for comparison.  <br>
NOTE: I suggest working on GPU for example on Google Colab (free GPU usage) to get the highest possible performance.
 
#### AmazonReview:
  ```
  Experiments\AmazonReview\GCMC-AmazonReview
  ```
#### Douban:
NOTE: Here I used the 10-Core approach, which may differ from author to author. 
  ```
  Experiments\Douban\GCMC-Douban
  ```
  
#### ML100K (with Features):
  ```
  Experiments\MovieLens100K\GCMC-MovieLens-100k
  
  Experiments\MovieLens100K\GCMC-MovieLens+Feature-100k
  ```
  
#### Yahoo Music:
  ```
  Experiments\AmazonReview\GCMC-Yahoo Music
  ```
  
## Research Paper
You can get a deeper insight of our work <a href="https://www.researchgate.net/publication/355928151_Graph_Neural_Networks_for_Efficient_Recommender_Systems">here</a>.
This includes different types of Recommender-Systems, GNNs and Training methods.

## Cite
If you are interested and want to cite our work, please feel free to use:

  ```
  Publication ongoing
  @article{loremipsum,
  title={loremipsum},
  author={vloremipsum},
  journal={loremipsum},
  year={loremipsum}
  }
  ```
  
If you are also interested in the model and the technical implementation based on the experiments, also cite:
  
#### Authors of <a href="https://arxiv.org/abs/1909.01315">DGL</a>: 
  ```
  @misc{wang2020deep,
      title={Deep Graph Library: A Graph-Centric, Highly-Performant Package for Graph Neural Networks}, 
      author={Minjie Wang and Da Zheng and Zihao Ye and Quan Gan and Mufei Li and Xiang Song and Jinjing Zhou and Chao Ma and Lingfan Yu and Yu Gai and Tianjun Xiao and Tong He
  and George Karypis and Jinyang Li and Zheng Zhang},
      year={2020},
      eprint={1909.01315},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
  }
```
  
#### Authors of  the <a href="https://arxiv.org/abs/1706.02263">GCMC model</a>: 
``` 

  @article{vdberg2017graph,
  title={Graph Convolutional Matrix Completion},
  author={van den Berg, Rianne and Kipf, Thomas N and Welling, Max},
  journal={arXiv preprint arXiv:1706.02263},
  year={2017}
  }
```
