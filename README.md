Report-a-Dump is a mobile application that empowers citizens to take direct civic action by reporting illegal waste dump sites in their communities. The app enables users to capture and submit images and locations of waste dumps, allowing local authorities and environmental agencies to identify and respond to sanitation issues more quickly and effectively.


## Architecture
- The project follows Clean Architecture, which promotes the separation of concerns
- It also follows MVVM (Model View View-Model Architecture)
- The UI uses 100% Compose

## Stack
- Language: Kotlin
- UI: Jetpack Compose
- DI: Hilt
- Network: Retrofit
- Architecture: MVVM + Clean Architecture + Modularization

##
 The Architecture follows this:

        UI (VIEW)
            ↓
        ViewModel (VM)
            ↓
        UseCase (domain/business logic)
            ↓
        Repository interface (domain)
            ↓
        Repository impl (MODEL - data)
            ↓
           API

