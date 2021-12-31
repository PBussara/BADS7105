# Product Recommendation

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1VcfsXE3Oc9hGrVnVZo4pfTqjl2CMhOMy?usp=sharing)

# Dataset
Questionnaire by Google form have a yes or no question aboout 25 items that students in class have ever or nerver bought or used.

      - 25 items include โปรแกรมแท้, เครื่องซักผ้า, รองเท้าวิ่ง, ผักกรอบ, คอร์สเรียนเสริม, nintendo switch,
        BTC (Bitcoin), mechanical keyboard, เครื่องดูดฝุ่น Dyson,เคส ipad, โต๊ะปรับระดับ, สินค้าจากพิมรี่พาย,
        IPHONE 13, หูฟัง bluetooth (airpods,truewireless),แก้วน้ำ Starbucks, เบาะรองนั่ง, เครื่องชงกาแฟแคปซูล,
        ตั๋วเครื่องบินไปญี่ปุ่น, Ebook, ตู้เย็น, กล้องฟิล์ม, เครื่องดนตรี, whey protein, วัตถุมงคล, กระบองเพชรพูดได้,ROV Skin
        
 # Data preparing
    - changeg 'เคย ไม่เคย ซื้อ ไม่ซื้อ' to binary class (0 or 1)
    - check null value and remove it.
    
  # Recommedation  
  
  ###  Association Rules 
       - used apriori to found frequent itemsets by 0.1 of  min_support threshold.
       - made rule by life > 1.02 and confident > 0.6
   
   ![alt tag](https://github.com/PBussara/BADS7105/blob/main/03%20Product%20Recommendation/First_rule_graph.png)
   
  ### Collaborative filtering
        - Found similarity between pair - frequent itemsets by cosin similarity
        - filter pair frequent itemsets at cosin similarity > 0.5
   
   ![alt tag](https://github.com/PBussara/BADS7105/blob/main/03%20Product%20Recommendation/Similarity_graph.png)
  
   ### Result and analysis
         - the customers who bougth film camera have  high possibility to buy whey protein or nintendo switch.
           They have healthy lifestyle, hi-tech and artistic sensibilities. We offer them by  discount coupon of bluetooth headphone. 
