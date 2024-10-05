<h1>MonetGAN: Monet-esque Masterpieces with CycleGAN</h1>

<p>This project transforms ordinary photos into stunning paintings inspired by the style of Claude Monet, using a CycleGAN model. The model was developed using a dataset from the Kaggle competition <a href="https://www.kaggle.com/competitions/gan-getting-started">GAN Getting Started</a>, and the core of this repository lies in the ability to perform unpaired image-to-image translation.</p>

<h2>Project Overview</h2>

<p>MonetGAN leverages CycleGAN, a generative adversarial network (GAN), to learn the mapping between two visual domains without paired examples. The model can transform photographs into art pieces that resemble Monet's iconic impressionist paintings. This approach makes it possible to apply the style of Monet to any photograph, producing visually compelling and artistic outputs.</p>

<p>While the core model has been developed, <strong>the current implementation is still in Jupyter notebook format</strong>, and deployment is a work in progress. Stay tuned for updates as the project evolves!</p>

<h2>Key Features</h2>

<ul>
    <li><strong>Unpaired Image Translation</strong>: MonetGAN uses CycleGAN, enabling it to work without requiring paired images.</li>
    <li><strong>Claude Monet's Style Transfer</strong>: The model captures the style of Claude Monet's masterpieces, applying it to everyday photos.</li>
    <li><strong>Notebook-Based Model</strong>: The current model is fully implemented in a Jupyter notebook and can be easily run locally.</li>
    <li><strong>Upcoming Deployment</strong>: The model will soon be deployed as a web app to make it more accessible for users to transform their photos into Monet-inspired paintings.</li>
</ul>

<h2>Dataset</h2>

<p>The dataset used in this project is sourced from the Kaggle competition <a href="https://www.kaggle.com/competitions/gan-getting-started">GAN Getting Started</a>, containing both Monet paintings and photos. The dataset allows the model to learn the artistic style of Monet and apply it to various images.</p>

<h2>Usage</h2>

<p>Currently, the model can be run directly from the Jupyter notebook. Follow these steps to use the notebook:</p>

<ol>
    <li>Clone the repository:
        <pre><code>git clone https://github.com/yourusername/MonetGAN.git<br>cd MonetGAN</code></pre>
    </li><br>

    <li>Install dependencies:
        <pre><code>pip install -r requirements.txt</code></pre>
    </li><br>
    <li>Run the notebook:
        <p>Open the <code>MonetGAN.ipynb</code> notebook in Jupyter and run through the cells to train the model and generate Monet-style artwork.</p>
    </li>
</ol>


<h2>Future Work</h2>

<ul>
    <li><strong>Model Deployment</strong>: The model will be deployed as a web app using Flask or FastAPI, allowing users to upload their own photos and receive Monet-style paintings as output.</li>
    <li><strong>Improved Model Performance</strong>: Further tuning of hyperparameters and model architecture to enhance the quality of generated images.</li>
    <li><strong>Interactive GUI</strong>: Integrating a user-friendly interface for real-time image transformation.</li>
</ul>

<h2>Contributing</h2>

<p>Feel free to fork this repository, submit issues, or contribute by making pull requests.</p>

<h2>License</h2>

<p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for more details.</p>
