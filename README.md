## วิกฤติฝุ่นพิษ! PM2.5 พุ่งทะยานไม่หยุด ในไทยระหว่างปี 2018-2023

### 1.Data Set: ข้อมูลคุณภาพอากาศจากจุดตรวจวัดคุณภาพอากาศ จากกรมควบคุมมลพิษ
ข้อมูลฝุ่นละอองขนาดไม่เกิน 2.5 ไมครอน (PM2.5) รายวัน จำแนกรายสถานี (กรมควบคุมมลพิษทำการเก็บรวบรวมข้อมูลเป็นรายวันจากจุดตรวจวัดคุณภาพอากาศอัตโนมัติของกรมควบคุมมลพิษ ซึ่งกรมควบคุมมลพิษนำมาจัดทำรายงานเป็นรายปี)

URL: https://pcd.gdcatalog.go.th/it/dataset/air-quality-bangkok-metropolitan-region


### 2.Analysis

#### Part 1:  สถานการณ์ฝุ่นตั้งแต่อดีต - ปัจจุบัน (2018-2023) ของในประเทศ
  จากข้อมูลที่ได้มา เราจะทำการศึกษาค่าฝุ่น PM2.5 โดยเน้นไปที่การวิเคราะห์การกระจายตัวของค่าฝุ่นในแต่ละจังหวัดที่มีการจัดเก็บข้อมูล เราจะใช้เครื่องมือ กราฟ Boxplot เป็นวิธีการหลักในการวิเคราะห์ เนื่องจาก Boxplot สามารถแสดงข้อมูลเชิงสถิติที่สำคัญได้หลายด้าน ไม่ว่าจะเป็น ช่วยแสดงการกระจายตัวของค่าฝุ่น PM2.5 ในแต่ละจังหวัดอย่างชัดเจน
สามารถมองเห็น ค่ากลาง (Median) และช่วงของค่าฝุ่นที่เกิดขึ้นบ่อยๆ ในแต่ละจังหวัด Boxplot ยังช่วยให้เห็น Outliers ซึ่งเป็นค่าฝุ่นที่สูงหรือต่ำผิดปกติ Boxplot ซึ่งช่วยให้เราสามารถวิเคราะห์เหตุการณ์หรือสถานการณ์ที่ทำให้เกิดความผิดปกติในคุณภาพอากาศได้การศึกษาดังกล่าวจะช่วยให้เราเข้าใจถึงสถานการณ์ค่าฝุ่น PM2.5 ในแต่ละจังหวัดมากขึ้น ไม่ว่าจะเป็นการเปรียบเทียบค่าฝุ่นระหว่างจังหวัด รวมถึงการระบุปัญหาที่อาจเกิดขึ้นจากค่าฝุ่นที่ผิดปกติ
![image](Boxplot-All.png)


#### Part 2: วิเคราะห์ความสัมพันธ์ของปริมาณฝุ่น PM2.5 ระหว่างจังหวัดต่าง ๆ</span>

เพื่อดูว่าค่าฝุ่น PM2.5 ในจังหวัดหนึ่งมีความสัมพันธ์กับจังหวัดอื่นๆ อย่างไร การวิเคราะห์นี้จะช่วยบ่งบอกว่าจังหวัดใดมีการเคลื่อนตัวของฝุ่นไปยังจังหวัดข้างเคียง หรือได้รับผลกระทบจากแหล่งกำเนิดฝุ่นในบริเวณใกล้เคียงมากน้อยแค่ไหน
จังหวัดที่อยู่ใกล้เคียงกัน เช่น เชียงใหม่และลำปาง อาจมีค่าความสัมพันธ์เชิงบวกสูง เนื่องจากมีสาเหตุของการเกิดฝุ่นที่คล้ายคลึงกัน เช่น การเผาในที่โล่งในภาคเหนือ
จังหวัดที่อยู่ไกลจากกัน เช่น กรุงเทพฯ และภูเก็ต อาจมีค่าความสัมพันธ์ต่ำกว่า เนื่องจากปัจจัยการเกิดฝุ่นมาจากสาเหตุที่แตกต่างกัน เช่น การจราจรในเมืองใหญ่กับฝุ่นควันจากเรือในพื้นที่ชายฝั่ง

#### Part 3:  สถานการณ์ฝุ่นแต่ละภาค
สถานการณ์ฝุ่น PM2.5 ในแต่ละภาคของประเทศไทยมีความแตกต่างกันขึ้นอยู่กับลักษณะภูมิประเทศ กิจกรรมทางเศรษฐกิจ การขนส่ง และสภาพอากาศของแต่ละภาค ซึ่งสามารถสรุปสถานการณ์ฝุ่นในแต่ละภาคได้ดังนี้

#### Part 4: Top 5 high PM 2.5 provinces
จากการวิเคราะห์ข้อมูลปริมาณฝุ่น PM2.5 ในช่วงปี 2018-2023 พบว่ามี 5 จังหวัดในประเทศไทยที่ประสบปัญหาค่าฝุ่น PM2.5 สูงที่สุดเป็นประจำทุกปี จังหวัดเหล่านี้ล้วนเป็นพื้นที่ที่มีปัจจัยต่างๆ เช่น การเผาในที่โล่ง อุตสาหกรรม และการจราจรที่หนาแน่น ซึ่งทำให้ค่าฝุ่นสะสมอยู่ในระดับที่เป็นอันตรายต่อสุขภาพของประชาชน โดย 5 จังหวัดที่มีปริมาณฝุ่น PM2.5 สูงสุดได้แก่
Part 5:  คาดการณ์สถานการณ์ ฝุ่น ในอนาคต for top 5 province

### 3.Summary


### 4.Our Challenge
