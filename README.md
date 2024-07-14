This is our submission for Myntra WeForShe Hackkeramp'24.
# Trendy Outfit Matching and Visualizer Using AI

## Overview

This project aims to enhance Gen Z's shopping experience on MYNTRA by focusing on sustainable fashion trends and interactive solutions. Our solution leverages advanced AI models for image captioning, item suggestion, and real-time outfit visualization. Additionally, we integrate eco-friendliness information and location-based engagement features to promote sustainable fashion practices.

## Key Features

1. **Image Captioning with LLaVA-7b**:
   - Utilizes the `llava-hf/llava-1.5-7b-hf` model to generate detailed captions for items in the user's cart, capturing attributes like color, style, and fabric.

2. **Complementary Item Suggestions with Meta-Llama-3-8B-Instruct**:
   - Captions are fed into `mistralai/Mistral-7B-Instruct-v0.3`, trained on fashion data and user purchase history, to suggest complementary items based on style compatibility, color coordination, and fashion trends.
   - The system retrieves previously bought items that match the suggestions for visualization.

3. **Real-Time Outfit Visualization Using U-Net**:
   - The U-Net model segments and blends top and bottom pieces from clothing images, generating realistic visualizations of complete outfits.
   - These visualizations combine new suggestions with previously bought items, tailored to different body types and poses.

4. **Sustainable Fashion Practices**:
   - Promotes the reuse of existing wardrobe items and encourages multiple repeat interactions with the platform.
   - Implements a color-coded system to indicate the sustainability of fashion items, based on fabric and supply chain practices.
   - Incorporates a location filter to prioritize locally sourced items, reducing transportation emissions.

5. **Location-Based Engagement**:
   - Integrates pre-loved fashion stores on MYNTRA and implements location-based alerts to notify users when they pass by a store with an item from their cart.
   - Allows users to share clothes in their cart with nearby app users or pre-loved stores for exchanges, second-hand purchases, or borrowing, fostering community interaction.

## Problem Statement

- Develop a trendy outfit matching algorithm and visualizer using AI.
- Ensure transparency in access to eco-friendliness information about various items.
- Enhance location-based engagement with the nearest store or pre-loved stores.

## Implementation Details

### 1. Image Captioning

- **Model**: `llava-hf/llava-1.5-7b-hf`
- **Purpose**: Generate detailed captions for items in the user's cart.
- **Attributes Captured**: Color, style, fabric, and notable design elements.

### 2. Complementary Item Suggestions

- **Model**: `mistralai/Mistral-7B-Instruct-v0.3`
- **Purpose**: Analyze captions and suggest complementary items.
- **Criteria**: Style compatibility, color coordination, fashion trends, and user purchase history.

### 3. Real-Time Outfit Visualization

- **Model**: U-Net
- **Purpose**: Segment and blend clothing images to create realistic outfit visualizations.
- **Customization**: Tailored to different body types and poses.

### 4. Sustainable Fashion Practices

- **Eco-Friendliness**: Color-coded system based on fabric and supply chain factors.
- **Local Sourcing**: Location filter to prioritize nearby items, reducing transportation emissions.
- **Sustainability Parameters**: Manufacturing practices, supply chain, material durability, and carbon footprint.

### 5. Location-Based Engagement

- **Pre-Loved Stores**: Integration with MYNTRA and location-based alerts.
- **Community Interaction**: Options for exchanging, purchasing, or borrowing clothes from nearby users or stores.

## Benefits

1. Encourages repeat visits to MYNTRA with tailored outfit suggestions and real-time visualizations.
2. Establishes MYNTRA as a trusted fashion destination by providing clear sustainability information.
3. Boosts user engagement and satisfaction through interactive, AI-driven recommendations.

## Feasibility and Scalability for future Advancements

1. **Feasibility**: Utilizes advanced AI models and existing frameworks for implementation.
2. **Scalability**: Cloud-based AI services could enable handling of increasing user and data volumes.
3. **Integration**: Seamless integration with MYNTRA's infrastructure allows for continuous updates and improvements.

## Models and Libraries

-  https://huggingface.co/llava-hf/llava-1.5-7b-hf
-  https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.3



