you need have training data(e.g. train.tsv) and validation data(e.g. dev.tsv), and put it under a folder(e.g.TEXT_DIR )
 
you can generate data by yourself as long as data format is compatible with processor 
 
SentimentAnalysisFineGrainProcessor(alias as sentiment_analysis); 
 
you can also download data from here <a href=''>AI challenger-sentiment analysis</a>, which is generated by following

step by step: preprocess_char.ipynb 
 
 
 data format:  label1,label2,label3\t here is sentence or sentences\t
 
 it only contains two columns, the first one is target(one or multi-labels), the second one is input strings.
  
 no need to tokenized.
 
 sample:"0_1,1_-2,2_-2,3_-2,4_1,5_-2,6_-2,7_-2,8_1,9_1,10_-2,11_-2,12_-2,13_-2,14_-2,15_1,16_-2,17_-2,18_0,19_-2 浦东五莲路站，老饭店福瑞轩属于上海的本帮菜，交通方便，最近又重新装修，来拨草了，饭店活动满188元送50元钱，环境干净，简单。朋友提前一天来预订包房也没有订到，只有大堂，五点半到店基本上每个台子都客满了，都是附近居民，每道冷菜量都比以前小，味道还可以，热菜烤茄子，炒河虾仁，脆皮鸭，照牌鸡，小牛排，手撕腊味花菜等每道菜都很入味好吃，会员价划算，服务员人手太少，服务态度好，要能团购更好。可以用支付宝方便"
 
 check sample data in ./BERT_BASE_DIR folder  
 