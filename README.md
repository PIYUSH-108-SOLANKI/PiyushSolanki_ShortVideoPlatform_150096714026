# QuickClips — Short Video Platform

## Project Overview
QuickClips is a high-performance, scalable short-form video sharing platform designed to mimic the core architecture of TikTok. The system addresses critical challenges such as video buffering, latency, and real-time personalized recommendations. It is built using a microservices architecture, asynchronous video processing (FFmpeg + Kafka), global content delivery (AWS CloudFront), and a hybrid database strategy (PostgreSQL + Redis + Cassandra) to handle millions of concurrent users.

The core feature is the **Three-Signal Hybrid Recommendation Engine**, which scores videos based on watch completion rates, social graph signals, and viral velocity to generate an endless, highly personalized feed.

## Setup Instructions
To run the simulation and view the system design artifacts:

1. Clone the repository:
   ```bash
   git clone https://github.com/PIYUSH-108-SOLANKI/PiyushSolanki_ShortVideoPlatform_150096714026.git
   cd PiyushSolanki_ShortVideoPlatform_150096714026
   ```
2. Ensure you have Python 3.8+ installed on your system.
3. Install the required dependencies:
   ```bash
   pip install jupyter matplotlib
   ```

## Dependencies
- `Python 3.8+`
- `Jupyter Notebook` (for viewing the .ipynb file)
- `matplotlib` (for rendering the architectural and sequence diagrams)

## Execution Steps

### Jupyter Notebook (Primary Submission)
The complete academic report, architecture diagrams, and pipeline simulations are consolidated in the final notebook.
1. Open the notebook interface:
   ```bash
   jupyter notebook PiyushSolanki_ShortVideoPlatform_150096714026.ipynb
   ```
2. Run all cells sequentially from top to bottom.
3. Observe the output of the **Live Demo: Video Upload Flow** and the **Personalized Feed Generation** directly inside the notebook.

## Additional Project Details
- **Architecture:** Layered Microservices (API Gateway, Auth, Video, Social, Interaction, Encoding, Analytics).
- **Data Layer:** PostgreSQL (Metadata), Redis (Caching/Counters), Cassandra (Event Logging), AWS S3 (Blob Storage).
- **Video Delivery:** HLS Adaptive Bitrate Streaming via AWS CloudFront CDN.
- **Message Broker:** Apache Kafka / RabbitMQ for decoupled upload and encoding workflows.

---
*Piyush Solanki (Roll No. 150096724026) — Cohort: Mark Zuckerberg*
