<h1>Physics-Informed Neural Network (PINN)</h1>

<p>This repository contains the implementation of a Physics-Informed Neural Network (PINN) following the <a href="https://www.youtube.com/watch?v=G_hIppUWcsc">YouTube tutorial by Kourosh</a>.</p>

<h2>Overview</h2>
<p>Physics-Informed Neural Networks (PINNs) use physical laws described by PDEs to inform the learning process, combining data-driven and physics-informed loss functions.</p>

<h2>Requirements</h2>
<ul>
    <li>Python 3.x</li>
    <li>PyTorch</li>
    <li>NumPy</li>
    <li>Matplotlib</li>
</ul>
<p>Install the dependencies with:</p>
<pre><code>pip install torch numpy matplotlib</code></pre>

<h2>Usage</h2>
<ol>
    <li>Clone the repository:
        <pre><code>git clone https://github.com/yourusername/pinn-implementation.git
cd pinn-implementation</code></pre>
    </li>
    <li>Run the main script:
        <pre><code>python harmonic-oscillator-using-pinns.ipynb</code></pre>
    </li>
</ol>

<h2>Project Structure</h2>
<ul>
    <li><code>harmonic-oscillator-using-pinns.ipynb</code>: Main script for training and visualization.</li>
</ul>

<h2>Synthetic Observations</h2>
<img src="images/noisy_observations.png" alt="Noisy Observations" width="600">

<h2>Training Loop</h2>
<img src="images/training_0.png" alt="Training at 0 iterations" width="600">
<img src="images/training_5000.png" alt="Training at 5000 iterations" width="600">
<img src="images/training_10000.png" alt="Training at 10000 iterations" width="600">
<img src="images/training_15000.png" alt="Training at 15000 iterations" width="600">
<img src="images/training_inversion_0.png" alt="Training Inversion at 0 iterations" width="600">
<img src="images/training_inversion_5000.png" alt="Training Inversion at 5000 iterations" width="600">
<img src="images/training_inversion_10000.png" alt="Training Inversion at 10000 iterations" width="600">
<img src="images/training_inversion_15000.png" alt="Training Inversion at 15000 iterations" width="600">


<h2>References</h2>
<ul>
    <li><a href="https://www.youtube.com/watch?v=G_hIppUWcsc">YouTube Video by Kourosh</a></li>
    <li><a href="https://arxiv.org/abs/1711.10561">PINNs Paper</a></li>
    <li><a href="https://github.com/benmoseley/harmonic-oscillator-pinn-workshop/tree/main">PINNs Workshop</a></li>
</ul>

<h2>License</h2>
<p>This project is licensed under the MIT License.</p>
