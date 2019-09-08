# Video-Residual-Dense-Network<br><br>
## Abstract:
近年來卷積神經網路CNN在許多電腦視覺的工作取得卓越的成果，亦包含傳統上認為較困難的超解析度問題，
本篇論文於現有視訊超解析度的架構[1]上，先利用FlowNet2.0[2]估計光流與動作補償、對齊模型輸入的低解析度影格，然後，我們改良了單一影像超解析度的殘差密集網路RDN[3]，提出一種可使用於視訊超解析度的模型VRDN，將低解析度影格轉換為高解析度並且達到state-of-art的效能。<br><br>
## Model Overview:
![image](https://github.com/hugh102575/readme_img/blob/master/%E8%9E%A2%E5%B9%95%E5%BF%AB%E7%85%A7%202019-09-08%20%E4%B8%8B%E5%8D%8812.48.35.png)<br><br>
## VRDN:
![image](https://github.com/hugh102575/readme_img/blob/master/%E8%9E%A2%E5%B9%95%E5%BF%AB%E7%85%A7%202019-09-08%20%E4%B8%8B%E5%8D%8812.41.42.png)<br><br>
## Result 4X: 
![image](https://github.com/hugh102575/readme_img/blob/master/%E8%9E%A2%E5%B9%95%E5%BF%AB%E7%85%A7%202019-09-08%20%E4%B8%8B%E5%8D%8812.57.45.png)
### links: [[1]](https://arxiv.org/abs/1611.05250),[[2]](https://arxiv.org/abs/1612.01925),[[3]](https://arxiv.org/abs/1802.08797),[[15]](https://ieeexplore.ieee.org/document/7444187),[[16]](https://arxiv.org/abs/1704.02738)
