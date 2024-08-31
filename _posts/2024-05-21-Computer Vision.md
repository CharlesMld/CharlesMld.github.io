---
title: Computer Vision
# The author information of the post usually does not need to be filled in the Front Matter , they will be obtained from variables social.name and the first entry of social.links of the configuration file by default. But you can also override it as follows : (find charles_mld in _data)
# authors: [<author1_id>, <author2_id>] for multiple entries
author: <charles_mld>
date: 2024-08-31 18:00:00 +0800
categories: [Italy, University] # up to 2 elmts like category, sub-category
tags: [computer_vision] # TAG names should always be lowercase
# description: This post is a short introduction of myself and what I do in life
# toc: true # by default its on so don't have to do that, if want to change go to config
# comments: true # by default its on so don't have to do that, if want to change go to config
---

I recently completed a Computer Vision course as part of my Master's program in Information Engineering at the University of Padova. The course, taught by Professor Stefano Ghidoni, was a key component of my Erasmus semester. This review summarizes the main concepts and topics covered during the class, which I successfully passed at the conclusion of my exchange program. You'll be able to find the course's outline in the end of this post.

# Global review
The Computer Vision course offered a comprehensive overview of the field, living up to the professor's promise of covering the entire spectrum from basic object representation in cameras to advanced deep learning techniques using convolutional neural networks.

Weekly two-hour lab sessions complemented the theoretical lectures, providing hands-on experience with the OpenCV library. We worked in C, utilizing CMAKE files to streamline the compilation process. These practical sessions were designed to prepare us for the final group project.
Our final project involved analyzing pool game videos from multiple angles and with varying table/background colors. The main objectives were to:

Segment the pool table and balls
Color-code elements (green for the table, blue for solid balls, red for striped balls)
Detect and track ball movements
Create a bird's-eye view map of the pool table

While challenging, especially given my impending return to France, our group managed to pass the project. However, I feel I could have contributed more given different circumstances.
The final exam was moderately challenging. Although I performed well, I believe there was room for improvement. The most valuable aspect of the course was the learning process itself. I developed a skill for distilling complex presentations into concise, well-explained concepts. YouTube proved to be an invaluable resource for understanding the mathematical principles underlying image transformations.
I conclude this course with a set of clear, comprehensive notes that I'm confident will serve as a quick reference should I engage with computer vision in the future. The knowledge gained has provided a solid foundation in this field.

# 

# Course outline (as given by teacher)
**Low-level image processing** : Single pixel and histogram-based transform • Linear filters • Non-linear filters
**Mid-level image processing** Edge detection, derivative • Corner detection • Blob detection • Hough transform • Segmentation
**Image features** Keypoint detection and feature descriptor calculation • Feature matching
**High-level vision** Object detection & recognition • Image (semantic) segmentation • Machine learning for computer vision
**Image formation, cameras and colors** Imaging systems • Cameras: sensors, optics, camera working principle • Colorimetry: color spaces, color matching
**Projective geometry** Geometric representation of the image formation process • Non-ideal cameras • Reference systems
**Camera calibration** Study of lens distortion • Compensation of lens distortion • Zhang calibration method
**Deep Learning for computer vision** Deep networks dedicated to image processing • End-to-end learning • Transfer learning & fine-tuning
**C++** Templates: libraries and classes • Class hierarchies and inheritance • Data management & processing for computer vision
**Computer vision system designs** Intro to OpenCV, image loading, pixel manipulation, color spaces • Camera Calibration • Image equalization, histograms and filters • Hough transform and edge detection • Keypoints, descriptors and matching: building a panoramic image • Keypoints, descriptors and matching: object detection • Machine learning / deep learning: object detection
