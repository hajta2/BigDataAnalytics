# Assignment 3

Requirements:

- spark streaming + kafka
- persistent layer: redis/neo4j
- machine learning: spark mllib
- visual analytics: d3.js

Architecture:

- spotify/fake data generator - producer
- kafka - message broker
- spark streaming - consumer (processing)
- machine learning - spark mllib - consumer2 (recommendation, mood detection)
- redis - persistent layer - consumer3 (storage)
- visual analytics - grafana/d3.js - consumer4 (visualization)
