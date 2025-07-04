# facial-network

https://www.kaggle.com/datasets/jessicali9530/celeba-dataset/data

Model yaklaşık 200.000 kadar insan yüzünün %90 ile şu özellikleri kullanılarak eğitilir:

'5_o_Clock_Shadow', 'Arched_Eyebrows', 'Bags_Under_Eyes', 'Bald',
'Bangs', 'Big_Lips', 'Big_Nose', 'Black_Hair', 'Blond_Hair', 'Blurry',
'Brown_Hair', 'Bushy_Eyebrows', 'Chubby', 'Double_Chin', 'Eyeglasses',
'Goatee', 'Gray_Hair', 'Heavy_Makeup', 'High_Cheekbones', 'Male',
'Mouth_Slightly_Open', 'Mustache', 'Narrow_Eyes', 'No_Beard',
'Oval_Face', 'Pale_Skin', 'Pointy_Nose', 'Receding_Hairline',
'Rosy_Cheeks', 'Sideburns', 'Smiling', 'Straight_Hair', 'Wavy_Hair',
'Wearing_Earrings', 'Wearing_Hat', 'Wearing_Lipstick',
'Wearing_Necklace', 'Wearing_Necktie', 'Young'

Özelliklerin hepsi datasetinde var ya da yok olarak geçer, arası söz konusu değildir.
Aynı datasetin içindeki Attractive özelliği (Bu özellik de datasetinin içinde sadece doğru ya da yanlış şeklinde belirtilmiştir) target olarak belirlenilir. 
Eğitilen model, eğitildiği ve eğitilmediği örneklerde sadece yukarıdaki özelliklere bakarak verilen örneğin çekici olup olmadığına %78 başarı oranı ile tahmin edebilir.

=> Modelin kadın ve erkekler için hangisinde daha başarılı sonuç verdiği test edilmeli.
=> Modelin yaşlı ve gençler için hangisinde daha başarılı sonuç verdiği test edilmeli.
