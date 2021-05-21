# R6S Livetracker

*planned Project*

## Description

Livetracker for Rainbow Six Siege Streams on YouTube.

Streamdata will be transmitted via a database to a website to be fetched.

Data will consist of:
 1. Round Standing
 2. Round Number
 3. playing Teams
 4. Banned Operators
 5. Picked Operators
 6. DOA of Operators
 7. Kills / Deaths per Player
 8. Winning Condition

## Technologies
- Backend: Python (currently) or Rust
  - OpenCV
  - TesseracT
- Frontend: tbd (*possible are Go, Vert.X, Actix - depending on mood*)
- Database: InfluxDB (*maybe trying Firebase/Supabase*)
