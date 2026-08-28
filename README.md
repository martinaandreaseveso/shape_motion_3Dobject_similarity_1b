# shape_motion_3Dobject_similarity_1b

**Contributors**
Martina Andrea Seveso,
Rebecca Hirst,
Alan O'Dowd,
Fiona N. Newell

This experiment investigated whether adding motion-correlated sounds further influences perceived similarity between novel object shapes. Participants judged the similarity of shapes presented with both motion and corresponding sounds.

**Research aims**

The study aims to investigate the role of sounds on the perceived similarity of novel 3D moving objects. The study is a visual similarity rating task, where 3D novel objects are presented with different motion patterns (e.g., objects presented statically, with the same motion or two different motions) and different sound conditions (e.g., with or without correspondent sound matched to the motion pattern).
**
Method and Procedure
**
The study is develop in PsychoPy (version 2022.2.5; Peirce et al., 2019) and it is conduct online via Pavlovia and Prolific.

The study is a sequential audio-visual similarity judgments task. Participants are before exposed to a training phase (to familiarise with the procedure) and a testing phase. Both phases were structured as followed

_Instructions_: please examine pair of objects presented and rate how similar they are based on their shape, ignore other possibile information. Rate them on a rating scale (7 points Likert scale) ranging from 1 - “very dissimilar” to 7 – “very similar”.

The total duration of the experiment was around 25-30 minutes.

**Stimuli**

The experiment presents with static or moving audio visual 3D shapes of unfamiliar objects.

_Development of 3D shapes_: The 2D shapes were extracted from a visual circular shape space, designed and validated by Li et al. (2020). The 3D modelling procedure was accomplished with the software Blender 3.5.0 (2023) (www.blender.org). The 2D shape rotate of 360 degrees along the central vertical axes though the Spin Function in Edit mode (degrees 360, steps 100).

_Stimulus design pipeline for the 3D object models_: The objects were created using the pipeline (1) each shape was converted from .png to Scalable Vector Graphics (.svg) keeping three different colour levels constant (e.g., white, black, grey); (2) each vector was imported into the 3D-space; (3) the outline was isolated and converted into a mesh; (4)each mesh was rotated along the central vertical axes through the Spin Function in Edit mode (360°, steps-100); (5) each 3D-shape was extracted from Blender. The 3D-space, lighting (point, radius-0.1m,1000W; coordinates:11m,-14 m,6.9m; rotation:40°, 34.8°) and viewpoint (coordinates: 10.9m, -14m, 4m; rotation:70°, 0°) settings were kept constant. Each 3D-object was rendered using the Workbench Engine (28-render samples, Single pass Anti-Aliasing viewpoint; Studio Lighting, Colour Material [dark grey, RGB:107,109,109,254; HEX:#6b6d6d] and Specular Lighting). All the object images were extracted with a resolution of 1080 x 1080 px, scale100%, and presented in a canonical, 3/4view so that the 3D-object and relevant features (e.g., concavities) were visually accessible in the image. The camera angle (coordinates:10.9m, -14m, 4m; rotation:70°, 0°) and lighting (point, radius-0.1m, 1000W; coordinates: 11m, -14 m, 6.9m; rotation:40°, 34.8°) were both held constant.

_Animation procedure_ : Five main motion types were defined: swinging or jumping along the vertical axes, and continuous rotation and vibration along the horizontal axes, and abrupt movement on both vertical and horizontal axes. Each action was completed once during the video sequence, which had a total duration of 2 seconds. Animations were extracted in Blender keeping standard lighting and camera conditions.

_Sounds_ : Sounds were designed in Audacity to match the specific motion pattern, this was achieve by manipulation of their tempo and rhythm. All sounds (n=5) were extracted with constant sampling rate of 44100Hz.

**Design**

The experiment is a fully within-subejcts design.Each participant perceives all the 3 motion conditions (i.e., static, same movement, different motions), both sound conditions (i.e., with sound, no sound) and all the stimuli set. Each participant is randomly assigned to one set.

**Dependent variables**
Similarity ratings and RTs.

**Independent variables**
1) Steps distance between A & B.
2) Motion conditions: static, same movements, different movements.
3) Sound conditions: sound, no sound.
4) Set of stimuli assigned to each motion condition.

**Covariates**

Age, sex, and object type.

**Ethics**

Full ethical approval was obtained from the School of Psychology Ethics Committee, Trinity College Dublin.

[Peirce, J. W., Gray, J. R., Simpson, S., MacAskill, M. R., Höchenberger, R., Sogo, H., Kastman, E., Lindeløv, J. (2019). PsychoPy2: experiments in behavior made easy. Behavior Research Methods. 10.3758/s13428-018-01193-y]


**License**
a. Code (analysis scripts, stimuli generation): MIT License
b. All other materials (data, stimuli, experimental design): CC BY 4.0

All stimuli were created by the author (Seveso, M., A.). Data has been anonymised and contains no personal information.
