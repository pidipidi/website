+++
# Date this page was created.
date = "2017-04-17"

# Project title.
title = "Multimodal Execution Monitor"

# Project summary to display on homepage.
summary = "A new anomaly detection and classification framework for manipulation tasks."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "projects/execution_monitor.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["execution-monitor"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "" #"headers/execution_monitor.png"
caption = "" #"A Multimodal Execution Monitor"
+++

{{< youtube gLcPZQnDmkk >}}

Online detection of anomalous execution can be valuable for robot manipulation, enabling robots to operate more safely, determine when a behavior is inappropriate, and otherwise exhibit more common sense. By using multiple complementary sensory modalities, robots could potentially detect a wider variety of anomalies, such as anomalous contact or a loud utterance by a human. However, task variability and the potential for false positives make online anomaly detection challenging, especially for long-duration manipulation behaviors. In this paper, we provide evidence for the value of multimodal execution monitoring and the use of a detection threshold that varies based on the progress of execution. Using a data-driven approach, we train an execution monitor that runs in parallel to a manipulation behavior. Like previous methods for anomaly detection, our method trains a hidden Markov model (HMM) using multimodal observations from non-anomalous executions. In contrast to prior work, our system also uses a detection threshold that changes based on the execution progress. We evaluated our approach with haptic, visual, auditory, and kinematic sensing during a variety of manipulation tasks performed by a PR2 robot. The tasks included pushing doors closed, operating switches, and assisting able-bodied participants with eating yogurt. In our evaluations, our anomaly detection method performed substantially better with multimodal monitoring than single modality monitoring. It also resulted in more desirable ROC curves when compared with other detection threshold methods from the literature, obtaining higher true positive rates for comparable false positive rates.