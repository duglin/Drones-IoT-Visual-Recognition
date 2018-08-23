*Quick links :*
[Home](/README.md) - [Watson Studio](STUDIO.md) - [**Create a Project**](PROJECT.md) -
 [Visual Recognition Model](VISRECO.md)
***

## Lab Objectives

In this lab you will set up Watson Studio with a new Project.  You will learn:

- How to set up a new Watson Studio Project
- How to create a Visual Recognition model

### Watson Studio Projects

Projects are your workspace to organize your resources, such as assets like data, collaborators, and analytic tools like notebooks and models

#### Create a New Project

- Click on **New project**
- Select the **Complete** tile and press the **OK** button

![Watson Studio New project screenshot](screenshots/WatsonStudio-NewProject-Tiles.png)

- Give your Project a name : **Wildfire Burned Homes**
- The Cloud Object Storage instance created in an earlier step should be prefilled
- Press the **Create** button

![Watson Studio New project screenshot](screenshots/WatsonStudio-NewProject.png)

#### Add Assets to your Watson Studio
- Click on the **Assets** tab

![Watson Studio  screenshot](screenshots/WatsonStudio-Assets.png)

#### Create a New Visual Recognition model
- Click on the **New Visual Recognition model**

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModel.png)

#### Provision a new Watson Visual Recognition Service instance
- Your project needs to be associated with a Watson Visual Recognition Service instance
- Click on the **click here** link in the popup to provision a new service

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionService.png)

#### Create a Watson Visual Recognition Service
- Select the **Lite** plan
- Scroll to the bottom and click on the **Create** button

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionServiceInstance.png)

#### Rename Visual Recognition Model
- The **Default Custom Model** name is not descriptive so let's rename it
- Click on the **pencil** icon to edit the name.

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelRename1.png)

- Rename the model to **Count Burned Homes**

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelRename2.png)

#### Add Custom Classes to the Watson Visual Recognition Model
- Click on the **+** symbol to add a class

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelAddClass1.png)

- Name this class **Burned Home**
- Click the **Create** button

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelBurnedHomeClass.png)

- Add a second custom class by clicking on the **+** symbol again

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelAddClass2.png)

- Name this class **Intact Home**
- Click the **Create** button

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelIntactHomeClass.png)

#### Upload Zip Files to Watson Studio Project
- Three zip files have been prepared which contain aerial drone images.
- These zip files are on the local lab workstation
- Click on the **Browse** button
- Multi-select the three zip files **BurnedHomes.zip**, **AerialHomes.zip**, **NotHomes.zip**

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelAddZipFiles.png)

#### Drag the zip files to Custom Classes
- Grab the **BurnedHomes.zip** from the right navigation and drag it to the **Burned Home** class

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelZipFiles.png)

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelZipFileDrag.png)

- The images in the zip file will be added to the **Burned Home** class

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelZipFile2Class.png)

- Grab the **AerialHomes.zip** from the right navigation and drag it to the **Intact Home** class

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelZipFile2ClassIntactHome.png)

- Grab the **NotHomes.zip** from the right navigation and drag it to the **Negative** class

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelZipFile2ClassNotHomesNegative.png)

#### Train your Watson Visual Recognition Custom Classifier
- Click on the **Train Model** button
- Wait a few minutes for the model to train on the images

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelTrain.png)

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelTraining.png)

#### Congratulations
- Once the model has been trained, click on the **Click here** link to view and test your model.

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelTrained.png)

#### Review and Test
- Review the Classes and Model details
- Click on the **Test** tab

![Watson Studio  screenshot](screenshots/WatsonStudio-VisualRecognitionModelSummary.png)

*Quick links :*
[Home](/README.md) - [Watson Studio](STUDIO.md) - [**Create a Project**](PROJECT.md) -
 [Visual Recognition Model](VISRECO.md)
