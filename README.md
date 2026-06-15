# Technical Project Showcase — Kyunggon Kim

Interactive HTML presentations of two backend projects built at Interpass,
a real-time bus fleet management company serving 1,600 vehicles.

## Projects

### 1. GPS Correction Pipeline (`p1_gps_correct_en.html`)
Real-time telemetry processing system using Redis Streams (Java/Spring Boot).

Key results:
- End-to-end latency: 3 min → under 1 sec
- Redis Stream lag: 10,000+ records → under 10
- Redis network I/O reduced by 200× via pipeline batching
- GC pressure eliminated through zero-allocation object reuse

### 2. Trip Generator Pipeline (`p2_trip_generator_en.html`)
Offline batch analysis pipeline using Python (Pandas, NumPy, ProcessPoolExecutor).

Key results:
- Log generation time reduced by 83% (3 hours → 30 minutes)
- DP-based optimal path selection for stop matching
- BBox scanning + clustering for data reliability

## How to view
Download either `.html` file and open in any browser.
No dependencies or setup required.

---
📧 sorrynthx@gmail.com
🔗 linkedin.com/in/kyunggon-kim
