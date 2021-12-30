# Voice of Customers
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GHIE4J53E2usb9NULsye8qpWM4udLARx?usp=sharing)

## Dataset
Wongnai Reviews - Small

## What we do?
    - Tune model : 
       Umap: set random state = 15 ,component = 200
    - Add new words:"สตารบัก","กวงทะเลเผา","เบเกอรี่","ชานม","คาปูชิโน่","อเมซอน","ไม่ชอบ","ชานม","Dakasi","วโรชา","ยี่ห้อ","ตลาดหนองมน"
    - Remove words:'u', 'b', 'n', 'nn', 'nn-', '\n', 'ร้าน','ทาน','กิน',"ผม","ฉัน","บ้าน","ซอย","อาหาร","กก","รีวิว","(",")","ไหม","นขา"
    - Read to Understand customer in each group
    
 
## Result
    - Cluster ID : 0 (Coffee holic): นักดื่มกาแฟตัวยง มีไลฟ์สไตล์ในการดื่นกาแฟพร้อมเบอร์เกอรี่ง่ายๆ ก่อนทำงาน  เน้นรีวิวร้านกาแฟที่หาได้ตามห้างสรรพสินค้าทั่วไป
    - Cluster ID : 1 (Taster): กลุ่มนักชิมอาหารจากหลากหลายสถานที่ โดยเฉพาะอาหารไทย ค่อนข้างให้ความเห็นในเชิงบวก และเล่าความประทับใจเพื่อเชิญชวนให้ไปรับประทาน 
    - Cluster ID : 2 (Teaholic): กลุ่มคนหลงรักการดื่มชาโดยเฉพาะชานมไข่มุก ท่ามหกลางบรรยากาศ สบายๆ พร้อมเดิมชิมอาหารประเภทสตรีทฟู้ด
    - Cluster ID : 3 (Variety): กลุ่มคนรับประทานอาหารหลากหลาย ไม่ว่าจะเป็นอาหารเวียดนาม กาแฟเจ้าดัง ไอครีม ร้านไหนที่ว่าดี ต้องมีบุคคลกลุ่มเข้าไปเยื่อน 
