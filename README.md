# Classification of Diabetic Retinopathy Disease

Here I collected data, that has the ground truth given, from [Kaggle](https://www.kaggle.com/dola1507108/diabetic-retinopathy-classified).

I obtained my background information from the [Mayo Clinic](https://www.mayoclinic.org/diseases-conditions/diabetic-retinopathy/symptoms-causes/syc-20371611). They describe Diabetic Retinopathy is a diabetic complication that affects the eyes. It's caused by damage to the blood vessels of the light-sensitive tissue at the back of the eye called the retina. At first, diabetic retinopathy may cause no symptoms or only mild vision problems. Eventually, it can cause blindness.

The condition can develop in anyone who has Type 1 or Type 2 diabetes. The longer you have diabetes and the less controlled your blood sugar is, the more likely you are to develop this eye complication. 

The dataset had the images rated by the presence of diabetic retinopathy in each image on a scale of 0 to 4, according to the following scale:

- 0: No DR
- 1: Mild DR 
    **At this earliest stage, microaneurysms occur. They are small areas of balloon-like swelling in the retina's tiny blood vessels.**
- 2: Moderate DR 
    **As the disease progresses, some blood vessels that nourish the retina become blocked.**
- 3: Severe DR 
    **Many more blood vessels are blocked, depriving several areas of the retina with their blood supply. These areas of the retina send signals to the body to grow new blood vessels for nourishment.**
- 4: Proliferative DR 
    **At this advanced stage, the signals sent by the retina for nourishment trigger the growth of new blood vessels.  These new blood vessels are abnormal and fragile. They grow along the retina and along the surface of the clear, vitreous gel that fills the inside of the eye. By themselves, these blood vessels do not cause symptoms or vision loss. However, they have thin, fragile walls. If they leak blood, severe vision loss and even blindness can result.**

I will create a model that will classify the images based on the above scale. Without models, it could take 7-14 days to get results back after an eye exam, beacuse the doctor has to make the determination using the Fundus. This not only takes time delaying potential treatment, but also allows for error, since predictions are made with the human eye. The objective is to create a model which will allow for quicker and more accurate diagnosis, allowing for better treatment if needed.
