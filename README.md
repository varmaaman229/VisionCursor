
# Real-Time Face Detection For Improved Survellance and Access Control
![Capture](https://github.com/user-attachments/assets/f8d9b0e5-f3ca-40cf-9b86-c825842aad8b)

**Description:** VisionMouse aims to develop a computer vision-based virtual mouse controlled by head movements to improve accessibility for individuals with disabilities. This system tracks head movements and converts them into mouse movements on the screen, enhancing user experience in applications such as gaming and virtual reality.

**Objectives:**
1. Develop a robust computer vision algorithm for head movement tracking.
2. Integrate the system with existing operating systems and applications.
3. Implement a user-friendly interface for configuration and calibration.

**Key Features:**
- Real-time head movement tracking.
- Mouse control via head movements.
- User configuration settings.
- Cross-platform compatibility.
- Enhanced accessibility.

**Impact:** VisionMouse can significantly increase independence and improve the quality of life for individuals with disabilities, providing an alternative input method and enabling hands-free interaction with computers.

**Conclusion:** VisionMouse leverages advanced computer vision techniques to create a practical, impactful tool that brings us closer to the fictional technology seen in popular culture, benefiting those in need of alternative input methods.

## Working Actions

Open wide eyes + Mouth Open ==> Left Click

minimize eye + Mouth open ==> Right Click

move your eye sight to move the mouse

Video Explanation



https://github.com/user-attachments/assets/990a1fc6-8ca3-420b-96f0-69d32b1abd6a



https://github.com/user-attachments/assets/e970b370-25dd-4609-bf93-a82d45315965



https://github.com/user-attachments/assets/4b50a719-57cf-4976-9fa7-518fdc03d70f


# Authors

### TechWarriers
- Aman Varma
- Vishnu Rathod
- Akash Rathod


## Demo

![Capture](https://github.com/user-attachments/assets/f8d9b0e5-f3ca-40cf-9b86-c825842aad8b)



## Deployment

To deploy this project run

```bash
  python run
```





## Lessons Learned
It was my third hackathon. The Problem statement was so interesting that i was stuck to the computer screen straight 36 hrs, No Sleep, No distraction, complete focus...

Key Learnings

    - How the face and other objects are recognized with Mesh Detector

    - We started with 3 members but and at last i was alone left Key learning don't be afraid for errors

    - Always create a separate virtual environment (Very Important)

    - Installing few libraries may be challenging
        - Example Mediapipe requires python 10.5+(62 Bit) where as Autopy works on Python 8.0.0 only it was so hard to find out this later had to choose alternate of Autopy 

    - One of the most important thing I realised is to learn and execute always from command prompt (Importance of Linux)

What challenges did you face and how did you overcome them?

So as mentioned earlier I was constantly getting No Module Error inspite of successfully installing 
    steps to check if you face the same 
    - Always create venv

    - Check if the librari supports current python version

    - Few times you may have installed correct version but wrong bit (i.e.. 32 bit instead of 62 bit)

    - Try to find alternate libraries also 


## Installation

```bash
1. virtual environment
        python -m venv myenv

2. Install requirements from text file
        pip install -r requirements.txt
```
    
## Roadmap

- First
    Use mediapipe and try to locate the mesh for your face

- Second
    After locating the coordinates of eye lids try to find out the ratios of the eye as ratio will be consistent 

- Third 
    Once you have located the movement connect it with mouse with the help of pyautogui

- Fourth 
    Create a front end page for user interaction

- Fifth 
    With the help of Flask connect webpage and the backend


