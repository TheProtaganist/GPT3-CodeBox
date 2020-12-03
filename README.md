# GPT3-CodeBox
A code generation tool using OpenAI's new GPT3 language model 
To use is pretty straight foward simply download the main_application 
folder and run the one of the 3 py flies and make sure to provide a open ai api key
you can get at https://beta.openai.com. The app won't work without a key.

# Code Box Generator 
This is the most basic out of the 3 to use simply enter a prompt 
and make sure the values entered for frequency penalty, presence penalty
and top probability are below 1. Tokens have to be at least less then 650
otherwise the model will return an error. For log probability and best of 
parameters I would recommend to play around with but keep the values low.
You also get the option to echo back the completion if a even number is entered
for the echo section although I recommend entering a odd number since 
it will avoid errors later on but the file will still generated even if some errors happen.

# Code Box Chaos
This is a special tool becuase it uses the butterfly effect
also known as "Chaos" when processing the values. Every value entered will
be affected by every other value although log probality, tokens, best of, and 
the prompt remain the same.

# Code Box
This is the same as the previous one except the values are now
made smaller which leads to less errors. If you want to enter custom values
just use the Code Box generator otherwise if you want to mess with chaos and
see how the model responds to different outcomes choose this option.

# Parameters used

1.	prompt: The intention you wish to give the model and it will generate a code once you've entered all the values correctly

2.	max_tokens: The max tokens (words) you wish to generate (keep between 10 and 650)

3.	top_p: A number called nucleus sampling, where the model considers the results of the tokens with top_p probability mass. So, 0.5 means only the tokens comprising the top 50% probability mass are considered. 

4.	logprobs: An value that tells the API to include log probabilities on the most likely tokens and chosen tokens.

5.	echo: A boolean value that tells the API to echo back the prompt along with the completion

6.	presence penalty: A number between 0 and 1 (default 0) that penalizes new tokens based on whether they appear in the text so far. This increases the model's likelihood to talk about new topics.

7.	frequency penalty: A number between 0 and 1 (default 0) that penalizes new tokens based on their existing frequency in the text so far. This decreases the model's likelihood to repeat the same line verbatim. NOTE: highly recommend but keep between 0 and 1

8.	best_of: An integer that tells the API to only return the "best" of n completions (the one with the lowest log probability per token). 

# Install needed modules
pip install -r requirements.txt

or you can just open the requirements.txt and install each module one by one.

if tkinter not installed run command prompt and pip install tk (comes installed by defualt)

When generating files in the main_application is normal for the program to freeze. DO NOT EXIT UNLESS THE PROGRAM GAVE YOU A RESULT OR ERROR!!! Note: ALL values most be entered or it will crash.

If all fails try using the code_box.py and set values as low as you can...
