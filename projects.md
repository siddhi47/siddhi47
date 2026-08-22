# Projects

A categorized archive of things I've built. For a shorter, curated list see the [featured projects](./README.md#featured-projects) on my profile page.

## Computer Vision & Edge AI
| Project | Description|
|----------|------------|
|<a href = "https://github.com/siddhi47/dashcam">OAK Dashcam</a>| Multi-camera dashcam system for Raspberry Pi + Luxonis OAK cameras, with a web UI for live viewing, browsing, streaming, and downloading recordings. H.265 encoding, MJPEG preview, and YOLO detection all run on the OAK's Myriad X VPU so the Pi's CPU never touches a frame.|
|<a href = "https://github.com/siddhi47/yolo-ultralytics-clearml">YOLO Ultralytics + ClearML</a>| End-to-end YOLO training pipeline for CVAT-annotated video: annotations/videos exported from CVAT to S3, sampled into a versioned dataset, and trained with every experiment, dataset, and model artifact tracked in ClearML.|
|<a href = "https://github.com/siddhi47/oak-dual-camera-server">OAK Dual Camera Server</a>| Lightweight web server (Rust) for streaming and recording video from two OAK cameras on a Raspberry Pi, with low-latency previews, H.264 recordings, and optional S3 upload. Built for Balena fleets.|
|<a href = 'https://github.com/siddhi47/streamlit-image-classification'>Image Classification (Streamlit UI)</a>| A simple demonstration of end-to-end ML cycle of CNN models using NGROK, Flask API, Streamlit, and Pytorch|
|<a href = 'https://github.com/siddhi47/Jetson-camera-server'>Jetson Camera Server</a>| Lightweight camera server for Jetson devices. This can be used as a base for object detection models.|
|<a href = "https://github.com/siddhi47/oak-yolo">OAK YOLO</a>| Object detection and tracking on a Luxonis OAK camera using a video file source.|
|<a href = "https://www.i8labs.com/">Multi Object Tracker</a>| I worked on this project while working at Leapfrog Technologies. The project is a multi-object tracking system built using a Jetson nano developer kit. The project uses deepsort, yolov3, and opencv. I worked mostly on the core tracking module and interfacing with the hardware|
|<a href = 'https://github.com/siddhi47/reidentification'> Reidentification </a>| Training and evaluation scripts for Reidentification problems in multi-object tracking.|
|<a href = "https://github.com/siddhi47/3d-print-issue-detections">3D Print Issue Detection</a>| Computer vision project for detecting failures/issues during 3D printing from camera footage.|
|<a href = "https://github.com/siddhi47/Cursor-Control-using-Eye-Movement">Cursor control using head and eye movement</a>| This is a project we did for the LITE competition held at Kantipur Engineering College. The project is a cursor control system built using opencv and Python. The project uses a webcam to track the head and eye movement of the user and control the cursor accordingly.|
|<a href = "https://github.com/siddhi47/Nepalese-PAN-extraction">Nepalese Pan Document Extractor</a>|This is a pan document extractor built using opencv and tesseract. The project uses opencv and Tesseract to extract the PAN document from the image and dump the extracted data into the MySQL database. |
|<a href = "https://github.com/siddhi47/medicalimage_converter">Medical Image Converter</a>|A multithreaded approach for conversion of DICOM images |
|<a href = "https://github.com/siddhi47/mat2jpeg">Matlab Image converter</a>| A multithreaded approach for converting Matlab signals to mel spectrogram in jpeg. |

## LLM, NLP & Multimodal
| Project | Description|
|----------|------------|
|<a href = "https://github.com/siddhi47/RAG-chatbot"> RAG Document Q&A System </a> | Retrieval-augmented generation system with embedding-based vector search (ChromaDB) over multi-format documents (PDF, JSON, CSV, web). Tools: LangChain, LangGraph, LangSmith, Flask, Docker, Kubernetes.|
|<a href = "https://github.com/siddhi47/multimodal-emotion">Multimodal Emotion Analysis</a>| Multimodal network (LLMs + visual models) to identify emotion from speech and video streams. Tools: PyTorch Lightning, Python.|
|<a href = "https://github.com/siddhi47/resume_ai">Resume AI / Job Application Helper</a> | Generates answers to job application questionnaires from your resume using an LLM, packaged with docker-compose so it runs locally end-to-end.|
|<a href = "https://github.com/siddhi47/siamese-bert">Paraphrase detection</a>|Paraphrase detection using siamese network and BERT encoder. Paper Link: <a href = 'https://github.com/siddhi47/siamese-bert/blob/main/paraphrase-detection.pdf'> PDF</a>|

## ML Research & Graph Learning
| Project | Description|
|----------|------------|
|<a href = "https://github.com/siddhi47/bluesky-gnn">Bluesky GNN</a>| Graph neural network experiments on the Bluesky follow graph, crawled via the public (unauthenticated) AT Protocol API.|

## Recommendation Systems & Big Data
| Project | Description|
|----------|------------|
|<a href = "https://github.com/siddhi47/pyspark-recommentation">Pyspark Recommendation System</a>| This is a project done as a part of my master's course. The project is a recommendation system built using pyspark. The dataset used is the book recommendation dataset. The project uses cloud storage, MongoDB, pyspark, and hdfs.|
|<a href = "https://github.com/siddhi47/projects_and_researchs/tree/recommender_system">Recommendation Systems</a>| Different approaches towards recommendation systems. Check here for some documentation:<a href = https://github.com/siddhi47/projects_and_researchs/blob/recommender_system/reccomender_system_diff_approaches/Recommender.docx>DOCX</a>|
|<a href = 'https://github.com/siddhi47/airflow-2/tree/develop'>Synthetic data generation</a>|Backend for synthetic data generation of medical data using Airflow[Python]|

## Healthcare & Signal Processing
| Project | Description|
|----------|------------|
|<a href = "https://github.com/siddhi47/ecg-classification">Arrhythmia detection</a>| Detection of arrhythmia in ECG signals using spectral representation and deep learning networks|

## Reinforcement Learning & Quant Finance
| Project | Description|
|----------|------------|
|<a href = "https://github.com/siddhi47/rl-project">Stock and crypto market correlation analysis</a>| Analysis of effects of the crypto market on the stock market using deep reinforcement learning algorithms: PPO, A2C. Paper link: <a href = 'https://github.com/siddhi47/rl-project/blob/main/Reinforcement_Learning.pdf'>PDF</a>|
|<a href = "https://github.com/siddhi47/reinforcement-learning">Reinforcement Learning Toolkit</a>| This is part of a reinforcement learning course at the University of South Dakota. This is a toolkit for reinforcement learning algorithms. It has an implementation of the Markov Decision Process from scratch. Other algorithms will be added soon.|

## MLOps, Infra & Tools
| Project | Description|
|----------|------------|
|<a href = "https://github.com/siddhi47/pydantic-hydra">Pydantic × Hydra</a>| Type-safe, composable ML configs: combines Hydra's composable YAML config (mix & match model/data/training variants from the CLI) with Pydantic's strict validation, including a COCO-style dataset config example.|
|<a href = "https://github.com/siddhi47/CLearml-Hydra">ClearML + Hydra</a>| Pattern for combining ClearML experiment tracking with Hydra configuration management. Companion to <a href="https://siddhibajracharya.hashnode.dev/experiment-tracking-with-clearml-and-hydra?source=more_series_bottom_blogs">this blog post</a>.|
|<a href = "https://github.com/siddhi47/torch-from-yaml-">TorchFromYAML</a>| A class for creating and loading PyTorch models from YAML configuration files, for managing model architectures in a human-readable format.|
|<a href = "https://github.com/siddhi47/airflow_dag_template">Airflow DAG Template</a>| A reusable template for scaffolding new Airflow DAGs.|
|<a href = "https://github.com/siddhi47/tensorflow_serving">Simple tensorflow serving</a>|A template for tensorflow serving |
|<a href = "https://github.com/siddhi47/linear-programming-package">A linear programming solver</a>| Linear programming solver using python wrapper around R|

## Real-World Products
| Project | Description|
|----------|------------|
|<a href = "https://foneloan.com.np/">Foneloan</a>| This is a big project I was a part of when I was working at Extensodata. It is software that analyses the customers' financial transactions and makes a decision for credit approval. By integrating Foneloan with the banking software, the customer can get pre-approved loans up to a certain amount.|
|<a href = "https://bitbucket.org/siddhi47/ethereumvoting/src/master/voting/">Digital voting system using ethereum</a>|This is an ethereum voting system built using solidity and Django. The project was done as a part of an Engineering degree course. The project uses the ethereum blockchain to store the votes and Django to build the front end. |
