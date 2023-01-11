# 11/17:原先使用的演算法(CNN + DQN)
![image](https://user-images.githubusercontent.com/114141277/211732085-b860d5a0-7611-4e50-8adf-ea49cea96dcb.png)
# 11/24
![image](https://user-images.githubusercontent.com/114141277/211733271-5cff09e1-3c7c-4fa0-9b63-12f277b3e91c.png)
# 初步構想 MLP + 基因演算法
![image](https://user-images.githubusercontent.com/114141277/211733704-eb30a2a4-0466-4d75-b2c8-018dc170ec1c.png)
![image](https://user-images.githubusercontent.com/114141277/211733769-907bcb16-d73d-4977-9d0a-e19e74d6f42a.png)
# 12/8:使用 NEAT演算法
![image](https://user-images.githubusercontent.com/114141277/211733974-938435f3-6364-4c71-abfb-4a827ae9aec6.png)
# 規劃各節點/設計世代演化
![image](https://user-images.githubusercontent.com/114141277/211734002-61ef7593-0c93-43f3-b4f1-5c6273ed0c90.png)
![image](https://user-images.githubusercontent.com/114141277/211734036-02a5980e-0477-439c-b6ed-1b56394a097e.png)
![image](https://user-images.githubusercontent.com/114141277/211734069-773cb40c-da5a-4457-bcff-cfab778ac7d4.png)
# 修改 w 與 fitness解釋/輸入節點統一命名/修改世代演化
![image](https://user-images.githubusercontent.com/114141277/211735226-a75d2dc9-2d34-4f4b-ba26-15ae2a2507fb.png)
![image](https://user-images.githubusercontent.com/114141277/211735240-a320e58c-4ef9-4325-88b0-53044b67255a.png)
![image](https://user-images.githubusercontent.com/114141277/211735257-ae4e77e1-5f80-4e7c-818a-1e6e7cd9b0af.png)
# 1/5
# NEAT演算法的基因編碼
![image](https://user-images.githubusercontent.com/114141277/211738426-92c0c2f2-e60e-44e8-b4bf-285acb8584ed.png)
# 程式碼: NEAT演算法的激活函數與聚合函數(編碼方式)
![image](https://user-images.githubusercontent.com/114141277/211735973-6ec2b48d-2c64-4800-8927-cfb2a66f1ee3.png)
# 程式碼: 串接輸入節點/隱藏節點/輸出節點成為基因組，並在 node_evals函式中紀錄"基因組/激活函數/聚合函數(sum)/bias/response/inputs"
![image](https://user-images.githubusercontent.com/114141277/211736166-a5e03a64-b6ea-4cba-bdfd-80c3f335dc9a.png)
# 配對的編碼方式
![image](https://user-images.githubusercontent.com/114141277/211735734-50dd9b08-ec37-4499-9488-f9ec3f794c26.png)
# 程式碼: 透過同源基因組交叉配對節點
![image](https://user-images.githubusercontent.com/114141277/211737719-96581a15-50f2-404d-883f-56aca8e606a0.png)
# 突變的編碼方式
![image](https://user-images.githubusercontent.com/114141277/211735759-ebe5a82b-9a94-412c-8022-3fe68fab7e5b.png)
# 程式碼: 隨機選擇節點及連接
![image](https://user-images.githubusercontent.com/114141277/211737754-3140aaf3-c614-4443-96da-fdc7ea0a678c.png)
