# AutoSceneGen
We propose a novel framework, called AutoSceneGen, that automatically reconstructs driving scenarios from accident videos using large language models.


# "AutoSceneGen: Automated Reconstruction and Mutation of Accident Scenarios for Robust Autonomous Driving Testing"

Accurately testing autonomous driving systems in real-world scenarios is essential for ensuring their safety and reliability. However, manually creating test environments, especially for accident scenarios, is time-consuming and often lacks realism. In this paper, we propose a novel framework, called AutoSceneGen, that automatically reconstructs driving scenarios from accident videos using large language models. Our approach begins by selecting keyframes, including the initial, accident, and final moments from the video. We then use LLMs to analyze the scene, reconstruct the road topology in OpenDRIVE format, and identify traffic participants and their behaviors, which are converted into OpenSCENARIO format for simulation. Additionally, we apply parameter mutations to create diverse test scenarios, increasing the robustness of autonomous driving systems by exposing them to a wide range of conditions. Experimental results demonstrate the effectiveness of our framework in accurately reconstructing accident scenarios and generating high-fidelity simulations for autonomous driving testing. This work reduces the need for manual scenario generation and enhances the ability to test autonomous systems in complex, real-world-like environments.




