# 42_Hive-Wordle_rush
A quick project creating an interacting solver of the popular online game 'Worldle', using bash scripting

This was a project focused on discovering the use cases of bash scripting and how some logic could be applied to help solve the 'Wordle' game.

It uses the basic logic of initially founding words that have letters that occur in a lot of words in the english language, in the hopes of eliminating as many words as possible in the first few guesses. Then randomly choosing words out of the remaining to further narrow down choices.

This logics success rate is rather high but it fails to handle the edge case of letters appearing in multiple places in the chosen word of the day but not in the correct order. Subsequently, words may be elimanted from possibly being chosen and the word may not be found.

Have fun checkingit out by running the script.
