# CSC3105 Data Analytics Mini Project

## Group 8
- Felix Chang (2301105, 2957851C)
- Leo Oh Kang Weng (2301071, 2957949O)
- Lim Jing Chuan Jonathan (2300923, 2957906L)
- Jiang Weimin (2301083, 2957883J)
- Ryan Oh Tian Guan (2300916, 2957948O)

### Project Overview
This project focuses on analyzing UWB (Ultra-Wideband) LOS (Line of Sight) and NLOS (Non-Line of Sight) data for classification and range regression. We use machine learning techniques to detect NLOS conditions and improve indoor localization accuracy.

### Dataset
This project uses the UWB LOS and NLOS Data Set created using SNPN-UWB boards with DecaWave DWM1000 UWB radio modules.

**Dataset characteristics:**
- 42,000 total samples (21,000 LOS and 21,000 NLOS)
- Measurements from 7 different indoor locations
- Features include CIR (Channel Impulse Response), first path amplitude, noise measurements, and more
- Dataset is split into 7 smaller files for easier handling

### Repository Structure
- **Data Preprocessing**: Contains preprocessing notebooks
- **Data Mining**: Contains model implementation notebooks
- **Dataset/**: Original dataset files
- **Dataset/prepared/**: Preprocessed dataset
- **SourceCodes/**: Source code containing all .ipynb files
- **DAReportGroup08.pdf**: Project report
- **DADemoVideoGroup08.mp4**: Demo video (also available on [YouTube](https://youtu.be/QCwKMEaflY0))

### How to Use
1. Run the preprocessing notebooks first:
    - For NLOS classification: `NLOS_classifier_preprocessing.ipynb`
    - For range regression: `RANGE_regressor_preprocessing.ipynb`
2. Then run the main notebooks:
    - For NLOS classification: `NLOS_classifier.ipynb`
    - For range regression: `RANGE_regressor.ipynb`

### Dataset Citation
If you use this dataset in your research, please cite the original paper:

Klemen Bregar, Andrej Hrovat, Mihael Mohorčič, "NLOS Channel Detection with Multilayer Perceptron in Low-Rate Personal Area Networks for Indoor Localization Accuracy Improvement". Proceedings of the 8th Jožef Stefan International Postgraduate School Students' Conference, Ljubljana, Slovenia, May 31-June 1, 2016.

### Acknowledgements
Dataset author: Klemen Bregar, SensorLab, Jožef Stefan Institute. The research leading to these results received funding from the European Horizon 2020 Programme project eWINE under grant agreement No. 688116.
