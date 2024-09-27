# Adds System

A brief description of what this project does and who it's for

Adds System
This project includes a custom Adds System designed to manage and display ads within the game. The system is flexible and supports multiple ad providers, ensuring seamless integration and user experience.

# Features of the Adds System
* Ad Types Supported: Supports banner ads, interstitial ads, and rewarded video ads.
* Ad Placement: Easily manage ad placement through Unity's UI system.
* Provider Integration: Integrates with popular ad platforms like Google AdMob, Unity Ads, and others.
* Custom Callbacks: Includes custom callbacks for ad events (e.g., on ad load, on ad close, on reward).

* Setting Up the Adds System
 1 Configuration:

* Go to the Assets/AddsSystem/Config folder to configure the ad settings, including ad unit IDs and test mode.
You can toggle ad types and placements via Unity's Inspector.

2  Ad Manager Setup:

* The main script for managing ads is AdManager.cs, which handles initializing ads, loading, and displaying them.
* To add an ad in the scene, simply drag the AdManager prefab into your scene.

3 Testing:

* Use Unity's Play Mode to simulate different ad behaviors (successful load, failure to load, etc.).
* In Play Mode, the system automatically switches to test ads if test mode is enabled in the configuration.
