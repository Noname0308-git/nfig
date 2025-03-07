# NFIG: Autoregressive Image Generation with Next-Frequency Prediction

## Abstract

Autoregressive models have achieved promising results in natural language processing. However, for image generation tasks, they encounter substantial challenges in effectively capturing long-range dependencies, managing computational costs, and most crucially, defining meaningful autoregressive sequences that reflect natural image hierarchies. To address these issues, we present \textbf{N}ext-\textbf{F}requency \textbf{I}mage \textbf{G}eneration (\textbf{NFIG}), a novel framework that decomposes the image generation process into multiple frequency-based stages. Our approach first generates low-frequency components to establish global structure with fewer tokens, then progressively adds higher-frequency details, following the natural spectral hierarchy of images. This principled autoregressive sequence not only improves the quality of generated images by better capturing true causal relationships between image components, but also significantly reduces computational overhead during inference. Extensive experiments demonstrate that NFIG achieves state-of-the-art performance with fewer steps, offering a more efficient solution for image generation, with 1.25$\times$ speedup compared to VAR-d20 while achieving better performance (FID: 2.81) on the ImageNet-256 benchmark. We hope that our insight of incorporating frequency-domain knowledge to guide autoregressive sequence design will shed light on future research. 

## Generated Example

![](C:\Users\Lenovo\Pictures\pic\framework-Example.png)
