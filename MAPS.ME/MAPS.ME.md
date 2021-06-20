# Mapsme is using OpenStreetMap data illegally

This company is using OpenStreetMap data. It is a good news, but unfortunately this company failed to credit authors of this data.

Note that OpenStreetMap data is available for free and there are very limited requirements. And they still failed to follow them, [what is not OK](../README.md). Note that it is also illegal, as ODBL licence used by OpenStreetMap requires proper attribution, and requires it to be properly displayed. Hiding one in place where noone will see it is both against the common sense [and the licence](../README.md).

![what_maps_me_shows_as_an_attribution_inline.png](what_maps_me_shows_as_an_attribution_inline.png)

## Fixing
Can be easily fixed by replacing misleading attribution "MAPS.ME" in the bottom right corner by `© OpenStreetMap, © Booking.com for misplaced hotels` or `map data except hotel ads © OpenStreetMap` or `map data © OpenStreetMap, © Booking.com for misplaced hotels, style © MAPS.ME` or something similar.

Missing attribution may be also partially remediated by adding something like "Powered by OpenStreetMap data" at the startup screen.

There is a deeply hidden and insufficient attribution. It is not in a place ever visited by a typical user.

Attribution text will appear on the map, immediately after opening the app but only for [2 seconds and half-hidden](attribution_flash_2021.gif). If you cannot spot it then maybe [this image will help you find it](attribution_flash_2021.png).



## Reported

- [https://github.com/mapsme/omim/issues/11203](https://github.com/mapsme/omim/issues/11203) - 2019 VII
- [https://github.com/mapsme/omim/issues/11845](https://github.com/mapsme/omim/issues/11845) - 2019 X

## Reaction of the company

As of 2021-06-20 MAPS.ME attribution text remains pernamently visible while OpenStreetMap attribution is barely visible, in violation of the OpenStreetMap data license.

On 2019-07-18 they [posted](https://github.com/mapsme/omim/issues/11203#issuecomment-512743377) "Hi, we will add info to the loading screen in one of the upcoming releases. That is a good idea. Thanks!"

This claim turned out to be untrue. Instead, in of updates released in 2021 attribution shown for just two seconds become futher obscured.


## Problem reproduction

1. Install MAPS.ME on an Android phone, run it.
2. Try to find a required attribution.

## Typical MAPS.ME interface using OpenStreetMap data

Note that OpenStreetMap is not presented as a source. Instead there is a misleading "MAPS.ME" attribution in bottom right corner. MAPS.ME is allowed to use OpenStreetMap data for free (like everybody else) but is required to include a clearly visible attribution (like everybody else).

![MAPS.ME_application_missing_attribution_misleading_one_present_screenshot_2019-09-09-17-44-05.png](MAPS.ME_application_missing_attribution_misleading_one_present_screenshot_2019-09-09-17-44-05.png)
