# AutoSceneGen
We propose a novel framework, called AutoSceneGen, that automatically reconstructs driving scenarios from accident videos using large language models.


# "AutoSceneGen: Automated Reconstruction and Mutation of Accident Scenarios for Robust Autonomous Driving Testing"

Accurately testing autonomous driving systems in real-world scenarios is essential for ensuring their safety and reliability. However, manually creating test environments, especially for accident scenarios, is time-consuming and often lacks realism. In this paper, we propose a novel framework, called AutoSceneGen, that automatically reconstructs driving scenarios from accident videos using large language models. Our approach begins by selecting keyframes, including the initial, accident, and final moments from the video. We then use LLMs to analyze the scene, reconstruct the road topology in OpenDRIVE format, and identify traffic participants and their behaviors, which are converted into OpenSCENARIO format for simulation. Additionally, we apply parameter mutations to create diverse test scenarios, increasing the robustness of autonomous driving systems by exposing them to a wide range of conditions. Experimental results demonstrate the effectiveness of our framework in accurately reconstructing accident scenarios and generating high-fidelity simulations for autonomous driving testing. This work reduces the need for manual scenario generation and enhances the ability to test autonomous systems in complex, real-world-like environments.

## Introduction

**AutoSceneGen** is a novel framework for reconstructing accident scenarios from real-world video data using large-scale models. The framework automates the generation of realistic autonomous driving test scenarios in **OpenDRIVE** and **OpenSCENARIO** formats. It focuses on:
- **Intelligent Keyframe Selection**: Automatically selects the most critical frames (pre-accident, accident, and post-accident) from videos for accurate scene reconstruction.
- **Accident Scene Understanding**: Uses large models to analyze traffic participants, road environments, and dynamic behaviors, reconstructing complex accident scenes.
- **Scenario Mutation**: Generates diverse test scenarios by mutating traffic participant types, numbers, and trajectories, improving the robustness of autonomous driving system testing.

The framework's approach is designed to reduce manual intervention in generating accident scenarios and improve the coverage of critical edge cases during the testing of autonomous vehicles.

## Features

- **Automatic Scenario Generation**: Converts accident videos into **OpenDRIVE** and **OpenSCENARIO** files for use in autonomous driving simulators.
- **Accident Analysis**: Integrates accident understanding to provide detailed explanations of the scenario and identify critical causes and effects.
- **Scenario Mutation**: Creates a diverse set of test scenarios through parameter variations (participant types, behaviors, routes) to enhance the variety and richness of testing conditions.
- **Evaluation Metrics**: The framework has been tested using various metrics such as **Scene Element Coverage**, **Scene Attribute Accuracy**, **Behavior Prediction Accuracy**, and **Scenario File Richness**, outperforming existing models.

## Repository Contents

- `src/`: Contains the source code for the AutoSceneGen framework.
- `data/`: Example accident videos and datasets for scenario generation and testing.
- `doc/`: Detailed documentation of the framework, including a step-by-step guide for using the framework.

## Notice

The relevant code, dataset, and demonstration video are currently being organized. Please be patient and wait for further results.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.



