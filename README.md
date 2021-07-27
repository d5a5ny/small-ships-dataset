# small-ships-dataset
This is a ship dataset for small ships only. Most of the ship instances have a relative area of less than 1% of the input image. It consists of 3538 ships in 1416 images. The number of ships less than 1% is 2462 ships, and the number of ships occupies relative areas between 1% and 10% are 1058 ships. Only 18 ships have a relative area greater than 10%.  Such that, this dataset can be used to evaluate the detectors for small ships.
The dataset can be downloaded from here
<ul>
  <li><a href="https://drive.google.com/file/d/1_5sZHjcpnXdqAc8KaBk1Z5yB1Y5Z5gzz/view?usp=sharing">Google drive</a></li>
  <li><a href="https://www.kaggle.com/d5a5ny/smallshipsdataset">Kaggle</a></li>
</ul>

This dataset is proposed to test an improved RetinaNet with an aggregation context network. This improvment is compared with RetinaNet and other state-of-the-art-detectors.

More information can be found on <a href="https://spie.org/search?term=iCGIP&pageSize=5&pagesVisited=1&sortBy=Relevance">SPIE website</a> 
`Note: The paper is not published yet`

The benchmark used in the evaluation is the PASCAL VOC 2007 benchmark.

The dataset is in PASCAL VOC format, it consists of four folders as follows:
<ul>
  <li>Annotations: contains the xml files </li>
  <li>JPEGImages: contains all the images of the dataset</li>
  <li>ImageSets: inside it the "Main" folder which contains a text file for all the images name. You need to create three files inside the Main folder (train.txt, val.txt, test.txt)
  </li>
  <li>txt_labels: contains the x1,y1,x2,y2 for each target.</li>
</ul>

