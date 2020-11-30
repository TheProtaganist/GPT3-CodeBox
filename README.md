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
for the echo section.



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
