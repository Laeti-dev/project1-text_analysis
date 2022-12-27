# project1-text_analysis
First Matrice project : analyse a simple text and present the outcome with simple terms 

![jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
using matplotlib & wordcloud


In the event of COP27, I wanted to analyse a text on the topic of environment. Remembering Greta Tunberg's direct speeches, I found interesting to analyse words frequencies and make a wordcloud out of it. Then compare 'How dare you' speech, happening in 2019 at the U.N.'s Climate Action Summit and the 'Blah blah blah' speech made two years later in Milan, few month before COP26.

After getting rid of unwanted spaces and punctuation, words were uniformed (lower case), then stored in a list without stop words (keeping 'we', 'you', 'i', 'our', 'your' for the analysis).

Finally, a function taking this list of tokens as a parameter was counting all words frequencies, stores as key-value in a dictionnary.

As a visual support, the data were presented in a horizontal histogram. Different colors were used to separate frequencies as themes seemed to appear within each group.

![How dare you Speech top_25 words](https://github.com/Laeti-dev/project1-text_analysis/blob/master/figures/top_25_dare.png)
![Blah blah blah speech top_25 words](https://github.com/Laeti-dev/project1-text_analysis/blob/master/figures/top_25_blah.png)

In the fun of testing visual support, comparison of the two speeches with simple wordcloud gave us :

![How dare you Speech wordcloud](https://github.com/Laeti-dev/project1-text_analysis/blob/master/figures/dare_wordcloud.png)
![Blah blah blah speech wordcloud](https://github.com/Laeti-dev/project1-text_analysis/blob/master/figures/blah_wordcloud.png)

And to go further, we could play with wordcloud masks :
![How dare you Speech wordcloud world mask](https://github.com/Laeti-dev/project1-text_analysis/blob/master/figures/dare_mask_wordcloud.png)
![Blah blah blah speech wordcloud world mask](https://github.com/Laeti-dev/project1-text_analysis/blob/master/figures/blah_mask_wordcloud.png)
