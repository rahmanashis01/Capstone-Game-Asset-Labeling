Procedural Content Generation in Game Engines using Labeled Asset Libraries
Capstone Project for B.Sc. in Software Engineering
Project Overview
This project explores the use of machine learning to enhance procedural content generation (PCG) in modern game engines. The core of this project is a C++ based system that leverages a labeled dataset of 3D game assets to intelligently and contextually generate game environments. This approach aims to move beyond simple random placement of objects and create more believable and immersive game worlds.

The Problem
Traditional PCG methods often rely on noise algorithms and simple rules, which can lead to repetitive and unrealistic environments. To create more dynamic and believable worlds, a system needs to understand the relationships between different objects (e.g., trees grow in forests, not in the middle of a building). This requires a deeper understanding of the assets being placed, which can be achieved through machine learning.

The Solution
This project will utilize a labeled dataset of 3D game assets. Each asset will be annotated with metadata, such as:

Object Class: (e.g., flora, fauna, architecture, prop)

Biome: (e.g., forest, desert, urban)

Placement Rules: (e.g., on_ground, on_wall, in_water)

This labeled data will be used to train a model that can be integrated into a game engine to generate levels based on high-level rules and constraints.

Role of Labelbox
Labelbox is critical for the success of this project. I will be using the Labelbox platform to:

Create a custom ontology for my 3D game assets.

Annotate and classify a dataset of 3D models.

Manage the labeling workflow to ensure consistency and quality.

Export the labeled data in a format that can be used to train my machine learning model.

The advanced features of Labelbox will allow me to create the high-quality, structured data that is essential for this research.

Project Goals
To build a C++ library for procedural content generation.

To create a labeled dataset of at least 500 3D game assets using Labelbox.

To train a machine learning model that can intelligently place assets based on their labels.

To demonstrate the system by generating a sample game level in a game engine.

Technologies to be Used
Programming Language: C++

Data Labeling: Labelbox

Game Engine: Unreal Engine (or a custom C++ engine)

Machine Learning: TensorFlow or PyTorch (for model training)
