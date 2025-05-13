# cpl-project-1-pro-wordle-solved
**TO GET THIS SOLUTION VISIT:** [CPL Project 1-Pro-Wordle Solved](https://www.ankitcodinghub.com/product/cpl-project-1-pro-wordle-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94225&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CPL Project 1-Pro-Wordle Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

In this Project you are going to implement a modified version of the game Wordle 1 in Prolog (Pro-Wordle). The Pro-Wordle game is made up of two main phases:

(1) a knowledge base building phase and (2) a game play phase.

In the KB building phase, the player is prompted to enter words with their categories. Corresponding facts are added to the KB using the predicate word/2 where word(W,C) is true if W has a category of C. This continues until the player enters done. Below is a sample of the interaction between the game and the player in the KB building phase.

<pre>             Welcome to Pro-Wordle!
             ----------------------
</pre>
<pre>             Please enter a word and its category on separate lines:
             |: horse.
             |: animals.
             Please enter a word and its category on separate lines:
             |: panda.
</pre>
<pre>             |: animals.
              Please enter a word and its category on separate lines:
</pre>
<pre>             |: hello.
             |: greetings.
             Please enter a word and its category on separate lines:
             |: banana.
             |: fruits.
             Please enter a word and its category on separate lines:
             |: bison.
             |: animals.
             Please enter a word and its category on separate lines:
             |: hoard.
             |: collections.
             Please enter a word and its category on separate lines:
             |: done.
</pre>
<pre>             Done building the words database...
</pre>
In the example above, the following Prolog KB will be constructed.

1Check out the game here: https://www.nytimes.com/games/wordle/index.html 1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<pre>        word(horse,animals).
        word(panda,animals).
        word(hello,greetings).
        word(banana,fruits).
        word(bison,animals).
        word(hoard,collections).
</pre>
After the KB building phase, the game play phase begins. The game displays to the user the available categories to pick one from. The player is then prompted to pick a length and category for the word to be guessed. The game picks a word of the given length and category and the guessing game begins. The player is allowed a maximum number of guesses equal to the entered length plus one. In each guess, the user must enter a word of the chosen length. The game then displays to the user the correctly entered letters (not necessarily in correct positions), and the correctly entered letters in correct positions. Below is a sample of the interaction between the game and the player in the game play phase based on the example KB provided earlier.

<pre>        The available categories are: [animals,greetings,fruits, collections]
        Choose a category:
        |: animals.
        Choose a length:
</pre>
<pre>        |: 9.
        There are no words of this length.
        Choose a length:
        |: 5.
        Game started. You have 6 guesses.
</pre>
<pre>        Enter a word composed of 5 letters:
        |: hello.
        Correct letters are: [h,e,o]
        Correct letters in correct positions are: [h]
        Remaining Guesses are 5
</pre>
<pre>        Enter a word composed of 5 letters:
        |: hell.
        Word is not composed of 5 letters. Try again.
        Remaining Guesses are 5
</pre>
<pre>        Enter a word composed of 5 letters:
        |: hoard.
        Correct letters are: [h,o,r]
        Correct letters in correct positions are: [h,o]
        Remaining Guesses are 4
</pre>
<pre>        Enter a word composed of 5 letters:
        |: horse.
        You Won!
</pre>
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Here is another sample where the player loses.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>The available categories are: [animals,greetings,fruits,collections]
Choose a category:
|: things.
This category does not exist.
</pre>
<pre>Choose a category:
|: animals.
</pre>
<pre>Choose a length:
|: 5.
Game started. You have 6 guesses.
</pre>
<pre>Enter a word composed of 5 letters:
|: bison.
Correct letters are: [s,o]
Correct letters in correct positions are: []
Remaining Guesses are 5
</pre>
<pre>Enter a word composed of 5 letters:
|: bison.
Correct letters are: [s,o]
Correct letters in correct positions are: []
Remaining Guesses are 4
</pre>
<pre> Enter a word composed of 5 letters:
|: bison.
Correct letters are: [s,o]
Correct letters in correct positions are: []
Remaining Guesses are 3
</pre>
<pre> Enter a word composed of 5 letters:
|: bison.
Correct letters are: [s,o]
Correct letters in correct positions are: []
Remaining Guesses are 2
</pre>
<pre> Enter a word composed of 5 letters:
|: bison.
Correct letters are: [s,o]
Correct letters in correct positions are: []
Remaining Guesses are 1
</pre>
<pre> Enter a word composed of 5 letters:
|: bison.
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
You lost!

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Your implementation must contain the below predicates. You are allowed to use any other helper predicates if needed. All the examples given below are according to the KB at the beginning of Page 2.

<ul>
<li>is_category(C): succeeds if C is an available category in the KB. Examples:
<pre>            ?- is_category(animals).
            true.
</pre>
<pre>            ?- is_category(C).
            C= animals;
            C= animals;
            C= greetings;
</pre>
<pre>            C= fruits;
            C= animals;
            C= collections.
</pre>
</li>
<li>categories(L): succeeds if L is a list containing all the available categories without duplicates.

Examples:

<pre>            ?- categories(L).
            L=[animals,greetings,fruits,collections]
</pre>
</li>
<li>available_length(L): succeeds if there are words in the KB with length L. Examples:
<pre>            ?- available_length(5).
            true.
</pre>
</li>
<li>pick_word(W,L,C): succeeds if W is a word in the KB with length L and category C.
Examples:

<pre>            ?- pick_word(W,5,animals).
               W=horse;
</pre>
<pre>               W=panda;
               W=bison.
</pre>
</li>
<li>correct_letters(L1,L2,CL): succeeds if CL is a list containing the letters in both L1 and L2.

Examples:

<pre>            ?- correct_letters([h,e,l,l,o],[h,o,r,s,e],CL).
            CL=[h,o,e];
            false.
</pre>
4
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
• correct_positions(L1,L2,PL): succeeds if PL is a list containing the letters that occur in both L1 and L2 in the same positions.

Examples:

<pre>                 ?- correct_positions([h,e,l,l,o],[h,o,r,s,e],CP).
                 CP=[h];
                 false.
</pre>
<ul>
<li>build_kb: reponsible of the KB building phase as described above.</li>
<li>play: responsible of the game play phase as described above.</li>
<li>main: the main predicate that will be queried to initiate the KB building phase then the game play phase.
2. Teams. You are allowed to work in teams of four members. You must stick to the teams submitted in the team submission form. IDs for the submitted teams are posted on the CMS.

3. Report. You should submit a short report with your code containing a brief description of the implemented predicates and screenshots of two different runs of the game. The two runs must show the KB building phase. One run should show a winning scenario in the game play phase, and the other should show a losing scenario in the game play phase. The two runs must be different from the two runs shown in this description.

4. Deliverables. You should submit a single .pl file named with your team ID, and a single .pdf file with your report also named with your team ID. The submission link will be posted on the CMS prior to the submission.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
