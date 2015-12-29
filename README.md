# DownloadImageSingleNMultithreaded
This application allows users to download images from various online resources and display in form of slide-show or grid-view. The application prompts the user for URLs of images to download them concurrently via a BoundService or Started Service. User can request multiple image downloads at once or download one image at a time.

# Design Patterns Used
1. Bridge Pattern - It used to decouple the interface of the the Model layer from the particular type of Service used to implement this layer
2. This Android program is structured in accordance with the Model-View-Presenter (MVP) pattern

# Features of this application
1. Handle runtime configuration changes by saving the bulk of the state in the Presenter and Model layers so this state can be stored/retrieved during runtime configuration changes that cause the View Image Activity to be destroyed and recreated
2. Support both Started & Bound Service implementations.
3. Plug in different concurrency models for the Bound and/or Started Services without affecting other parts of the application.
4. Change the request and reply message formats without affecting other parts of the application.
5. Change the way in which the downloaded images are displayed without affecting other parts of the app design/implementation.

# Development Environment
1. Android Studio 1.5
2. Java 1.8
3. Android SDK 22
