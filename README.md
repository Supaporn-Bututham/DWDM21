# DWDM21
Data Warehouse &amp; Data Mining 2021

นางสาวสุภาภรณ์ บุตุธรรม 623020543-8

Group name : เอกาไร้สติ

1.**นางสาวสุภาภรณ์ บุตุธรรม 623020543-8**

2.นางสาวกัญญาวีร์ ศรีเทียมเงิน  623020511-1

3.นางสาวชลธิชา ศาลางาม 623020518-7

4.นางสาวจิราพร กลบรัตน์ 623020762-6

5.นางสาววิกานดา หงษ์บุญมี 623020764-2

# สารบัญ
* บทที่ 1 INTRODUCTION
  * [Lecture Introduction](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Chapter1_DWDM21.pdf)
    * Data Mining?
    * Knowledge Discovery (KDD) Process
    
* บทที่ 2 Getting to Know Your Data
  * [Lecture Data Objects and Attribute Types](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Chapter2_2.1.pdf)
    * Types of Data Sets
       * Record Data
       * Ordered Data
       * Spatial, image and multimedia Data
    * Important Characteristics of Structured Data
    * Data Objects
    * Attributes
    * Attribute Types
  * [Lecture Measuring Data Similarity and Dissimilarity](https://github.com/Supaporn-Bututham/DWDM21/blob/main/lecture_Chap2%20%E0%B9%80%E0%B8%9E%E0%B8%B4%E0%B9%88%E0%B8%A1%E0%B9%80%E0%B8%95%E0%B8%B4%E0%B8%A1.pdf)
    * Similarity, Dissimilarity, and Proximity
    * Data Matrix and Dissimilarity Matrix
    * Standardizing Numeric Data
    * Special Cases of Minkowski Distance
  * [Lecture Binary Distance](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Chapter2_Binary%20Distance.pdf)
    * Proximity Measure for Binary Attributes
    * Proximity Measure for Categorical Attributes
    * Ordinal Variables
    * Attributes of Mixed Type
    * Cosine Similarity of Two Vectors
  * [Basic Phython](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Data101(Chapter2).ipynb)
    * Variables
      * ข้อกำหนดในการตั้งชื่อตัวแปร
      * ทำตามที่กำนด
    * Casting int() float() str()
    * Data Structure
       * List
         * string คือ list ของตัวหนังสือ
         * วิธีการสร้าง list ว่าง
           * เติมค่าลงไปใน list (.append())
           * การชี้ค่าใน list (indexing)
         * list slicing
           * [จุดเริ่มต้น:จุดสุดท้าย:step]
         * list + list
         * format string
    * Loop
       * Nested loop
    * Condition (if ststement)
       * Quiz 1 หา min
       * HW ตัดเกรด
    * Function
       * Example1
       * Example2 (ไม่มี input)
       * Example 3 (ไม่มี output)
       * Example 3 (ไม่มี input และ output)
       * ลักษณะของ input(paremeter,argument)
       * Quiz2
  * [Pandas](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Data102(Chapter2).ipynb)
    * Read Data
        * .head() .tail()
    * Boxplot
    * Time Series Plot
  * [Visualization](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Data_Visualization.ipynb)
    * Scatter plot
    * Plot
    * Quiz กลุ่ม III วาดกราฟที่มี marker เป็น สี่เหลี่ยมจัตุรัส เส้นเป็น เส้นประสลับจุดไข่ปลา สีฟ้าอ่อน
    * Bar chart
       * Grouped Barchart
       * Sracked Barchart
    * Histogram
  * [Distance_Numpy](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Distance_Numpy_.ipynb)
    * Numpy array
       * สร้าง numpy array
           * matrix transpose
       * สร้าง matrix เริ่มต้น (zeros, ones)
       * สร้าง matrix random
           * matrix transpose
       * Indexing & Slicing
       * Useful functions
       * วนลูปเอง
           * summation
       * Quiz กลุ่ม
    * Distance Matrix
       * Euclidean Distance (L2-norm)
       * Distance function
       * Manhattan Distance (L1-norm)
       * HW11
       * เฉลย HW11
       * Distance of Binary Value
       
* บทที่ 3 Data Preprocessing
  * [Lecture Data Preprocessing](https://github.com/Supaporn-Bututham/DWDM21/blob/main/lecture_Chap3.pdf)
       * Data Preprocessing: An Overview
       * Data Cleaning      
  * [Data Preprocessing](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Data_Preprocessing_(Chapter_3)_.ipynb)
       * Meta Data (Data ที่ใช้อธิบาย Data)
         * ชี้ข้อมูลในตาราง
              * ชี้แบบธรรมดา ใช้ [ชื่อ column][index]
              * ชี้แบบ .iloc[] (มองข้อมูลเป็น matrix)
      * Missing Values
         * Handling Missing Value 1 (ลบค่า missing)
         * Quiz 3 ให้หาว่า การทำ dropna() ทำให้ข้อมูลหายไปกี่ %
         * Handling Missing Value 1.5 (ลบค่า missing เฉพาะใน คอลัมล์ที่เราสนใจเท่านั้น)
         * Quiz 3.1 ให้ หาว่า การทำ dropna() แบบเลือก drop เฉพาะ คอลัมล์ที่เราสนใจ ทำให้ข้อมูลหายไป กี่%
           * แก้ไขควิซ
         * Handling Missing Value 2 (แทนด้วย class ใหม่ (unknown))
         * Handling Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
         * Handling Missing Value 4 (แทนด้วย ค่ากลาง)
           * ถ้าเป็น numeric ใช้ mean
           * ถ้าเป็น norminal (ตัวหนังสือ) จะใช้ mode
           * ถ้าเป็น ordinal ใช้ median
             * เติมด้วยค่าของ column ใกล้เคียง (เดี๋ยวย้อนกลับมา)
         * Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน)
      * Select data by values [PD]
         * สร้าง list ของ boolean
           * นำ list ของ boolean มาเลือกค่าในตาราง
      * Quiz 4 + HW
         * records ที่ กักตัวที่ขอนแก่น
         * records ที่ กักตัวที่ ขอนแก่น+โคราช+อุดร
         * records ที่ เป็นผู้หญิงที่พบเชื้อที่ กทม
         * records ที่เป็นผู้ชาย อายุ 18-22 ปี ที่กักตัวที่เชียงใหม่
         * หาอายุเฉลี่ยของคนที่พบเชื้อที่ ขอนแก่น
            * พบที่ขอนแก่น
            * เอาค่า mean ไปเติมตรง missing column 'age'
            * ต่อตารางแนวแกน Y [PD]
         * Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน)(ต่อ)
         * การเรียงข้อมูล [PD]
      * Outlier
         * ตัด outlier แบบ manual
      * Quiz 5
      * HW หรือ Quiz กลุ่ม (III) แก้ให้ function box_vals สามารถรับ input ที่ box plot วาดแบบแนวนอนได้ (vert = False)
      * Pandas' looping (.iterrows)
      * การรวมตาราง Data Integration (ต่อตารางในแนวแกน x)
          * รวม 2 ตาราง (.merge())
          * เลือกเฉพาะ column ที่ต้องการมาแปะ (.map())
          * ตารางรอง (ตารางข้างขวา) ต้องไม่มี index ซ้ำ
          * Group by (pandas)
          * HW + Quiz
             * (จากตาราง w_restaurant กับ search_click) หา จังหวัดที่มีคนกดเข้าไปดูผลการ search 3 อันดับแรก
             * (จากตาราง w_restaurant กับ search_click) เมืองไหนที่มีค่าเฉลี่ยของ 'weighted_average_rating' สูงที่สุด
             * (จากตาราง confirmed-cases) เรียงลำดับ risk ที่ทีให้คนติดโรค 5 อันดับแรก
             * (จากตาราง confirmed-cases) หาจังหวัดที่มีคนกักตัวมากที่สุด 10 อันดับแรก
             * เฉลย HW10 + Quiz
          * [PD] save ตารางเอาไปใช้ที่อื่น
          * [PD] การสร้างตาราง
                   
* บทที่ 4 Data Warehousing and On-line Analytical Processing
  * [Lecture Data Warehousing and On-line Analytical Processing](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Lecture_Chap4.pdf)
       * What is a Data Warehouse?
       * From Tables and Spreadsheets to Data Cubes
* บทที่ 5 Association Rules
  * [Lecture Mining Frequent Patterns, Association and Correlations: Basic Concepts and Methods](https://github.com/Supaporn-Bututham/DWDM21/blob/main/lecture_Chap6.pdf)
       * Basic Concepts
         * What Is Pattern Discovery?
  * [Data 'reduced_marketbasket' Case](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Ch6_Association_Rules.ipynb)
       * ลบ records ที่ถูก cancel ออกไป
       * [Q] มีประเทศสาขาของ supermarket นี้ทั้งหมดกี่ประเทศ
       * [HW13] วาดกราฟสรุปจำนวน items และ ยอดขายของแต่ละประเทศ
       * เฉลยการบ้าน
         * ดูว่า คอลัมน์ไหนมี ค่า missing บ้าง
         * เพิ่มคอลัมน์ ยอดขาย (Quantity*UnitPrice)
         * เตรียม Data สำหรับ (Fequence Pattern) Association Rule
       * Apriori
         * (Quiz7) หา k-itemset ที่มีความน่าสนใจ (โดยพิจารณาลูกค้าเป็นรายคน) พร้อมทั้งอธิบายว่าน่าสนใจยังไง
         * แก้ไข Quiz7
 * บทที่ 6 Classification
   * [Lecture Classification: Basic Concepts](https://github.com/Supaporn-Bututham/DWDM21/blob/main/lecture_Chap8.pdf)
       * Basic Concepts
         * Supervised vs. Unsupervised Learning (1)
         * Supervised vs. Unsupervised Learning (2)
         * Prediction Problems: Classification vs. Numeric Prediction
         * Classification—Model Construction, Validation and Testing
       * Decision Tree Induction
         * An Example
         * Information Gain
   * [HW Decision Tree คำนวณมือ](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Decision-Tree_%E0%B8%84%E0%B8%B3%E0%B8%99%E0%B8%A7%E0%B8%93%E0%B8%A1%E0%B8%B7%E0%B8%AD.pdf)
   * [Lecture Decision Tree](https://github.com/Supaporn-Bututham/DWDM21/blob/main/lecture_ch8%20%E0%B9%80%E0%B8%9E%E0%B8%B4%E0%B9%88%E0%B8%A1%E0%B9%80%E0%B8%95%E0%B8%B4%E0%B8%A1.pdf)
   * [Decision Tree](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Chap7_Classification_(Decision_Tree).ipynb) 
      * Load Data
      * Train Model
         * import (เรียกใช้ algorithm ที่เราต้องการ)
         * define (กำหนด parameters ให้กับ model)
         * train (ฝึกสอนตัวแบบ)
      * Plot tree
      * Evalution
         * Random
      * Advanced Tree
         * Import
         * Define
         * Train
      * TEST
      * Start here
         * Import
         * Define
         * Train
         * Evaluate
      * HW
         * ต้นไม้ที่ใช้เกณฑ์ Entropy มีความสูงไม่เกิน 4 ชั้น
            * Import
            * Define
            * Train
            * Evaluate
         * ต้นไม้ที่ใช้เกณฑ์ Gini มีใบไม่เกิน 25 ใบ
            * import
            * Define
            * Train
            * Evaluate
         * ต้นไม้ที่ใช้เกณฑ์ Entropy และใช้การ split แบบ random
            * import
            * Define
            * Train
            * Evaluate
         * ต้นไม้ที่เราคิดเอง
            * import
            * Define
            * Train
            * Evaluate
         * เลือก mytreeNo3 แล้ว train ใหม่ด้วย Training
         * เฉลย HW
         * เลือก T4 แล้ว train ใหม่ด้วย Training
   * [Lecture k-Nearest Neighbor](https://github.com/Supaporn-Bututham/DWDM21/blob/main/lecture_14.10.64.pdf)
        * Bayes’ Theorem: Basics
        * Naïve Bayes Classifier
           * Categorical vs. Continuous Valued Features
           * Training Dataset
        * Lazy Learner: Instance-Based Methods
        * The k-Nearest Neighbor Algorithm
   * [Lecture Evaluation & Neural Networks](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Lecture_Precision_Recall%20%E0%B9%80%E0%B8%9E%E0%B8%B4%E0%B9%88%E0%B8%A1%E0%B9%80%E0%B8%95%E0%B8%B4%E0%B8%A1.pdf)
        * Classifier Evaluation Metrics
           * Confusion Matrix
           * Accuracy, Error Rate,Sensitivity and Specificity
           * Precision and Recall, and F-measures
        * Neural Network for Classification
   * [k-Nearest Neighbor & Neural Networks](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Chap7_Classification(KNN_NN).ipynb)
        * Load Data
        * Split Data
        * Train Model
           * import
           * knn1
           * KNN2
           * knn3
        * Retrain & Evaluate
        * Neural Network
           * Import
           * Define
           * Train - Test
           * ANN 2
           * ANN 3
   * [Evaluation](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
       * Load data
       * แบ่ง Data
       * สร้าง Model ทำนาย
          * Import
          * Define
          * Train
          * Evaluation

* บทที่ 7 Clustering
  * [Clustering](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Chap8_Clustering.ipynb)
    * K-means
     * Generate Data
     * Explore Data
     * Clustering
        * Import
        * Define
        * Fit-Predict
        * Plot
    * Example Application (Color Quantization)
      * นับจำนวนสี
      * จัดกลุ่มสีให้เหลือ 16 สี
      * ใช้ centroid เป็นตัวแทนของสี
* Group Project
  * [Project กลุ่ม](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Project_DWDM.ipynb)
      * รายชื่อสมาชิกในกลุ่ม
      * แหล่งที่มาของข้อมูล
      * ปัญหา
      * ชุดข้อมูลที่ 1 รับเรื่องร้องเรียน/แจ้งเบาะแสยาเสพติด
        * คำอธิบายตาราง
        * ตรวจสอบค่า Missing ของตาราง data_01
      * ชุดข้อมูลที่ 2 ปริมาณของกลางยาเสพติด
        * คำอธิบายตาราง
        * ตรวจสอบค่า Missing ของตาราง data_02
      * ชุดข้อมูลที่ 3 จำนวนคดี ผู้ต้องหาคดียาเสพติด
        * คำอธิบายตาราง
        * ตรวจสอบค่า Missing ของตาราง data_03
      * ข้อมูลชุดที่ 4 ข้อมูลทั่วไปของจังหวัด
        * คำอธิบายตาราง
        * ตรวจสอบค่า Missing ของตาราง data_04
      * เชื่อมต่อตาราง
        * ตรวจสอบค่า Missing ของตาราง 2 ตารางที่เชื่อมต่อกันแล้ว
        * ตรวจสอบค่า Missing ของตาราง 3 ตารางที่เชื่อมต่อกันแล้ว
      * Classification
        * ปัญหา
        * เลือกคอลัมน์ที่ต้องการนำมาใช้งาน
        * Decision Tree
        * KNN
        * Neural Network
      * Evaluation
        * Retain & Evaluation
      * Data_Visualization
      * THE END
* [ไฟล์นำเสนองานกลุ่มเอกาไร้สติ](https://github.com/Supaporn-Bututham/DWDM21/blob/main/Group-Project.pdf)
