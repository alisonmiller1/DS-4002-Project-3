# DS-4002-Project-3

## Software & Platform
For data downloading and preprocessing, we used Jupyter Notebook with python. The following packages will need to be installed for downloading and preprocessing: “load_dataset”, “datetime”, “pandas”, and “os”.  EDA visualizations were also completed with python in a Jupyter Notebook file.  The “pandas”, “matplotlib”, “seaborn”, “numpy”, and “datetime” were used to complete the visualizations.  “Matplotlib”, “seaborn”, and “numpy” would need to be installed for recreation as they were not installed during the downloading and preprocessing.

For modeling, analysis, and evaluation with the Yolov8s model, we used python in a Jupyter Notebook.  The packages used in these steps were “ultralytics”, “pandas”, “os”, “matplotlib”, “numpy”, and “sklearn”.  The packages not previously used, “ultralytics” and “sklearn”, need to be installed for modeling, analysis, and evaluation.

For creating the Gradient Boosting model as well as the partial dependence plot, we again used Jupyter Notebook with python. The following packages were used: "pandas", "numpy", "scikit-learn" (specifically train_test_split, GradientBoostingRegressor, mean_squared_error, and PartialDependenceDisplay), and "matplotlib".

X

All work was completed on Mac OS.

## Map of Documentation
```
DS-4002-Project-3 Folder Outline
│
├── DATA
│   ├── filter_posters10k
│   ├── filtered_posters500
│   ├── .DS_Store
│   ├── movies_10y_metadata10k.csv
│   ├── movies_10y_metadata500.csv
│   └── project3_data_appendix.pdf
│
├── OUTPUT
│   ├── yolo_train_results
│   ├── gradient_boost_results.png
│   ├── Intial_EDA_Visualizations.pdf
│   ├── movies_10y_metadata_with_counts.csv
│   └── partial_dependence_plot.png
│
├── SCRIPTS
│   ├── ProjectPosters.yolov8
│   │   ├── runs/detect/train
│   │   │   └── weights
│   │   │       ├── best.pt
│   │   │       └── last.pt
│   │   ├── test
│   │   │   ├── images
│   │   │   ├── labels
│   │   │   └── labels.cache
│   │   ├── train
│   │   │   ├── images
│   │   │   ├── labels
│   │   │   └── labels.cache
│   │   ├── valid
│   │   │   ├── images
│   │   │   ├── labels
│   │   │   └── labels.cache
│   │   ├── data.yaml
│   │   └── yolov8s.pt
│   ├── data_collection.ipynb
│   ├── gradient_boosting_and_plots.ipynb
│   ├── yolo_modeling_labeled.ipnyb
│   ├── yolo_modeling_no_label.ipnyb
│   └── yolov8s.pt
│
├── LICENSE
│
└── README.md
```

## Instructions for Reproduction of Results
To reproduce our results..


## References
[1] 	stzhao, “Datasets: stzhao/movie_posters_100k_controlnet,” Hugging Face, Nov 19 ,2024. https://huggingface.co/datasets/stzhao/movie_posters_100k_controlnet (accessed April  5, 2026).

[2]	Moses Olafenwa, “Train Object Detection AI with 6 lines of code,” Medium, Aug 1, 2019.https://medium.com/deepquestai/train-object-detection-ai-with-6-lines-of-code-6d087063f6ff (accessed April  5, 2026).

[3]	“Object Detection using yolov8,” Geeks for Geeks, Jul 23, 2025. https://www.geeksforgeeks.org/machine-learning/object-detection-using-yolov8/ (accessed April  5, 2026).

[4]	Ultralytics, “Image Classification Datasets Overview,” Ultralytics, Feb, 2026. https://docs.ultralytics.com/datasets/classify/ (accessed April  5, 2026).

[5]	Vidhi Singhal. “The Most Misunderstood Part of YOLO: Confidence Thresholding & Box Decoding,” Medium, Jan 14, 2026. https://isvidhi.medium.com/the-most-misunderstood-part-of-yolo-confidence-thresholding-box-decoding-076d57222e59  (accessed April 12, 2026).

[6]	Frouke Hermens, “Automatic object detection for behavioural research using YOLOv8,” PubMed Central NCBI, https://pmc.ncbi.nlm.nih.gov/articles/PMC11362367/ (accessed April 13, 2026). 

[7] Piotr Skalski, "How to Train YOLOv8 Object Detection on a Custom Dataset," Roboflow, Jan 10,2023. https://blog.roboflow.com/how-to-train-yolov8-on-a-custom-dataset/ (accessed April 15, 2026).
