---
title: "AR Survivor.io Clone"
excerpt: "A clone of the popular roguelike game Survivor.io set up in the AR environment <br/><img src='/images/AR_SURVIVOR_IO_CLONE_SCREENSHOT_1.png' height='300' width='500'>"
collection: portfolio
---

As a fan of rogue-like games, I enjoyed playing Survivor.io on my phone during my downtime and thought it would be exciting to create my own version. With a strong interest in Augmented Reality (AR), I set out to develop a 3D AR clone of Survivor.io.

In my version, players can move around a dynamic playfield, automatically attack waves of spawned enemies, and collect gems to level up—similar to the original Survivor.io gameplay.

## Key Achievements:

- Developed plane detection and AR playfield setup using Unity's AR Foundation package.
- Implemented automated weapon targeting and basic AI-driven enemy movement.
- Created smooth character movement with animations for an enhanced player experience.
- Designed gem collection mechanics and a progression system with level-up capabilities.

Click the link below to watch the gameplay demo

[AR Survivor.io Clone Dev Log](https://www.youtube.com/watch?v=fI0D3IZSMkc)

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
        <img src="/images/ARSI_1.jpeg">
    </div>
    <div class="image-container">
        <img src="/images/ARSI_2.jpeg">
    </div>
    <div class="image-container">
        <img src="/images/ARSI_3.jpeg">
    </div>
    <div class="image-container">
        <img src="/images/ARSI_4.jpeg">
    </div>
</div>



