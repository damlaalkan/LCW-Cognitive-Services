# LCW-Cognitive-Services

**Intelligent Kiosk**

•	Microsoft Cognitive Servisler üzerine kurulu iş akışlarını ve deneyimlerini gösteren bir demolar koleksiyonudur. Github linkinden veya Microsoft Store’dan indirilebilir.

•	Github: https://github.com/Microsoft/Cognitive-Samples-IntelligentKiosk

•	Microsoft Store: https://www.microsoft.com/en-us/p/intelligent-kiosk/9nblggh5qd84?activetab=pivot%3Aoverviewtab


**FACE**  

•	Face detect, identify, emotion gibi API’ların çağırıldığı, person group oluşturma ve train etme gibi özellikleri içeren projenin linki: https://github.com/gpeipman/CognitiveServicesDemo


**OCR**

•	Computer Vision servisinin kullanıldığı, fiş üzerindeki tarihi, fiş numarasını ve toplam tutarını hem json formatında tutan ve csv dosyasına aktaran projenin linki: https://github.com/damlaalkan/OCR_Receipt_Recognition

•	https://azure.microsoft.com/en-us/services/cognitive-services/computer-vision/ linkindeki “Read both printed and handwritten text in images” kısmında OCR demosu ile karakterlerin nasıl okunduğu incelenebilir.

•	API için linkten faydalanabilirsiniz. https://docs.microsoft.com/en-us/azure/cognitive-services/Computer-vision/quickstarts/csharp-print-text 

•	Yukarıda paylaştığım Fiş Tanıma projesinde kullandığımız method “OCR” yerine “RecognizeText” methodudur. OCR servisinin diğer methodlarını incelemek için ise https://westcentralus.dev.cognitive.microsoft.com/docs/services/5adf991815e1060e6355ad44/operations/56f91f2e778daf14a499e1fc linkinden faydalanılabilir.

**Custom Vision**

•	https://www.customvision.ai/ classification ve object detection modelleri oluşturulabilecek platform.

•	Publish ettikten sonra elde ettiğiniz Prediction Key ve Prediction URL kullanarak çalıştırabileceğiniz console application (C#) : https://github.com/damlaalkan/Custom_Vision_Prediction

•	https://github.com/Azure-Samples/cognitive-services-onnx12-customvision-sample/ linkindeki application, export ettiğiniz ONNx modelinizden gelen ONNx file eklenerek çalıştırılabilir. Ayrıntılı bilgi için https://docs.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/custom-vision-onnx-windows-ml  linkini inceleyebilirsiniz.

•	TensorFlow modelini export ederseniz  https://docs.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/export-model-python linkinden faydalanabilirsiniz.


**LUIS**

•	https://www.luis.ai/ linki kendi NLP modelinizi hazırlayabilirsiniz. Detaylı bilgi için https://docs.microsoft.com/en-us/azure/cognitive-services/luis/what-is-luis linki incelenebilir.

•	Bugünkü örneğimizi, “Import new app” seçeneği üzerinden paylaştığımız json dosyasını indirerek üzerinde çalışabilir, yemek, eğitim ve ulaşım gibi tanımlanmış olan intentleri test edebilirsiniz.


