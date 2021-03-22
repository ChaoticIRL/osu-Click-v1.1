# osu-Click-v1.1

Live BPM counter for osu!Standard and osu!Mania. Currently only has support for Windows ( altough I havent tested Linux or Mac ).

# Usage

 Made mostly for Twitch livestreaming but also has some use in gauging or benchmarking streaming capabilities. Works best for longer streams.

1. [Download the program](https://github.com/ChaoticIRL/osu!Click/releases/latest)
<img src=https://i.imgur.com/nV9pVNr.png>
<details>
  <summary>2. Enter your osu! bindings into bindings.txt ( *Click here if confused* )</summary>
<img src=https://i.imgur.com/m0u8cWh.png>
</details>
3. Open up the .exe file.

And voila! Youre ready to use it to your hearts content!

For Streaming:
<details>
<summary>Optional ( CLICK ME )</summary>

4.* If you want to use this on your stream youve gotta do a few more things. First open obs and make a window capture of the program.
<img src=https://i.imgur.com/bJPJ8fr.png>
5.* Add a filter to the window capture called "chroma key". Mess about with the settings till you get it right for your stream.

<img src=https://i.imgur.com/lxzaCI3.png>

6.** This last step is personal preference. Since the BPM counter has a slight delay before displaying the information ( time necessary for it to gather enough data ) you can also add a filter called "render delay" on your osu!Game capture to make them match. Warning! Doing this might impact your stream quality and youll also have to delay your audio so it matches with the visuals!  
</details>

# What is it?
> Simple python program that displays your bpm every second. 
> At the moment its slightly innacurate due to it updating every second ( lack of information in such a small timeframe ) but overall it works pretty well.

