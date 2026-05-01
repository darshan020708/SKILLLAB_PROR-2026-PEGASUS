# SKILL LAB PRATICAL HACKATHON

## Final Project README

> **Project Weight:** 100%  
> **Team Size:** 4/3 students  
> **Project Duration:** 16 hours  
> **Total Time Available:** 32 effort-hours per team  
> **Project Type:** Playful, interactive, technology-based experience

---

# Before you begin

## Fork and rename this repository

After forking this repository, rename it using the format:

`SKILLLAB_PROR-2026-TeamName`

### Example

`SKILLLAB_PROR-2026-AuroWizards`

Do not keep the default repository name.

---

# How to use this README

This file is your team’s **working project document**.

You must keep updating it throughout the build period.  
By the final review, this README should clearly show:

- your idea,
- your planning,
- your design decisions,
- your technical process,
- your build progress,
- your testing,
- your failures and changes,
- your final outcome.

## Rules

- Fill every section.
- Do not delete headings.
- If something does not apply, write `Not applicable` and explain why.
- Add images, screenshots, sketches, links, and videos wherever useful.
- Update task status and weekly logs regularly.
- Use this file as evidence of process, not only as a final report.

---

# 1. Team Identity

## 1.1 Group Name - Pegasus



## 1.2 Team Members

| Name                  | Primary Role                     | Secondary Role     | Strengths Brought to the Project                     |
|-----------------------|----------------------------------|--------------------|------------------------------------------------------|
| Bhakti Milind Kasare  | Electronics / Coding             | Documentation      | Documentation, Communication, Repo Management        |
| Darshan Dubey         | Hardware Setup / UI Design       | Assigning Roles    | Hardware Handling, UI Design                         |
| Jyotiraditya Bhosale  | Systems Integration / OpenCV     | Hardware Setup     | Camera Integration, Network Streaming, Debugging     |
| Sneha Tiwari          | Creative Lead / Documentation    | Ideation           | Version Control, GitHub Management, Concept Design   |

## 1.3 Project Title

Project Title: Ping Pong Game

 Camera Controlled Ping Pong Game

<img width="1600" height="1131" alt="image" src="https://github.com/user-attachments/assets/c64bfbd4-b3b7-43d9-83ad-c203a5aa11bc" />

## 1.4 One-Line Pitch

A computer vision-based Ping Pong game where the paddle is controlled by tracking a real-world object using a camera.

## 1.5 Expanded Project Idea

In 1–2 paragraphs, explain:

- what your project is,
- what kind of experience it creates,
- what technologies are involved.

**Response:**  
- Our project is an interactive Ping Pong game that replaces traditional controls with computer vision. Instead of using a keyboard or mouse, the player controls the paddle by moving a physical blue object (such as a phone or colored marker) in front of a camera.
The system uses a camera module to continuously capture frames and detect the position of the object in real time. This position is then mapped to the movement of the paddle (white block) on the screen.
The game is developed using Python with OpenCV for object tracking and Pygame for rendering the game environment. This creates a more natural and engaging interaction, blending physical motion with digital gameplay.

---

# 2. Inspiration

## 2.1 References

List what inspired the project.

| Source Type | Title / Link                                                      | What Inspired You |
|video        | https://www.instagram.com/reel/DW4CT7WCDry/?igsh=cXg3dzAxYmdncDBo |                   |
|project      | Computer Vision Games (OpenCV examples)                           |                   |
|game         | Classic Ping Pong Game                                            |                   |


## 2.2 Original Twist

What makes your project original?

**Response:**  
The uniqueness of our project lies in replacing conventional input devices with vision-based interaction.

Key innovations:
- Paddle controlled using real-world object movement
- No physical controller required
- Real-time camera tracking integration
- Natural hand-eye coordination gameplay

---

# 3. Project Intent

## 3.1 User Journey 

Describe exactly how a user will use the project.Make it a story

**Response:**  

The user starts the game on the computer screen. A camera is positioned in front of the player.
The system detects a predefined object (such as a phone or colored marker). As the user moves the object left or right, the camera tracks its position in real time.
This movement is instantly reflected on the screen, where the white paddle follows the object’s motion.
The ball begins moving, and the user must physically move the object to hit the ball and keep it in play.
The experience feels intuitive, as the player directly controls the game using real-world movement instead of buttons.
                                        
---

# 4. Definition of Success

## 4.1 Definition of “Usable”

What is the smallest version of this project that still delivers the core experience?

**Response:**  

A usable system is one where:
- Object tracking is accurate
- Paddle movement is smooth
- Game runs without lag
- User can easily understand how to play

## 4.2 Minimum Usable Version

- Camera detects object
- Paddle moves with object
- Ball collision works

  ## 4.3 Stretch Features

What features are nice to have but not essential?

- Support for tracking multiple colors or objects instead of only blue  
- Improved tracking accuracy and stability in different lighting conditions  
- Multiplayer mode (two paddles controlled by different objects)  
- Score display and game levels (difficulty increase over time)  
- Sound effects for collisions and scoring  
- Better UI design with animations and visual effects  
---

# 5. System Overview

## 5.1 Project Type

Check all that apply.

- [ ] Electronics-based

- [ ] Mechanical

- [ ] Sensor-based

- [ ] App-connected

- [ ] Motorized

- [ ] Sound-based

- [ ] Light-based

- [✅] Screen/UI-based

- [ ] Fabricated structure

- [✅] Game logic based

- [ ] Installation

- [ ] Other:

## 5.2 High-Level System Description

Explain how the system works in simple terms.

Include:

- input,
- processing,
- output,
- physical structure,
- app interaction if any.

**Response:**  
Input:
Camera captures real-time video.

Processing:
OpenCV detects the object and calculates its position.

Decision:
The object’s X-position is mapped to paddle movement.

Output:
The paddle moves on the screen using Pygame.

Flow:
Camera → OpenCV → Position Mapping → Game Logic → Display


## 5.3 Input / Output Map

| System Part   | Type            | What It Does               |
| Camera Module | Input           | Captures real-time video   |
| OpenCV	       |Process	Detects  | Detects object position    |
| Game Logic	   |Decision	Converts| Position to paddle movement|
| Pygame Display|	Output	         | Displays game              |


---

# 6. System Design, Sketches and Visual Planning 

## 6.1 Concept Architecture/sketch/schematic

The system uses a camera to capture movement of a real-world object. OpenCV processes the video feed and detects the object's position. This position is mapped to the paddle movement in the game, creating a real-time interactive system.

**Insert image below:**  
<img width="2560" height="1102" alt="image" src="https://github.com/user-attachments/assets/5238175c-80cc-4382-a591-76d1ea13cd39" />


## 6.2 Labeled Build Sketch/architecture/flow diagram/algorithm

Add a sketch with labels showing:

- structure,
- electronics placement,
- user touch points,
- moving parts,
- output elements.

**Insert image below:**  

<img width="1600" height="1371" alt="image" src="https://github.com/user-attachments/assets/e821749a-87d6-4e65-86d7-4dfb19671aef" />

## 6.3 Approximate Dimensions

| Dimension        | Value   |
| ---------------- | ------- |
| Length           | `16 cm` |
| Width            | `16 cm` |
| Height           | `8 cm`  |
| Estimated weight | `400 g` |

---

# 7. Electronics Planning

## 7.1 Electronics Used

| Component                | Quantity | Purpose                                      |
|--------------------------|----------|----------------------------------------------|
| Raspberry Pi 4B          | 1        | Handles system setup / video handling        |
| Laptop                   | 1        | Runs OpenCV processing and Pygame            |
| Smartphone (IP Camera)   | 1        | Provides live video feed                     |
| Camera App (IP Webcam)   | 1        | Streams video over network                   |

## 7.2 Wiring Plan

Describe the main electrical connections.

**sample Response:**  
`No complex wiring is required.
- The system uses a smartphone camera connected via an IP camera application. The video stream is transmitted over the same network and accessed on the laptop using VLC media player.
- The Raspberry Pi is used as part of the system setup, but there are no motor drivers or physical wiring connections involved.`

## 7.3 Circuit Diagram/architecture diagram

Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
Not applicable.
This project does not involve a traditional electronic circuit.  
The system follows a software-based architecture:
Phone Camera (IP Camera) → VLC Media Player → OpenCV Processing → Pygame (Game Output)

# 7.4. Power Plan

| Question         | Response                                                                 |
|------------------|--------------------------------------------------------------------------|
| Power source     | Laptop power supply + smartphone battery                                |
| Voltage required | Standard operating voltage of devices                                   |
| Current concerns | Not significant (low-power system)                                      |
| Safety concerns  | Ensure stable power supply and avoid overheating of devices             |

---

# 8. Software Planning/

## 8.1 Software Tools

| Tool / Platform                | Purpose                                        |
| ------------------------------ | ---------------------------------------------- |
| `Raspbery Pi OS`               | `Software and game integration`                |
| `[Python/PyGame/OpenCV]`       | `Track markers, game logic, create projection` |
| `Thonny`                       | `Prototyping structure`                        |                 
 
## 8.2 Software Logic/Algorithm

Describe what the code must do.

Include:

- startup behavior,
- input handling,
- sensor reading,
- decision logic,
- output behavior,
- communication logic,
- reset behavior.

**Response:**  
1. Start the system and initialize the camera feed (via IP camera and VLC).
2. Open the game window using Pygame.
3. Continuously capture frames from the video stream.
4. Preprocess each frame (resize, convert to HSV color space).
5. Detect the blue-colored object using color thresholding.
6. Extract the object's centroid (X-coordinate).
7. Map the X-coordinate to the paddle position on the screen.
8. Update the paddle position accordingly.
9. Move the ball automatically based on game logic.
10. Check for collisions with paddle and walls.
11. Update the display using Pygame.
12. Repeat the loop until the game ends.

- **Sample Startup behavior:**  
  - Initialize video stream from phone (IP camera via VLC).
  - Load game window and set initial paddle and ball positions.
- **Input handling:**  
  - Input is taken from the camera feed.
  - Movement of the blue object is used to control paddle position.
- **Sensor reading:**  
  - Frames are continuously captured from the IP camera stream.
  - OpenCV processes each frame to detect the blue-colored object.
- **Decision logic:**  
 - The object's X-coordinate is mapped to paddle movement.
 - Boundary conditions are applied to keep paddle within screen limits.
 - Collision logic determines ball direction changes.
- **Output behavior:**  
 - Paddle position is updated in real time.
 - Ball movement and collisions are displayed on screen.
 - Game visuals are rendered using Pygame.
- **Communication logic:**  
 - The system runs locally.
 - Video is streamed from the phone to the laptop via IP camera and accessed using VLC.
 - No additional device-to-device communication is used.
- **Reset behavior:**  
 - The game resets when the player misses the ball.
 - Paddle and ball return to initial positions.
 - The system continues running until manually exited.

## 8.3 Code Flowchart

Insert a flowchart showing your code logic.

Suggested sequence:

- start,
- initialize,
- wait for input,
- read input,
- decision,
- trigger output,
- repeat or reset,
- error handling.

**Insert image below:**  
<img width="1149" height="1369" alt="image" src="https://github.com/user-attachments/assets/e9e2b1b4-7c98-462e-a7b6-aef62ad2f14e" />





# 9. Bill of Materials (Not applicable)

## 9.1 Full BOM

| Item                           | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec              | Why This Choice?                    |
|------------------------------- |---------:|-------- |--------------|----------------|------------------------------|-------------------------------------|
| Raspberry Pi 4B                | 1        | Yes     | No           | 0              | 4GB RAM                      | For handling camera/system setup    |
| Laptop                         | 1        | Yes     | No           | 0              | Standard                     | Runs OpenCV + Pygame                |
| Smartphone (IP Camera)         | 1        | Yes     | No           | 0              | Android/iOS                  | Provides live video feed            |
| Camera App (IP Webcam)         | 1        | Yes     | No           | 0              | Mobile App                   | Streams video over network          |
| VLC Media Player               | 1        | Yes     | No           | 0              | Software                     | Receives video stream               |
| Blue Object (pouch/any object) | 1        | Yes     | No           | 0              | Colored object               | Used for tracking                   |

## 9.2 Material Justification

Explain why you selected your main materials and components.

**Response:**  
- `The Raspberry Pi and laptop were used to handle video processing and game execution. A smartphone was used as an IP camera to provide a flexible and wireless video input.
- OpenCV was chosen for object detection due to its efficiency in real-time image processing, while Pygame was used for game development because of its simplicity and ease of integration.
- A blue-colored object was selected for tracking because it provides clear color segmentation and improves detection accuracy.`


## 9.3 Items You chose

| Item                       | Why Needed                     | Purchase Link | Latest Safe Date | Status     |
|----------------------------|--------------------------------|---------------|------------------|------------|
| Smartphone (IP Camera)     | Capture video feed             | —             | Already available| Used       |
| Raspberry Pi 4B            | System setup                   | —             | Already available| Used       |
| Laptop                     | Run game and processing        | —             | Already available| Used       |

## 9.4 Budget Summary

| Budget Item           | Estimated Cost |
|-----------------------|---------------:|
| Electronics           | 0              |
| Software              | 0              |
| Additional Materials  | 0              |
| Contingency           | 0              |
| **Total**             | 0              |

## 9.5 Budget Reflection

If your cost is too high, what can be simplified, removed, substituted, or shared?

**Response:**  

Since all components used were already available, the project did not incur additional cost. The system was designed to be low-cost and easily replicable using commonly available devices.

---

# 10. Planning the Work

## 10.1 Team Working Agreement

Write how your team will work together.

Include:

- how tasks are divided,
- how decisions are made,
- how progress will be checked,
- what happens if a task is delayed,
- how documentation will be maintained.

**Response:**  
- The team worked by dividing tasks based on individual strengths. Coding and system integration were handled by members comfortable with programming, while others focused on testing, setup, and documentation.
- Decisions were made collaboratively after quick discussions, ensuring that everyone agreed on the approach before implementation.
- Progress was checked regularly by testing the system after each major change, especially for object tracking and gameplay functionality.
- If a task was delayed, other team members supported to complete it faster and avoid bottlenecks.
- Documentation was maintained alongside development, with updates added after completing each major section of the project.

## 10.2 Task Breakdown

| Task ID | Task                          | Owner                | Estimated Hours | Deadline    | Dependency | Status |
|-------- |-------------------------------|----------------------|----------------|--------------|------------|--------|
| T1      | Finalize concept              | All                  | 1              | 30th April   | None       | Done   |
| T2      | Setup IP camera (phone + VLC) | Jyotiraditya         | 1              | 30th April   | T1         | Done   |
| T3      | Implement object tracking     | Jyotiraditya         | 2              | 30th April   | T2         | Done   |
| T4      | Develop game (Pygame)         | Darshan              | 1              | 30th April   | T1         | Done   |
| T5      | Integrate tracking + game     | Bhakti               | 2              | 30th April   | T3, T4     | Done   |
| T6      | Testing & debugging           | All                  | 2              | 30th April   | T5         | Done   |
| T7      | Documentation                 | Sneha                | 2              | 30th April   | All        | Done   |


## 10.3 Responsibility Split

| Area                 | Main Owner             | Support Owner        |
|----------------------|------------------------|----------------------|
| Concept              | Mrugendra              | All                  |
| Electronics/Setup    | Jyotiraditya           | Darshan              |
| Coding (OpenCV)      | Jyotiraditya           | Bhakti               |
| Coding/UI (Pygame)   | Darshan                | Jyotiraditya         |
| Testing              | All                    | —                    |
| Documentation        | Sneha                  | Bhakti               |

---

# 11 hour Milestones

## 11.1 8-hour Plan(tentetively you may set)

### Bi Hour 1 — Plan and De-risk

Expected outcomes:

- [x] Idea finalized
- [x] Core interaction decided
- [x] Sketches made
- [x] BOM completed
- [x] Purchase needs identified
- [ ] Key uncertainty identified
- [x] Basic feasibility tested

### Bi Hour 2 — Build Subsystems

Expected outcomes:

- [x] Electronics tests completed
- [ ] CAD / structure planning completed
- [ ] App UI started if needed
- [x] Mechanical concept tested
- [x] Main subsystems partially working

### Bi Hour 3 — Integrate

Expected outcomes:

- [x] Physical body built
- [x] Electronics integrated
- [x] Code connected to hardware
- [ ] App connected if required
- [x] First playable version exists

### Bi Hour 4 — Refine and Finish

Expected outcomes:

- [x] Technical bugs reduced
- [x] Playtesting completed
- [x] Improvements made
- [x] Documentation completed
- [x] Final build ready

## 12.2  Update Log

| Days   | Planned Goal   | What Actually Happened | What Changed   | Next Steps     |
| ------ | -------------- | ---------------------- | -------------- | -------------- |
| Day 1 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |
| Day 2 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |
| Day 3 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |
| Day 4 | `[Write here]` | `[Write here]`         | `[Write here]` | `[Write here]` |

---

# 13. Risks and Unknowns

## 13.1 Risk Register

| Risk                                                            | Type         | Likelihood | Impact   | Mitigation Plan                                                                       | Owner                |
| --------------------------------------------------------------- | ------------ | ---------- | -------- | ------------------------------------------------------------------------------------- | -------------------- |
| WiFi connection between laptop and Phone IP camera becomes unstable       | `Technical`  | `Medium`   | `High`   | Keep phone IP camera close, ensure stable power supply, reduce network load, add fail-safe stop | `[Mrugrendra]`           |


## 13.2 Biggest Unknown Right Now

What is the single biggest uncertainty in your project at this stage?

**Response:**  

Latency Jitter 
Since data is sent via HTTP over Wi-Fi from a smartphone to the Raspberry Pi 4B, the biggest unknown is the consistency of arrival times.

Wi-Fi is prone to interference and congestion.

Even if processing is fast, a "hiccup" in the network can cause a frame drop, breaking the 60 FPS experience.



---

# 14. Testing 

## 14.1 Technical Testing Plan

| What Needs Testing       | How You Will Test It                                     | Success Condition                          |
|--------------------------|----------------------------------------------------------|--------------------------------------------|
| IP Camera Video Feed     | Connect phone camera via IP and open in VLC              | Continuous smooth video stream             |
| Object Tracking          | Move blue object in front of camera                      | Object detected consistently               |
| Paddle Mapping           | Compare object movement with paddle                      | Paddle follows object smoothly             |
| Game Responsiveness      | Play continuously                                        | No noticeable lag                          |
| Collision Detection      | Hit ball with paddle                                     | Ball responds correctly                    |
| Raspberry Pi Processing  | Run tracking via Pi + laptop integration                 | Stable performance without crashes         |
| Lighting Conditions      | Test in bright and dim environments                      | Detection remains usable                   |

## 14.2 Testing and Debugging Log

| Date       | Problem Found                              | Type       | What You Tried                                | Result               | Next Action                |
|------------|-------------------------------------------- |-----------|-----------------------------------------------|----------------------|----------------------------|
| 30th April | IP camera lag / delay                       | Technical | Adjusted network and reduced resolution       | Improved             | Optimize further            |
| 30th April | Blue object not detected properly           | Technical | Tuned HSV color range in OpenCV               | Fixed                | Fine-tune for lighting      |
| 30th April | Paddle movement jitter                      | Technical | Applied smoothing/filtering                   | Reduced jitter       | Improve stability           |
| 30th April | Tracking failed in low light                | Technical | Changed lighting / background                 | Partially solved     | Improve robustness          |


## 14.3 Playtesting Notes
 
| Tester                      | What They Did                    | What Confused Them          | What They Enjoyed              | What You Will Change                 |
|-----------------------------|----------------------------------|-----------------------------|--------------------------------|--------------------------------------|
| Team Member (Jyotiraditya)  | Played using object control      | Initial object positioning  | Real-time interaction          | Add simple instructions              |
| Friend                      | Played full game                 | Slight delay in movement    | Unique control method          | Improve smoothness                   |


---

# 15. Build Documentation

## 15.1 Fabrication Process(if any)

Describe how the project was physically made.

Include:

- cutting,
- 3D printing,
- assembly,
- fastening,
- wiring,
- finishing,
- revisions.

**Response:**  
`Not applicable.
This project is primarily software-based and does not involve physical fabrication such as cutting, 3D printing, or assembly.
The system was developed using a combination of a Raspberry Pi 4B and a laptop. The Raspberry Pi was used for handling the camera input, while the laptop was used to run the game and processing.
A phone camera was connected using an IP camera application, and the video feed was accessed on the laptop using VLC media player. OpenCV was used to process the video stream and detect the blue-colored object, while Pygame handled the game logic and rendering.
Minor setup involved properly positioning the phone camera to ensure clear object detection. Multiple adjustments were made to improve tracking accuracy and gameplay responsiveness.
Revisions mainly focused on stabilizing object detection, reducing jitter, and refining the mapping between object movement and paddle control.`

## 16 Build Photos

Add photos throughout the project.

Suggested images:

- early sketch,
- prototype,
- electronics testing,
- mechanism test,
- app screenshot,
- final build.
-<img width="1280" height="960" alt="image" src="https://github.com/user-attachments/assets/26a247d4-b15a-4dce-bff8-3851608fa0e0" />





# 17. Final Outcome

## 17.1 Final Description

Describe the final version of your project.

**Response:**  
- The final system is a camera-controlled Ping Pong game where a real-world object is used to control the paddle.
- The camera captures the movement of the blue color object, and OpenCV processes the video feed to detect its position in real time. This position is mapped to the paddle (white block) on the screen.
- The game is developed using Pygame and includes ball movement, collision detection, and basic scoring. The user interacts with the game by physically moving the object, creating a real-time connection between physical motion and digital gameplay.

## 17.2 What Works Well

- Reliable tracking of blue-colored object  
- Smooth mapping of object movement to paddle  
- Real-time responsiveness  
- Accurate collision detection  
- Simple and intuitive gameplay  

## 17.3 What Still Needs Improvement

- Currently limited to blue-colored objects only  
- Performance depends on lighting conditions  
- Minor jitter in paddle movement  
- UI and visual improvements can be added  

## 17.4 What Changed From the Original Plan

How did the project change from the initial idea?

**Response:**  

- Initially, the project idea involved hardware-based interaction and to control the paddle by hand gesture using the web camera.
- During development, we faced challenges with stable object tracking, which led us to temporarily shift to using a phone as a joystick to control the paddle. This approach helped us continue development while troubleshooting the tracking issues.
- After resolving the detection problems, we reverted back to our original idea of using object-based control through computer vision.
- The system uses a phone camera connected via IP streaming (VLC) along with Raspberry Pi and laptop for processing and gameplay.
-This iterative change improved our understanding of the system and helped us build a more stable and effective final solution.

---

# 18. Reflection

## 18.1 Team Reflection

What did your team do well?  
What slowed you down?  
How well did you manage time, tasks, and responsibilities?

**Response:**  
- The team worked collaboratively by dividing tasks into coding, testing, and documentation.
-During development, we faced a major challenge where we had to change our main idea. Initially, we planned to hand gesture as the paddle using the camera. Then we planned to work on object detecting as a paddle . Due to technical difficulties, we temporarily shifted to using a phone as a joystick to control the paddle. After resolving the tracking issues, we successfully reverted back to our original idea of object-based control.
This process slowed us down slightly, but it also helped us better understand the system and improve our implementation. Overall, we managed our time well by focusing on completing the core functionality first and supporting each other when required.
- We managed time effectively and adapted to changes in the project plan. Simplifying the idea helped us focus on building a working system within the given time.

## 18.2 Technical Reflection

What did you learn about:

- electronics,
- coding,
- mechanisms,
- fabrication,
- integration?

**Response:**  

- We learned how to stream video from a phone using IP camera and VLC, process it using OpenCV, and integrate it with game logic using Pygame.
- Worked with Raspberry Pi and understood how to handle real-time video input and system integration.
- To use OpenCV for object detection and tracking, and how to process real-time video input.
- Game development using Pygame, including handling movement, collision detection, and rendering.
- Additionally, we understood how to map real-world input to digital control systems.

## 18.3 Design Reflection

What did you learn about:

- designing ,
- delight,
- clarity,
- physical interaction,
- understanding,
- iteration?

**Response:**  
- We learned the importance of simple and intuitive interaction design.
- Using physical movement instead of traditional controls made the system more engaging.
- We also understood how iteration improves usability and overall user experience.

## 18.4 If You Had One More hour

What would you improve next?

**Response:**  

`We would improve tracking accuracy, reduce jitter, and add better visuals and sound effects to enhance the gameplay experience. `

---

# 19. Final Submission Checklist

Before submission, confirm that:

- [✅] Team details are complete
- [✅] Project description is complete
- [✅] Inspiration sources are included
- [✅] Sketches are added
- [✅] BOM is complete
- [✅] Purchase list is complete
- [✅] Budget summary is complete
- [✅] Code flowchart is added
- [✅] Task breakdown is complete
- [✅] Risk register is complete
- [✅] Testing log is updated
- [✅] Playtesting notes are included
- [✅] Build photos are included
- [✅] Final reflection is written


---


---


