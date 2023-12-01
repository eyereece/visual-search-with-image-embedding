# Powering a Visual Search System with Image Embedding


<figure>
  <center>
    <img src="https://static.wixstatic.com/media/81114d_4ea9eeaf7c9c457ab30faf4e95f91ba8~mv2.png" alt="preview" height="300" width="560">
  </center>
</figure>
<br>


> Highlights from the current model:
> * Reduced index size by 85% over baseline model (163.8 MB to 25 MB) through dimensionality reduction using an autoencoder network
> * Increased mAP score by 9% over baseline model through strategic adjustments, including increasing convolutional and max-pooling layers in the network architecture.

<br>

I have also created a blog post underlining the process, evaluation, analysis, visualization, recommendations, and sample results on this project, available here: 
https://www.joankusuma.com/post/powering-visual-search-with-image-embedding

<br>

#### The dataset used to train the model is available <a href="https://github.com/eileenforwhat/complete-the-look-dataset/tree/master">here</a>:
<div class="box">
  <pre>
    @online{Eileen2020,
  author       = {Eileen Li, Eric Kim, Andrew Zhai, Josh Beal, Kunlong Gu},
  title        = {Bootstrapping Complete The Look at Pinterest},
  year         = {2020}
}
  </pre>
</div>
