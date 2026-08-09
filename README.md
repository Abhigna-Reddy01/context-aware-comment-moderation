# Context-Aware Comment Moderation System

An AI-based web application for detecting and classifying toxic comments using context-aware NLP and machine learning techniques.

## 📌 Overview

Online platforms receive large volumes of user-generated comments, making automated moderation important for maintaining safe and healthy digital communities.

This project implements a context-aware comment moderation system that analyzes user comments and classifies them based on their toxicity. It combines machine learning models with NLP-based feature extraction to improve automated toxicity detection.

## ✨ Features

- Toxic comment detection
- Context-aware NLP analysis
- Multiple machine learning models
- Hybrid model-based classification
- TF-IDF based text feature extraction
- Web-based user interface
- FastAPI backend
- Real-time comment analysis
- Probability/risk-based classification
- Modular frontend and backend architecture

## 🏗️ System Architecture

```text
User Comment
     ↓
Frontend Interface
     ↓
FastAPI Backend
     ↓
Text Preprocessing
     ↓
TF-IDF Feature Extraction
     ↓
Machine Learning Models
     ↓
Hybrid Classification
     ↓
Toxicity Prediction
     ↓
Result Displayed to User
