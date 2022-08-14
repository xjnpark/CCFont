# CCFont : Component-Based Chinese Font Generation Model using GANs

#### J. Park, A. U. Hassan and J. Choi, "Few-Shot Korean Font Generation based on Hangul Composability," KIPS Transactions on Software and Data Engineering, vol. 10, no. 11, pp. 473-482, 2021. DOI: https://doi.org/10.3745/KTSDE.2021.10.11.473.

 [MDPI](https://www.mdpi.com/journal/applsci) Appl. Sci. 2022, 12(16), 8005; https://doi.org/10.3390/app12168005 [PDF](https://www.mdpi.com/2076-3417/12/16/8005)
 
---
### Abstract    

##### Font generation using deep learning has made considerable progress using image styletransfer, but the automatic conversion/generation of Chinese characters still remains a difficult taskowing to the complex character shape and large number of Chinese characters. Most known Chinesecharacter generation models use the image conversion method of the Chinese character shape itself;however, it is difficult to reproduce complex Chinese characters.  Recent methods have utilizedcharacter compositionality by separating up to three or four components to improve the qualityof generated characters, but it is still difficult to generate high-quality results for complex Chinesecharacters with many components. In this study, we proposed the CCFont model (component-basedChinese font generation model using generative adversarial networks (GANs)) that automaticallygenerates all Chinese characters using Chinese character components (up to 17 components). TheCCFont model generates all Chinese characters in various styles using the components of Chinesecharacters based on conditional GAN. By acquiring local style information from the components,the information is more accurate and there is less information loss than when global informationis obtained from the image of the entire character,  reducing the failure of style conversion andimproving quality to produce high-quality results. Additionally, the CCFont model generates high-quality results without any additional training (zero-shot font generation without any additionaltraining) for the first-seen characters and styles. For example, the CCFont model, which was trainedwith only traditional Chinese (TC) characters, generates high-quality results for languages that canbe divided into components, such as Korean and Thai, as well as simplified Chinese (SC) charactersthat are only seen during inference. CCFont can be adopted as a multi-lingual font-generation modelthat can be applied to all languages, which can be divided into components.  To the best of ourknowledge, the proposed method is the first to generate a zero-shot multilingual generation modelusing components. Qualitative and quantitative experiments were conducted to demonstrate theeffectiveness of the proposed method.
---
### Results
---
 <img src = "https://user-images.githubusercontent.com/62954678/184543239-81a8aa0d-5d64-4c8e-9158-5f7aabe800cc.png" width="1000" height = "400">  
<p> #### Sample output images of the TC characters generated</p> 

<img src = "https://user-images.githubusercontent.com/62954678/184543559-1a8a9875-5266-40d9-8af9-e1de49511072.png" width="1000" height = "400">

<img src = "https://user-images.githubusercontent.com/62954678/184544065-063f4127-1534-4809-9a02-279f3d0f66e7.png" width="1000" height = "400">

