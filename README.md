# LEVEL 0


# TASK 1: 3D PRINTING
 
### OBJECTIVE:
Understand the  working of 3D printer. Understand about STL file and learn to slice it. Learn about SOP'S regarding 3D printer, printer settings. Make a 3D model of your choice.
### OUTCOMES:
3D printer is a device that creates physical object from a digital  design . The common type of printer used is a fusion deposition model(FDM) .          
 * Parts of 3D printer includes extruder, build surface, motion system and the framework and brains .

 * STL(Standard tessellation language) file: STL also called as stereolithography.

 Work: It describes the surface geometry of a 3D object using thousands of tiny triangles.

 Drawback: Don't know the color,material,temperature.It only knows the shape. 

* Slicer: The device that performs slicing.Slicing is the process of turning blueprint into a set of instructions the printer understands.
### Printer settings:
In 3D printing, Slicer settings are the instructions that tell the hardware how to behave. 
### 1. Temperature Settings (The Thermal Foundation): This is specific to the material you are using (like PLA).
 * Printing Temperature (Nozzle): For PLA, this is usually 200°C–210°C. 
 * Build Plate Temperature (Bed): For PLA, 60°C is standard. 
### 2. Quality & Geometry
 * Layer Height: 
   * 0.1mm (Fine): Extremely smooth, but takes a long time.
   * 0.2mm (Standard): The best balance of speed and look.
   * 0.3mm (Draft): Very fast, but you will see visible "steps" or lines on the model.
 * Wall Line Count (Shells): The number of layers on the outside of the object. For most parts, 2 or 3 walls are enough. For functional parts that need to be strong, use 4 or more.
### 3. Infill 

 * Infill Density:
   * 5–10%: For decorative models (figures).
   * 15–25%: Standard for most objects.
   * 50%+: For heavy-duty functional parts.
 * Infill Pattern: Grid/Lines are the Fastest to print.
   Gyroid is Extremely strong in all directions and looks cool while printing.
### 4. Speed Settings
  Print Speed: Usually 50–60 mm/s. 
 * Initial Layer Speed: This should be slow (20 mm/s). 
### 5. Travel & Retraction 
 Retraction: When the printer moves from one point to another without printing, it sucks the filament back slightly.
   * Retraction Distance: Usually 5–6mm for Bowden tube printers (like the Ender 3).
   * Retraction Speed: 40–50 mm/s. This prevents stringing (thin hairs of plastic across your model).
### 6. Cooling
  Fan Speed: For PLA, you want the fan at 100%. Cooling the plastic quickly allows for bridging  and sharp details.
  For the first layer, the fan is usually turned OFF to help with bed adhesion.
  ### Pre printing maintenance:
  clean the bed with 70% isopropyl alcohol to remove oils from fingerprints
### Post printing maintenanace:
store filament in dry box or sealed bag with silica gel to prevent it from absorbing moisture,which causes sounds and brittle prints .
Below is the image of my 3D printed model:

### TASK 2: API
---
### OBJECTIVE:
Understand API ,Using any API of your choice, build a user interface (web app, mobile app, etc.) to make calls and display information
### OUTCOMES AND LEARNINGS:
API(Application programming interface) is a messenger that takes requests  and tells a system what you want to do and return the response.
### Purpose : 
increase modularity,portability,integration,
standardize communication.
### Applications :
Embedded systems,robotics,automotive,telecommunication,industrial automations,cloud computing,AI systems.

Below is the image of weather app built using open weather API:
![image](https://github.com/user-attachments/assets/3668cd32-aedf-4fed-8ce8-d90ef2b7f597)
[Click here](https://github.com/thrishacl02-prog/report.md.git) to view github repository.

[Click here](https://youtu.be/rYtEnbnfQ_8) for the video.

### TASK 03: GITHUB
---

### OBJECTIVE: Working with GitHub
Familiarize yourself with GitHub integrated workflows such as GitHub Actions, Issues, and pull requests. Visit the provided git repository and perform the tasks stated in the README file.

### OUTCOMES AND LEARNINGS:

* Learnt to create github account and clone the repository given.
* Learnt to make new branch, edit and add files, commit the changes,push the branch and open pull request.
* Learnt the github actions and how to work with issues.

Here is the image of my work :

<img width="1903" height="892" alt="Screenshot 2026-02-14 095209" src="https://github.com/user-attachments/assets/5ccf8b3c-4cf1-49b2-8c41-9fce2fa94956" />
<img width="1731" height="511" alt="Screenshot 2026-02-14 095704" src="https://github.com/user-attachments/assets/c4d3e3c0-3e96-4211-a4a2-38211f5c8900" />

[Click](https://github.com/thrishacl02-prog/git-task.git) to view the changes made.

### TASK 04: UBUNTU
---
### OBJECTIVE:Command Line on Ubuntu
Get familiar with the command line on Ubuntu by completing the following subtasks:
Create a folder named test.
cd into that folder.Create a blank file without using any text editor.
List the files in that folder.
Create 2600 folders in this folder, each named with a format like M90 or B56.
Concatenate two text files containing random text and display them on the terminal.
### OUTCOMES AND LEARNINGS:
Ubuntu is a operating system i.e a software system that lets to open a browser,save files,move mouse.I learnt about the linux command line i.e basically component that talks to computer to perform the operations.Got to know about the layers of the command line and the grammar of command.
Familiarized with the structure of command:command,options and arguments.

Subtasks:

1.To create a folder named test.cd: command mkdir foldername .

2.To cd(change the directory) into that folder : command cd folder name.

3 To create an empty file :command touch filename.txt;

4 To list the files in that folder: command ls .
To create 2600 folders in this folder, each named with a format like M90 or B56: command mkdir M{1...2600} .

5.Concatenate two text files containing random text and display them on the terminal:create a folder,in that create two files named blank.txt and blank1.txt and write down the random text in both files and use the command cat blank.txt blank2.txt .

Here is the image of the subtasks :

![image](https://github.com/user-attachments/assets/f8a485b9-2f79-45c0-b37c-fb7639ce49b3)

![image](https://github.com/user-attachments/assets/9af2c5ad-1a46-4738-95ad-de4f8f5b994a)

![image](https://github.com/user-attachments/assets/97a6e551-dca9-4578-bfa1-c5d4395828c4)

### TASK 5: Build Your Own Brain -Linear Regression from Scratch
---

### OBJECTIVE:
Dive into the core of machine learning by implementing Linear Regression from scratch using , and compare its performance with the scikit-learn implementation. Use the California Housing dataset to evaluate your model on real-world data.

### OUTCOMES AND LEARNINGS:
1. Learnt basics of linear regression and gradient descent and implement linear regression manually using Python (without ML libraries).

2. Learnt model evaluation skills i.e
- MSE (Mean Squared Error): measures average squared difference between predictions and actual values.
- MAE (Mean Absolute Error): measures average absolute difference.
- R² (Coefficient of Determination): shows how well the model explains variance in the data.

3. Mathematical formulas:

<img width="867" height="728" alt="image" src="https://github.com/user-attachments/assets/8d0a9b28-8e22-4290-806d-407f9b5442c0" />


here is the image of the graph:



<img width="1536" height="754" alt="graph" src="https://github.com/user-attachments/assets/18652fa4-c67e-49c0-929d-61c38e37e630" />


[Click](https://github.com/thrishacl02-prog/linear-regression.git) to view the repository.

### TASK 6: The Matrix Puzzle — Decode with NumPy & Reveal the Image
---

### OBJECTIVE: 

Get hands-on with NumPy and Matplotlib by solving a visual puzzle. You’ll be given a scrambled matrix, and your mission is to decode it into a hidden image using NumPy operations and visualization techniques.

### OUTCOMES AND LEARNINGS:

1. Learned that images are made up of numbers arranged in the form of a matrix.

2. Understood the basics of NumPy and how to reshape arrays into the correct format.

3. Successfully decoded the scrambled matrix to reveal the hidden image.

4. Learned how data can be converted into visual form.

Here is the image of my work:

<img width="600" height="600" alt="fig" src="https://github.com/user-attachments/assets/37e1e8f8-733d-4718-b105-4dd2b9faf106" />

[Click](https://github.com/thrishacl02-prog/matrix-puzle.git) to visit the github repository.












### TASK 7: PORTFOLIO WEBPAGE
---
### OBJECTIVE: Create a Portfolio Webpage
Create a website to showcase your portfolio, including information about yourself, interests, projects, and social media profiles. Ensure the site is responsive and pushed to a git repository. Use any CSS framework of your choice.

### OUTCOMES AND LEARNINGS:
Here is the portfolio webpage:


![Screenshot_27-1-2026_194536_](https://github.com/user-attachments/assets/08a91445-8e0e-462b-8f24-b5218e015d33)

[Click here](https://github.com/thrishacl02-prog/portfolio-website.git) to view git repository.

### TASK 8 MARKDOWN
---
### OBJECTIVE:
Writing Resource Article Using Markdown.
Markdown is a markup language used to format plain text. Write a technical resource article on a particular use case or application of UAVs. This article will help you gain technical knowledge and create a framework for future projects.

### OUTCOMES AND LEARNINGS:
1. Able to write the resource article using the markdown language.

2. Features of markdown:
* Size of the text can be varied using the hastags.More the hastags,lesser the size.
* The font can be based on the symbol "*".
* Two data can be compared and listed in table.
* Use of images,links and dividers.

3. I Learnt to write the report using markdown.

Refer to the resource article here:

### TASK 9: TINKERCAD
---
### OBJECTIVE: 
Create a Tinkercad account and familiarize yourself with the application. Simulate a simple circuit using an ultrasonic sensor to estimate the distance between an obstacle and the sensor, and display the results on the serial monitor. Create a radar system using an ultrasonic sensor and servo motor to detect objects within a certain range.
### OUTCOMES AND LEARNINGS:
Introduction to tinkercad:Tinkercad by autodesk is a 3D modelling software.Tinkercad operates on a CSG (Constructive Solid Geometry) system.It includes 3D modelling,circuit building and code blocks.

1.Here is the circuit to estimate the distance between an obstacle and the sensor using ultrasensor:
![Screenshot_8-2-2026_20114_www tinkercad com](https://github.com/user-attachments/assets/5aa16d44-f685-4114-b252-39c5880dcb9e)
Components used are:

<img width="947" height="263" alt="image" src="https://github.com/user-attachments/assets/4ec2b20d-cadf-4366-bf9b-3bebe1893ae6" />
Connections are made as following:

<img width="1122" height="781" alt="image" src="https://github.com/user-attachments/assets/1f238918-bc12-4bc2-b0a0-a70a79941c4d" />
Here is the circuit to create a radar system using an ultrasonic sensor and servo motor to detect objects within a certain range:

<img width="1264" height="745" alt="image" src="https://github.com/user-attachments/assets/815d5040-4884-44ce-8d6c-1aed5543cde8" />

2. Understanding ultrasonic sensors and servo motors and basics of radar technology:

* ultrasonic sensors are the elctronic device used to measure the object distance using ultrasonic waves.Operating frequency is >20kHz.
There are mainly two essential elements which are the transmitter and receiver. Using the piezoelectric crystals, the transmitter generates sound, and from there it travels to the target and gets back to the receiver component.

To know the distance between the target and the sensor, the sensor calculates the amount of time required for sound emission to travel from transmitter to receiver. The calculation is done as follows:
D = 1/2 T * C

Where ,‘T’ corresponds to time measured in seconds

‘C’ corresponds to sound speed = 343 measured in mts/sec

<img width="1200" height="615" alt="image" src="https://github.com/user-attachments/assets/c5daef8e-406b-4512-93d6-172199be31e7" />

* Servo motors are specialized electric motors designed for precise control of angular or linear position, speed, and torque.
How Servo Motors Work:
Servo motors operate using a feedback mechanism that continuously monitors the motor's position and adjusts it to match the desired position. The controller compares the actual position (measured by the sensor) with the desired position and generates an error signal to correct any discrepancies.

* Radar technology uses radio waves to detect, locate, and track objects, providing critical information about distance, speed, and direction.

Click on these links to tinker the circuits

[Click](https://www.tinkercad.com/things/aVXrEN2yElH-ultrasonic-sensor) here to tinker the ultrasonic sensor .

[Click](https://www.tinkercad.com/things/1BkmYzxsV64-radar) here to tinker radar.

### TASK 10: Speed Control of DC Motor
---
### OBJECTIVE: 
Explore techniques for controlling DC motors using the L298N motor driver and Arduino board. Control the speed of a 5V DC motor with an Arduino UNO and H-Bridge L298N motor driver. Simulate this on Tinkercad and then perform it on hardware. Record videos of the process.

### OUTCOMES AND LEARNINGS:
I learnt the control of DC motor using LSP32 motor driver.The components and the functions of each pin of arduino,the H-bridge circuit,pins and its working in motor driver(L298N). 

The below image is the circuit diagram I followed:

<img width="818" height="522" alt="image" src="https://github.com/user-attachments/assets/39efcb52-f272-4508-b9ef-be513b7f5bde" />

Components includes :

<img width="881" height="321" alt="image" src="https://github.com/user-attachments/assets/ea002530-faaf-4862-b1bb-8cdb86c434f7" />


[Click](https://youtu.be/l3yFOxI_kbs) here for the video .

### TASK 11: LED Toggle Using ESP32
---
#### OBJECTIVE:

Learn how to use an ESP32 to create a standalone web server that controls an LED connected to the ESP32 GPIOs. Use the Arduino IDE to code and upload the program to the ESP32.

Reference:

Control LEDs Using ESP32 Web Server

### OUTCOMES AND LEARNINGS:

- I learnt in detail about ESP32.It's special features, pinout diagram, programming environments, development board and its functions.
- Familiarized installation of ESP32 in arduino
- Functional Web Server: ESP32 hosts a webpage accessible from any device on the same Wi-Fi network.
- Remote LED Control: LED can be toggled ON/OFF via browser buttons.
- Standalone Operation: No need for external servers or cloud services; ESP32 handles everything
- I also learnt that ESP32 is not just a microcontroller but also a mini web server capable of handling requests and serving HTML/CSS content.Learnt the networking fundamentals i.e IP addresses and role of ports.
- Another outcome of the task is that I learnt to upload code, solved the issues uploading it, accessing the web server and testing the results.

Here is the pindiagram of ESP32:

<img width="945" height="511" alt="Screenshot 2026-02-14 145450" src="https://github.com/user-attachments/assets/0da8c7a6-0c5f-4e82-9d2b-93df9cf71c32" />

Components used are:

<img width="1718" height="647" alt="image" src="https://github.com/user-attachments/assets/af89ff4f-77c8-440c-b83d-99ed9c0384c7" />


The circuit I used to accomplish the task:

<img width="975" height="794" alt="Screenshot 2026-02-14 150416" src="https://github.com/user-attachments/assets/f8b058b7-4472-49b9-9f87-2ea1968c205c" />

Here is the image of my work:

![alt text](image.png)

[Click](https://www.youtube.com/shorts/CKhZFmvyIRU?feature=share) here for the video.

### TASK 12: Soldering Prerequisites
---
### OBJECTIVE: 

Learn about soldering equipment such as solder, soldering iron, soldering wick, and flux. Perform basic soldering on a perf board, such as a simple LED circuit, under the supervision of a coordinator.

### LEARNINGS AND OUTCOMES:

In this task I learnt to do soldering. The tools and it's functions.
The soldering tools includes soldering iron, soldering station, soldering tip, soldering iron stand, solder, third eye, brass or conventional sponge. Learnt the safety measures and  safety equipments used during soldering.

Learnt desoldering.Type of solder commonly used(it's composition), heating tenperature of solder and voltage.
 
 Here is the image of the soldered LED on perf board:

  ![led](https://github.com/user-attachments/assets/b7e91d93-9d68-41ff-b13f-59797169fe4a)

  The soldering process can be referred by the following video:

  [Click](https://youtu.be/kTURB6QboNY) here.

 ### TASK 13: Design a 555 Astable Multivibrator
 ---

### OBJECTIVE: 

Design a 555 astable multivibrator with a duty cycle of 60%. Assemble the circuit on a breadboard and observe the output on a Digital Storage Oscilloscope (DSO).


### OUTCOMES AND LEARNINGS:

The components used in this task are:

| Name  | Component           | Quantity |
|----   |----                 |----      |
| U1	  | 555 IC timer        | 1        |
| C1,C2 |0.01 uF capacitors   | 2        |
|R1     |	10 kilo ohms        |	1        |
|R2     |	20 (10+10) kilo ohms|	1        |
|V1     |	VRPS- 5V            |	1        |  

Here is the circuit diagram:

![image](https://github.com/Asshray-Sudhakar/Marvel-Task-1-Images/blob/main/Astable%20multivibrator%20ckt%20dia.png?raw=true)

 I referred this video to know the working of  555 IC timer:

[Click](https://youtu.be/Y1yVEf2kwU4) here for the video.

### Learnings:

1. I learnt the pin diagram of 555 IC, working principle of 555, Astable multivibrator using 555, frequency and duty cycle , applications ,core functions of 555 in its (monostable,astable,bistable modes).

2. I also learnt about DSO(digital storage oscilloscope),difference from CRO (cathode ray oscilloscope),working priciple of DSO, Key features, advantages and applications of it.

3. After connections made , I got the duty cycle of 59.989% and got the square waveform.

Here is the image of output:

![WhatsApp Image 2026-02-14 at 2 25 22 PM](https://github.com/user-attachments/assets/2d6d1ef0-49c4-4051-89d2-5b90221f4121)
![WhatsApp Image 2026-02-14 at 2 25 28 PM](https://github.com/user-attachments/assets/dabc7e5b-68eb-4f2e-87d8-8b5e3b93c47c)

































