This project is inspired by a recent paper from Williams, Schliep, Fosdick, and Elmore that proposes a novel player evaluation metric called Expected Points Above Average(EPAA) which measures a player's offensove contribution relative to an average NBA team.

The paper can be read here:  https://arxiv.org/html/2405.10453v2

Ultimately, I aim to develop a miniature analytics pipeline inspired by this paper with a few differences worth noting:
1. I'll be using Python and not R (even though R is an amazing language in my opinion)
2. I will only use the last 3-4 seasons because... I think it's more managable, only using more recent data is likely to be less sensitive to how the NBA's rules, policies, and methods change over time, and I believe that is still a sufficient amount of data for inferrence.
3. I intend to use Hamilitonian Monte Carlo instead of Gibbs sampling which is used in the paper to see if there are any meaningful differences between the two methods.
4. I may use simpler ways of clustering and modeling at first just to get accustomed to the whole idea to begin with.

