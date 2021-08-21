## Usage
Under the root directory of the project, run the commands like the following format to call all functions:  
```
python output.py arg1 [arg2 [arg3]]  
```
Details of the three arguments above:  
* There are three posible options as "*arg1*":
    * `play` : Play an animation of a specific sorting algorithm or all algorithms in a new window, as a "figure" to Matplotlib.
    * `save-html` : Save the animation as a HTML page with a sequence of images.
    * `save-mp4` : Save the animation as a MP4 video.
* There are nine posible options as "*arg2*":
    * `all` *(default)* : Show the visualization of all sorting algorithms in the animation.
    * `bubble-sort` : Only show the visualization of bubble sorting algorithm in the animation. The following arguments have similar functions.
    * `comb-sort`
    * `heap-sort`
    * `insertion-sort`
    * `merge-sort`
    * `quick-sort`
    * `selection-sort`
    * `shell-sort`
* There are four posible options as "*arg3*":
    * `almost-sorted` : Sort an almost-sorted sequence.
    * `few-unique` : Sort a few-unique sequence.
    * `random` *(default)* : Sort a random sequence.
    * `reversed` : Sort a descending sequence.  

For example, run `python output.py play heap-sort reversed` to create a new window to play the animation of sorting, which use heap sorting algorithms and sort a descending sequence.  

