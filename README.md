# <div align="center"> **How the Beatles' Music Changed Over the Years**
## <div align="center"> A Text Analysis of Beatles Lyrics

### <div align="right"> *By John Cox*


# The Motivation Behind this Analysis

One thing that Beatles' fans agree on is that the Beatles' music changed over the years.  Their earlier music is significantly different from their later music, with a distinction usually drawn at the album 'Revolver'--the first album the Beatles created after their touring years ended.  From Revolver on, the Beatles' music became much more experimental and had large influence over the direction of the music industry.  The Beatles early music, which was immensely popular and brought the band to fame, had a similar style to other popular rock music of the 50's and early 60's.  On the other side, each album in the Beatles later years was unique in that each covered different genres of music --some which were just being invented, and each had its own distinct style.  If you are unfimiliar with the Beatles and want to know a glimpse of what I am talking about, listen to these two songs and guess which one was from the early and late Beatles https://www.youtube.com/watch?v=v1HDt1tknTc and https://www.youtube.com/watch?v=usNsCeOV4GM (hint, the latter is late).  

What I wanted to test in this project is whether there is a noticable difference between early Beatles' lyrics and late Beatles' lyrics.  My inclination is that there is more lyrical complexity in the later Beatles' music, but only the data can reveal the truth.  

What this project is **not** testing is which Beatles music is better or more advanced.  This analysis is staying within the scope of just the lyrics and trends in lyrical complexity over time.  What I am missing in this analysis is data on anything outside of the lyrics.  It would be unfair to say that music is defined solely by its lyrics, much of what people love about music is the melodies, harmonies, and rhythms.  Therefore this project can only answer questions that pertain to the lyrics.

# The Stucture of this Project

For this project I decided the best way to present my findings is through a Jupyter Notebook blog-style post.  This structure allows me to be transparent with the methods I use and makes my analysis easily repeatable.  If you are reading this and want to replicate my findings or add to them, you can reach the full project's repository with this link https://github.com/jcox22/Beatles-Text-Analysis.  The entirety of this analysis is done through Python code.

I broke down this project into five distinct section to help readability:


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   **1) The Dataset.**  This section introduces the dataset that was used for this project and where it was sourced from, along with the data cleaning and manipulation that was needed to perform meaningful analysis.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **2.) Exploring Trends in the Data.**  This section plots and analyzes the variables of interest to test my hypothesis. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **3.) Are These Trends Unique to the Songwriter?**  This section tests to see if the trends are caused by a specific songwriter --John, Paul, George, or Ringo.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **4.) Comparing the Beatles to Other 60's Bands**  This section compares the results of the Beatles analysis to other rival 60's artists.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  **5.) Trends in Word Usage**  This section looks at trends in specific word usage of Beatles' lyrics over time.
