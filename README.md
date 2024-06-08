

# Gesture Controlled Virtual Mouse &nbsp;[![](https://img.shields.io/badge/python-3.8.5-blue.svg)](https://www.python.org/downloads/) [![platform](https://img.shields.io/badge/platform-windows-green.svg)](https://github.com/xenon-19/Gesture_Controller) 

Gesture Controlled Virtual Mouse makes human computer interaction simple by making use of Hand Gestures and Voice Commands. The computer requires almost no direct contact. All i/o operations can be virtually controlled by using static and dynamic hand gestures along with a voice assistant. This project makes use of the state-of-art Machine Learning and Computer Vision algorithms to recognize hand gestures and voice commands, which works smoothly without any additional hardware requirements. It leverages models such as CNN implemented by [MediaPipe](https://github.com/google/mediapipe) running on top of pybind11. It consists of two modules: One which works direct on hands by making use of MediaPipe Hand detection, and other which makes use of Gloves of any uniform color. Currently it works on Windows platform.

Note: Use Python version: 3.8.5

# Features
 _click on dropdown to know more_ <br>

### Gesture Recognition:
<details>
<summary>Neutral Gesture</summary>
 <figure>
  <img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/gesture/neutral.jpg" alt="Palm" width="711" height="400"><br>
  <figcaption>Neutral Gesture. Used to halt/stop execution of current gesture.</figcaption>
</figure>
</details>

<details>
<summary>Left Click</summary>
<img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/gesture/left%20click.jpg" alt="Left Click" width="711" height="400"><br>
 <figcaption>Gesture for single left click</figcaption>
</details>

<details>
<summary>Right Click</summary>
<img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/gesture/right%20click.jpg?raw=true" alt="Right Click" width="711" height="400"><br>
 <figcaption>Gesture for single right click</figcaption>
</details>

<details>
<summary>Double Click</summary>
<img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/gesture/double%20click.jpg?raw=true" alt="Double Click" width="711" height="400"><br>
 <figcaption>Gesture for double click</figcaption>
</details>

<details>
<summary>Scrolling</summary>
<img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/gesture/Scrolling.jpg?raw=true" alt="Scrolling" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for horizontal and vertical scroll. The speed of scroll is proportional to the distance moved by pinch gesture from start point. Vertical and Horizontal scrolls are controlled by vertical and horizontal pinch movements respectively.</figcaption>
</details>

<details>
<summary>Drag and Drop</summary>
<img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/gesture/Drag%20and%20Drop.jpg?raw=true" alt="Drag and Drop" width="711" height="400"><br>
 <figcaption>Gesture for drag and drop functionality. Can be used to move/tranfer files from one directory to other.</figcaption>
</details>

<details>
<summary>Multiple Item Selection</summary>
<img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/gesture/Multiple%20Item%20Selection.jpg?raw=true" width="711" height="400"><br>
 <figcaption>Gesture to select multiple items</figcaption>
</details>

<details>
<summary>Volume Control</summary>
<img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/gesture/.%20Volume%20Control.jpg?raw=true" alt="Volume Control" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for Volume control. The rate of increase/decrease of volume is proportional to the distance moved by pinch gesture from start point. </figcaption>
</details>

<details>
<summary>Brightness Control</summary>
<img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/gesture/Brightness%20Control.jpg?raw=true" alt="Brightness Control" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for Brightness control. The rate of increase/decrease of brightness is proportional to the distance moved by pinch gesture from start point. </figcaption>
</details>

<details>
<summary>Screenshot</summary>
<img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/gesture/Screenshot.jpg?raw=true" alt="Screenshot" width="711" height="400"><br>
 <figcaption>Gestures for screenshot left index. </figcaption>
</details>

<details>
<summary>Switch tabs</summary>
<img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/gesture/Switch%20Tabs.jpg?raw=true" width="711" height="400"><br>
 <figcaption>Gestures for Switching tabs V Gest. </figcaption>
</details>

<details>
<summary>Zooming</summary>
<img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/gesture/Zooming%20Feature.jpg?raw=true" alt="Zooming" width="711" height="400"><br>
 <figcaption>Gesture for Zooming. </figcaption>
</details>


### Voice Assistant ( ***ION*** ):
<details>
<summary>Launch / Stop  Gesture Recognition</summary>
<img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/launch%20or%20stop.jpg?raw=true" alt="launch stop gesture recognition" width="800" height="auto">
<ul>
  <li>
    <code> ion Launch Gesture Recognition </code><br>
    Turns on webcam for hand gesture recognition.
  </li>
  <li>
    <code> ion Stop Gesture Recognition </code><br>
    Turns off webcam and stops gesture recognition.
    (Termination of Gesture controller can also be done via pressing <code>Enter</code> key in webcam window)
   </li>
</ul>
</details>

<details>
<summary>Google Search</summary>
<img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/Google%20Search.jpg?raw=true" width="800" height="auto">
<ul>
  <li>
    <code>ion search {text_you_wish_to_search}</code><br>
    Opens a new tab on Chrome Browser if it is running, else opens a new window. Searches the given text on Google.
  </li>
</ul>
</details>

<details>
<summary>Find a Location on Google Maps</summary>
 <img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/Location.jpg?raw=true" alt="ion find location" width="800" height="auto">
  <ol>
    <li> 
      <code>ion Find a Location</code><br>
      Will ask the user for the location to be searched.
    </li>
    <li> 
      <code>{Location_you_wish_to_find}</code><br>
      Will find the required location on Google Maps in a new Chrome tab.
    </li>
  </ol>
</details>

<details>
<summary>File Navigation</summary>
<img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/File%20Navigation.jpg?raw=true" alt="ion list files" width="800" height="auto">&emsp;
  <ul>
    <li>
      <code>ion list files</code> / <code> ion list </code><br>
      Will list the files and respective file_numbers in your Current Directory (by default C:)
    </li>
    <li>  
      <code> ion open {file_number} </code><br>
      Opens the file / directory corresponding to specified file_number.
    </li>
    <li>
      <code>ion go back </code> / <code> ion back </code><br>
      Changes the Current Directory to Parent Directory and lists the files.
    </li>
  </ul>
</details>

<details>
<summary>Current Date and Time</summary>
<img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/date%20and%20time.jpg?raw=true" alt="ion date / time" width="800" height="auto">
  <ul>
    <li>
      <code> ion what is today's date </code> / <code> ion date </code><br>
      <code> ion what is the time </code> / <code> ion time </code><br>
      Returns the current date and time.
    </li>
  </ul>
</details>

<details>
<summary>Copy and Paste</summary>
 <img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/copy%20paste%20.jpg?raw=true" alt="ion copy" width="800" height="auto">

  <ul>
    <li>
      <code> ion Copy </code><br>
      Copies the selected text to clipboard.<br>
    </li>
    <li>
      <code> ion Paste </code><br>
      Pastes the copied text.
    </li>
  </ul>
</details>

<details>
<summary>Sleep / Wake up ion</summary>
  <img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/sleep%20wakeup.jpg?raw=true" alt="ion sleep / wake up" width="800" height="auto">
  <ul>
    <li>
      Sleep<br>
      <code> ion bye </code><br>
      Pauses voice command execution till the assistant is woken up.
    </li>
    <li>
      Wake up<br>
      <code> ion wake up </code><br>
      Resumes voice command execution.
    </li>
  </ul>
</details>

<details>
<summary>Exit</summary>
   <img src="https://github.com/ab0rahman/gesture-controlled-virtual-mouse/blob/main/media/exit.jpg?raw=true" alt="ion exit" width="800" height="auto">
  <ul>
    <li>
      <code> ion Exit </code> <br>
      Terminates the voice assisstant thread. GUI window needs to be closed manually.
    </li>
  </ul>
</details>

# Getting Started

  ### Pre-requisites
  
  Python: (3.6 - 3.8.5)<br>
  Anaconda Distribution: To download click [here](https://www.anaconda.com/products/individual).
  
  ### Procedure
  ```bash
  git clone https://github.com/ab0rahman/gesture-controlled-virtual-mouse
  ```
  For detailed information about cloning visit [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository).
  
  Step 1: 
  ```bash
  conda create --name gest python=3.8.5
  ```
  
  Step 2:
  ```bash
  conda activate gest
  ```
  
  Step 3:
  ```bash
  pip install -r requirements.txt
  ```
  
  Step 4:
  ```bash 
  conda install PyAudio
  ```
  ```bash 
  conda install pywin32
  ```
  
  Step 5:
  ``` 
  cd to the GitHub Repo till src folder
  ```
  Command may look like: `cd C:\Users\.....\gesture-controlled-virtual-mouse\src`
  
  Step 6:
  
  For running Voice Assistant:
  ```bash 
  python ion.py
  ```
  ( You can enable Gesture Recognition by using the command "ion Launch Gesture Recognition" )
  
  Or to run only Gesture Recognition without the voice assisstant:
  
  Uncomment last 2 lines of Code in the file `Gesture_Controller.py`
  ```bash 
  python Gesture_Controller.py
  ```
  

  
# Collaborators
  | Abdur Rahman | [Github](https://github.com/ab0rahman) | [Email](mailto:letsmail.him@gmail.com) | 
  
  | Kondapalli Likhitha | [GitHub](https://github.com/Likhitha36912) | [Email](mailto:kondapallilikhitha.20.it@anits.edu.in) | 
  
  | Muralasetti Nanditha | [Github]() | [Email](mailto:nandhithamuralasetti@gmail.com) | 
  
