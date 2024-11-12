---
title: "Air Hockey with AI opponent"
excerpt: "Single-player Air Hockey game with AI opponent, trained with ML-Agents package <br/><img src='/images/AH_1.png' height='300' width='500'>"
collection: portfolio
---

This project is a single-player Air Hockey game. The human player (red) can play against an AI opponent (blue). I trained
the AI model using Deep Reinforcement Learning with Unity's ML-Agents package. Through a process called self-play, 
the model is able to learn how to play air hockey from scratch by playing it with itself.

Key Achievements:
- Applied deep reinforcement learning to train an AI player capable of competing with human players
- Designed game mechanics for realistic air hockey simulation, including striker control, score tracking, and puck movement
- Trained the AI model using Unity ML-Agents Toolkit with over 40,000 rounds of adversarial self-play to enhance its performance

Click the link below to see the code repository

[Air Hockey Code](https://github.com/tianhengMa/Air_Hockey_AI_Opponent)

Click the link below to watch the gameplay demo

[Air Hockey Game Demo](https://www.youtube.com/watch?v=Mj13nd_Z1u0)

<style>
    /* Container for the horizontal scrolling bar */
    .scrolling-gallery {
        display: flex;
        overflow-x: scroll;
        scroll-behavior: smooth;
        padding: 10px;
        background-color: #f4f4f4; /* Optional background color */
        border-radius: 8px;
        box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        gap: 10px;
    }

    /* Style scrollbar for Webkit browsers */
    .scrolling-gallery::-webkit-scrollbar {
        height: 8px;
    }

    /* Customize scrollbar thumb */
    .scrolling-gallery::-webkit-scrollbar-thumb {
        background-color: #e0e0e0; /* Lighter shade to blend in */
        border-radius: 4px;
        border: 1px solid #f0f0f0;;
    }

    /* Customize scrollbar track */
    .scrolling-gallery::-webkit-scrollbar-track {
        background-color: #f4f4f4;
    }

    /* Each image container */
    .image-container {
        flex: 0 0 auto;
        width: 500px; 
        height: 260px; /* Adjust width as needed */
        overflow: hidden;
        text-align: center;
        border-radius: 8px;
        box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.15);
    }

    /* Image styling */
    .image-container img {
        width: 100%;
        height: 100%; /* Adjust height as needed */
        object-fit: cover;
        transition: transform 0.3s ease-in-out;
        border-radius: 8px 8px 0 0;
    }

    /* Scale image on hover */
    .image-container:hover img {
        transform: scale(1.1);
    }

    /* Caption styling */
    .caption {
        font-size: 14px;
        color: #333;
        background-color: #fff;
        font-weight: 500;
        padding: 4px 0;
    }
</style>

<div class="scrolling-gallery">
    <!-- Replace the src with actual image URLs -->
    <div class="image-container">
        <img src="/images/AH_1.png">
    </div>
    <div class="image-container">
        <img src="/images/AH_2.png">
    </div>
</div>
