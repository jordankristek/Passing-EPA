<b>The goal of this project is to perform an in-depth analysis of NFL passing EPA data over a 5-year period. EPA, which stands for Expected Points Added, is a widely-used metric for quantifying the value of each play. 
A positive EPA indicates that the play was a success and is likely to add points to the team's score, while a negative EPA indicates that the play was likely to diminish a team's score. 

One of the first steps was to create a column that classified each pass play as "short" or "long" based on air yards.

The following histogram and boxplot show the distribution of data for short vs long passes

![image](https://github.com/jordankristek/Passing-EPA/assets/150874257/2b81cc00-1325-4dfd-982f-2690a97fdc8d)
![image](https://github.com/jordankristek/Passing-EPA/assets/150874257/d6a7a669-a341-4cea-aae1-f2f7ac56e8da)

The images above show that there is a wider range of EPA outcomes for long passes compared to short passes. This is to be expected, as long passes are considered more "high-risk, high-reward."

Next, I filterd the dataframe to remove any records with less than 30 long passes and less than 100 short passes. After that, I created a new column for Prior Year EPA so that I could find the correlation between seasons for EPA of short and long passes.

![image](https://github.com/jordankristek/Passing-EPA/assets/150874257/f7ce1622-ba1c-40b7-9ab7-2be7e7883af2)
