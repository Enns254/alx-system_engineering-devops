Regular Expression

This project contains tasks for learning about regular expressions using the Oniguruma library with ruby.

Tasks To Complete

 0. Simply matching School
0-simply_match_school.rb contains a Ruby script that scans the first argument for texts that match only School.

 1. Repetition Token #0
1-repetition_token_0.rb contains a Ruby script that scans the first argument for texts that match hbttn, and there has to be a minimum of 2 adjacent t's and a maximum of 5 adjacent t's.

 2. Repetition Token #1
2-repetition_token_1.rb contains a Ruby script that scans the first argument for texts that match hbtn but the b is optional.

 3. Repetition Token #2
3-repetition_token_2.rb contains a Ruby script that scans the first argument for texts that match hbtn and there can be as many adjacent t's as possible but there must be at least one t between b and n.

 4. Repetition Token #3
4-repetition_token_3.rb contains a Ruby script that scans the first argument for texts that match hbtn but the t is optional and there can be as many adjacent t's as possible.

 5. Not quite HBTN yet
5-beginning_and_end.rb contains a Ruby script that scans the first argument for a full match of a text that starts with h ends with n and can have any single character in between.

 6. Call me maybe
6-phone_number.rb contains a Ruby script that scans the first argument for a full match of a 10 digit phone number.

 7. OMG WHY ARE YOU SHOUTING?
7-OMG_WHY_ARE_YOU_SHOUTING.rb contains a Ruby script that scans the first argument for texts that match CAPITAL LETTERS.

 8. Textme
100-simply_match_school.rb contains a Ruby script that scans the first argument, which should be a line of a TextMe app text message transaction, and extracts the sender, receiver, and the flags that were used. Samples of text message transactions are shown below.

Feb 1 11:00:00 ip-10-0-0-11 mdr: 2016-02-01 11:00:00 Receive SMS [SMSC:SYBASE1] [SVC:] [ACT:] [BINF:] [FID:] [from:Google] [to:+16474951758] [flags:-1:0:-1:0:-1] [msg:127:This planet has - or rather had - a problem, which was this: most of the people on it were unhappy for pretty much of the time.] [udh:0:]
Feb 1 11:00:00 ip-10-0-64-10 mdr: 2016-02-01 11:00:00 Receive SMS [SMSC:SYBASE2] [SVC:] [ACT:] [BINF:] [FID:] [from:+17272713208] [to:+19172319348] [flags:-1:0:-1:0:-1] [msg:136:Orbiting this at a distance of roughly ninety-two million miles is an utterly insignificant little blue green planet whose ape-descended] [udh:0:]
Feb 1 11:00:00 ip-10-0-64-11 mdr: 2016-02-01 11:00:00 Sent SMS [SMSC:SYBASE1] [SVC:backendtextme] [ACT:] [BINF:] [FID:] [from:18572406905] [to:14022180266] [flags:-1:0:-1:-1:-1] [msg:136:Far out in the uncharted backwaters of the unfashionable end of the western spiral arm of the Galaxy lies a small unregarded yellow sun.] [udh:0:]
