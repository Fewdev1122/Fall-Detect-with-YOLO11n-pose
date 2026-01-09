# Real-time Fall Detection using YOLO11n-pose, Rule-Based Filtering, and Random Forest.

**Tri-Stage Detection:**
1. **Pose Estimation:** Uses **YOLO11n-pose** to extract skeletal keypoints.
2. **Pre-Filtering:** **Rule-based** logic filters out normal activities (standing, sitting).
3. **Classification:** **Random Forest** model analyzes movement velocity and posture to confirm a fall.
