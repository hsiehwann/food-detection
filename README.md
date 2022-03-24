

專案整體流程：
使用LabelIMG將物件標記類別，接著使用Roboflow將資料切分為訓練集、測試集和驗證集，再使用Colab線上GPU資源進行模型訓練，並評估模型訓練結果加以優化，最後部署至物聯網上。

技術架構圖：

<img width="613" alt="技術架構圖" src="https://user-images.githubusercontent.com/97154985/159950878-a9b2d3a3-ba97-475a-887a-b8fd0864dc96.PNG">



專案目標：
小吃AI化---> 將模型部署至物聯網，進行食材即時偵測，取得雲端資訊，提升攤商結帳效率。

模型評估：
Yolov5s.ipynb為colab訓練yolov5s模型過程
考量後續需部署至終端裝置上，使用模型容量小、推理速度快的yolov5s做為訓練

測試結果：

![95_jpg rf 83faf4d0d6d4904b94fe22611db82c88](https://user-images.githubusercontent.com/97154985/159410398-8a7c84b1-6055-4408-8e0e-443ba0cbcc66.jpg)
![207_jpg rf ccc9cfff7533c5cb7b6b18e4a3020594](https://user-images.githubusercontent.com/97154985/159419001-2e08d2ee-a540-4fcd-95f3-e825373c4bff.jpg)
![467_jpg rf 7154140492ff471f2d2e473537ce45a5](https://user-images.githubusercontent.com/97154985/159419000-d581fcdd-2235-4f1c-b965-628640de3725.jpg)
![609_jpg rf dd7ea48899914fc9122748e180497e33](https://user-images.githubusercontent.com/97154985/159419008-8fb7bd40-86a1-487c-b713-8642867afa1e.jpg)
![185_jpg rf f05c9efcef299dbbbe528c2bed9dd82c](https://user-images.githubusercontent.com/97154985/159419034-380028e0-fb0c-49ea-a78b-29068047127a.jpg)
![409_jpg rf f9b7b96286b19cdf95512043e8e44c4c](https://user-images.githubusercontent.com/97154985/159419095-06d4c726-4713-4965-9c83-7597c9e8d4cb.jpg)
