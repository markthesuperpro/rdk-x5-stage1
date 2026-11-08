# rdk-x5-stage1 — RDK X5 Robotics Project
Robotics Dream Keeper Challenge — Winter 2026

**Robotics Dream Keeper Challenge 2026 Winter**

- **Participant:** Mark
- **Project:** rdk-x5-stage1-demo
- **Current stage:** Stage 1 — Ignite
- **Hardware:** D-Robotics RDK X5
- **Repository status:** Development

---

## Demonstration

The RDK board is sucessfully able to boot up Ubuntu, connect to the computer using remote desktop, and run /app/ Yolo11 demos

### Main Result

![Main demonstration result](evidence/Yolo11_demo.png)

**What this demonstrates:**

- The board is able to request video/0/ from connected usb webcam
- The demo Yolo11 pose model is able to run fluently

## Project Overview

### Approach

Our project approach is to first understand foundational part of our hardware and software. After that, we will experiment with ROS2 and AI models.

### Objectives

- 1.Learn the fundementals
- 2.Try ROS
- 3.Proceed with the project goal.

## Hardware

| Component | Model / Specification | Purpose |
|---|---|---|
| Development board | D-Robotics RDK X5 | Main computing platform |
| Storage | microSD card | System storage and Boot Firmware |
| Camera | Usb Webcam | Video Capture |
| Sensor | LiDar / N/A | Navigation |
| Actuator | Motor - Future goal | Movement |
| Development PC | Laptop | Development and remote access |

### Hardware Setup

![Hardware setup](evidence/[hardware-setup-image].jpg)

**Connection details:**

[Explain how your camera, sensors, actuators and other hardware are connected.]

## Tested Software Environment

Record the actual versions running on your tested hardware.

| Component | Version / Configuration |
|---|---|
| RDK OS | [Version] |
| Ubuntu | [Version] |
| Linux kernel | [Version] |
| CPU architecture | [Architecture] |
| Python | [Version] |
| ROS 2 | [Version / Not used] |
| OpenCV | [Version / Not used] |
| AI framework | [Version] |
| BPU Platform | [Version / Not used] |
| DNN Runtime / HBRT | [Versions / Not used] |
| Other dependencies | [Versions] |

**Environment verification evidence:**

![System information](evidence/[system-information].png)

## Project Architecture

Explain how the hardware and software components communicate.

### Architecture Diagram

```text
[Sensor / Camera]
        |
        v
[Data Acquisition]
        |
        v
[Processing / AI Model]
        |
        v
[RDK X5 BPU / CPU]
        |
        v
[Decision / Output]
        |
        v
[Actuator / Display / Result]
```

Replace the example components with your actual implementation.

### Architecture Explanation

1. **Input:** [Where the data comes from.]
2. **Processing:** [How the data is processed.]
3. **Inference / Logic:** [How your model or algorithm works.]
4. **Output:** [What happens after processing.]
5. **Communication:** [How the components communicate.]

## Repository Structure

```text
your-project/
|
+-- README.md
+-- LICENSE
+-- requirements.txt
|
+-- src/
|   +-- [your-main-script].py
|   +-- [other-source-files]
|
+-- models/
|   +-- [model-files-or-download-instructions]
|
+-- config/
|   +-- [configuration-files]
|
+-- docs/
|   +-- [documentation]
|
+-- evidence/
    +-- [hardware-setup].jpg
    +-- [system-information].png
    +-- [sensor-test].png
    +-- [ai-result].jpg
    +-- [execution-log].log
```

Only include directories that actually exist in your repository.

## Prerequisites and Dependencies

### Hardware Requirements

- [Required RDK X5 hardware]
- [Required sensors and actuators]
- [Other necessary equipment]

### Software Requirements

- [Operating system]
- [Programming language and version]
- [Required frameworks]
- [Required SDKs and runtimes]

### Dependencies

| Dependency | Version | Purpose |
|---|---|---|
| [Package 1] | [Version] | [Purpose] |
| [Package 2] | [Version] | [Purpose] |
| [Package 3] | [Version] | [Purpose] |

## Installation and Setup

### 1. Prepare the RDK X5

[Explain how to flash the system image, boot the board and complete initial configuration.]

**Commands:**

```bash
[Your setup commands]
```

**Evidence:**

![RDK X5 setup](evidence/[setup-evidence].png)

### 2. Connect to the RDK X5

[Explain network configuration and SSH connection from your development computer.]

**Commands:**

```bash
[Your connection and verification commands]
```

**Evidence:**

![SSH connection](evidence/[ssh-evidence].png)

### 3. Install Dependencies

[Explain how to install the necessary packages, SDKs and libraries.]

**Commands:**

```bash
[Your dependency installation commands]
```

### 4. Configure Hardware

[Explain how to connect and configure cameras, sensors, actuators and peripherals.]

**Commands:**

```bash
[Your hardware configuration commands]
```

**Evidence:**

![Hardware configuration](evidence/[hardware-configuration].png)

## Running the Project

### 1. Start the Application

[Explain how to start the main application.]

```bash
[Your execution command]
```

### 2. Run the AI Workload

[Explain how to load the model and execute inference on the RDK X5.]

```bash
[Your AI execution command]
```

### 3. Verify the Output

[Explain what successful execution looks like and how to check the results.]

```bash
[Your verification commands]
```

**Expected output:**

```text
[An actual example of successful output]
```

**Execution evidence:**

![Application output](evidence/[execution-evidence].png)

## AI Model and Processing

### Model Information

| Property | Description |
|---|---|
| Model name | [Model name] |
| Model source | [Official source / URL] |
| Model architecture | [Architecture] |
| Input resolution | [Resolution] |
| Input format | [Format] |
| Runtime | [Runtime] |
| Execution device | [BPU / CPU / Other] |
| Model file | [Filename] |

### AI Processing Pipeline

[Explain how input data becomes a model prediction.]

### Model Output

![AI model output](evidence/[ai-output].jpg)

**Observed result:**

[Describe what the model successfully detected, classified, recognized or generated.]

## Sensors and Actuators

### Sensor Demonstration

**Sensor:** [Sensor name and model]

**Interface:** [USB / MIPI / I2C / SPI / GPIO / Other]

**Purpose:** [What information it provides.]

**Test procedure:**

[Explain how you tested the sensor.]

**Commands:**

```bash
[Your sensor test commands]
```

**Evidence:**

![Sensor demonstration](evidence/[sensor-evidence].png)

### Actuator Demonstration

[Describe your motor, servo, GPIO output or other actuator, if applicable.]

**Evidence:**

![Actuator demonstration](evidence/[actuator-evidence].png)

[Write Not implemented yet if you do not have an actuator demonstration.]

## Results and Verification

Record actual observations from your experiments.

| Test | Configuration | Actual Result | Status |
|---|---|---|---|
| System boot | [Configuration] | [Observed result] | [Status] |
| Network / SSH | [Configuration] | [Observed result] | [Status] |
| Sensor | [Configuration] | [Observed result] | [Status] |
| AI inference | [Configuration] | [Observed result] | [Status] |
| Actuator | [Configuration] | [Observed result] | [Status] |

### Performance Measurements

Only include measurements you have actually taken.

| Metric | Measurement | Test Conditions |
|---|---|---|
| Inference latency | [Value / Not measured] | [Conditions] |
| Inference throughput | [Value / Not measured] | [Conditions] |
| CPU utilization | [Value / Not measured] | [Conditions] |
| BPU utilization | [Value / Not measured] | [Conditions] |
| Memory usage | [Value / Not measured] | [Conditions] |
| Temperature | [Value / Not measured] | [Conditions] |
| Power consumption | [Value / Not measured] | [Conditions] |

**Measurement methodology:**

[Explain how you collected the measurements, the duration, the number of tests and the measurement tools.]

### Additional Evidence

- [Screenshot or log 1](evidence/[file-1])
- [Screenshot or log 2](evidence/[file-2])
- [Demonstration video](YOUR_VIDEO_LINK)
- [Detailed experiment report](YOUR_DOCUMENTATION_LINK)

## Troubleshooting

### [Problem 1]

**Symptoms:**

[What happens?]

**Possible cause:**

[What caused the problem?]

**Solution:**

[How did you resolve it?]

### [Problem 2]

**Symptoms:**

[What happens?]

**Possible cause:**

[What caused the problem?]

**Solution:**

[How did you resolve it?]

## Known Limitations

- [Current limitation 1]
- [Current limitation 2]
- [Current limitation 3]

## Future Development

### Planned Improvements

- [Improvement 1]
- [Improvement 2]
- [Improvement 3]

### Next Challenge Stages

| Stage | Planned development |
|---|---|
| Stage 1 — Ignite | [Initial hardware and AI demonstration] |
| Stage 2 — Build | [Further development and integration] |
| Stage 3 — Launch | [Complete project demonstration and evaluation] |

Update this section as your project develops.

## Reproducibility

**Tested hardware:** [RDK X5 configuration]

**Tested software:** [Operating system and software versions]

**Reproduction procedure:**

1. [Step 1]
2. [Step 2]
3. [Step 3]
4. [Step 4]

**Expected result:** [Describe the result another developer should observe.]

## Attribution

[List external code, examples, pretrained models, datasets, SDKs and other resources used.]

[Preserve original copyright notices and third-party license requirements.]

## License

This project's original materials are licensed under [Your License].

See [LICENSE](LICENSE) for details.

Third-party components remain subject to their respective licenses.

## Challenge Information

**Program:** Robotics Dream Keeper Challenge 2026 Winter

**Organizer:** D-Robotics

**Current stage:** [Stage number and name]

- [Official Challenge Repository](https://github.com/D-Robotics/Robotics-Dream-Keeper-Challenge-Winter)
- [Project Showcase](YOUR_SHOWCASE_PR_URL)
- [Community Update](YOUR_DISCORD_MESSAGE_LINK)
