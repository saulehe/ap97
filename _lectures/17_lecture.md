---
type: lecture
date: 2019-04-29T8:00:00+4:30
title: Session 17 - Operator Overloading + Dictionary
slides: http://drive.iust.ac.ir/index.php/s/pvH40tElHCvu3MG/download?path=%2FSlides&files=AP_Session17.pdf
video: http://drive.iust.ac.ir/index.php/s/pvH40tElHCvu3MG/download?path=%2FClassVideos&files=S17.mp4
codes: http://drive.iust.ac.ir/index.php/s/pvH40tElHCvu3MG/download?path=%2FCode&files=S17.zip
data: http://drive.iust.ac.ir/index.php/s/pvH40tElHCvu3MG/download?path=%2FData&files=WHO.zip
tldr: "In this session we started by demonstrating that Object.Equals doesn't work as expected for most objects. The operator == has the same problem. We overrided the Equals method for a new class to work as expected. We also overloaded the == operator. We demonstrated how null checking in the == operator can result in a StackOverflowException. We then introduced the generic Dictionary collection and how we can override the Object.GetHashCode method and implement the IEquatable interface to have Dictionary work correctly for a class as a key. We demonstrated a dictionary lookup can be much faster if a good hash code is selected. Finally, we introduced the +, -, ... operators in addition to the indexer"
#thumbnail: /static_files/presentations/lec.jpg
---
