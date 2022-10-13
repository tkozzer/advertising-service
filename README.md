# Advertising Service

## The Problem: ATA Advertising

ATA's AdvertisingService serves advertisements for ATA. These advertisements show up on the retail website and use 
targeting to present different ATA advertisements to each individual. The targeting tries to take advantage of what 
Amazon knows about you to show you the particular ad that is most likely to appeal to you.

An overview of the service is covered in the [design document](DESIGN_DOCUMENT.md). We encourage you to read that now
before continuing below.

## Project Mastery Tasks
#### Under each mastery task I have linked to parts of the project that are my code.
### [Mastery Task 1: Filter out the noise](tasks/project-mastery-tasks/MasteryTask01.md)
My Contributions:
- [AdvertisementSelectionLogic's selectAdvertisement](https://github.com/tkozzer/advertising-service/tree/sprint-25/src/com/amazon/ata/advertising/service/businesslogic/AdvertisementSelectionLogic.java)
- [TargetingEvaluator's evaluate](https://github.com/tkozzer/advertising-service/tree/sprint-25/src/com/amazon/ata/advertising/service/targeting/TargetingEvaluator.java) 
- [AddTargetingGroupActivity's addTargetingGroup](https://github.com/tkozzer/advertising-service/tree/sprint-25/src/com/amazon/ata/advertising/service/activity/AddTargetingGroupActivity.java)
### [Mastery Task 2: Concurrent Tasks](tasks/project-mastery-tasks/MasteryTask02.md)
My Contributions:
- [AdvertisementSelectionLogic's selectAdvertisement](src/com/amazon/ata/advertising/service/businesslogic/AdvertisementSelectionLogic.java)
- [AddTargetingGroupActivity's addTargetingGroup](src/com/amazon/ata/advertising/service/activity/AddTargetingGroupActivity.java)
- [TargetingEvaluator's evaluate](src/com/amazon/ata/advertising/service/targeting/TargetingEvaluator.java)  

### [Mastery Task 3: Ads don't grow on trees (or do they?)](tasks/project-mastery-tasks/MasteryTask03.md)
- [AdvertisementSelectionLogic's selectAdvertisement](src/com/amazon/ata/advertising/service/businesslogic/AdvertisementSelectionLogic.java)]

*note: This is a project adapted from Amazon Technical Academy by Bloomtech.*
