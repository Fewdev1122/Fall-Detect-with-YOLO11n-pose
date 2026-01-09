# Real-time Fall Detection using YOLO11n-pose, Rule-Based Filtering, and Random Forest.

**Tri-Stage Detection:**
  **Pose Estimation:** Uses **YOLO11n-pose** to extract skeletal keypoints.
  **Pre-Filtering:** **Rule-based** logic filters out normal activities (standing, sitting).
  **Classification:** **Random Forest** model analyzes movement velocity and posture to confirm a fall.
