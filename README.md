## Evaluating different tools for Image annotation tasks

### Criteria for selecting these tools
- Run on Windows / Linux / Mac
- Works offline

Compiled list : https://www.datasetlist.com/tools/

1. [LabelImg](https://github.com/tzutalin/labelImg)

    - Pros:
        - Supports both YOLO and Pascal data format
        - Nice set of shortcuts for saving, selecting the tool etc

    - Cons:
        - Have to select the tool everytime
        - No segmentation option
        - No support for videos

2. [Labelme](https://github.com/wkentaro/labelme)

    - Pros:
        - Same Interface as LabelImg, so all the functionalities are there by default
        - Works on Videos
        - Supports Semantic and Instance Segmentation

    - Cons:
        - Supports only Polygons, difficult to draw rects


3. [VoTT](https://github.com/Microsoft/VoTT)

    - Pros:
        - Supports Rects and Squares
        - Simple Interface
        - Allows different data saving formats like YOLO, PASCAL, CNTK TAGs etc
        - Works on Videos

    - Cons:
        - Doesn't support Polygons

4. [ImageTagger](https://github.com/bit-bots/imagetagger)

    - Pros:

    - Cons:
        - Requires a lot of dependencies for tagging!

5. [FAMO](https://github.com/udaypk/FastAnnotationMultipleObjects)

    - Pros:

    - Cons:
        - Unclear usage instructions, if someone is able to try and give suggestions, welcome.


