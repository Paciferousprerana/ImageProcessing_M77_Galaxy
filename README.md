# ImageProcessing (Computer Vision) on M77 Galaxy

In this notebook, I have selected NGC 1068, also known as Messier 77 (M77), as my subject. This galaxy caught my attention due to its brightness, distance
 from Earth, and the presence of a black hole at its core. To gather information, I conducted a thorough literature review using sources such as Wikipedia and NED
 (NASA/IPAC Extragalactic Database). These sources provided valuable details about the galaxy's discovery, coordinates, morphology, distance, type, and unique characteristics.

Based on the information gathered, I formulated a hypothesis suggesting that NGC 1068 is a spiral galaxy housing a black hole at its center. To test this hypothesis, I
performed exploratory data analysis (EDA) and applied various filters to enhance the image visualization, enabling me to draw inferences. Initially, I obtained the image and
examined its header file to extract essential information, including the galaxy's coordinates. Subsequently, I processed the image data, conducting quantitative analyses such
 as determining its shape, minimum and maximum values, as well as calculating the mean and standard deviation. Notably, I observed that the pixel data exhibited a left-skewed
  distribution, prompting me to apply log normalization. This normalization technique significantly improved the image quality, revealing prominent spiral features within the
   galaxy.

To extract further information and confirm my findings, I employed specific filters. A denoising filter was applied to remove noise, an edge filter enhanced edge visibility,
 and a ridge filter accentuated ridges in the image. These filters collectively highlighted the presence of spiral structures, providing evidence to support the classification
  of NGC 1068 as a spiral galaxy. Furthermore, the filters indicated high intensity or density near the galaxy's center. Accordingly, I zoomed in on the center region, applying
   sharpening techniques and Fourier transform analysis. The Fourier transform effectively removed low-intensity points and unveiled a prominent ring of high intensity at the
   center, surrounded by negligible intensity. This characteristic strongly suggested the presence of a black hole within the galaxy.

In conclusion, through comprehensive research, image processing, visualization, and careful observations, it can be confidently inferred that NGC 1068 is a spiral galaxy
housing a black hole at its center.
