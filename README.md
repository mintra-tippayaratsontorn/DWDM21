# DWDM21
Data Warehouse &amp; Data Mining 2021

มินตรา ทิพยรัตน์สุนทร รหัสนักศึกษา 623020041-2

Group Name : ลูกหมี

1. มินตรา ทิพยรัตน์สุนทร รหัสนักศึกษา 623020041-2
2. กัลยารัตน์ แสนสมบัติ รหัสนักศึกษา 623020513-7
3. ฐิติชญา ไกรวงค์ รหัสนักศึกษา 623020520-0
4. นันทิชา วิชิต  รหัสนักศึกษา 623020526-8
5. ศศิกานต์ บุญมี  รหัสนักศึกษา 623020539-9


# สารบัญเนื้อหา
* บทที่ 1 [introduction](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Ch1_Introduction.pdf)
  * Why Data Mining? : ทำไมต้องทำเหมืองข้อมูล
  * What Is Data Mining? : Data Mining คืออะไร
  * A Multi-Dimensional View of Data Mining : มุมมองหลายมิติของการทำเหมืองข้อมูล
  * What Kinds of Data Can Be Mined? : ข้อมูลประเภทใดที่สมารถขุดได้
  * What Kinds of Patterns Can Be Mined? : รูปแบบใดที่สามารถขุดได้
  * What Kinds of Technologies Are Used? ใช้เทคโนโลยีประเภทใดบ้าง
  * What Kinds of Applications Are Targeted? : แอพพลิเคชันเป้าหมาย
  * Major Issues in Data Mining : ประเด็นสำคัญในการทำเหมืองข้อมูล
  * A Brief History of Data Mining and Data Mining Society : ประวัติความเป็นมา
  * Summary : สรุป
  * [Slide บทที่ 1](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Ch1_Introduction.pdf)


* บทที่ 2 know your data ประกอบไปด้วย 2 ส่วยย่อยคือ
  * [Basic Python](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Data101(Chapter2).ipynb)
    * Casting
    * Data structure
    * Loop
    * Condition
    * Function
  * [Data Exploration](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Data102(Chapter2).ipynb)
    * Boxplot
    * Time Series Plot
  * [Data Visualization](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Data_Visualization.ipynb)
    * Scatter plot (plot จุดแบบกระจาย)
    * Plot (มีเส้นเชื่อมระหว่างจุด)
    * Bar chart (plot แบบเป็นแท่ง)
      * Grouped Barchart
      * Stacked Barchart
    * Histogram
  * [Distance Numpy](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Distance_Numpy.ipynb)
    * Numpy Array
      * สร้าง numpy array (matrix) จาก list
      * สร้าง matrix เริ่มต้น (zeros, ones)
      * สร้าง matrix random
      * Indexing & Slicing
      * Useful functions
    * Distance Matrix
      * Euclidean Distance (L2-norm)
      * Distance function
      * Manhattan Distance (L1-norm)
      * Distance of Binary Value
  * [Slide บทที่ 2](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Chapter2.pdf)


* บทที่ 3 [Data Preprocessing](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Data_Preprocessing_(Chapter_3).ipynb)
  * Meta Data (Data ที่ใช้อธิบาย Data)
  * ชี้ข้อมูลในตาราง
    * ชี้แบบธรรมดา ใช้ [ชื่อ column][index]
    * ชี้แบบ .iloc[] (มองข้อมูลเป็น matrix)
  * Missing Values
    * Handling Missing Value 1 (ลบค่า missing)
    * Handling Missing Value 1.5 (ลบค่า missing เฉพาะใน column ที่เราสนใจ)
    * Handling Missing Value 2 (แทนด้วย class ใหม่(unknown))
    * Handling Missing Value 3 (แทนด้วย class ใหม่(ค่าที่เหมาะสม))
    * Handling Missing Value 4 (แทนด้วย ค่ากลาง)
    * Handling Missing Value 5 (แทนด้วย ค่ากลางของ sample ใน class เดียวกัน)
  * Select date by values [PD]
    * ต่อตารางในแนวแกน Y [PD]
    * การเรียงข้อมูล [PD]
    * Outlier
  * การรวมตาราง (ต่อตารางในแนแกน x)
    * รวม 2 ตาราง (.merge())
    * เลือกเฉพาะ column ที่ต้องการมาแปะ (.map())
    * Group by (pandas)
    * [PD] save ตารางเอาไปใช้ที่อื่น
    * [PD] การสร้างตาราง
  * [Slide บทที่ 3]()


* บทที่ 4 [Data Warehousing and On-line Anaalytical Processing](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Chapter4.pdf) ประกอบด้วยหัวข้อ ดังนี้
  * Basic Data Warehouse
  * Data Cube and OLAP
    * OLTP vs. OLAP
    * Data Cubes
    * Conceptual Modeling of Data Warehouse
  * การออกแบบ และการใช้งานคลังข้อมูล
  * ความสำคัญของคลังข้อมูล
  * [Slide บทที่ 4](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Chapter4.pdf)


* บทที่ 5 [Association Rules](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Chapter6_Association_Rules.ipynb)
  * การลบ records ที่ถูก cancel ออก
  * เตรียม Data สำหรับ (Fequence Pattern) Association Rule
  * Apriori
  * [Slide บทที่ 5](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Chapter6.pdf)


* บทที่ 6 Classifications 
  * [Desition Tree](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Chapter7_Classification_(Decision_Tree).ipynb)
    * Load data
    * Train Model
    * Evaluation
    * Advanced Tree
    * TEST
      * import
      * define
      * train
      * evaluation
  * [KNN](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Chap7_Classification_(KNN_NN).ipynb)
    * Load data
    * Split Data
    * Train Model
      * knn 
    * Retrain & Evaluate
    * Neural Network
      * ann
  * [Evaluation](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
    * Load data
    * Split Data
    * สร้าง Model ทำนาย
      * import
      * define
      * train
      * evaluation
  * [Slide บทที่ 6](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Chapter8.pdf)


* บทที่ 7 [clustering](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Chap8_Clustering.ipynb)
  * K-means
    * Generate Data
    * Explore Data
    * Clustering
      * import
      * define
      * fit-predict
    * Example Application (Color Quantization)
      * นับจำนวนสี
      * จัดกลุ่มสีให้เหลือ 16 สี
  * [Slide บทที่ 7]()


* Exam
  * [MiniExam](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/MiniExam.ipynb)


* Project กลุ่มลูกหมี
  * [Project Colab](https://github.com/mintra-tippayaratsontorn/DWDM21/blob/main/Project_DWDM.ipynb)
  * [Project Present](https://github.com/mintra-tippayaratsontorn/DWDM21/commit/b733ebf26d880c1d15521aecc145fc348b63e013)
