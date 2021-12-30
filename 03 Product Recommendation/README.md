# Product Recommendation

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/16h4FQPLm9m4JNyZredtDc9-TBRdmFdyn?usp=sharing)

# Dataset
Questionnaire by Google form have a yes or no question aboout 25 items that students in class have ever or nerver bought or used.

      - 25 items include โปรแกรมแท้, เครื่องซักผ้า, รองเท้าวิ่ง, ผักกรอบ, คอร์สเรียนเสริม, nintendo switch,
        BTC (Bitcoin), mechanical keyboard, เครื่องดูดฝุ่น Dyson,เคส ipad, โต๊ะปรับระดับ, สินค้าจากพิมรี่พาย,
        IPHONE 13, หูฟัง bluetooth (airpods,truewireless),แก้วน้ำ Starbucks, เบาะรองนั่ง, เครื่องชงกาแฟแคปซูล,
        ตั๋วเครื่องบินไปญี่ปุ่น, Ebook, ตู้เย็น, กล้องฟิล์ม, เครื่องดนตรี, whey protein, วัตถุมงคล, กระบองเพชรพูดได้,ROV Skin
        
 # Data preparing
    - changeg 'เคย ไม่เคย ซื้อ ไม่ซื้อ' to 1 or 2
    - check null value and remove it.
    
  # Recommedation  
  
  ###  Association Rules (filtered by Support > 0.5 and Lift > 1.05)
       - used apriori to found frequent itemsets by 0.35 min_support threshold.
       - made rule by life > 1.02 and confident > 0.6
       
  
