# Predictive-Maintenance-with-Hazard-Mapping-NASA-Signals-and-Reliability-Analytics
Condition based predictive maintenance pipeline combining Faster R-CNN detection, shadow and hazard mapping, NASA DONKI signals, MTBF, MTTR, OEE analytics

# What’s inside

- Object detection with Faster R-CNN MobileNetV3 on a COCO-style dataset to localize assets and hazards (Asteroid, Damage, Debris, Explosion, Satellite)

- Shadow detection and per-class mask generation to create pixel-level hazard maps for visualization and downstream scoring

- NASA DONKI integrations to fetch solar flare, CME, and geomagnetic storm events and visualize correlations over time

- Reliability analytics: MTBF, MTTR, and OEE computation from timestamped logs, plus a simple baseline regression for repair-time estimation

# Why it matters

- Blend condition signals from images, environment, and logs to prioritize interventions, reduce downtime, and inform scheduling
  
- This toolkit unifies computer vision, space-weather telemetry, and reliability metrics to build practical maintenance intelligence
