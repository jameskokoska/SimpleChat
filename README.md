# SimpleChat
* Uses the Wikipedia library and basic English understanding to give an appropriate answer to a question
## Goal
* Create a straightforward natural understanding program to answer simple questions with some logic
## Features
* Can answer simple questions
* Can determine whether to search for an answer on Wikipedia
* Identify the subject of a basic question, and incorporate it into an answer
* Answer a simple question with a mix of English and mathematical symbols
* Easily add responses into a list, based on the context of a question asked
## Example Questions
* What is five plus 5 times thirty six? `(5)+(5)×(30+6)=185`
* Can you flip a coin? `I choose heads.`
* Choose me or you? `I choose the second: you.`
* What is an elephant? `Elephants are mammals of the family Elephantidae and the largest existing land animals.`
* How are you? `Excellent.`
## Usage
* Ensure the Wikipedia and PyDictionary libraries are installed (via pip)
## Adding responses
* Use the `questions` list and add responses within
* First 2 elements of the list can be 'keywords' (Start entry with `kw`)
* Example usage: `["kwhello", "response1", "response2",...]` -> since no space between kw and the keyword, then hello must be the first word in the question in order to return a random result from the remaining elements in the list
* Example usage: `["kw hello", "response1", "response2",...]` -> since space between kw and the keyword, then hello can be anywhere within the question in order to return a random result from the remaining elements in the list
