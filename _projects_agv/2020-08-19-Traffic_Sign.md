---
title: "Traffic Sign Detection"
collection: projects_intern
permalink: /projects_intern/2020-08-19-Traffic_Sign
excerpt: 'Performed detection and classification of Indian Traffic Signs. Used object trackers to minimize the number of passes through the DL models as to improve the FPS of operating algorithm. Also estimated the distance of the sign from camera.'
# date: 2009-10-01
# venue: 'International Conference on Pattern Recognition Applications and Methods 2019, Prague, Czech Republic'
# paperurl: 'http://www.insticc.org/Primoris/Resources/PaperPdf.ashx?idPaper=73925'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
group: "Autonomous Ground Vehicles Research Group"
# guide: "Prof Zico Kolter"
---
<!-- This paper is about the number 1. The number 2 is left for future work. -->

<!-- [Download paper here](http://www.insticc.org/Primoris/Resources/PaperPdf.ashx?idPaper=73925) -->

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->

Traffic Sign Detection and Classification are perhaps one of the most important tasks in self driving. The issue is that there is no public dataset available for Indian Traffic Signs. So we modified a subset of the German Traffic Sign Recognition Benchmark to mimic Indian Traffic Signs. Used a trained object detector that detected traffic signs (only detected) and a classifier trained on the subset generated to classify these detections. This worked as the detecting traffic signs can easily be transferred across countries but classification cannot. Later we used KLT-Tracker to track the detected and classified bounding box for a few frames to obtain a high FPS output. Used simple geometric techniques to estimate the distance of the sign from the camera.