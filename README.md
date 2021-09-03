# **Game Introduction**

A Basic version of Rock paper Scissor Made with python. Jupyter notebook is used as the IDE.

# **Game Concept**

Rock paper scissors (also known by other orderings of the three items, with "rock" sometimes being called "stone", or as Rochambeau, roshambo, or ro-sham-bo) is a hand game usually played between two people, in which each player simultaneously forms one of three shapes with an outstretched hand. These shapes are "rock" (a closed fist), "paper" (a flat hand), and "scissors" (a fist with the index finger and middle finger extended, forming a V). "Scissors" is identical to the two-fingered V sign (also indicating "victory" or "peace") except that it is pointed horizontally instead of being held upright in the air.

A simultaneous, zero-sum game, it has only two possible outcomes: a draw, or a win for one player and a loss for the other. A player who decides to play rock will beat another player who has chosen scissors ("rock crushes scissors" or sometimes "blunts scissors"), but will lose to one who has played paper ("paper covers rock"); a play of paper will lose to a play of scissors ("scissors cuts paper"). If both players choose the same shape, the game is tied and is usually immediately replayed to break the tie. The type of game originated in China and spread with increased contact with East Asia, while developing different variants in signs over time.

Rock paper scissors is often used as a fair choosing method between two people, similar to coin flipping, drawing straws, or throwing dice in order to settle a dispute or make an unbiased group decision. Unlike truly random selection methods, however, rock paper scissors can be played with a degree of skill by recognizing and exploiting non-random behavior in opponents

# **Game Name**

The name Rochambeau, sometimes spelled roshambo or ro-sham-bo and used mainly in the Western United States, is widely believed to be a reference to Count Rochambeau, who, according to a widespread legend, played the game during the American Revolutionary War. This legend is clearly untrue as all evidence points to the game first becoming known in the United States no sooner than sometime during the 1930s.It is unclear why exactly this name ended up being associated with the game, with hypotheses ranging from a slight phonetic similarity with the Japanese name jan-ken-pon  to the presence of a statue of Rochambeau in a certain Washington, D.C. neighborhood.

# **Strategies**

It is impossible to gain an advantage over a truly random opponent. However, by exploiting the psychological weaknesses of inherently non-random opponents, it is possible to gain a significant advantage. Indeed, human players tend to be non-random. As a result, there have been programming competitions for algorithms that play rock paper scissors.

During tournaments, players often prepare their sequence of three gestures prior to the tournament's commencement. Some tournament players employ tactics to confuse or trick the other player into making an illegal move, resulting in a loss. One such tactic is to shout the name of one move before throwing another, in order to misdirect and confuse their opponent.

The "rock" move, in particular, is notable in that it is typically represented by a closed fist—often identical to the fist made by players during the initial countdown. If a player is attempting to beat their opponent based on quickly reading their hand gesture as the players are making their moves, it is possible to determine if the opponent is about to throw "rock" based on their lack of hand movement, as both "scissors" and "paper" require the player to reposition their hand. This can likewise be used to deceive an anticipating opponent by keeping one's fist closed until the last possible moment, leading them to believe that you are about to throw "rock".

# **Algorithms**

As a consequence of rock paper scissors programming contests, many strong algorithms have emerged. For example, Iocaine Powder, which won the First International RoShamBo Programming Competition in 1999,uses a heuristically designed compilation of strategies.[33] For each strategy it employs, it also has six metastrategies which defeat second-guessing, triple-guessing, as well as second-guessing the opponent, and so on. The optimal strategy or metastrategy is chosen based on past performance. The main strategies it employs are history matching, frequency analysis, and random guessing. Its strongest strategy, history matching, searches for a sequence in the past that matches the last few moves in order to predict the next move of the algorithm. In frequency analysis, the program simply identifies the most frequently played move. The random guess is a fallback method that is used to prevent a devastating loss in the event that the other strategies fail. There has since been some innovations, such as using multiple history matching schemes that each match a different aspect of the history – for example, the opponent's moves, the program's own moves, or a combination of both. There have also been other algorithms based on Markov chains.

In 2012, researchers from the Ishikawa Watanabe Laboratory at the University of Tokyo created a robot hand that can play rock paper scissors with a 100% win rate against a human opponent. Using a high-speed camera the robot recognizes within one millisecond which shape the human hand is making, then produces the corresponding winning shape.

# **Python Implementation**

While implementing in Python , the most crucial feature to keep in mind is of course the proper placing if all the if else arguments and also using the random function from Numpy library correctly to ensure randomness of the computer selection.

# **End Notes**

So in here we'vae learned how to build a perfect model of Rock paper Scissor gamein python and also learned a bit about the history , algorithms of the game.

Did you find this Readme useful? Do you have any useful trick? Did you use any other method for feature extraction? Feel free to discuss your experiences in comments below or on the discussion portal and we’ll be more than happy to discuss.


