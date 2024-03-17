<div align="center">
<h1 align="center">MRI Analysis for Brain Tumor Detection</h1>

  <p align="center">
    A combined methodology using Anisotropic Diffusion and Watershed Segmentation
  </p>

</div>

## OBJECTIVE

The primary objective of this project is to enhance the accuracy of brain tumor detection from Magnetic Resonance Imaging (MRI) scans. Leveraging advanced image processing techniques, specifically Anisotropic Diffusion Filtering (ADF) and Watershed Segmentation, this research seeks to provide a robust tool for early detection and accurate segmentation of brain tumors, thereby facilitating timely and effective treatment strategies.

## METHODOLOGY

Our methodology unfolds in a structured process aimed at improving the precision of tumor identification from MRI images. Key steps include:

1. **Data Acquisition**: Utilizing a dataset of 80 brain MRI images from Kaggle, focusing on tumorous images to refine our segmentation techniques.
2. **Preprocessing**: Applying ADF for noise reduction, skull stripping to isolate brain tissue, and contrast enhancement to improve tumor visibility.
3. **Binarization**: Simplifying the image processing by converting grayscale images into binary, focusing on the most relevant information for tumor identification.
4. **Segmentation**: Employing the Watershed algorithm for effective segmentation, followed by morphological operations to refine tumor boundaries.
5. **Performance Evaluation**: Quantitative assessment using metrics such as SSIM, PSNR, and GLCM features to evaluate the accuracy and efficiency of the proposed method.

The entire process emphasizes preserving crucial image details while significantly reducing noise, thereby enabling more accurate segmentation and identification of tumor regions.

## RESULTS & DISCUSSION

Our findings demonstrate notable enhancements in the processed MRI images at each stage of the applied methodology. Quantitative evaluations reveal high levels of accuracy, as evidenced by performance metrics like SSIM, PSNR, and enhanced image features via GLCM analysis. These results underscore the effectiveness of combining ADF and Watershed Segmentation in distinguishing between tumorous and healthy tissues, significantly outperforming existing methods in terms of accuracy and processing speed.

Moreover, the integration of textural features with machine learning classifiers emerges as a promising direction for future research, suggesting potential for even more refined tumor detection capabilities.

## CONCLUSION

This project successfully demonstrates an advanced methodology for the detection and segmentation of brain tumors in MRI scans, with significant implications for improving diagnostic accuracy and treatment outcomes. The synergy of Anisotropic Diffusion Filtering and Watershed Segmentation, complemented by a thorough performance evaluation, establishes a solid foundation for future advancements in medical imaging and diagnostics.

The promising results, particularly in texture analysis using the GLCM, pave the way for integrating these methodologies with artificial intelligence to develop more sophisticated diagnostic tools. Our research invites further validation across diverse datasets, aiming to solidify its applicability and effectiveness in real-world medical settings.
