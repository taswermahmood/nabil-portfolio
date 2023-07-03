<template>
    <v-row style="padding: 5% 5%" class="text-center">
        <v-col class="pa-2 align-self-center text-left" cols="12">
            <div data-aos-duration="1500" data-aos="fade-left" style="padding-bottom:2%">
                <div style="font-family: 'Lilita One', cursive; font-size: 40px; padding-bottom: 1%;"> Key Projects</div>
                <v-row style="padding-left:2%" justify="center">
                    <v-col cols="7">
                        <a href="https://github.com/ftnabil97/Construction-Site-Safety-Inspection-Application" target="_blank" style="font-weight:bold; font-size: 20px; padding:1% 0%">Construction Site Safety Inspection Application</a>
                        <div style="padding-top:1%">
                            Construction safety is of utmost significance in the construction industry, ensuring the well-being and protection of workers, stakeholders, and the public. The construction Site Inspection
                            Application is developed to inspect and promote safety protocol at the construction site. The app is developed by
                            integrating a custom-trained object detection model using Python Programming language.
                        </div>
                        <div style="font-weight:bold;">Features:</div>
                        <li>A user-friendly Graphical User Interface (GUI).</li>
                        <li>The app allows for multiple images upload and webcam integration, enabling real-time safety gear
                            detection.</li>
                        <li>Users can select individual items for detection which gives them more control over inspection.
                        </li>
                        <li>Users can keep records of inspection while using webcam through Capture Image, and it is
                            automatically saved to the application folder.</li>
                        <li> The application employs computer vision algorithm, more precisely custom-trained object
                            detection
                            model provided by Ultralytics library.</li>
                        <div>The application is developed leveraging different library frameworks. The interface was created
                            using the Tkinter library. Tkinter library’s filedialog module was implemented for integrating the file uploading
                            feature. Tkinter provides integration with PIL (Python Imaging Library) through the ImageTk
                            module, which allows PIL images to be displayed and manipulated. OpenCV framework is used to process
                            images and webcam integration. To assimilate the custom-trained detection model into the application,
                            Ultralytics library was imported and the model returns NumPy array. Tkinter, as a GUI library, does not have
                            built-in functionality to directly read or handle NumPy arrays. However, NumPy array can be converted into a compatible PIL image. There are also buttons assigned to selectively detect objects as well as
                            all of them at once.</div>
                    </v-col>
                    <v-col style="padding-top: 2%;" cols="5">
                        <div style="text-align: center;">
                            <v-img height="320px" width="600px" src="../assets/inspection.png"></v-img>
                        </div>
                    </v-col>
                </v-row>
                <v-row style="padding-left:2%" justify="center">
                    <v-col cols="7">
                        <a href="https://github.com/ftnabil97/Construction-Site-Safety-Gears-Detection/tree/main" target="_blank" style="font-weight:bold; font-size: 20px; padding:1% 0%"> Construction-Site-Safety-Gears-Detection</a>
                        <div style="padding-top:1%">
                            Construction site safety gears detection project primarily focuses training a pretrained model
                            provided by Ultralytics library to develop the custom-trained object detection model. The model
                            namely best.pt is specifically trained based on yolov8s.pt. The model is trained with a dataset
                            consisting of 424 images which were collected and annotated using the Roboflow framework.
                            After training, it returns visuals of the confusion matrix, p curve, F1 curve, and more. This
                            training model can be utilized to develop further applications. The code was written on google
                        </div>
                    </v-col>
                    <v-col style="padding-top: 2%;" cols="5">
                        <div style="text-align: center;">
                            <v-img height="320px" width="600px" src="../assets/gear.png"></v-img>
                        </div>
                    </v-col>
                </v-row>
            </div>
        </v-col>
    </v-row>
</template>
  
<script>
export default {
    name: 'Skills',
}
</script>