# microbit-explorer

## Learning Intentions
-

## Success Criteria

## Syllabus

## Overview
In this activity we will use a micro:bit to record sites of First Nations importance as we walk along the [Aboriginal Heritage Walk](https://www.nationalparks.nsw.gov.au/things-to-do/walking-tracks/aboriginal-heritage-walk). The purpose is to understand how to log and manipulate data and also build a better understanding of the First Nations people who lived in Darug country for around 60,000 years before colonisation. 

## Apperatus
- Micro:bit v2
- Software from this repository
- Booklet with images of possible flora and sites of First Nation significance

## Step 1: Calibrate the Microbit
To record your steps with the micro:bit and ensure that distances are approximately correct
you will need to calibrate the micro:bit accelerometer to pick up your steps correctly.

1. Load the [./step_logging.mpy]() file onto your micro:bit. 

> [!TIP]
> This can be easily done using https://python.microbit.org/ and connecting you micro:bit to your computer with the provided usb cable

2. Disconnect the micro:bit from your computer, attach the battery, press `Button A` until a TICK :heavy_check_mark: is shown and then go for a walk around the building. Please ensure not to disturb other classes and do not run.
3. Once you have returned press `Button B` and you should see a CROSS :heavy_multiplication_x: to indicate recording of your steps has stopped. 
4. Leave your battery connected and connect the micro:bit to your computer. You should have a drive available to you from the micro:bit and a file called `MY_DATA.HTM`. Open the fill and look at the graph. Depending on where you attached the micro:bit you will see that either the *Y* or *Z* coordinates gives a signal of when you take a step. For me it is the *Y* as I had the micro:bit in my pocket and the number I will use is 750.
5. Open the `compass_logger.mpy` program and change the logger code to the axis and value to chose in the previous step.
6. Load the `compass_logger.mpy` onto your micro:bit and go for another walk around the building. See that the data logged is now steps taken and direction.

### Extensions
You might want to modify the code so that it also records:
- noise level
- temperature
- light level

Remember that there is limited storage space, about 30k. If you include the above ensure to calculate the amount of storage required for a 2hr walk and document it in your report.

## Step 2: Excursion to the Aboriginal Heritage Walk
1. Once we have arrived at the walk, plug the battery into the micro:bit and calibrate the compass. 
1. press `Button A` to start recording your steps and direction.
1. Everytime you reach a point where there is a site of cultural importance or you see one of the flora in the booklet you have, press `Button B` to record the location and take a photo with your phone camera.
1. When we have finished, touch the logo to stop recording. We will use this data to analyse our walk and document the StoryMap you create on [Story Maps](https://storymaps.com/). [This is an example](https://storymaps.com/stories/df2f47bd02674c43ba6c70e861bdf997) of what you should create with your steps, photos and direction you were facing

## Step 3: Analyse the data
1. Once back in the classroom you should:
    - create a story map like the one above
    - load your data in an excel spreadsheet
    - analyse how many steps you took per photo and per minute
        - Describe any trends you notice
    - classify the photes between flora, fauna and location. 
        - Are there any trends you notice in the data? If so, what reasons can you provide for the trend or not.