---
title: "Merge Life"
excerpt: "Merge Life is a casual mobile game where players merge items to help a character grow up, unlocking new rooms, decorations, and upgrades as they progress through life stages. <br/><img src='/images/MLife_Icon.jpg' height='300' width='300'>"
collection: portfolio
---

Merge Life is a casual mobile game where players merge items to progress through various life stages of a character. The gameplay is similar to other merge games: players combine matching items on a grid to create higher-level objects. In Merge Life, these items often represent things related to growing up, like toys, clothes, or school supplies. As players merge items, they unlock new levels and customize the character's room, decorating it with different themes, colors, and furniture.

Here are my main responsibilities in Merge Life:

- Implemented the "Retirement" feature, enabling players to unlock pieces of a retirement mansion image by completing in-game tasks.
- Developed the Piggy Bank feature, allowing players to accumulate gems and open the bank upon purchase, increasing the game's IAP revenue.
- Maintained and continuously developed core merge item features.

[<img src='/images/AppStore.png' width='200'>](https://apps.apple.com/us/app/merge-life/id1556497052)

[<img src='/images/GPC.png' width='200'>](https://play.google.com/store/apps/details?id=cc.lionstudios.mergelife&hl=en_US)

<style>
    /* Container for the horizontal scrolling bar */
    .scrolling-gallery {
        display: flex;
        overflow-x: auto;
        scroll-behavior: smooth;
        padding: 10px;
        background-color: #f4f4f4; /* Optional background color */
        border-radius: 8px;
        box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        gap: 10px;
    }

    /* Remove scrollbar for Webkit browsers */
    .scrolling-gallery::-webkit-scrollbar {
        display: none;
    }

    /* For other browsers */
    .scrolling-gallery {
        -ms-overflow-style: none;  /* IE and Edge */
        scrollbar-width: none;  /* Firefox */
    }

    /* Each image container */
    .image-container {
        flex: 0 0 auto;
        width: 200px; /* Adjust width as needed */
        height: 150px; /* Adjust height as needed */
        overflow: hidden;
        border-radius: 8px;
        box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.15);
    }

    /* Image styling */
    .image-container img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        transition: transform 0.3s ease-in-out;
    }

    /* Scale image on hover */
    .image-container:hover img {
        transform: scale(1.1);
    }
</style>

<div class="scrolling-gallery">
    <!-- Replace the src with actual image URLs -->
    <div class="image-container">
        <img src="/images/MLife_MergeBoard.PNG" alt="Image 1">
    </div>
    <div class="image-container">
        <img src="/images/MLife_Setup.PNG" alt="Image 2">
    </div>
    <div class="image-container">
        <img src="/images/MLife_Retirement_4.PNG" alt="Image 3">
    </div>
    <div class="image-container">
        <img src="/images/MLife_Retirement_4.PNG" alt="Image 4">
    </div>
    <div class="image-container">
        <img src="/images/MLife_Piggy.PNG" alt="Image 5">
    </div>
    <!-- Add more images as needed -->
</div>


![Merge Board](/images/MLife_MergeBoard.PNG)
![Character](/images/MLife_Setup.PNG)
![Retirement](/images/MLife_Retirement_4.PNG)
![Piggy Bank](/images/MLife_Piggy.PNG)