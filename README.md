# Pnemonia_Detection_CV_Deep_Learning

Pneumonia is an infection of the lungs. Bacteria, viruses and fungi cause it. The infection causes inflammation in the air sacs which are called alveoli.

Pneumonia accounts for a lot of deaths of children worldwide. In recent times, it has resulted in death of patients being affected by the novel CoronaVirus. Its detection hence holds a very important place today when COVID-19 is still a pandemic and the detection of symptoms of severe pneumonia in the lungs may be life threatening to the COVID patients.

The detection of pneumonia is done using a chest radiograph(CXR) which is reviewed by highly trained specialists and confirmed through clinical history, vital signs and laboratory examinations. Pneumonia is identified in a CXR as a region of opacity. This detection becomes complicated as several other conditions can also account to opacity in CXR of lungs. Thus CXR taken of patients at different times and correlation with clinical symptoms are vital in the identification of pneumonia.

The positioning of the patient affects the appearance of a CXR. Also, clinicians read many CXR in a shift. Thus Automating the pneumonia detection would assist physicians in making better clinical decision 

The goal of the capstone project is to build a pneumonia detection system, to locate the position of inflammation in an image of the lungs. Tissues with sparse material, such as lungs which are full of air, do not absorb the X-rays and appear black in the image. Dense tissues such as bones absorb X-rays and appear white in the image. While we are theoretically detecting “lung opacities”, there are lung opacities that are not pneumonia related. In the data, some of these are labeled “Not Normal No Lung Opacity”. This extra third class indicates that while pneumonia was determined not to be present, there was nonetheless some type of abnormality on the image and oftentimes this finding may mimic the appearance of true pneumonia. 

Position of pneumonia induced opacity in the lungs is to be marked using bounding boxes. A single CXR can have multiple bounding boxes which are to be identified using object detection. Transfer learning technique is to be incorporated and hyper parameters set to the best range to fine-tune the model. 

