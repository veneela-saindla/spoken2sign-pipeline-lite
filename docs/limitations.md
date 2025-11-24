# Limitations — spoken2sign-pipeline-lite

This is a lightweight, baseline pipeline implementation with real-world limitations:

1. Small dataset (only 50 samples)
2. Pre-extracted MediaPipe keypoints (quality issues present)
3. No hand or face landmarks included (only 33 pose joints)
4. Rule-based text-to-gloss mapping (not transformer-based)
5. No linguistic validation by a sign language expert
6. Some joints contain noisy Z-values or missing frames
7. Output skeleton motions are approximate and not fully accurate signs

This project focuses on studying pipeline architecture, not producing perfect sign language translations.
