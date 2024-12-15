<!DOCTYPE html>
<html>
<head>
    <title>Tree Detection on Street View Images</title>
</head>
<body>
    <h1>Tree Detection on Street View Images by Mask R-CNN</h1>
    
    <h2>Introduction</h2>
    <p>Urban greenery plays a vital role in enhancing the quality of life in cities. Identifying and cataloging trees is a crucial step toward sustainable urban planning. This project leverages Mask R-CNN, a powerful deep learning model, to detect and segment trees in street-view images efficiently.</p>

    <h2>Dataset</h2>
    <p>The dataset used in this study comprises 200 annotated images collected from the 27th Electrical Engineering Conference in Yazd, Iran (ICEE2019). The images were preprocessed to sizes of 1024 &times; 1024 and 2048 &times; 2048 to evaluate model performance on different resolutions.</p>
    <p>Below is an example image from the dataset:</p>
    <img src="example_dataset_image.jpg" alt="Example dataset image showing annotated trees" width="600">

    <h2>Results</h2>
    <p>The Mask R-CNN model demonstrated strong performance in detecting and segmenting trees. The results are summarized as follows:</p>
    <ul>
        <li>Leafless trees: IoU 91% (1024 &times; 1024), 92% (2048 &times; 2048)</li>
        <li>Leafy trees: IoU 92% (1024 &times; 1024), 95% (2048 &times; 2048)</li>
        <li>Mixed trees: IoU 92% (1024 &times; 1024), 93% (2048 &times; 2048)</li>
    </ul>
    <p>Here are some visualization examples of the results:</p>
    <img src="result_image1.jpg" alt="Visualization of leafless tree detection" width="600">
    <img src="result_image2.jpg" alt="Visualization of leafy tree detection" width="600">
    <img src="result_image3.jpg" alt="Visualization of mixed tree detection" width="600">

    <h2>Authors</h2>
    <ul>
        <li><strong>Fatemeh Jokar:</strong> Lead developer and main contributor (<a href="mailto:shekufeh.j@gmail.com">shekufeh.j@gmail.com</a>)</li>
        <li><strong>Mahmood Amintoosi:</strong> Primary supervisor (<a href="mailto:m.amintoos@um.ac.ir">m.amintoos@um.ac.ir</a>, <a href="mailto:m.amintoos@hsu.ac.ir">m.amintoos@hsu.ac.ir</a>)</li>
        <li><strong>Somayeh Sobati Moghadam:</strong> Co-supervisor (<a href="mailto:s.sobati@hsu.ac.ir">s.sobati@hsu.ac.ir</a>)</li>
        <li><strong>Mehdi Zaferanieh:</strong> Advisor (<a href="mailto:mehdi.zaferanieh@gmail.com">mehdi.zaferanieh@gmail.com</a>)</li>
    </ul>

    <h2>Repository</h2>
    <p>The code for this paper is available on GitHub: <a href="https://github.com/BLOSSOM1994/Tree_maskRcnn">https://github.com/BLOSSOM1994/Tree_maskRcnn</a></p>
</body>
</html>
