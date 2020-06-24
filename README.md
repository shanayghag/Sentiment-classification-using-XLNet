# Sentiment-classification-using-XLNet
Fine-tuning XLNet model for sentiment classification.                              
Find my medium article on sentiment-analysis using XLNet<a href = "https://medium.com/swlh/using-xlnet-for-sentiment-classification-cfa948e65e85"> here</a>

<b>About XLNet</b>:
<ul>
  <li>The <b>XLNet</b> model was proposed by researchers in <b><i>Carnegie Mellon University</i></b>, and <b><i>Google AI Brain Team</i></b>. XLNet is an extension of the          <b>Transformer-XL</b> model pre-trained using an autoregressive method to learn bidirectional contexts by maximizing the expected likelihood over all permutations of the input     sequence factorization order.</li>
  <li>XLNet leverages the advantages of both, <b><i>Auto-regressive</i></b> and <b><i>Auto-encoding</i></b> methods for its pretraining which helps it to overcome <b>pretrain-       finetune discrepancy</b>.</li>
  <li>XLNet can be used for any specific task easily, by downloading the pretrained model and fine-tuning it for the downstream task. To make our work more easy, <b>Huggingface     Transformers</b> have already provided few model classes for performing specific downstream tasks using XLNet. We just need to download and <i>fine-tune</i> them, without         writing custom model class i.e additional layers on top of the XLNet model.</li>
</ul>

The notebook is divided into following parts:
<ol>
  <li>Install and import all the dependencies required to set the code working.</li>
  <li>Prepare data</li>
  <li>Writing function to perform train step and evaluation.</li>
  <li>Fine-tuning XLNet model.</li>
  <li>Evaluate performance of the model.</li>
  <li>Making predictions on raw text.</li>
</ol>

Results:
<ul>
  <li><b> Test Accuracy : 96% </b></li>
</ul>
