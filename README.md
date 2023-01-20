# An Adjustable Semantic Differential Array question for LimeSurvey versions 5.x and 6.x
**A semantic differential array question in which you can move the position of the last answer column.**

This may be useful if:
- You want to have a "No Answer" item outside of the semantic differential layout in a mandatory question.
- You want to place a column before the semantic differential layout.

Compatible with LimeSurvey versions 5.x and 6.x.

![Image Adjustable Semantic Diff Array 2](/Adjustable-Semantic-Diff-Array/survey/questions/answer/arrays/array/assets/images/asda_2.png)

**Implementation:**

1) - **Manual installation** - Extract the download and upload the *Social-Value-Orientation* folder to */pathToLimeSurvey/upload/themes/question/*.
    - **Theme manager** - Extract the download, compress (zip) the *Social-Value-Orientation* folder and import via the theme manager.

2) Create an "Adjustable Semantic Differential Array" type question, click Save.   
![Image Adjustable Semantic Diff Array 4](/Adjustable-Semantic-Diff-Array/survey/questions/answer/arrays/array/assets/images/asda_4.png)

3) Implement [the semantic differential feature](https://manual.limesurvey.org/Question_type_-_Array#Short_description) by placing a pipe character between the left/right sub-question labels.  
![Image Adjustable Semantic Diff Array 3](/Adjustable-Semantic-Diff-Array/survey/questions/answer/arrays/array/assets/images/asda_3.png)

4) Adjust the "Column position" setting in the "Custom options" question attributes. The last answer column will be moved to this position.  
![Image Adjustable Semantic Diff Array 5](/Adjustable-Semantic-Diff-Array/survey/questions/answer/arrays/array/assets/images/asda_5.png)

**Notes:**

1) The styles for the theme can be modified in */pathToLimeSurvey/upload/themes/question/Adjustable-Semantic-Diff-Array/survey/questions/answer/arrays/array/assets/css/asda.css*.

4) Demo survey in */Adjustable-Semantic-Diff-Array/survey/questions/answer/arrays/array/assets/demo/*.
    
    
*Custom themes are given without any warranty, implied or otherwise.*
