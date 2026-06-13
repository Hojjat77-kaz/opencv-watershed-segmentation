# Watershed Segmentation with OpenCV

This project demonstrates object segmentation using the Watershed algorithm in OpenCV.

The pipeline combines thresholding, morphological operations, distance transform, connected components, and watershed segmentation to separate touching objects.

## Features

- Otsu thresholding
- Morphological opening
- Background extraction
- Distance transform
- Foreground extraction
- Connected component labeling
- Watershed segmentation
- Boundary visualization

  ## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib

  ## Processing Pipeline

1. Load image
2. Convert image to grayscale
3. Apply Otsu thresholding
4. Remove noise using morphological opening
5. Extract sure background using dilation
6. Compute distance transform
7. Extract sure foreground
8. Determine unknown regions
9. Label connected components
10. Apply Watershed algorithm
11. Visualize segmentation boundaries

    ## Concepts Practiced

- Image Segmentation
- Morphological Operations
- Distance Transform
- Connected Components
- Watershed Algorithm
- Foreground and Background Extraction

  ## Example Result

Input:
- Image containing touching coins

Output:
- Segmented coins with watershed boundaries highlighted

  ## What I Learned

This project helped me understand:

- How morphological operations remove image noise
- How distance transform identifies object centers
- How connected components label separate regions
- How Watershed segmentation separates touching objects
- How multiple image processing techniques work together in a segmentation pipeline

  ## Future Improvements

- Automatic object counting
- Shape classification after segmentation
- Color analysis of segmented objects
- Real-time webcam segmentation
- Support for multiple object types
