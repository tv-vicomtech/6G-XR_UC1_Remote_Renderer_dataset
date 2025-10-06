
# 6G-XR_UC1_Remote_Renderer_dataset

This repository contains the logs generated during the validation of the **XR Remote Renderer** component within the **6G-XR** project.

---

## Repository Structure

The repository is organized into three main folders, each corresponding to a different experiment:

- `UC1_1.2-webrtc`
- `UC1_1.2-dash`
- `UC1_1.3-webrtc`

Each experiment folder contains 4 subfolders corresponding to the different runs conducted during the experiment:

- `run1`
- `run2`
- `run3`
- `run4`

Inside each `run` folder, there are 6 log files capturing various metrics from the experiment.

---

## Log Contents

### WebRTC Experiments (`UC1_1.2-webrtc` and `UC1_1.3-webrtc`)

Each run contains the following log files:

- Video metrics from the WebRTC session.
- Audio metrics from the WebRTC session.
- CPU usage metrics.
- GPU usage metrics.
- Memory usage metrics.
- A file exported directly from Chrome containing all WebRTC metrics.

### DASH Experiment (`UC1_1.2-dash`)

Each run contains:

- DASH audio metrics.
- DASH video metrics.
- CPU usage metrics.
- GPU usage metrics.
- Memory usage metrics.
- The MPD (Media Presentation Description) file corresponding to the DASH session.

---

## Purpose of the Repository

This repository serves as a storage location for the logs generated during the various experiments performed for validating the XR Remote Renderer component, to facilitate later consultation and analysis.

---

## Additional Notes

- There are currently no specific recommendations for searching or navigating the logs.
- No tools or scripts for automatic analysis are included.

---

## Contact

For any questions or inquiries regarding this repository, please contact the 6G-XR project team.
