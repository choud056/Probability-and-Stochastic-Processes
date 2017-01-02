# Probability-and-Stochastic-Processes
Probability and Stochastic Processes_UMN course projects

### **MiniProject1**: Implementation of Principal Component Analysis (PCA) in matlab to reduce dimensions of images thus compressing images
1. **EE 5531 F15 MiniProject1.pdf**: pdf file of problem statement.
2. **Miniproject1_output.pdf**: pdf file of output and matlab code used.
3. **gauss_scatter.m**: Matlab code to study the effect of rank of covariance matrix on the instrinsic structure (or effective dimension) of the data.
4. **reader.m**: Matlab code to divide input data into training and testing dataset.

### **MiniProject2**: Implementation of Wiener Filter in matlab to de-blur an image
1. **EE 5531 F15 MiniProject2.pdf**: pdf file of problem statement.
2. **miniproject2.pdf**: pdf file of output and matlab code used.
3. **Hubble.mat**: contains three data structuers, 
     * blurred galaxy.mat – a simulated grayscale image of a blurred and noisy galaxy, such as would have been acquired by the Hubble space telescope before its lens was fixed.
     * estimated g.mat – the two-dimensional impulse response of the lens aberration that caused the distortion
     * clean galaxy.mat – another (clean) image of a similar galaxy, to be used for approximating the power spectral density of the unknown galaxy image
4. **zero_pad.m**: to zero-pad (i.e., resize) the impulse response to the size of the image. This function also shifts the impulse response (a minor technicality) so that the filtering operation doesn’t induce an artificial phase shift. 
