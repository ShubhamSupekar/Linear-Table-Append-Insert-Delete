# Linear-Table-Append-Insert-Delete
1 Insert a student's score anywhere in the one-dimensional array scores:
     First create a temporary array tempArray larger than the original scores array length
     Copy each value of the previous value of the scores array from the beginning to the insertion position to tempArray
     Move the scores array from the insertion position to each value of the last element and move it back to tempArray
     Then insert the score 75 to the index of the tempArray.
     Finally assign the tempArray pointer reference to the scores
    
2 Delete the value of the index=2 from scores array:
     Create a temporary array tempArray that length smaller than scores by 1
     Copy the data in front of i=2 to the front of tempArray
     Copy the array after i=2 to the end of tempArray
     Assign the tempArray pointer reference to the scores
     Printout scores
   
3 (Append)Add a score 75 to the end of the one-dimensional array scores.:
    First create a temporary array(tempArray) larger than the original scores array length
    Copy each value of the scores to tempArray
    Assign 75 to the last index position of tempArray
    Finally assign the tempArray pointer reference to the original scores
