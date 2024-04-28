# Introduction

LearnGPT is a free project, created by ShadowRocket227, for helping students at middle school level in studyng, searching and generally, learning.
LearnGPT is a customized prompt for the web extension "WebChatGPT": you can use this prompt searching his name in the "1-click prompts" sector on chat.openai.com, after
the extension installation.

The only requirment is the extension, downloadble for any modern browser like Chrome, Edge and Firefox, from their official stores.

Why LearnGPT is better then ChatGPT ? For a lot of reasons:

-It can search on the web.
-It use the informations taken on the internet for checking the generated contents.
-It leave a complete source mapping, for checking the web pages visited by ChatGPT.
-Is focus on the school, so he can adapt to various subjects and topic using the most correct vocabulary, tone, writing style etc. based on the selected subject.
-You can customize a lot of options, like banned web addresses, writing style and output language, directly from the prompt bar of WebChatGPT, after selecting the prompt.

And so on.

You can find the raw prompt in the "LearnGPT-prompt.md" file. 

DISCLAIMER: DON'T USE THE PROMPTS CONTAINED ON BRANCH "dev". THEY ARE BETA PROMPTS AND IS NOT GURANTEED A SMOOTH EXECUTION AND EXPERIENCE. ONLY LOOK ON BRANCH "main".

Have fun...and don't forget your homework !

# Requirments

1) Modern browser, like:

    -Google Chrome
    -Mozilla Firefox
    -Microsoft Edge
    -Opera
    -Brave

2) WebChatGPT official extension. If you use Google Chrome, you can download it from
   https://chromewebstore.google.com/detail/webchatgpt-chatgpt-con-ac/lpfemeioodjbpieminkklglpmhlngfcn. For any other browser, you can easily find the product searching "WebChatGPT".

# User instructions

To use in the most efficient way the prompt, you should follow thes guidelines:

1) The prompt has a space called "Blocked", in the input bar. Here you can insert all the web URLs that you don't want are used by    LearnGPT for his responses. You have to write the banned addresses separated by a ";", like this:

    www.facebook.com; www.tikok.com; www.wikipedia.org

IMPORTANT: THE ADDRESSES PROVIDED HERE ARE ONLY EXAMPLES FOR EXPLAINING HOW THE PROMPT WORKS.

2) Always insert clearly the subject and the topic that you want to search with LearnGPT. You have these two informations in the spaces in the prompt windows, called "Subject" and "Topic".

3) If the LearnGPT output isn't good for you and you want to fastly say "Do this again, but in a better way.", you can type in the chat (after the first LearnGPT response) the keyword "/REDO". This command will force LearnGPT to follow your guidelines and make his work better. If the answer still hasn't the desired quality, just perform a new chat with LearnGPT and explain better the task.


# General ChatGPT tips

In general, always remeber that you're talking to an AI, so avoid complex language and expressions, always be clear and don't include useless terms like "Please, do...", "Can you please..." and also exclude direct questions. This's becuase ChatGPT works better with "commands": at example, if you want to know how to say a "hi" in spanish, don't type "How can i say hi in spanish ?" but instead say "Tell me how to say hi in spanish."

Onother good habit is to use delimiters. At example, if you want a translations of a text, you can write your request like this:

"Translate he following text in spanish:"

(Avoid type the marks here, i used them to separate my text from the example).

As you can see, i typed a command request, not a question, and i also inserted the ":" charachter; this helps ChatGPT to recognize that the text before the ":" is your request, and after the ":" there's the text
that ChatGPT actually has to translate.

Talkig about this, another good action is to use some characters to "contain" the text. If you have to include a second text after your request, you can use determinate character to say "My secondary text starts here and ends there". 

Here at example, to divide better the text to translate to our request we can use delimiters like marks (""), brackets (like "[]" and the "{}". I don't reccomed using the round brackets, becuase ChatGPT usually confuse them with the actual text) and other characters at your own choice. In my opinion, the best characters are simple marks (""), but sometimes you will want to insert them in the text; in that case, you can use the "<>". These ones are really good, becuase the various languages usually don't have this letters in their vocabulary and ChatGPT will automatically detect them as text delimiters.

Your delimiters are your choice, select them basing on the situation, if you need to insert a character in the text or something else.
