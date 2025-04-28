# cs61a-project-0--magic-the-lambda-ing-solved
**TO GET THIS SOLUTION VISIT:** [CS61A Project 0- Magic: the Lambda-ing Solved](https://www.ankitcodinghub.com/product/cs61a-project-0-extra-credit-magic-the-lambda-ing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119686&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS61A  Project 0- Magic: the Lambda-ing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
But it does have this!

Introduction

Download starter files

To get started, download all of the project code as a zip archive.

About the Game

In this project, we will be implementing a card game! This game is inspired by the similarly named Magic: The Gathering.

Rules of the Game

This game is a little involved, though not nearly as much as its namesake. Here’s how it goes:

There are two players. Each player has a hand of cards and a deck, and at the start of each round, each player draws a random card from their deck. If a player’s deck is empty when they try to draw, they will automatically lose the game.

Cards have a name, an attack value, and a defense value. Each round, each player chooses one card to play from their own hands. Once both players have chosen a card, the cards’ power stats are then calculated and compared. The card with the higher power wins the round. Each played card’s power value is calculated as follows:

py (player card’s attack) – (opponent card’s defense)

For example, let’s say Player 1 plays a card with 2000 attack and 1000 defense and Player 2 plays a card with 1500 attack and 3000 defense. Their cards’ powers are calculated as:

py P1: 2000 – 3000 = 2000 – 3000 = -1000 P2: 1500 – 1000 = 1500 – 1000 = 500

So Player 2 would win this round.

The first player to win 8 rounds wins the match!

Special Effects

An AI card will allow you to add the top two cards of your deck to your hand via drawing.

This game uses several different files.

Code for all questions can be found in classes.py.

The game loop can be found in cardgame.py, and is responsible for running the game. You won’t need to open or read this file to receive full credit.

Once you’ve implemented the game, you can start it by typing:

py python3 cardgame.py

While playing the game, you can exit it and return to the command line with Ctrl-C or Ctrl-D.

Feel free to refer back to these series of rules later on, and let’s start making the game!

Logistics

The project is worth 2 extra credit points based on correctness.

You will turn in the following files:

classes.py

You do not need to modify or turn in any other files to complete the project. To submit the project, run the following command:

py python3 ok –submit

You will be able to view your submissions on the Ok dashboard.

Throughout this project, you should be testing the correctness of your code. It is good practice to test often, so that it is easy to isolate any problems. However, you should not be testing too often, to allow yourself time to think through problems.

We have provided an autograder called ok to help you with testing your code and tracking your progress. The first time you run the autograder, you will be asked to log in with your Ok account using your web browser. Please do so. Each time you run ok, it will back up your work and progress on our servers.

The primary purpose of ok is to test your implementations.

We recommend that you submit after you finish each problem. Only your last submission will be graded. It is also useful for us to have more backups of your code in case you run into a submission issue. If you forget to submit, your last backup will be automatically converted to a submission.

If you do not want us to record a backup of your work or information about your progress, you can run

py python3 ok –local

With this option, no information will be sent to our course servers. If you want to test your code interactively, you can run

py python3 ok -q [question number] -i

with the appropriate question number (e.g. 01) inserted. This will run the tests for that question until the first one you failed, then give you a chance to test the functions you wrote interactively.

You can also use the debugging print feature in OK by writing

py print(“DEBUG:”, x) which will produce an output in your terminal without causing OK tests to fail with extra output.

Part 1: Basic Game

Before attempting any of the following questions, be sure to look at the Deck class included at the bottom of classes.py. A central mechanic of the game is manipulating the player’s deck of available cards; many methods of the Deck class will prove to be useful throughout the project.

Q1: Making Cards

To play a card game, we’re going to need to have cards, so let’s make some! We’re gonna implement the basics of the Card class first.

First, implement the Card class constructor in classes.py. This constructor takes three arguments:

a string as the name of the card an integer as the attack value of the card an integer as the defense value of the card Each Card instance should keep track of these values using instance attributes called name, attack, and defense.

You should also implement the power method in Card, which takes in another card as an input and calculates the current card’s power. Refer to the Rules of the Game if you’d like a refresher on how power is calculated.

Use Ok to test your code: py python3 ok -q Card.__init__ python3 ok -q Card.power

For this mini-project, we provide doctests to incrementally test your code; note that the Part 1’s questions will be considered together under a different ok test, which is included at the end of the section.

Q2: Making a Player

Now that we have cards, we can make a deck, but we still need players to actually use them. We’ll now fill in the implementation of the Player class.

A Player instance has three instance attributes:

name is the player’s name. When you play the game, you can enter your name, which will be converted into a string to be passed to the constructor.

deck is an instance of the Deck class. You can draw from it using its .draw() method.

hand is a list of Card instances. Each player should start with 5 cards in their hand, drawn from their deck. Each card in the hand can be selected by its index in the list during the game. When a player draws a new card from the deck, it is added to the end of this list. Complete the implementation of the constructor for Player so that self.hand is set to a list of 5 cards drawn from the player’s deck.

Next, implement the draw and play methods in the Player class. The draw method draws a card from the deck and adds it to the player’s hand. The play method removes and returns a card from the player’s hand at the given index.

Hint: use class methods wherever possible when attempting to draw from the deck when implementing Player.__init__ and Player.draw.

Use Ok to test your code: py python3 ok -q Player.__init__ python3 ok -q Player.draw python3 ok -q Player.play

For this mini-project, we provide doctests to incrementally test your code; note that the Part 1’s questions will be considered together under a different ok test, which is included at the end of the section.

After you complete this problem, you have finished Part 1, and you’ll be able to play a working version of the game!

Use Ok to test your code:

py python3 ok -q 01

Additionally, type:

py python3 cardgame.py to start a game of Magic: The Lambda-ing!

This version doesn’t have the effects for different cards yet. In the next part, we’ll be implementing effects for the various cards.

Part 2: Card Effects

To make the card game more interesting, let’s add effects to our cards! We can do this by implementing an effect function for each card class, which takes in the opponent card, the current player, and the opponent player.

You can find the following questions in classes.py.

Important: For the following sections, do not overwrite any lines denoted under You should add your implementation above this. In addition, there are pre-designated variables in certain effect methods which are used to determine when to print text. Be sure to set the variables to the correct values in your implementation, such that the text is printed when the effect occurs.

Q3: AIs: Resourceful Resources

In the AICard class, implement the effect method for AIs. An AICard will allow you to add the top two cards of your deck to your hand via drawing from your deck.

Use Ok to test your code:

py python3 ok -q AICard.effect

For this mini-project, we provide doctests to incrementally test your code; note that the Part 2’s questions will be considered together under a different ok test, which is included at the end of the section.

Use Ok to test your code:

py python3 ok -q TutorCard.effect

For this mini-project, we provide doctests to incrementally test your code; note that the Part 2’s questions will be considered together under a different ok test, which is included at the end of the section.

Q5: TAs: Power Transfer

In the TACard class, implement the effect method for TAs. A TACard discards the card with the highest power in your hand, and add the discarded card’s attack and defense to its own respective stats. Discarding a card removes the card from your hand. If there are no cards in hand, the TACard should not do anything for its effect.

Use Ok to test your code:

py python3 ok -q TACard.effect

For this mini-project, we provide doctests to incrementally test your code; note that the Part 2’s questions will be considered together under a different ok test, which is included at the end of the section.

To implement the “survive” functionality, the InstructorCard should re-add itself to the player’s hand.

Use Ok to test your code: py python3 ok -q InstructorCard.effect

For this mini-project, we provide doctests to incrementally test your code; note that the Part 2’s questions will be considered together under a different ok test, which is included at the end of the section.

After you complete this problem, you’ll have a fully functional game of Magic: The Lambda-ing!

Use Ok to test your code:

py python3 ok -q 02

Additionally, type:

py python3 cardgame.py to start a game.

This doesn’t have to be the end, though; we encourage you to get creative with more card types, effects, and even adding more custom cards to your deck!

Submit

Make sure to submit this assignment by running:

py python3 ok –submit
