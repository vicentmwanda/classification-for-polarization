#Multilingual Text Classification for English and Hausa

This repository contains code and experiments for SemEval 2026 Task 9, focusing on multilingual text classification. The tasks involve English (high-resource) and Hausa (low-resource) languages and include:

Subtask 1: Polarization Detection (binary classification)

Subtask 2: Polarization Type Classification (multi-label classification)

Subtask 3: Manifestation Identification (multi-label classification)

Overview

The goal of this project is to evaluate the performance of pretrained transformer models and classical baselines on multilingual datasets, highlighting the challenges of low-resource languages and class imbalance. The models evaluated include:

BERT Base Cased – pretrained on English

MDeBERTa V3 Base – multilingual pretrained on 100 languages

Afro XLMR Base – pretrained on African and high-resource languages

TF-IDF + Logistic Regression – baseline

Features

Training and evaluation pipelines for all three subtasks

Data augmentation using back-translation to mitigate class imbalance

Hyperparameter tuning for optimal model performance

Support for English and Hausa datasets

Generation of predictions and submission packages
