---
title: "Merge Life"
excerpt: "Merge Life is a casual mobile game where players merge items to help a character grow up, unlocking new rooms, decorations, and upgrades as they progress through life stages <br/><img src='/images/MLife_Icon.jpg' height='300' width='300'>"
collection: portfolio
---

Merge Life is a casual mobile game where players merge items to progress through various life stages of a character. The gameplay is similar to other merge games: players combine matching items on a grid to create higher-level objects. In Merge Life, these items often represent things related to growing up, like toys, clothes, or school supplies. As players merge items, they unlock new levels and customize the character's room, decorating it with different themes, colors, and furniture.

## Main responsibilities:

- Implemented the "Retirement" feature, enabling players to unlock pieces of a retirement mansion image by completing in-game tasks.
- Developed the Piggy Bank feature, allowing players to accumulate gems and open the bank upon purchase, increasing the game's IAP revenue.
- Maintained and continuously developed core merge item features.

[<img src='/images/AppStore.png' width='200'>](https://apps.apple.com/us/app/merge-life/id1556497052)

[<img src='/images/GPC.png' width='200'>](https://play.google.com/store/apps/details?id=cc.lionstudios.mergelife&hl=en_US)

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
        width: 300px; 
        height: 600px; /* Adjust width as needed */
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
        <img src="/images/MLife_MergeBoard.PNG" alt="Image 1">
        <div class="caption">Merge Board</div>
    </div>
    <div class="image-container">
        <img src="/images/MLife_Setup.PNG" alt="Image 2">
        <div class="caption">Character</div>
    </div>
    <div class="image-container">
        <img src="/images/MLife_Piggy.PNG" alt="Image 5">
        <div class="caption">Piggy Bank</div>
    </div>
    <div class="image-container">
        <img src="/images/MLife_Retirement_1.PNG" alt="Image 3">
        <div class="caption">Retirement</div>
    </div>
    <div class="image-container">
        <img src="/images/MLife_Retirement_2.PNG" alt="Image 3">
        <div class="caption">Retirement</div>
    </div>
    <div class="image-container">
        <img src="/images/MLife_Retirement_3.PNG" alt="Image 3">
        <div class="caption">Retirement</div>
    </div>
    <div class="image-container">
        <img src="/images/MLife_Retirement_4.PNG" alt="Image 3">
        <div class="caption">Retirement</div>
    </div>
    <!-- Add more images as needed -->
</div>