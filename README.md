# Arabic Support For Unity
This plugin allows you to use accurate and correct Arabic text in your game or 3D application. Supports Tashkeel and Hindu numbers. Supports 4 Persian Characters.

Assalamu Alaikum! (Peace upon you all!)
This asset will enable you to use Arabic Words in your game with no problems. 
There are two main problems to address here:
1.	Arabic Letters orders. It's like reading "Hello" as "olleH".
السلام  is displayed as:  م ا ل س ل ا
2.	Arabic Letters connectivity. As seen here: “السلام  is displayed as:  م ا ل س ل ا” the letters are no disconnected.

# Notes
1.	You'll need to use a font that got Arabic letters in it.
2.	You'll need to modify the text attribute through script. This does not fix the problem if you write directly in a text field.
3.	The script is written in C#.

# Steps
1.	To use the Unity Arabic Support asset inside a script, use: "using ArabicSupport;"
2.	After using the using statement, use the following method (returns a string):	ArabicFixer.Fix(textToBeFixed);
3.	And you're done! You can use the alternative: ArabicFixer(string, tashkeel, hindoNumbers) for more customization options.

# Extras
1.	You can now show Harakat such as ًٌٍَُِ~ّْ using the plugin. Also, you have option to remove the Harakat realtime by setting the plugin to ignore the Harakat by using the ShowHarakat() HideHarakat() Methods. Please note that not all fonts support the Harakat well. Arial font and Arabic Typesetting font were tested and words well. The default is to show the Harakat.
2.	You can now use hindu numbers instead of the default of the font if needed. (٠	١	٢	٣	٤	٥	٦	٧	٨	٩) Use the UseHinduNumbers() and UseDeafultNumbers() method to switch your settings. The default value is not to use hindu numbers.
3.	4 Persian characters have been added (3.0): چژ گپ
4. Multiple lines are supported. However, you have to supply the breaklines to the Fix method yourself.

I hope you'll find this asset useful and enjoy using it!

# Contact
If you need any help with the asset, please contact me at: abdullah.konash@gmail.com or https://twitter.com/Konash

I'll be very happy if you showed me the game you used the plugin with! I don't mind a free copy of it either! 

Abdullah Konash
