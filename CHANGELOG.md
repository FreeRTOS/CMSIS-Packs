## Remaining Release of 202406 LTS Library Versions

###
- This release updates FreeRTOS+TCP and FreeRTOS LTS packs to the current 202406 versions.

## Partial Release of 202406 LTS Library Versions

### Updates 
- This release updates most packs to the 202406 LTS version (currently the FreeRTOS+TCP and FreeRTOS LTS packs are excluded from this update, but will be added in the next update).
- The AWS IoT MQTT File Streams pack has been added.

## Re-release of LTS2.0 packs due to URL change ( June 2023 )

### Updates
-  The new version of the CMSIS packs were required for the reimport of the package description file which contains the Amazon CloudFront URL. 
-  Contents of the new packs are same as the LTS 2.0 packs released in Feb 2023. 

## CloudFront Update ( June 2023 )

### Updates
-  Updated the Package Index File (.pidx) with the cloudFront Url. Moving forward all of the CMSIS packs stored in the S3 bucket will be accessed via Amazon CloudFront. 

## LTS 2.0 ( Feb 2023 )

### Updates
-  CMSIS pack release containing LTS 2.0 versions of the FreeRTOS kernel and the associated libraries.

## 4.0.0 ( June 2022 )

### Updates
- Source location of the FreeRTOS [LTS](https://freertos.org/lts-libraries.html) CMSIS packs moved to [S3](https://aws.amazon.com/s3/) storage.

## Beta ( October 2021 )
This is a beta release for the repository.

This repository contains a Package Index File (.pidx) that describes the location of the CMSIS Packs for various FreeRTOS [LTS](https://freertos.org/lts-libraries.html) libraries. This Package Index File enables the CMSIS Packs to be integrated into development tools.
