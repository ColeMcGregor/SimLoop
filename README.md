# SimLoop

SimLoop is a small-scale racing sandbox where cars compete on procedurally generated tracks.
Each vehicle can be controlled by different controllers — a human player, a baseline algorithm, or a machine learning model. The game supports one or two vehicles per race, enabling head-to-head comparisons of algorithms or player versus player matches.

Features

 - Procedural Track Generation
    - Each run generates a new closed-loop track.
    - Track defined by a centerline and width, ensuring consistent physics and AI reference frames.

 - Extensible Controllers
    - PlayerController: keyboard or gamepad input.
    - BaselineController: a simple algorithm such as pure pursuit.
    - MLController: connects to external machine learning models.
    - ReplayController: record and replay laps as ghosts.

- Two-Vehicle Competition

    - Spawn two cars on the same track.
    - Assign any controller type to each car.
    - Compare lap times, racing lines, and interactions directly.
    - Supports player vs. player, player vs. bot, or bot vs. bot.

- Lightweight Physics

    - Kinematic car model with acceleration, braking, and steering.
    - Lateral drift when turning at high speed.
    - Boundary collisions clamp the car inside the track and reduce speed.

 - Lap Timing & Data

    - Checkpoints and lap counters for each vehicle.
    - Individual lap times and summaries stored per race.
    - Direct comparison between controller strategies.


<img width="1905" height="775" alt="image" src="https://github.com/user-attachments/assets/a4c6c303-44f4-453e-99a0-b2e33594f73e" />

<img width="1913" height="666" alt="image" src="https://github.com/user-attachments/assets/a3467b2d-e8e2-4c73-8a07-07b4e7961ee4" />

