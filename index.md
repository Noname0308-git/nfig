# NFIG: Autoregressive Image Generation with Next-Frequency Prediction

## Abstract

Autoregressive models have achieved promising results in natural language processing. However, for image generation tasks, they encounter substantial challenges in effectively capturing long-range dependencies, managing computational costs, and most crucially, defining meaningful autoregressive sequences that reflect natural image hierarchies. To address these issues, we present \textbf{N}ext-\textbf{F}requency \textbf{I}mage \textbf{G}eneration (\textbf{NFIG}), a novel framework that decomposes the image generation process into multiple frequency-based stages. Our approach first generates low-frequency components to establish global structure with fewer tokens, then progressively adds higher-frequency details, following the natural spectral hierarchy of images. This principled autoregressive sequence not only improves the quality of generated images by better capturing true causal relationships between image components, but also significantly reduces computational overhead during inference. Extensive experiments demonstrate that NFIG achieves state-of-the-art performance with fewer steps, offering a more efficient solution for image generation, with 1.25$\times$ speedup compared to VAR-d20 while achieving better performance (FID: 2.78) on the ImageNet-256 benchmark. We hope that our insight of incorporating frequency-domain knowledge to guide autoregressive sequence design will shed light on future research. We will release our implementation and trained models on GitHub following the acceptance of this paper to facilitate reproducibility and future research..

## Section with Images

### First Image Example

Here you can describe your first image. Images can be inserted using the following syntax:

![](C:\Users\Lenovo\Pictures\pic\framework-Example.png)

For example:

![Mountain landscape](https://example.com/mountain.jpg)

### Second Image Example

Here's how to add another image with some descriptive text:

![Ocean view](https://example.com/ocean.jpg)

You can also adjust image size with HTML (though this isn't standard markdown, it works in many markdown renderers):

<img src="https://example.com/landscape.jpg" alt="Landscape view" width="500"/>

## Image Types and Sources

You can include images from various sources:

1. **Web URLs** - Link directly to images on the web (as shown above)

2. Local files

    \- Reference images in the same directory as your markdown file

   - Example: `![Local image](./images/photo.jpg)`

3. Relative paths

    \- Reference images in subdirectories

   - Example: `![Relative path image](../assets/images/diagram.png)`

## Adding Captions

To add captions to your images, you can use this approach:

<figure>   <img src="https://example.com/chart.jpg" alt="Data chart">   <figcaption>Figure 1: Analysis of quarterly data</figcaption> </figure>

## Tables with Images

You can combine images with tables:

| Category | Image                                               | Description        |
| -------- | --------------------------------------------------- | ------------------ |
| Nature   | ![Nature](https://example.com/nature-thumb.jpg)     | Forest landscape   |
| Urban    | ![Urban](https://example.com/urban-thumb.jpg)       | City skyline       |
| Abstract | ![Abstract](https://example.com/abstract-thumb.jpg) | Geometric patterns |

## Additional Formatting

You can format text around your images:

**Bold text** can emphasize important points.

*Italic text* can be used for emphasis or terms.

> Blockquotes can highlight important information or testimonials alongside images.

Code examples can be included:

```python
def analyze_image(image_path):
    # Image analysis code here
    return results
```

## Conclusion

This concludes the markdown template. Modify it to fit your specific needs and content.