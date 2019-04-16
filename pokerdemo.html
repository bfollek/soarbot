<html>
<head>
<title>Poker Demo</title>
<meta name="robots" content="noindex,nofollow">
<link rel=stylesheet href="codeblitz.css" type="text/css">
</head>

<body>
Bob Follek<br>
<a href="mailto:bfollek@gmail.com">bfollek@gmail.com</a><br>
Thesis I, Fall 2002<br>
<center><h2>Poker Demo</h2></center><br>

<h4>Poker Log</h4>
<pre>
--- NEW GAME --- 536349 ---
 > RutnBot        71346
B> Pokibrat-4     40162
 > thetwo         -988
 > Pokibrat       62206
 > AKA            -514
 > Pokibot-3      146914
 > SoarBot03      -221
 > badvibes       1615
 > Pokibot        159518
-----------------------
     SoarBot03:   Ts Tc
thetwo blinds $5
Pokibrat blinds $10
AKA folds
Pokibot-3 folds
SoarBot03 raises $10
badvibes folds
Pokibot folds
RutnBot folds
Pokibrat-4 calls $20
thetwo folds
Pokibrat folds

 * FLOP:   7d 9s Jh
SoarBot03 checks
Pokibrat-4 bets $10
SoarBot03 calls $10

 * TURN:   7d 9s Jh 4c
SoarBot03 checks
Pokibrat-4 bets $20
SoarBot03 calls $20

 * RIVER:  7d 9s Jh 4c 9h
SoarBot03 checks
Pokibrat-4 bets $20
SoarBot03 calls $20
     Pokibrat-4:   Th Ks
     SoarBot03:   Ts Tc
SoarBot03 wins $155 with Two Pair, Tens and Nines
</pre>

<h4>Soar Log</h4>
<pre>
=============================================================
NEW GAME 536349 @ Tue Nov 19 07:37:43 EST 2002
=============================================================
=============================================================
NEW STAGE preflop (536349) @ Tue Nov 19 07:37:43 EST 2002
=============================================================

analysis == pair
analysis == high-pair
analysis == pair-in-hole
   434:    O: O699 (preflop)
      :    ==>S: S140 (operator no-change)
   436:       O: O704 (preflop*bet-raise*excellent-cards)
best-hand-probability == 0
bet-size == 10
bet-timing == middle
bets-to-call == 1.
bluff == no
check-raise-used == no
num-bets == 1
pot-odds == 1.5
stage == preflop
unacted == 5
bet.action == raise
preflop-strength == 2
debug {pokerIo}: Setting g_betAction to raise @ clock == 159
=============================================================
NEW STAGE flop (536349) @ Tue Nov 19 07:37:44 EST 2002
=============================================================

analysis == 3-straight-on-board
analysis == pair
analysis == high-pair
analysis == pair-in-hole
analysis == inside-straight
   437:    O: O705 (flop)
      :    ==>S: S141 (operator no-change)
   439:       O: O714 (flop*call*1-player)
best-hand-probability == 0.84
bet-size == 10
bet-timing == middle
bets-to-call == 0.
bluff == no
check-raise-used == no
num-bets == 0
pot-odds == 9999
stage == flop
unacted == 2
bet.action == call
flop-strength == 6
flop-strength == 7
debug {pokerIo}: Setting g_betAction to call @ clock == 160

   440:       O: O717 (flop*call*1-player)
best-hand-probability == 0.84
bet-size == 10
bet-timing == middle
bets-to-call == 1.
bluff == no
check-raise-used == no
num-bets == 1
pot-odds == 6.5
stage == flop
unacted == 0
bet.action == call
flop-strength == 6
flop-strength == 7
debug {pokerIo}: Setting g_betAction to call @ clock == 161
</pre>

<h4>Soar Productions</h4>

<pre>
sp  {preflop*elaborate*preflop-strength*strong-pairs
    (state &lt;s&gt; ^name preflop
               ^io.input-link.game &lt;g&gt;)
    (&lt;g&gt; ^card &lt;hc1&gt;
         ^card &lt;hc2&gt;)
    (&lt;hc1&gt; ^type hole ^num 1 ^rank { &lt;&lt; k q j t &gt;&gt; &lt;r1&gt; })
    (&lt;hc2&gt; ^type hole ^num 2 ^rank &lt;r1&gt;)
--&gt;
    (&lt;g&gt; ^preflop-strength 2)
}
</pre>
<hr>
<pre>
sp  {preflop*propose*bet-raise*excellent-cards
    (state &lt;s&gt; ^name preflop
               ^io &lt;io&gt;)
    (&lt;io&gt; ^input-link &lt;il&gt;
          ^output-link &lt;ol&gt;)
    (&lt;il&gt; ^clock &lt;cl&gt;
          ^game &lt;g&gt;)
    (&lt;g&gt; ^num-bets &lt;= 1
         ^preflop-strength &lt;= 2)
--&gt;
    (&lt;s&gt; ^operator &lt;o&gt; +)
    (&lt;o&gt; ^name preflop*bet-raise*excellent-cards
         ^bet.action raise
         ^score 30)
}  
</pre>
<hr>
<pre>
# --------------------------------------------------------------------
# call proposal - Against just 1 player, stay in with almost anything.
# This will help in cases where we're heads-up on the flop, and we're
# getting driven out. This won't cost us more than 1 bet.
# --------------------------------------------------------------------

sp  {flop*propose*call*1-player
    (state &lt;s&gt; ^name flop
               ^io &lt;io&gt;)
    (&lt;io&gt; ^input-link &lt;il&gt;
          ^output-link &lt;ol&gt;)
    (&lt;il&gt; ^clock &lt;cl&gt;
          ^game &lt;g&gt;)
    (&lt;g&gt; ^num-active-players 2
         ^flop-strength &lt;= 7)
--&gt;
    (&lt;s&gt; ^operator &lt;o&gt; +)
    (&lt;o&gt; ^name flop*call*1-player
         ^bet.action call
         ^score 20)
}   
</pre>
</body>