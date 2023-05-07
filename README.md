Download Link: https://assignmentchef.com/product/solved-lab-6-learning-in-reproducing-kernel-hilbert-spaces-advanced-machine-learning-data442-642
<br>
<strong>Exercise 1</strong>

Test the the prediction power of the kernel ridge regression in the presence of noise and outliers. The original data are samples from a music recording of Blade Runner by Vangelis Papathanasiou <a href="https://en.wikipedia.org/wiki/Vangelis">https://en.wikipedia.org/wiki/Vangelis</a><a href="https://en.wikipedia.org/wiki/Vangelis">.</a>

<ul>

 <li>Read the audio file, BladeRunner.wav, using the Python SoundFile library (<a href="https://pypi.org/project/SoundFile/">https:// </a><a href="https://pypi.org/project/SoundFile/">org/project/SoundFile/</a><a href="https://pypi.org/project/SoundFile/">)</a>. Then take 100 data samples starting from the 100,000th sample. Add white Gaussian noise at a 15 dB level and randomly “hit” 10% of the data samples with outliers (set the outlier values to 80% of the maximum value of the data samples).</li>

 <li>Find the reconstructed data samples using the unbiased kernel ridge regression method,that is,</li>

</ul>

<em>y</em>ˆ(<em>x</em>) = <em>y</em><sup>&gt;</sup>(<strong>K </strong>+ <em>C</em><strong>I</strong>)<sup>−1</sup><em>κ</em>(<em>x</em>)<em>.</em>

Employ the Gaussian kernel with <em>σ </em>= 0<em>.</em>004 and set <em>C </em>= 0<em>.</em>0001. Plot the fitted curve of the reconstructed samples together with the data used for training.

<ul>

 <li>Repeat step (b) using <em>C </em>= 10<sup>−6</sup><em>,</em>10<sup>−5</sup><em>,</em>0<em>.</em>0005<em>,</em>0<em>.</em>001<em>,</em>0<em>.</em>01<em>,</em>0<em>.</em></li>

 <li>Repeat step (b) using <em>σ </em>= 0<em>.</em>001<em>,</em>0<em>.</em>003<em>,</em>0<em>.</em>008<em>,</em>0<em>.</em>01<em>,</em>0<em>.</em></li>

 <li>Comment on the results.</li>

</ul>