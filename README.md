# ## CNN Architectures: 
Several key concepts in CNN

* **Network Depth:** The sources consistently emphasize the importance of network depth in achieving high accuracy. Deeper networks, however, pose challenges related to training, such as vanishing gradients. 
* **Residual Learning:**  ResNet's introduction of residual learning revolutionized the field by enabling the training of significantly deeper networks. The concept of using "shortcut connections" to bypass layers allows gradients to flow more easily through the network, mitigating the vanishing gradient problem. 
* **Efficient Convolutions:** As CNNs grew deeper and more complex, the need for more efficient computations became apparent, especially for mobile and resource-constrained applications. The sources explore various techniques, including depthwise separable convolutions and inverted residuals that reduce the number of parameters and computations while maintaining accuracy.  
* **Network Design Spaces:** While manual design has driven many successful architectures, the sources also recognize the value of exploring design spaces. Techniques like compound scaling offer a principled approach to balancing network width, depth, and resolution for optimal performance under specific constraints.  


* **The early focus on simply increasing network depth (exemplified by VGG) quickly gave way to a more nuanced understanding of how to train very deep networks.**  ResNet's residual learning framework provided a crucial breakthrough, paving the way for even deeper and more complex architectures.
* **The pursuit of efficiency has been a constant theme**, with architectures like MobileNet, Xception, and EfficientNet employing innovative techniques to reduce computational costs without compromising accuracy.
* **The rise of automated architecture search methods, highlighted in sources like "designNetwork.pdf" and "efficientNet.pdf", signals a shift towards more data-driven approaches** for discovering optimal network configurations.

